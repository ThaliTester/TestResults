#### Test 5038801932cd575_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SocialFeedProvider( 1249): +disConnect socialManager
I/SocialFeedProvider( 1249): disconnect socialManager
I/SocialFeedProvider( 1249): -disConnect socialManager
,E/cutils-trace( 3446): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3446): ====startRecUseTime====
D/htc.customization.log.level( 3446):  is 
W/CustomizationLogLevel( 3446): Level value is invalid, use default level 2
D/CustomizationManager( 3446):  Read ACC file spent 0.086 (s)
D/CIDMapFileReader( 3446): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3446): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3446): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3446): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3446): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3446): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3446): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3446): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3446): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3446): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3446): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3446): Parsing tag category name = system
I/CustomizationCIDLoader( 3446): Parsing tag category name = application
I/CustomizationCIDLoader( 3446): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3446): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3446): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3446): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3446): Parsing tag category name = Settings
D/CustomizationManager( 3446):  Read CID file spent 0.139 (s)
D/CustomizationManager( 3446):  All configurations done spent 0.139 (s)
W/HtcNativeFlag( 3446): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3446): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3446): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3446): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3455 uid=10080 gids={50080, 5001, 1028, 1015}
D/Process (  907): killProcessQuiet, pid=3223
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3223:com.htc.stock/u0a81 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3223
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/asset   (  907): Copying FileAsset 0x6aed3f10 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1113981104
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3446
D/PMS     (  907): acquireHCC(42661060): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(4263dae0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
D/PMS     (  907): acquireWL(427649f8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3469 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
I/FeedHostManager( 1249): [onPause]
I/FeedProviderManager( 1249): onPause
I/FeedHostManager( 1249): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42132c78
I/SocialFeedProvider( 1249): +onPause
I/SocialFeedProvider( 1249): -onPause
D/PMS     (  907): releaseWL(42128818): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/TrimMemoryManager( 1249): [trimMemory] 20
I/SoundPicker( 3455): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3455): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
E/ActivityThread( 1249): Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1249): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1249): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3590)
E/ActivityThread( 1249): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3684)
E/ActivityThread( 1249): 	at android.app.ActivityThread.access$1100(ActivityThread.java:153)
E/ActivityThread( 1249): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1376)
E/ActivityThread( 1249): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1249): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread( 1249): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/ActivityThread( 1249): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread( 1249): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread( 1249): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread( 1249): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread( 1249): 	at dalvik.system.NativeStart.main(Native Method)
I/SoundPicker( 3455): SoundPickerReceiver [onReceive] startService
W/asset   ( 3469): Copying FileAsset 0x5c84e428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/SoundPicker( 3455): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3455): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3455): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3455): MODE_GSM access default DB
I/ActivityManager(  907): Activity reported stop, but no longer stopping: ActivityRecord{423e4740 u0 com.htc.launcher/.Launcher t1}
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3455): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3455): MODE_GSM access default DB
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
V/WebViewChromiumFactoryProvider( 3469): Binding Chromium to main looper Looper (main, tid 1) {41b08f98}
I/LibraryLoader( 3469): Expected native library version number "",actual native library version number ""
I/chromium( 3469): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3469): Initializing chromium process, renderers=0
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41edb988:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3469): 1102183760: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  907): acquireWL(427c2d78): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(427c3bb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): releaseWL(427c2d78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/Adreno-EGL( 3469): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3469): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3469): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3469): Local Branch: 
I/Adreno-EGL( 3469): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3469): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3469):                  aa63bbd948f41d15fc72f585e
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
W/chromium( 3469): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
W/dalvikvm( 3469): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3469): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3469): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3469): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3469): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3469): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3469): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3469): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3469): CordovaWebView is running on device made by: HTC
,I/HtcModeClient( 1492): handler message = 4011
E/HtcModeClient( 1492): Check connection and retry 6 times.
W/AwContents( 3469): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1249
W/ResourceType( 3469): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3469): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b51098, mServedView=org.apache.cordova.engine.SystemWebView{41b17070 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  907): Enable input method client, pid=3469
W/XT9_C   ( 1187): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1187): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3469): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +305ms
D/PMS     (  907): releaseWL(427649f8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
E/AndroidProtocolHandler( 3469): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3469): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3469): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3469): JniHelper::setJavaVM(0x415e3048), pthread_self() = 1657992960
D/JX-Cordova( 3469): jxcore cordova android initializing
W/jxcore-log( 3469): Initializing JXcore engine
W/jxcore-log( 3469): JXcore engine is ready
W/jxcore-log( 3469): Starting JXcore engine
D/DFPI.PIReciver( 3194): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3194): onHandleIntent
I/DFPI.ApkInstallService( 3194): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3194): check CID = HTC__032
I/DFPI.ApkInstallService( 3194): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
W/jxcore-log( 3469): Platform android
W/jxcore-log( 3469): 
W/jxcore-log( 3469): Process ARCH arm
W/jxcore-log( 3469): 
I/jxcore-log( 3469): JXcore Cordova bridge is ready!
I/jxcore-log( 3469): 
W/jxcore-log( 3469): JXcore engine is started
E/jxcore-log( 3469): >> HTC-HTC Desire 820
E/jxcore-log( 3469): 
I/jxcore-log( 3469): Total memory 1964650496
I/jxcore-log( 3469): 
I/jxcore-log( 3469): Free memory 694579200
I/jxcore-log( 3469): 
I/jxcore-log( 3469): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3469): 
I/jxcore-log( 3469): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3469): 
I/jxcore-log( 3469): userPath [ 'www' ]
I/jxcore-log( 3469): 
I/jxcore-log( 3469): Size 720 1184
I/jxcore-log( 3469): 
I/jxcore-log( 3469): Screen Brightness 10
I/jxcore-log( 3469): 
E/jxcore-log( 3469): Dummy Error Log.
E/jxcore-log( 3469): 
I/ActivityManager(  907): Waited long enough for: ServiceRecord{426be6f0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
I/SoundPicker( 3455): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3455): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3455): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  907): Resuming delayed broadcast
I/SoundPicker( 3455): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3455): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3455): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3455): MODE_GSM access default DB
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3455): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3455): MODE_GSM access default DB
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content:/,/media/internal/audio/media/94 type=8
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/TelephonyReceiver( 1223): bind: true
I/ActivityManager(  907): Resuming delayed broadcast
D/GenericMessagesProvider( 2553): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 2553): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 2553): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 2553): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 2553): DB info: errno = 2, errno message = No such file or directory
E/SQLiteDatabase( 2553): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2553): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2553): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2553): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2553): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2553): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2553): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2553): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2553): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 2553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 2553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 2553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 2553): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 2553): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 2553): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 2553): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2553): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 2553): 	at dalvik.system.NativeStart.run(Native Method)
D/TelephonyReceiver( 1223): switchBindHtcMsgCursor: null
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  907): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3520 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3194): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3194): onHandleIntent
,I/DFPI.ApkInstallService( 3194): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3194): check CID = HTC__032
,I/DFPI.ApkInstallService( 3194): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/SoundPicker( 3455): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3455): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3455): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3455): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3455): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3455): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3455): MODE_GSM access default DB
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3455): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3455): MODE_GSM access default DB
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/EASAppSvc( 3520): [ NA ]- onCreate()
,I/EASAppSvc( 3520): [ NA ]> onUpgrade: version = 63
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,D/ORMLib  ( 3208): put()
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  907): Resuming delayed broadcast
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (3520/10063)
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (3520/10063)
,D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (3520/10063)
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/EASAppSvc( 3520): [ NA ]- onDestroy()
,I/EASAppSvc( 3520): [ NA ]> uninitEASService
,I/EASRequestController( 3520): [ NA ]release
,I/EASAppSvc( 3520): [ NA ]< uninitEASService
,I/EASAppSvc( 3520): [ NA ]- onCreate()
,I/EASAppSvc( 3520): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (3520/10063)
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (3520/10063)
D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (3520/10063)
,D/ORMLib  ( 3208): put()
,I/EASAppSvc( 3520): [ NA ]- onDestroy()
,I/EASAppSvc( 3520): [ NA ]> uninitEASService
,I/EASRequestController( 3520): [ NA ]release
,I/EASAppSvc( 3520): [ NA ]< uninitEASService
,I/jxcore-log( 3469): getBuffer is called!!!!
I/jxcore-log( 3469): 
I/ActivityManager(  907): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3561 uid=10067 gids={50067, 3003, 5012}
,I/MediaStoreImporter( 3401): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/Process (  907): killProcessQuiet, pid=3235
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3235:com.htc.stock:remote/u0a81 (adj 15): empty #17
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  907): Recipient 3235
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Resuming delayed broadcast
,D/DFPI.PIReciver( 3194): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3194): onHandleIntent
I/DFPI.ApkInstallService( 3194): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3194): check CID = HTC__032
,I/DFPI.ApkInstallService( 3194): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 3455): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3455): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3455): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3455): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3455): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3455): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3455): MODE_GSM access default DB
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3455): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3455): MODE_GSM access default DB
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
D/ORMLib  ( 3208): put()
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/aud,io/notifications/Lilac.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3401): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/Process (  907): killProcessQuiet, pid=3137
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3137:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3137
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 1203): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  907): acquireWL(421c42f0): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(421c42f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 1203): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1203, uid=10028, userID:0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3586 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3152
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3152:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1376): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1376): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Recipient 3152
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3602 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3602, uid=10073, userID:0
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(42661060): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(4263dae0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/Finsky  ( 3602): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3602/10073)
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3602/10073)
,D/Finsky  ( 3602): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3602): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3602): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/AlarmManager(  907): sending alarm PendingIntent{41e6c490: PendingIntentRecord{42513470 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448315187351, Int=0
I/SocialManager[SocialBiLogHelper]( 3247): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3247): last commit ulog time 1448257748911
,I/SocialManager[SocialBiLogHelper]( 3247): skip commit this time
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3602, uid=10073, userID:0
,D/Process (  907): killProcessQuiet, pid=3263
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1249): action: android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  907): Killing 3263:com.google.android.talk/u0a111 (adj 15): empty #17
D/Finsky  ( 3602): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3602): [1] 2.run: Finished loading 1 libraries.
,I/IcingCorporaProvider( 2677): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Finsky  ( 3602): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  907): Delaying start of: ServiceRecord{4252aa88 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
D/PMS     (  907): acquireWL(4239db30): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(4239db30): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Recipient 3263,
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42353f78): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(42353f78): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(424f5438): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(424f5438): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(425cf630): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(425cf630): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(42333738): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(42333738): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/AutoSetting( 1376): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1376): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1376): service - requestNLP() NetworkLocationProvider not enabled
,D/PMS     (  907): acquireWL(4234b300): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(4234b300): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(427e3588): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(427e3588): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(427e2ec8): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(427e2ec8): PARTIAL_WAKE_LOCK  Icing 0x1 null,
,D/PMS     (  907): acquireWL(427dfef8): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(427dfef8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(427dc690): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(427dc690): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2677): Copying FileAsset 0x635f65b0 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2677): UpdateCorporaTask done [took 519 ms] updated apps [took 519 ms] 
D/Finsky  ( 3602): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3641 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 3641): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3641 dbg=false s=true
,I/DeviceManagement( 3641): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3654 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3300
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3300:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3300
,V/AlarmManager(  907): sending alarm PendingIntent{425601f0: PendingIntentRecord{427be678 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448315191174, Int=0
,I/SensorManager(  907): mEventCount = 300
,D/PMS     (  907): releaseWL(427c3bb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GAV2    ( 3654): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  907): Delay finish: com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/GoogleHttpClient( 1335): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1335): Using GMS GoogleHttpClient
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3602): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3602): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/ActivityManager(  907): Resuming delayed broadcast
,W/GAV2    ( 3654): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3678 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,I/htcbackup-core( 3678): ModelRegistry: Loading model meta data from resources...
W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ContextImpl( 3678): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,W/Finsky  ( 3602): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3602): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3602): [1] DailyHygiene.reschedule: Scheduling new run in 733 minutes (failures=5)
W/ContextImpl( 3678): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3641): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3641): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.android.providers.settings, android, com.htc.usage, com.htc.autobot.cargps.provider, com.htc.home.personalize, com.htc.lockscreen, com.htc.checkinprovider, com.htc.feedback, com.htc.backupreset, com.htc.cirmodule, com.htc.backup, com.htc.guide, com.android.keychain, com.android.inputdevices, com.htc.android.htcloglevel, com.qualcomm.timeservice, com.android.location.fused, com.htc.smartdim, com.qualcomm.privinit, com.htc.android.htcsetupwizard, com.htc.htcpowermanager, com.htc.drive.activator, com.android.CSDFunctionG, com.android.settings, com.htc.mirrorlinkserver]
,I/DeviceManagement( 3641): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,D/Process (  907): killProcessQuiet, pid=3286
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3697 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  907): Killing 3286:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/DeviceManagement( 3641): WorkflowService: Starting workflow service
I/DeviceManagement( 3641): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b464a8] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 3641): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/DeviceManagement( 3641): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  907): Recipient 3286
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 3641): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3641): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3697):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,D/Process (  907): killProcessQuiet, pid=3317
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
I/ActivityManager(  907): Killing 3317:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3317
,D/WifiService(  907): Client connection lost with reason: 4
,I/DeviceManagement( 3641): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 3641): SessionStateController: Checking invariants...
,I/DeviceManagement( 3641): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3641): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b464a8]
,I/DeviceManagement( 3641): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3712 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3336
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3336:com.android.settings/1000 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3336
,V/AlarmManager(  907): sending alarm PendingIntent{41fb0b90: PendingIntentRecord{42822430 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1448315192241, Int=0
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(425522f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3712 10160 null
,D/PMS     (  907): acquireWL(4238e508): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3712 10160 null
,D/PMS     (  907): releaseWL(425522f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackageAddedReceiver
,D/PMS     (  907): acquireWL(425d1f30): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3712 10160 null
,D/PMS     (  907): releaseWL(4238e508): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3712/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3712/10160)
,D/PMS     (  907): releaseWL(425d1f30): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=3735 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  907): Killing 3365:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3365
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3365
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3735): -onCreate()
,V/Settings:HtcSettingsApplication( 3735): [3735/3735] onCreate()
,D/Process (  907): killProcessQuiet, pid=3179
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3179:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
D/PMS     (  907): acquireWL(4278caa8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1492 10014 null
I/ActivityManager(  907): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  907): acquireWL(42619250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42619250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1556): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1556): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(4278caa8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3753 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/Process (  907): killProcessQuiet, pid=2553
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/TelephonyReceiver( 1223): bind: false
,D/TelephonyReceiver( 1223): switchBindHtcMsgCursor: null
I/ActivityManager(  907): Killing 2553:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  907): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3766 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3179
I/ActivityManager(  907): Recipient 2553
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Settings:HtcWirelessFeatureFlags( 3735): id/is att sku: 99/false
,W/SystemReader( 3735): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3735): Cannot find support_harman, use default value instead
,W/SystemReader( 3735): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3735): no such activity!
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3735): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3735): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3735): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportHomeButton]support         :false
,W/FingerprintManager( 3735): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3735): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3735): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3735): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3735): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3735): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3735): [supportHomeButton]support         :false
,W/FingerprintManager( 3735): hasFingerprint() - sSensorCode = 0
,I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 3735): Failed to find provider info for com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 3735): isSupportVoWifi: null
,W/GAV2    ( 3766): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/DotMatrix( 1556): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  907): notification sound not played, stream=5 volume=0 always=false
,I/RemoteViews( 1110): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41eede08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/Process (  907): killProcessQuiet, pid=3208
,I/ActivityManager(  907): Killing 3208:com.htc.task/u0a70 (adj 15): empty #17
I/RemoteViews.Performance( 1110): com.htc.updater 2 7 1 10
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/RemoteViews( 1110): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41e1eea0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/PMS     (  907): acquireWL(426960c8): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
I/RemoteViews.Performance( 1110): com.htc.updater 1 7 0 10
,D/PMS     (  907): releaseWL(426960c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3796 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/PMS     (  907): acquireWL(425dba78): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,I/ActivityManager(  907): Recipient 3208
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,D/PMS     (  907): releaseWL(425dba78): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/Gmail   ( 3766): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3766): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Babel   ( 3796): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3796): MmsConfig.loadMmsSettings
,E/dalvikvm( 3796): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 3796): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,I/Gmail   ( 3766): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3766): calculateUnknownSyncRationalesAndPurgeInBackground: running
E/dalvikvm( 3796): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 3796): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 3796): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=3826 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3796, uid=10111, userID:0
,W/Settings( 3796): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 3826): onCreate
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3796, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3796, uid=10111, userID:0
D/MmsCustomizationProvider( 3826): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 3826): GetPrviateResource
,V/GetPrviateResource( 3826): GetPrviateResource
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3796, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3796, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3796, uid=10111, userID:0
D/PMS     (  907): acquireWL(41b5dbe0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3796 10111 null
,D/MmsCustomizationProvider( 3826): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3796): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3796): MmsConfig.loadFromDatabase
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,E/Babel   ( 3796): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3796): MmsConfig.loadFromResources
,I/ActivityManager(  907): Killing 3520:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3520
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,E/Babel   ( 3796): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3796): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  907): Recipient 3520
,I/HtcModeClient( 1492): handler message = 4011
,E/HtcModeClient( 1492): Check connection and retry 7 times.
,I/NotifUtils( 3766): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/ProviderInstaller( 3796): Installed default security provider GmsCore_OpenSSL
,D/MessageCustFlag( 3826): sense_version=6.0
,D/BTAccessoryUtil( 3826): createReceiver
,D/BTAccessoryUtil( 3826): registerReceiver return intent = null
D/MessageCustFlag( 3826): sku_id=99
,W/SystemReader( 3826): Cannot find message_ambs_application_id, use default value instead
D/Messaging( 3826): supportCMAS(SIE)/init? false/true
D/MmsConfig( 3826): networkCode: 
,D/MessageCustFlag( 3826): sku_id=99
D/MmsConfig( 3826): SIE smsPri: null
,D/MmsConfig( 3826): networkCode: 
,D/HtcTelephonyCapability( 3826): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 3826): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 3826): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3826): Cannot find qct_8960_interface, use default value instead
,I/NotifUtils( 3766): validateNotifications - cancelling account 61035162 / folder -317575340
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Killing 3561:com.htc.task.gtask/u0a67 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3561
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3561
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(41eb7c90): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/PMS     (  907): releaseWL(41eb7c90): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PackageBroadcastService( 1203): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PeopleContactsSync( 1203): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1203, uid=10028, userID:0
D/PMS     (  907): acquireWL(42602b28): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
D/PMS     (  907): releaseWL(42602b28): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1376): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1376): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
D/PMS     (  907): releaseWL(41b5dbe0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (3796/10111)
,I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2677): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (3796/10111)
,I/IcingCorporaProvider( 2677): UpdateCorporaTask done [took 45 ms] updated apps [took 45 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(425b91c0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3712 10160 null
,D/PMS     (  907): releaseWL(425b91c0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3870 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,D/PMS     (  907): acquireWL(424d3c58): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3870 10070 null
,D/PMS     (  907): acquireWL(426485a0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3870 10070 null
,D/Process (  907): killProcessQuiet, pid=3194
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3194:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
I/ActivityManager(  907): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
E/TodoTaskNotifyService( 3870): java.lang.NullPointerException
W/System.err( 3870): java.lang.NullPointerException
,W/System.err( 3870): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
,W/System.err( 3870): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3870): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3870): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3870): stopSelfResult true
D/PMS     (  907): releaseWL(424d3c58): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  907): releaseWL(426485a0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,I/WSP     ( 1376): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1376): Weather sync is On
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/WSP     ( 1376): [Receiver] next auto-sync alarm event is 60 mins later, at time: Mon Nov 23 23:46:33 CET 2015
,W/WSP     ( 1376): [Receiver] can't get active network info
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1376/10053)
,V/WSP     ( 1376): [SyncService] no data connection, stop sync service
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1376/10053)
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3194
,W/MediaManager( 3384): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3870): update TASK shortcut>
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  907): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  907): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
,W/Settings:Agent(  907): >> traceCallingStack()
,W/Settings:Agent(  907): Process.myPid(): 907
,W/Settings:Agent(  907): Process.myTid(): 1236
,W/Settings:Agent(  907): Process.myUid(): 1000
,W/Settings:Agent(  907): 
,W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 18(ms)
,D/BluetoothManagerService(  907): Message: MESSAGE_DISABLE
,D/WifiManager( 3469): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: false pid=3469, uid=10355
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
,W/Settings:Agent(  907): >> traceCallingStack()
,W/Settings:Agent(  907): Process.myPid(): 907
,W/Settings:Agent(  907): Process.myTid(): 1235
,W/Settings:Agent(  907): Process.myUid(): 1000
,W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
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
W/Settings:Agent(  907): << traceCallingStack(): 12(ms)
I/jxcore-log( 3469): ****TEST TOOK:  5072  ms ****
I/jxcore-log( 3469): 
I/jxcore-log( 3469): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3469): 
,E/cutils-trace( 3890): Error opening trace file: No such file or directory (2)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (3796/10111)
,D/CustomizationManager( 3890): ====startRecUseTime====
D/htc.customization.log.level( 3890):  is 
,W/CustomizationLogLevel( 3890): Level value is invalid, use default level 2
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/CustomizationManager( 3890):  Read ACC file spent 0.058 (s)
,D/CIDMapFileReader( 3890): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__Y13
,D/CIDMapFileReader( 3890): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3890): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3890): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3890): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3890): Parsing tag category name = system
,I/CustomizationCIDLoader( 3890): Parsing tag category name = application
,I/CustomizationCIDLoader( 3890): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3890): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3890): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3890): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3890): Parsing tag category name = Settings
D/CustomizationManager( 3890):  Read CID file spent 0.100 (s)
,D/CustomizationManager( 3890):  All configurations done spent 0.100 (s)
W/HtcNativeFlag( 3890): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3890): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3890): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3890): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=3890, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,W/asset   (  907): Copying FileAsset 0x63b23540 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  907): killProcessQuiet, pid=3469,
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Killing 3469:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  907): Force removing ActivityRecord{426609f0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  907): Skipping PackageSetting{422d4c20 com.test.thalitest/10348} due to missing metadata
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  907): WIN DEATH: Window{42304188 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  907): Client connection lost with reason: 4
,I/ActivityManager(  907): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/acms    ( 1763): Unregistering com.example.hello
,E/acms    ( 1763): Could not unregister removed application com.example.hello
,D/DotMatrix( 1556): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1556): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1556): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/FeedHostManager( 1249): [onResume]
I/FeedProviderManager( 1249): onResume
,I/SocialFeedProvider( 1249): +onResume
,I/ConnectivityHelper( 1249): [getCurrentConnectionType] no network connection
I/SocialFeedProvider( 1249): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1249): -onResume
,W/GeofencerStateMachine( 1398): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1309): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1309): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1249/10075)
D/PMS     (  907): acquireWL(427e3588): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1398 10028 null
,D/PMS     (  907): releaseWL(427e3588): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1237): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1309): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,E/ExternalAccountType( 1309): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,D/PhoneApp( 1223): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3469 uid 10355
,W/Binder  ( 1187): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1187): java.lang.NullPointerException
W/Binder  ( 1187): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1187): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1187): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1187): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  907): Enable input method client, pid=1249
,W/PackageManager(  907): Unable to load service info ResolveInfo{427cc128 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/Messaging( 3826): mNeedToUpdateDate2 start
,D/MmsConfig( 3826): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 3826): startAsyncQueryReports ---
,D/SettingsManager( 3826): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b167a8
D/MmsAsyncWorkHandler( 3826): 
D/MmsAsyncWorkHandler( 3826): HM tk = 20001
,D/ReportIndicatorCache( 3826): MSG_QUERY_REPORTS >>
D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1223):  phoneType = -1
D/MmsSmsV2Provider( 1223): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,I/Messaging( 3826): mccmnc> 
,D/DraftCache( 3826): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 3826): [DraftCache/1] refresh
,D/MmsConfig( 3826): networkCode: 
,D/Messaging( 3826): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1223):  phoneType = -1
,D/MmsSmsV2Provider( 1223): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 3826): HtcWrapEnvironment.getSupportedStorages() >1
D/Messaging( 3826): mNeedToUpdateDate2: false
D/PhoneStorageUtil( 3826): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 3826): createReceiver
D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1223): sku_id=99
,D/MessageCustFlag( 3826): sense_version=6.0
D/TelephUtils( 1223): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/Jerry   ( 3826): start to preload cursor >>>>>>>
V/MmsProvider( 1223): Update uri=content://mms, match=0
,V/MmsProvider( 1223): selection=st=129 AND m_type!=134
,D/Messaging( 3826): Reset downloading state: 0
,V/MmsSystemEventReceiver( 3826): TransactionService is going to be woken up.
,I/ActivityManager(  907): Delaying start of: ServiceRecord{426ac780 u0 com.htc.sense.mms/.transaction.TransactionService}
D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/DraftCache( 3826): [DraftCache/391] rebuildCache
D/MmsSmsV2Provider( 1223):  phoneType = -1
,D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1223):  phoneType = -1
D/MmsSmsV2Provider( 1223): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/Messaging( 3826): ViewCache CreatePreload
,D/Messaging( 3826): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/Jerry   ( 1223): URI_DRAFT
,D/Cust_MMSMS( 3826): _has_set_default_values_2=true
D/DraftCache( 3826): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3826): [DraftCache/391] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 3826): 
D/MmsAsyncWorkHandler( 3826): HM tk = 20002
D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1223):  phoneType = -1
,D/MmsSmsV2Provider( 1223): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 3826): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MsgPreferenceUtils( 3826): def_index: 0
,D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1223): sku_id=99
,D/MsgPreferenceUtils( 3826): globalIndex = 1
D/MsgPreferenceUtils( 3826): phone state: true
D/MsgPreferenceUtils( 3826): sd state: false
,D/MsgPreferenceUtils( 3826): vIndex = 0
D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1223): sku_id=99
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/GAV2    ( 3654): Thread[GAThread,5,main]: No campaign data found.

```
