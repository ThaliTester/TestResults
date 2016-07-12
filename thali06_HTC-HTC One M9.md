#### Test 72145431744cc2c_thali06_HTC-HTC One M9 Logs


```
--------- beginning of main
07-12 11:35:27.960  7351  7442 D libc    : [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 4
07-12 11:35:27.960  7351  7442 D libc    : [NET] android_getaddrinfofornet-, err=8
07-12 11:35:28.030  7538  7538 V CameraProfiler: [PROFILE] Start timer 'CameraApplication.OnCreate.Start'
07-12 11:35:28.040  7538  7560 W CameraApplication: getCustomizedBundle() - No data
07-12 11:35:28.040  7538  7560 W HTCLOG  : use specified tag [CameraBase], func [0].
07-12 11:35:28.040  7538  7560 W HTCLOG  : mask=0x18
,07-12 11:35:28.080  7538  7560 W FeatureConfig: mIsRawPhotoSupported:true
07-12 11:35:28.080  7538  7538 V CameraProfiler: [PROFILE] Start timer 'CameraApplication.OnCreate.End'
07-12 11:35:28.080  7538  7538 V CameraProfiler: [PROFILE][INTERVAL][CameraApplication.OnCreate.Start -> CameraApplication.OnCreate.End] 50.657 ms (50656979 ns)
07-12 11:35:28.110  7303  7535 W MediaManager: [DualLensScanUtil]	mmpCursor count is 0
--------- beginning of system
07-12 11:35:28.230  1114  3722 I ActivityManager: Resuming delayed broadcast
07-12 11:35:28.250  1114  3722 I ActivityManager: Start proc 7568:com.htc.sdm/u0a64 for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver
07-12 11:35:28.260  1114  3500 I ActivityManager: Killing 6626:com.htc.cs.pns:boot_complete/u0a119 (adj 15): empty #17
07-12 11:35:28.260  1114  3500 D Process : killProcessQuiet, pid=6626
07-12 11:35:28.260  1114  3500 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
07-12 11:35:28.260  7566  7566 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-12 11:35:28.260  7566  7566 W HTCLOG  : mask=0x18
07-12 11:35:28.270  7568  7568 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 11:35:28.270  7568  7568 W HTCLOG  : mask=0x18
07-12 11:35:28.330  1114  3447 I ActivityManager: Recipient 6626
07-12 11:35:28.420  7568  7568 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-12 11:35:28.420  7568  7568 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-12 11:35:28.430  1114  3437 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
07-12 11:35:28.430  7568  7589 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-12 11:35:28.430  7568  7589 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-12 11:35:28.440  7568  7589 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-12 11:35:28.450  7568  7589 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-12 11:35:28.450  7568  7589 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-12 11:35:28.450  7568  7589 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 11:35:28.450  7568  7589 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-12 11:35:28.450  7568  7589 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-12 11:35:28.450  7568  7589 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 11:35:28.450  7568  7589 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-12 11:35:28.450  7568  7589 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-12 11:35:28.450  7568  7589 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 11:35:28.450  7568  7589 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-12 11:35:28.460  7568  7589 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-12 11:35:28.460  7568  7589 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-12 11:35:28.460  7568  7589 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-12 11:35:28.460  7568  7589 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-12 11:35:28.460  7568  7589 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-12 11:35:28.460  7568  7589 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-12 11:35:28.460  7568  7589 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-12 11:35:28.460  7568  7589 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-12 11:35:28.460  7568  7589 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-12 11:35:28.460  7568  7589 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-12 11:35:28.470  7568  7589 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-12 11:35:28.470  7568  7589 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-12 11:35:28.470  7568  7589 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-12 11:35:28.470  1114  3500 I ActivityManager: Resuming delayed broadcast
07-12 11:35:28.480  1114  1133 I ActivityManager: Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
07-12 11:35:28.490  3450  3799 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-12 11:35:28.490  3450  3799 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1d2cf148 +
07-12 11:35:28.490  3450  3799 I Prism.WidgetManager: onLoadItems() +
07-12 11:35:28.520  3450  3799 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-12 11:35:28.590  7566  7594 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-12 11:35:28.590  7566  7594 W HTCLOG  : mask=0x18
07-12 11:35:28.590  7566  7594 E cutils-trace: Error opening trace file: Permission denied (13)
07-12 11:35:28.650  7566  7566 D CustomizationManager: ====startRecUseTime====
07-12 11:35:28.650  7566  7566 D htc.customization.log.level:  is 
07-12 11:35:28.650  7566  7566 W CustomizationLogLevel: Level value is invalid, use default level 2
07-12 11:35:28.700  7566  7566 D CustomizationManager:  Read ACC file spent 0.027 (s)
07-12 11:35:28.700  7566  7566 D CIDMapFileReader: Parsing tag item name = HTC__001
07-12 11:35:28.700  7566  7566 D CIDMapFileReader: Parsing tag item name = HTC__002
07-12 11:35:28.700  7566  7566 D CIDMapFileReader: Parsing tag item name = HTC__016
07-12 11:35:28.700  7566  7566 D CIDMapFileReader: Parsing tag item name = HTC__031
07-12 11:35:28.700  7566  7566 D CIDMapFileReader: Parsing tag item name = HTC__032
07-12 11:35:28.700  7566  7566 D CIDMapFileReader: Parsing tag item name = HTC__102
07-12 11:35:28.700  7566  7566 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-12 11:35:28.700  7566  7566 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-12 11:35:28.700  7566  7566 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-12 11:35:28.700  7566  7566 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-12 11:35:28.700  7566  7566 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: Parsing tag category name = application
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: Parsing tag category name = system
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: Parsing tag category name = Settings
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: Parsing tag category name = ACC
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 42507
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 21902
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 23420
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 22299
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 24002
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 23210
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 23205
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 23806
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 23430
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 23408
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 27205
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-12 11:35:28.700  7566  7566 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-12 11:35:28.700  7566  7566 D CustomizationManager:  Read CID file spent 0.056 (s)
07-12 11:35:28.700  7566  7566 D CustomizationManager:  All configurations done spent 0.056 (s)
07-12 11:35:28.710  3450  3799 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-12 11:35:28.730  1114  3891 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 7566 on display 0
07-12 11:35:28.740  7446  7609 D Messaging: mNeedToUpdateDate2 start
07-12 11:35:28.740  7446  7446 D MessageUtils: [isPackageExists] packageName: com.htc.vvm.att does not exist
07-12 11:35:28.740  7446  7446 D MessageCustFlag: sku_id=118
07-12 11:35:28.740  1114  1177 D PMS     : acquireHCC(3a8352b9): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1114 1000 null
07-12 11:35:28.740  1114  1177 D PMS     : acquireHCC(2134c6fe): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1114 1000 null
07-12 11:35:28.740  7446  7446 D ReportIndicatorCache: startAsyncQueryReports --- , first = true
07-12 11:35:28.740  7446  7470 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
07-12 11:35:28.740  1114  3891 V WindowManager: addAppToken: AppWindowToken{d7d6175 token=Token{1af280ac ActivityRecord{1e8e4e5f u0 com.test.thalitest/.MainActivity t124}}} to stack=1 task=124 at 0
07-12 11:35:28.740  7446  7446 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@22afb513
07-12 11:35:28.740  7446  7469 D MmsAsyncWorkHandler: 
07-12 11:35:28.740  7446  7469 D MmsAsyncWorkHandler: HM tk = 20002
07-12 11:35:28.750  7446  7446 D DraftCache: [DraftCache/1] DraftCache.constructor
07-12 11:35:28.750  1114  3891 D PMS     : acquireWL(792550a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1114 1000 null
07-12 11:35:28.750  7446  7446 D DraftCache: [DraftCache/1] refresh
07-12 11:35:28.750  1114  1154 I AnimationUtil: isHTCRecent(ThaliTest/Recents screens.)/3
07-12 11:35:28.750  7566  7566 W HTCLOG  : use specified tag [IPCThreadState], func [0].
07-12 11:35:28.750  7566  7566 W HTCLOG  : mask=0x18
07-12 11:35:28.750  7566  7607 W HTCLOG  : use specified tag [Vector], func [0].
07-12 11:35:28.750  7566  7607 W HTCLOG  : mask=0x18
07-12 11:35:28.750  3450  3450 I FeedHostManager: [onPause]
07-12 11:35:28.750  3450  3450 I FeedProviderManager: onPause
07-12 11:35:28.750  7446  7612 D MmsConfig: Start to get Carrier ID
07-12 11:35:28.750  3450  3450 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@13d84291
07-12 11:35:28.750  3407  4521 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 106
07-12 11:35:28.750  3407  4521 D MmsSmsV2Provider:  slotId = -1
07-12 11:35:28.750  3407  4521 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
07-12 11:35:28.750  3450  4832 I SocialFeedProvider: +onPause
07-12 11:35:28.750  3450  4832 I SocialFeedProvider: -onPause
07-12 11:35:28.750  3450  3450 I ContextualWidget: onPause
07-12 11:35:28.750  3450  3450 I ContextualWidget: notifyWidgetDeactive
07-12 11:35:28.760  7446  7446 D MmsConfig: networkCode: 
07-12 11:35:28.760  3407  4241 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-12 11:35:28.760  7446  7611 I Messaging: mccmnc> 
07-12 11:35:28.760  3407  3993 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
07-12 11:35:28.760  1114  1154 V WindowManager: Adding window Window{3f2d4a2d u0 Starting com.test.thalitest} at 2 of 7 (after Window{35591cdd u0 com.htc.launcher/com.htc.launcher.Launcher})
07-12 11:35:28.760  3407  3993 D MmsSmsV2Provider:  slotId = -1
07-12 11:35:28.760  3407  3993 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select _id,msg_id from addr where (type = 129 or type = 130 or type = 151) , selectionArgs: null
07-12 11:35:28.760  3407  4241 D PhoneApp: -- N1 =1
07-12 11:35:28.760  3407  4241 D PhoneApp: -- N2 =0
07-12 11:35:28.760  7446  7614 D Messaging: ViewCache CreatePreloadOnlyConversationList
07-12 11:35:28.760  3407  4241 D PhoneApp: -- N3 =0
07-12 11:35:28.760  3407  4207 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
07-12 11:35:28.760  3407  4207 D MmsSmsV2Provider:  slotId = -1
07-12 11:35:28.760  3407  4207 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
07-12 11:35:28.760  7446  7614 D MessageCustFlag: sense_version=7.0
07-12 11:35:28.770  7446  7446 D HfmClient: getIHFMServiceHMSApiLevel: +++
07-12 11:35:28.770  7446  7446 E HfmClient: Failed to load meta-data, NameNotFound: com.htc.hfm
07-12 11:35:28.770  7446  7446 E HfmClient: getIHFMServiceHMSApiLevel: load meta-data from HtcSpeak
07-12 11:35:28.770  7446  7446 D HfmClient: getIHFMServiceHMSApiLevel: Level = 1
07-12 11:35:28.770  7446  7446 D HfmClient: HfmServiceHMS API Level = 1
07-12 11:35:28.770  7446  7614 D Jerry   : start to preload cursor >>>>>>>
07-12 11:35:28.770  1114  3717 I ActivityManager: Start proc 7616:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-12 11:35:28.770  3407  3407 D IccSmsInterfaceManager: [IccSmsInterfaceManager] Cannot get carrier id
07-12 11:35:28.770  7446  7612 D MmsConfig: Carrier ID is NULL
07-12 11:35:28.770  1114  3507 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-12 11:35:28.770  3407  3993 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
07-12 11:35:28.780  7446  7446 D ew      : createReceiver
07-12 11:35:28.780  3407  3434 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
07-12 11:35:28.780  3407  3434 D MmsSmsV2Provider:  slotId = -1
07-12 11:35:28.780  3407  3434 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
07-12 11:35:28.780  7446  7631 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
07-12 11:35:28.780  1114  3717 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
07-12 11:35:28.780  7616  7616 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 11:35:28.780  7616  7616 W HTCLOG  : mask=0x18
07-12 11:35:28.780  7446  7446 D HtcBuildUtils: getRATByHtcTelephonyCapability:1
07-12 11:35:28.780  3407  3431 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 59
07-12 11:35:28.780  3407  3431 V MmsProvider: Update uri=content://mms, match=0
07-12 11:35:28.780  3407  3431 V MmsProvider: selection=st=129 AND m_type!=134
07-12 11:35:28.780  7446  7446 W SystemReader: Cannot find support_cw, use default value instead
07-12 11:35:28.780  7446  7609 D Messaging: mNeedToUpdateDate2: false
07-12 11:35:28.780  7446  7446 W SystemReader: Cannot find qct_8960_interface, use default value instead
07-12 11:35:28.790  3407  4207 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
07-12 11:35:28.790  7446  7631 D ew      : HtcStorageHelper.getPhoneStorageDir = /storage/emulated/0
07-12 11:35:28.790  7446  7632 D Messaging: Reset downloading state: 0
07-12 11:35:28.790  7446  7632 V Messaging: Start TransactionService after 2 minutes from now
07-12 11:35:28.790  1114  2928 V AlarmManager: sending alarm PendingIntent{34f28112: PendingIntentRecord{1480a0e3 com.aiqidii.mercury broadcastIntent}}, i=null, t=1, cnt=1, w=1468316126043, Int=86400000
07-12 11:35:28.790  3407  3434 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
07-12 11:35:28.790  1114  2928 V AlarmManager: sending alarm PendingIntent{2d53c50c: PendingIntentRecord{5fcbe55 com.aiqidii.mercury broadcastIntent}}, i=null, t=1, cnt=1, w=1468316126045, Int=86400000
07-12 11:35:28.790  3407  3434 D MmsSmsV2Provider:  slotId = -1
07-12 11:35:28.790  1114  2928 V AlarmManager: sending alarm PendingIntent{1959206a: PendingIntentRecord{2ecf495b com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1468316126070, Int=0
07-12 11:35:28.790  3407  3434 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
07-12 11:35:28.790  7446  7631 D ew      : /storage/emulated/0 : mounted
07-12 11:35:28.790  1114  3500 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
07-12 11:35:28.790  7446  7631 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
07-12 11:35:28.790  7446  7610 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
07-12 11:35:28.800  3407  3993 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
07-12 11:35:28.800  3407  3993 D MmsSmsV2Provider:  slotId = -1
07-12 11:35:28.800  3407  4207 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
07-12 11:35:28.800  7446  7614 D Messaging: ViewCache CreatePreload
07-12 11:35:28.800  7446  7614 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
07-12 11:35:28.810  7446  7469 D DraftCache: [DraftCache/126] rebuildCache
07-12 11:35:28.810  7446  7614 D Cust_MMSMS: _has_set_default_values_2=true
07-12 11:35:28.810  7446  7614 D TextSizeManager: [get_list_body_TextSize]__size57
07-12 11:35:28.810  7446  7614 D TextSizeManager: [get_list_body_TextSize]__size48
07-12 11:35:28.810  7446  7614 D TextSizeManager: [get_list_body_TextSize]__size0
07-12 11:35:28.810  7446  7614 D TextSizeManager: [get_list_body_TextSize]__size57
07-12 11:35:28.810  7446  7614 D TextSizeManager: [get_list_body_TextSize]__size66
07-12 11:35:28.810  7446  7614 D TextSizeManager: [get_list_body_TextSize]__size74
07-12 11:35:28.810  7446  7614 D TextSizeManager: [get_list_body_TextSize]__size83
07-12 11:35:28.810  7446  7614 D MsgPreferenceUtils: def_index: 0
07-12 11:35:28.820  7446  7614 D MsgPreferenceUtils: globalIndex = 2
07-12 11:35:28.820  1114  2949 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
07-12 11:35:28.820  7446  7614 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
07-12 11:35:28.820  3407  3434 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
07-12 11:35:28.820  3407  3434 D Jerry   : URI_DRAFT
07-12 11:35:28.820  7446  7614 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
07-12 11:35:28.820  1114  3436 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
07-12 11:35:28.820  1114  1147 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-12 11:35:28.820  1114  1147 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{3f2d4a2d u0 Starting com.test.thalitest}
07-12 11:35:28.820  1114  1147 D StatusBarManagerService: hiding MENU key
07-12 11:35:28.830  7446  7469 D DraftCache: hasDraft() = false mNeedNotifyChange = true
07-12 11:35:28.830  7446  7469 D DraftCache: [DraftCache/126] rebuildCache time: 0
07-12 11:35:28.830  3068  3068 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-12 11:35:28.830  3068  3068 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-12 11:35:28.830  7446  7614 D MsgPreferenceUtils: phone state: true
07-12 11:35:28.830  7446  7614 D MsgPreferenceUtils: sd state: false
07-12 11:35:28.830  7446  7614 D MsgPreferenceUtils: vIndex = 1
07-12 11:35:28.850  7446  7614 D PersonalizeUtils: isHTCThemeChange_full equal time= null,old=
07-12 11:35:28.850  7446  7614 D PersonalizeUtils: isHTCThemeChange_full isChange= false
07-12 11:35:28.850  7446  7658 D RcsWorkingHandler: handler msg:{ when=-1ms what=1 target=com.htc.sense.mms.rcschat.bo }
07-12 11:35:28.850  7446  7658 D RcsWorkingHandler: not support Rcs, return
07-12 11:35:28.850  7446  7614 D PersonalizeUtils: isHTCThemeChange_wallpaper equal time= null,old=
07-12 11:35:28.850  7446  7614 D PersonalizeUtils: isHTCThemeChange_wallpaper isChange= false
07-12 11:35:28.850  7446  7614 D PersonalizeUtils: isHTCThemeChange_CC equal time= 1440293058,old=1440293058
07-12 11:35:28.850  7446  7614 D PersonalizeUtils: isHTCThemeChange_CC isChange= false
07-12 11:35:28.850  3450  3450 I TrimMemoryManager: [trimMemory] 20
07-12 11:35:28.870  7616  7616 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
07-12 11:35:28.890  3450  3799 W asset   : Copying FileAsset 0xaba009a0 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
07-12 11:35:28.940  7616  7616 I LibraryLoader: Time to load native libraries: 38 ms (timestamps 1487-1525)
07-12 11:35:28.940  7616  7616 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:35:28.950  3450  3799 I Prism.WidgetManager: onLoadItems() -
07-12 11:35:28.950  3450  3799 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1d2cf148 -
07-12 11:35:28.950  7616  7616 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {287d0877}
07-12 11:35:28.950  7616  7616 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:35:28.960  7616  7616 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 11:35:28.960  7616  7616 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-12 11:35:28.960  7616  7616 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 11:35:28.970  7616  7616 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 11:35:28.990  7616  7661 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,07-12 11:35:29.000  7616  7665 D BluetoothAdapter: 417008868: getState() :  mService = null. Returning STATE_OFF
,07-12 11:35:29.000  7616  7616 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-12 11:35:29.000  7616  7616 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345
07-12 11:35:29.000  7616  7616 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
,07-12 11:35:29.010  7616  7616 W HTCLOG  : use specified tag [libEGL], func [3].
07-12 11:35:29.010  7616  7616 W HTCLOG  : mask=0x18
,07-12 11:35:29.020  7616  7616 W HTCLOG  : use specified tag [libEGL], func [3].
,07-12 11:35:29.020  7616  7616 W HTCLOG  : mask=0x18
07-12 11:35:29.020  7616  7616 I Adreno  : QUALCOMM build                   : 065751b, 
07-12 11:35:29.020  7616  7616 I Adreno  : Build Date                       : 04/15/15
07-12 11:35:29.020  7616  7616 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
07-12 11:35:29.020  7616  7616 I Adreno  : Local Branch                     : 
07-12 11:35:29.020  7616  7616 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
07-12 11:35:29.020  7616  7616 I Adreno  : Remote Branch                    : NONE
07-12 11:35:29.020  7616  7616 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,07-12 11:35:29.090  1114  3446 I ActivityManager: Resuming delayed broadcast,
,07-12 11:35:29.090  7616  7671 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,07-12 11:35:29.090  1114  3437 I ActivityManager: Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,07-12 11:35:29.100  1114  3717 I ActivityManager: Resuming delayed broadcast,
,07-12 11:35:29.110  7616  7616 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 11:35:29.110  1114  3717 I ActivityManager: Start proc 7680:com.htc.updater/u0a68 for broadcast com.htc.updater/.UpdaterReceiver
,07-12 11:35:29.120  7680  7680 W HTCLOG  : use specified tag [FDManager], func [0].,
07-12 11:35:29.120  7680  7680 W HTCLOG  : mask=0x18
,07-12 11:35:29.120  7616  7616 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 11:35:29.130  7616  7616 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,07-12 11:35:29.140  7616  7616 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 11:35:29.140  7616  7616 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 11:35:29.170  1114  3436 I ActivityManager: Delay finish: com.htc.updater/.UpdaterReceiver
,07-12 11:35:29.170  7680  7704 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
07-12 11:35:29.170  7680  7704 W HTCLOG  : mask=0x18
07-12 11:35:29.170  7616  7706 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-12 11:35:29.170  7616  7706 W HTCLOG  : mask=0x18
,07-12 11:35:29.180  7680  7680 V UpdaterAPK | DownloadService: Service onStart
,07-12 11:35:29.180  7680  7705 V UpdaterAPK | DownloadService: Updating for startId 1
,07-12 11:35:29.190  7680  7705 V UpdaterAPK | DownloadProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,07-12 11:35:29.190  7680  7704 V UpdaterAPK | DownloadProvider: starting query, database is not null; projection[0] is status; selection is update_type=?; selectionArgs[0] is FOTA; sort is null.
,07-12 11:35:29.190  7680  7704 V UpdaterAPK | DownloadProvider: created cursor android.database.sqlite.SQLiteCursor@3ce0c949 on behalf of 7680
,07-12 11:35:29.190  7680  7705 V UpdaterAPK | DownloadProvider: created cursor android.database.sqlite.SQLiteCursor@2080224e on behalf of 7680
,07-12 11:35:29.190  1114  3446 I ActivityManager: Resuming delayed broadcast
07-12 11:35:29.200  7680  7680 V UpdaterAPK | DownloadService: Service onDestroy
,07-12 11:35:29.200  7680  7705 V UpdaterAPK | DownloadService: Nothing left; stopped
,07-12 11:35:29.200  1114  1133 D PMS     : acquireWL(159f25b1): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 7094 10008 null
,07-12 11:35:29.200  1114  3500 I ActivityManager: Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,07-12 11:35:29.200  7094  7708 E SQLiteLog: (284) automatic index on view_events(_id)
,07-12 11:35:29.210  1114  1134 D PMS     : releaseWL(159f25b1): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,07-12 11:35:29.210  1114  3446 I ActivityManager: Resuming delayed broadcast
,07-12 11:35:29.230  1114  3435 V WindowManager: Adding window Window{37a4ca04 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3f2d4a2d u0 Starting com.test.thalitest}),
,07-12 11:35:29.230  1114  3447 D Process : killProcessQuiet, pid=6675
,07-12 11:35:29.230  1114  3446 I ActivityManager: Start proc 7710:com.htc.autobot/u0a27 for broadcast com.htc.autobot/.AlarmReceiver
07-12 11:35:29.230  1114  3447 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
07-12 11:35:29.230  1114  3447 I ActivityManager: Killing 6675:tv.peel.app/u0a123 (adj 15): empty #17,
,07-12 11:35:29.240  7710  7710 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 11:35:29.240  7710  7710 W HTCLOG  : mask=0x18
,07-12 11:35:29.290  1114  1134 I ActivityManager: Recipient 6675
,07-12 11:35:29.360  7710  7710 D AlarmReceiver: ACTION_RESTART_INTENT
,07-12 11:35:29.370  1114  3722 I ActivityManager: Delay finish: com.htc.autobot/.AlarmReceiver,
07-12 11:35:29.370  7616  7616 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
07-12 11:35:29.370  7616  7616 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
07-12 11:35:29.370  7616  7616 W HTCLOG  : mask=0x18
07-12 11:35:29.370  7616  7616 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
,07-12 11:35:29.370  7616  7616 W HTCLOG  : mask=0x18,
07-12 11:35:29.370  7710  7710 D LocalBluetoothProfile: getPriorityOnValue = 100
07-12 11:35:29.370  7710  7710 D LocalBluetoothProfile: getPriorityOffValue = 0
07-12 11:35:29.370  7710  7710 D Utils   : CMD:getprop ro.htc.htcmode.socket.type,
07-12 11:35:29.380  7616  7706 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-12 11:35:29.380  7616  7706 W HTCLOG  : mask=0x18
,07-12 11:35:29.380  7616  7706 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-12 11:35:29.380  7616  7706 W HTCLOG  : mask=0x18
07-12 11:35:29.380  7616  7706 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-12 11:35:29.380  7616  7706 W HTCLOG  : mask=0x18
07-12 11:35:29.380  7710  7710 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
07-12 11:35:29.380  7616  7706 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-12 11:35:29.380  7616  7706 W HTCLOG  : mask=0x18
07-12 11:35:29.380  7616  7706 W HTCLOG  : use specified tag [Surface], func [3].
07-12 11:35:29.380  7616  7706 W HTCLOG  : mask=0x18
07-12 11:35:29.380  7616  7706 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
07-12 11:35:29.380  7616  7706 W HTCLOG  : mask=0x18
07-12 11:35:29.390  7616  7706 W HTCLOG  : use specified tag [qdmemalloc], func [0].
07-12 11:35:29.390  7616  7706 W HTCLOG  : mask=0x18
,07-12 11:35:29.420  7710  7736 D HtcModeClient: start the htcmodeservice thread
,07-12 11:35:29.420  7710  7736 D HtcModeClient: initCanAgent
,07-12 11:35:29.420  7710  7736 I CANMesgAgentLocalSocket: CANAgent Id = 0
,07-12 11:35:29.420  7710  7736 D HtcModeClient: sense info: version = none, id = 2
,07-12 11:35:29.430  7710  7736 D HtcModeClient: display info: width = 1080, height = 1776
07-12 11:35:29.430  7710  7736 D HtcModeClient: display info: mode = 10
,07-12 11:35:29.460  7616  7616 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@365894ac, mServedView=org.apache.cordova.engine.SystemWebView{a0be575 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1478890a
,07-12 11:35:29.480  1114  3247 I InputMethodManagerService: Disable input method client, pid=3450
07-12 11:35:29.480  1114  3247 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-12 11:35:29.480  1114  3247 I InputMethodManagerService: Enable input method client, pid=7616
,07-12 11:35:29.480  3068  3068 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-12 11:35:29.500  1114  1154 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +741ms
,07-12 11:35:29.500  7616  7616 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7616,
,07-12 11:35:29.500  1114  3891 D PMS     : releaseWL(792550a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,07-12 11:35:29.510  7680  7731 W HtcThemeUtils: Can not get alternative color from specificInfo:C:0:0:0:0:0:0:0:0:0:0:0:0, with category(0),
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: java.lang.IllegalArgumentException: Unknown color
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at android.graphics.Color.parseColor(Color.java:216)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.setAlternativeColor(HtcThemeUtils.java:611)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.checkResourceSrc(HtcThemeUtils.java:534)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.createResourceInstance(HtcThemeUtils.java:486)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.init(HtcThemeUtils.java:476)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.access$600(HtcThemeUtils.java:451)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils.init(HtcThemeUtils.java:390)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcCommonUtil.initTheme(HtcCommonUtil.java:315)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at com.htc.updater.util.NotificationUtil.getNotificationThemeColor(NotificationUtil.java:472)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at com.htc.updater.util.NotificationUtil.notifyDownload(NotificationUtil.java:152)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:259)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at android.os.Looper.loop(Looper.java:155)
07-12 11:35:29.510  7680  7731 W HtcThemeUtils: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:35:29.520  7710  7710 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
07-12 11:35:29.520  7710  7710 D HtcModeClient: connectState: BT_TURNON_BYME = false
07-12 11:35:29.520  7710  7710 D HtcModeClient: connectState: CONNECTION_READY = false
07-12 11:35:29.520  7710  7710 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
07-12 11:35:29.520  7710  7710 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
07-12 11:35:29.520  7710  7710 D HtcModeClient: connectState: PHONE_PULGIN = false
07-12 11:35:29.520  7710  7710 D HtcModeClient: connectState: Force_AWAKE = false
07-12 11:35:29.520  7710  7710 D HtcModeClient: connectState: PHONE_PULGIN = true
07-12 11:35:29.520  7710  7710 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,07-12 11:35:29.520  7680  7731 W HTCLOG  : use specified tag [asset], func [0].
07-12 11:35:29.520  7680  7731 W HTCLOG  : mask=0x18
,07-12 11:35:29.520  7680  7731 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/CResources.apk is neither a directory nor file (type=0).
07-12 11:35:29.530  7680  7731 D HtcThemeUtils: AssetMaanger addAssetPath CResources fail!
,07-12 11:35:29.530  1114  1114 D ValidateNoPeople: setContact(com.htc.updater,0.0,false)
,07-12 11:35:29.530  1114  1114 D PMS     : acquireWL(31f02a5d): PARTIAL_WAKE_LOCK  *vibrator* 0x1 1114 1000 WorkSource{10068}
,07-12 11:35:29.540  3179  3204 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837684, tag: null, isClearable: false, isForDotMatrix: false
,07-12 11:35:29.550  3068  3068 I RemoteViews: apply:com.htc.updater 0 7 1 37
,07-12 11:35:29.560  1114  3247 I ActivityManager: Killing 6737:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
07-12 11:35:29.560  1114  3247 D Process : killProcessQuiet, pid=6737
,07-12 11:35:29.560  1114  3247 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-12 11:35:29.560  3068  3068 I NotificationStackScrollLayout: setBlockTouchEnabled:false
,07-12 11:35:29.610  7616  7616 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-12 11:35:29.630  1114  3891 I ActivityManager: Recipient 6737
,07-12 11:35:29.650  1114  5310 I art     : Explicit concurrent mark sweep GC freed 18088(981KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.618ms total 142.684ms
,07-12 11:35:29.680  7616  7738 D jxcore_app_log: JniHelper::setJavaVM(0xaacc3b70), pthread_self() = -1413278592
,07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6edfae added. We now have 1 listener(s)
07-12 11:35:29.700  1114  3895 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,07-12 11:35:29.700  7616  7738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:3C:62:6A
,07-12 11:35:29.700  7616  7738 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:3C:62:6A"
,07-12 11:35:29.700  7616  7738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 11:35:29.700  7616  7738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:3C:62:6A
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 11:35:29.700  7616  7738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20a215e5 added. We now have 1 listener(s)
07-12 11:35:29.710  7616  7738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 11:35:29.720  7616  7738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:35:29.720  7616  7738 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-12 11:35:29.720  1114  2940 D WifiService: New client listening to asynchronous messages
,07-12 11:35:29.720  7616  7738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-12 11:35:29.720  7616  7738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 11:35:29.720  7616  7738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 11:35:29.720  7616  7738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-12 11:35:29.720  7616  7738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 11:35:29.720  1114  3247 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
07-12 11:35:29.720  7616  7738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:3C:62:6A
,07-12 11:35:29.720  7616  7738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:35:29.720  7616  7738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:35:29.720  7616  7738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:35:29.720  7616  7738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:35:29.720  7616  7738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:35:29.720  7616  7738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:35:29.720  7616  7738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:35:29.720  7616  7738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:35:29.720  7616  7738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:35:29.720  7616  7738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 11:35:29.720  7616  7738 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 11:35:29.720  7616  7738 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 11:35:29.730  1114  1177 D PMS     : releaseHCC(3a8352b9): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
07-12 11:35:29.730  1114  1177 D PMS     : releaseHCC(2134c6fe): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-12 11:35:29.770  7616  7616 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 11:35:29.890  1114  7744 D PMS     : releaseWL(31f02a5d): PARTIAL_WAKE_LOCK  *vibrator* 0x1 WorkSource{10068}
,07-12 11:35:30.210  1114  2928 V AlarmManager: sending alarm PendingIntent{3f1b491b: PendingIntentRecord{14c68ab8 android broadcastIntent}}, i=NextAlarmTracker.trigger, t=0, cnt=1, w=1468316130220, Int=0,
07-12 11:35:30.210  1114  1114 D PMS     : acquireWL(191d5091): PARTIAL_WAKE_LOCK  NextAlarmTracker 0x1 1114 1000 null,
,07-12 11:35:30.370  7616  7749 W jxcore-log: Initializing JXcore engine
07-12 11:35:30.370  7616  7749 W jxcore-log: JXcore engine is ready
,07-12 11:35:30.420  7616  7749 W jxcore-log: Starting JXcore engine,
,07-12 11:35:30.480  7616  7749 W jxcore-log: Platform android,
07-12 11:35:30.480  7616  7749 W jxcore-log: 
07-12 11:35:30.480  7616  7749 W jxcore-log: Process ARCH arm
07-12 11:35:30.480  7616  7749 W jxcore-log: ,
,07-12 11:35:30.490  1114  1146 I ActivityManager: Waited long enough for: ServiceRecord{19412b85 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
07-12 11:35:30.490  1114  1146 I ActivityManager: Resuming delayed broadcast
,07-12 11:35:30.520  1114  1146 I ActivityManager: Start proc 7750:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver,
,07-12 11:35:30.550  7750  7750 W HTCLOG  : use specified tag [FDManager], func [0].,
07-12 11:35:30.550  7750  7750 W HTCLOG  : mask=0x18
,07-12 11:35:30.550   576   576 I art     : Explicit concurrent mark sweep GC freed 8683(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 126us total 30.750ms,
,07-12 11:35:30.570   576   576 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 70us total 17.949ms,
,07-12 11:35:30.580   576   576 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 68us total 13.123ms,
,07-12 11:35:30.600  7616  7749 I jxcore-log: JXcore Cordova bridge is ready!,
07-12 11:35:30.600  7616  7749 I jxcore-log: 
07-12 11:35:30.600  7616  7749 W jxcore-log: JXcore engine is started
,07-12 11:35:30.610  7616  7738 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 11:35:30.610  7616  7616 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 11:35:30.620  7616  7749 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-12 11:35:30.620  7616  7749 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
07-12 11:35:30.620  7750  7750 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
,07-12 11:35:30.620  1114  1133 I ActivityManager: Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
07-12 11:35:30.630  7750  7771 D PowerUtils: getUserIdOfProcess, curUserId = 0
07-12 11:35:30.630  7750  7771 D PowerUtils: isRunningUnderOwner, isOwner = true
,07-12 11:35:30.630  7750  7771 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
07-12 11:35:30.630  7616  7616 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-12 11:35:30.630  7616  7616 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-12 11:35:30.650  1114  3891 D PMS     : acquireWL(211b5bf7): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1114 1000 null
,07-12 11:35:30.650  7616  7738 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
07-12 11:35:30.660  7750  7771 D PowerUsageService: repeat time = 1468317030651
,07-12 11:35:30.670  7616  7616 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-12 11:35:30.670  7616  7616 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-12 11:35:30.680  1114  3507 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,07-12 11:35:30.680  3450  3450 I FeedHostManager: [onResume]
07-12 11:35:30.680  3450  3450 I FeedProviderManager: onResume
07-12 11:35:30.680  3450  4832 I SocialFeedProvider: +onResume
07-12 11:35:30.680  3450  4832 I SocialFeedProvider: updateAccounts - Accounts is no change
07-12 11:35:30.680  3450  4832 I SocialFeedProvider: -onResume
07-12 11:35:30.680  3450  3450 I ConnectivityHelper: [getCurrentConnectionType] no network connection
,07-12 11:35:30.690  3450  3450 I ContextualWidget: onResume
07-12 11:35:30.690  3450  3450 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-12 11:35:30.690  3450  3450 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
07-12 11:35:30.690  3450  4007 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
07-12 11:35:30.690  3450  3450 I ContextualWidget: postSyncRecommendedApps, isReady=true allowAutoSync=true syncMode=1 isEnableRecommend=true
,07-12 11:35:30.690  3450  4007 I ContextualWidget: handleMessage, what=1017 mode=GettingOut maxcount=8
,07-12 11:35:30.690  1114  3435 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-12 11:35:30.690  1114  3891 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-12 11:35:30.690  1114  3437 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,07-12 11:35:30.690  1114  3447 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-12 11:35:30.700  1114  1147 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-12 11:35:30.700  1114  1147 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{35591cdd u0 com.htc.launcher/com.htc.launcher.Launcher}
07-12 11:35:30.700  1114  1147 D StatusBarManagerService: hiding MENU key
07-12 11:35:30.700  3068  3068 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-12 11:35:30.700  3068  3068 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-12 11:35:30.700  3450  3450 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
07-12 11:35:30.700  3450  3450 I ThreadedRenderer: Defer allocateBuffers to drawing time
,07-12 11:35:30.710  1114  3247 I InputMethodManagerService: Disable input method client, pid=7616
07-12 11:35:30.710  3068  3068 I PhoneStatusBar: setImeWindowStatus(false,false)
07-12 11:35:30.710  1114  3247 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,07-12 11:35:30.710  1114  3247 I InputMethodManagerService: Enable input method client, pid=3450
,07-12 11:35:30.710  7616  7616 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,07-12 11:35:30.740  1114  3717 D PMS     : releaseWL(211b5bf7): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-12 11:35:30.750  1114  1147 D StatusBarManagerService: setSystemUiVisibility(0xc0000700),
,07-12 11:35:30.750  3068  3068 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-12 11:35:30.750  1114  1147 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{35591cdd u0 com.htc.launcher/com.htc.launcher.Launcher}
07-12 11:35:30.750  3068  3068 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-12 11:35:30.750  1114  1147 D StatusBarManagerService: hiding MENU key
07-12 11:35:30.760  3450  7772 D HtcTelephonyManager: wrong phone slot in non-dual projects
07-12 11:35:30.770  1114  1146 I ActivityManager: Killing 6758:com.android.smith/1000 (adj 15): empty #17
07-12 11:35:30.770  1114  1146 D Process : killProcessQuiet, pid=6758
07-12 11:35:30.770  1114  1146 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityStack.destroyActivityLocked:3407 
,07-12 11:35:30.830  3450  7772 D HtcTelephonyManager: wrong phone slot in non-dual projects
,07-12 11:35:30.840  3450  7772 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 4,
07-12 11:35:30.840  3450  7772 D libc    : [NET] android_getaddrinfofornet-, err=8
07-12 11:35:30.840  3450  7772 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024,
07-12 11:35:30.840  3450  7772 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-12 11:35:30.840  3450  7772 D libc    : [NET] android_getaddrinfo_proxy+
07-12 11:35:30.840  3450  7772 D libc    : [NET] android_getaddrinfo_proxy get netid:0,
,07-12 11:35:30.840   522  7776 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-12 11:35:30.840   522  7776 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-12 11:35:30.840   522  7776 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-12 11:35:30.840   522  7776 D libc    : [NET] android_getaddrinfofornet-, err=7
07-12 11:35:30.840  3450  7772 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-12 11:35:30.840  3450  7772 E ServerCorridor: BaseException: ServiceUnavailableException java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-12 11:35:30.840  3450  7772 W System.err: com.htc.prism.feed.corridor.exceptions.ServiceUnavailableException: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-12 11:35:30.840  3450  7772 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:192)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:98)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.htc.prism.feed.corridor.RestClient.getString(RestClient.java:367)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.htc.prism.feed.corridor.recommendation.RecommendationNService.getWelcomeAppSuggest(RecommendationNService.java:125)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.syncRecommendedApps(HtcContextualWidgetService.java:374),
07-12 11:35:30.840  3450  7772 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:168)
07-12 11:35:30.840  3450  7772 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 11:35:30.840  3450  7772 W System.err: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:35:30.840  3450  7772 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-12 11:35:30.840  3450  7772 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61),
07-12 11:35:30.840  3450  7772 W System.err: Caused by: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-12 11:35:30.840  3450  7772 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
07-12 11:35:30.840  3450  7772 W System.err: 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
07-12 11:35:30.840  3450  7772 W System.err: 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:403)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:116)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.connect(DelegatingHttpsURLConnection.java:89)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.connect(HttpsURLConnectionImpl.java:25)
07-12 11:35:30.840  3450  7772 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:137)
07-12 11:35:30.840  3450  7772 W System.err: 	... 9 more
07-12 11:35:30.840  7773  7773 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-12 11:35:30.840  7773  7773 W HTCLOG  : mask=0x18
,07-12 11:35:30.890  1114  3500 I ActivityManager: Recipient 6758,
,07-12 11:35:30.980  7750  7771 I PowerUsageList:PowerUsageHelper: calcPower(), PowerProfile::POWER_SCREEN_FULL = 154.8,
,07-12 11:35:30.980  7616  7616 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-12 11:35:30.980  7616  7616 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-12 11:35:30.990  7616  7616 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-12 11:35:30.990  7616  7616 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-12 11:35:30.990  7616  7616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 11:35:30.990  7616  7616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 11:35:30.990  7616  7616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 11:35:30.990  7616  7616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-12 11:35:30.990  7616  7616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6edfae removed from the list
07-12 11:35:30.990  7616  7616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 11:35:30.990  7616  7616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20a215e5 removed from the list
07-12 11:35:30.990  7616  7616 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 11:35:30.990  7616  7616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-12 11:35:30.990  7616  7616 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-12 11:35:31.010  7750  7771 D PowerUtils: getUserIdOfProcess, curUserId = 0
,07-12 11:35:31.020  7750  7771 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,07-12 11:35:31.020  7750  7771 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,07-12 11:35:31.020  7750  7771 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,07-12 11:35:31.030  7750  7771 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,07-12 11:35:31.030  7750  7771 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 10102, sipper.name = com.google.android.talk,
,07-12 11:35:31.040  7616  7616 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7616
,07-12 11:35:31.040  7750  7771 D PowerUsageService: calcPower(), no data
07-12 11:35:31.040  1114  3435 I ActivityManager: Resuming delayed broadcast
,07-12 11:35:31.050  1114  3435 I ActivityManager: Start proc 7777:com.google.android.gm/u0a95 for broadcast com.google.android.gm/.widget.GmailWidgetProvider
,07-12 11:35:31.060  1114  1133 I ActivityManager: Killing 6656:com.htc.cs.pns/u0a119 (adj 15): empty #17
07-12 11:35:31.060  1114  1133 D Process : killProcessQuiet, pid=6656
07-12 11:35:31.060  1114  1133 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 ,
,07-12 11:35:31.070  7777  7777 W HTCLOG  : use specified tag [FDManager], func [0].,
07-12 11:35:31.070  7777  7777 W HTCLOG  : mask=0x18
,07-12 11:35:31.130  7773  7800 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-12 11:35:31.130  7773  7800 W HTCLOG  : mask=0x18
07-12 11:35:31.130  7773  7800 E cutils-trace: Error opening trace file: Permission denied (13)
,07-12 11:35:31.160  1114  3722 I ActivityManager: Recipient 6656,
,07-12 11:35:31.170  7773  7773 D CustomizationManager: ====startRecUseTime====,
07-12 11:35:31.170  7773  7773 D htc.customization.log.level:  is 
07-12 11:35:31.170  7773  7773 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-12 11:35:31.220  7773  7773 D CustomizationManager:  Read ACC file spent 0.027 (s),
07-12 11:35:31.220  7773  7773 D CIDMapFileReader: Parsing tag item name = HTC__001
07-12 11:35:31.220  7773  7773 D CIDMapFileReader: Parsing tag item name = HTC__002
07-12 11:35:31.220  7773  7773 D CIDMapFileReader: Parsing tag item name = HTC__016
,07-12 11:35:31.220  7773  7773 D CIDMapFileReader: Parsing tag item name = HTC__031,
07-12 11:35:31.220  7773  7773 D CIDMapFileReader: Parsing tag item name = HTC__032
07-12 11:35:31.220  7773  7773 D CIDMapFileReader: Parsing tag item name = HTC__102
07-12 11:35:31.220  7773  7773 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-12 11:35:31.220  7773  7773 D CIDMapFileReader: Parsing tag item name = HTC__J15
,07-12 11:35:31.220  7773  7773 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-12 11:35:31.220  7773  7773 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-12 11:35:31.220  7773  7773 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: Parsing tag category name = application,
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: Parsing tag category name = system
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: Parsing tag category name = Settings
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: Parsing tag category name = ACC
,07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 42507
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 21902
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 23420
,07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 22299
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 24002,
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 23210
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 23205
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 23806
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 23430
,07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 23408
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 27205
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0,
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0,
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0,
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-12 11:35:31.220  7773  7773 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-12 11:35:31.230  7773  7773 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-12 11:35:31.230  7773  7773 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-12 11:35:31.230  7773  7773 D CustomizationManager:  Read CID file spent 0.059 (s)
07-12 11:35:31.230  7773  7773 D CustomizationManager:  All configurations done spent 0.059 (s)
07-12 11:35:31.240  3450  4152 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-12 11:35:31.250  1114  3437 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=7773, uid=2000
,07-12 11:35:31.250  1114  1146 D Process : killProcessQuiet, pid=7616,
07-12 11:35:31.250  1114  1146 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-12 11:35:31.250  1114  1146 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
07-12 11:35:31.250  1114  1146 I ActivityManager: Killing 7616:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,07-12 11:35:31.280  1114  1182 W PackageSettings: Skipping PackageSetting{e5b15fd com.example.hello/10193} due to missing metadata
,07-12 11:35:31.310   540   540 W HTCLOG  : use specified tag [Vector], func [0].
07-12 11:35:31.310   540   540 W HTCLOG  : mask=0x18
,07-12 11:35:31.310  7777  7818 I Gmail   : getAccountsCursor
,07-12 11:35:31.320  1114  3437 I ActivityManager: Recipient 7616
07-12 11:35:31.320  1114  2940 D WifiService: Client connection lost with reason: 4
,07-12 11:35:31.320  3234  3234 W HTCLOG  : use specified tag [InputEventReceiver], func [0].
07-12 11:35:31.320  3234  3234 W HTCLOG  : mask=0x18
07-12 11:35:31.320  3234  3234 E InputEventReceiver: Looper::removeFd(33) is failed, result(0), input channel 'ClientState{14e42f88 uid 10000 pid 7616} (c)'
,07-12 11:35:31.370  1114  1182 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed,
,07-12 11:35:31.400  1114  1134 I ActivityManager: Start proc 7821:com.google.android.gm.exchange/u0a156 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
07-12 11:35:31.400  3179  3179 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-12 11:35:31.400  7777  7819 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
07-12 11:35:31.400  3179  3179 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false,
07-12 11:35:31.400  4250  4692 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-12 11:35:31.400  1114  3500 D PMS     : acquireWL(6a530e7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4250 10020 WorkSource{10020 com.google.android.gms}
07-12 11:35:31.400  4952  4952 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
07-12 11:35:31.400  1114  2937 V NetworkPolicy: ACTION_UID_REMOVED for uid=10000
07-12 11:35:31.400  4952  4952 D [MirrorLinkServer]MirrorLinkServer: ACTION_PACKAGE_REMOVED intent received
07-12 11:35:31.400  1114  3437 W ActivityManager: Spurious death for ProcessRecord{22e66494 7616:com.test.thalitest/u0a0}, curProc for 7616: null
07-12 11:35:31.400  4952  4952 D [MirrorLinkServer]MirrorLinkServer: Counter : 1
07-12 11:35:31.400  1114  2936 D PMS     : acquireWL(2d361b3d): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1114 1000 null
07-12 11:35:31.400  4952  4952 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
,07-12 11:35:31.410  1114  3447 D PMS     : releaseWL(6a530e7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
07-12 11:35:31.410  3644  4102 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,07-12 11:35:31.410  7821  7821 W HTCLOG  : use specified tag [FDManager], func [0].,
07-12 11:35:31.410  7821  7821 W HTCLOG  : mask=0x18
07-12 11:35:31.410  4250  4250 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 11:35:31.410  1114  2931 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-12 11:35:31.410  4952  4952 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_REMOVED
07-12 11:35:31.410  4952  4952 D [MirrorLinkServer]MirrorLinkServer: Application Removed
07-12 11:35:31.420  4952  4952 D [MirrorLinkServer]MirrorLinkServer:  Application removed : com.test.thalitest
07-12 11:35:31.420  4952  4952 D [MirrorLinkServer]d: onApplicationRemoved
07-12 11:35:31.420  4952  4952 I [MirrorLinkServer]d: Package name found : com.test.thalitest
07-12 11:35:31.420  4952  7843 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
,07-12 11:35:31.420  3644  4102 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,07-12 11:35:31.420  4952  4952 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
07-12 11:35:31.420  4952  4952 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
07-12 11:35:31.420  4952  4952 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
07-12 11:35:31.420  4952  4952 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
07-12 11:35:31.420  4952  4952 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
07-12 11:35:31.420  3644  4102 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
,07-12 11:35:31.440  1114  2936 D PMS     : releaseWL(2d361b3d): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-12 11:35:31.440  1114  2937 V NetworkPolicy: writePolicyLocked()
,07-12 11:35:31.440  3644  4102 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
07-12 11:35:31.440  3450  3450 I art     : Explicit concurrent mark sweep GC freed 39355(2MB) AllocSpace objects, 39(2MB) LOS objects, 30% free, 37MB/53MB, paused 1.167ms total 80.162ms
,07-12 11:35:31.450  7777  7834 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-12 11:35:31.450  7777  7834 W HTCLOG  : mask=0x18
07-12 11:35:31.450  3407  3407 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
07-12 11:35:31.460  3644  4102 E ExternalAccountType: Unsupported attribute readOnly
07-12 11:35:31.460  1114  1145 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
07-12 11:35:31.460  1114  2937 D NetworkPolicy: notifyPoliciesChangeLocked: no change
07-12 11:35:31.460  1114  2937 V NetworkPolicy: updateNetworkEnabledLocked()
07-12 11:35:31.460  1114  2937 V NetworkPolicy: updateNotificationsLocked()
,07-12 11:35:31.480  1114  3247 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=7777, uid=10095, userID:0
,07-12 11:35:31.490  1114  3717 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-12 11:35:31.490  1114  3435 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=7777, uid=10095, userID:0
,07-12 11:35:31.490  1114  1134 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-12 11:35:31.500  1114  1134 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=1, flag=1, pid=7777, uid=10095, userID:0
,07-12 11:35:31.500  1114  1133 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=7777, uid=10095, userID:0
,07-12 11:35:31.500  7821  7821 I Exchange: EasService.onCreate
,07-12 11:35:31.510  7777  7848 I Gmail   : Observing account changes for notifications
,07-12 11:35:31.510  1114  3500 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=1, flag=1, pid=7777, uid=10095, userID:0
,07-12 11:35:31.510  1114  3436 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=7777, uid=10095, userID:0
,07-12 11:35:31.520  7821  7853 I Exchange: RestartPingTask
,07-12 11:35:31.530  7710  7736 I HtcModeClient: handler message = 4011
,07-12 11:35:31.530  7710  7736 D HtcModeClient: getConnectionCheckCount first 0
07-12 11:35:31.530  7710  7736 D HtcModeClient: getConnectionCheckCount count = 1
07-12 11:35:31.530  7710  7736 E HtcModeClient: Check connection and retry 2 times.
,07-12 11:35:31.530  7710  7736 D HtcModeClient: setConnectionCheckCount count = 2
07-12 11:35:31.530  1114  1182 I art     : Explicit concurrent mark sweep GC freed 23268(1820KB) AllocSpace objects, 5(532KB) LOS objects, 33% free, 17MB/26MB, paused 1.460ms total 157.733ms
07-12 11:35:31.530  7710  7736 D HtcModeClient: setupRestart delayedTime = 3000
07-12 11:35:31.530  7777  7777 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 11:35:31.540  7821  7821 I Exchange: RestartPingsTask did not start any pings.
07-12 11:35:31.540  1114  1145 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-12 11:35:31.540  7821  7821 I Exchange: PSS stopIfIdle
07-12 11:35:31.540  7821  7821 I Exchange: PSS has no active accounts; stopping service.
,07-12 11:35:31.540  7710  7710 D HtcModeClient: setBtPriority priority = on,
,07-12 11:35:31.540  7710  7710 D HtcModeClient: unbindBlueToothService
07-12 11:35:31.540  7710  7710 D HtcModeClient: Don't start project servcice
07-12 11:35:31.540  7710  7710 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
07-12 11:35:31.540  7710  7710 D HtcModeClient: connectState: CONNECTION_READY = false
07-12 11:35:31.540  7710  7710 D SilentMusic: call stop
,07-12 11:35:31.540  4250  4250 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 11:35:31.540  4250  4250 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 11:35:31.540  7710  7710 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
07-12 11:35:31.540  7710  7737 W CANMesgAgentLocalSocket: read the terminate packet, so break
07-12 11:35:31.550  1114  1114 W PackageManager: Unable to load service info ResolveInfo{f649042 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-12 11:35:31.550  1114  1114 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-12 11:35:31.550  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-12 11:35:31.550  1114  1114 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,07-12 11:35:31.550  7710  7710 D HtcModeClient: onDestroy
07-12 11:35:31.560  7773  7773 I art     : System.exit called, status: 0
07-12 11:35:31.560  7773  7773 W HTCLOG  : use specified tag [Vector], func [0].
07-12 11:35:31.560  7773  7773 W HTCLOG  : mask=0x18
,07-12 11:35:31.600  7777  7861 E Gmail   : Error finding the version of the Email provider.....
07-12 11:35:31.600  7777  7861 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-12 11:35:31.600  7777  7861 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-12 11:35:31.600  7777  7861 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
07-12 11:35:31.600  7777  7861 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
07-12 11:35:31.600  7777  7861 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65),
07-12 11:35:31.600  7777  7861 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:35:31.600  7777  7861 E Gmail   : 	at android.os.Looper.loop(Looper.java:155)
07-12 11:35:31.600  7777  7861 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:35:31.600  7777  7861 W EmailMigration: We do not support migrating this version of the Email provider.
,07-12 11:35:31.610  7821  7821 I Exchange: onDestroy,
,07-12 11:35:31.620  1114  3895 D Process : killProcessQuiet, pid=6835
07-12 11:35:31.620  1114  3895 I ActivityManager: Killing 6835:com.htc.usage/1000 (adj 15): empty #17
07-12 11:35:31.620  1114  3895 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-12 11:35:31.660  1114  1114 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
,07-12 11:35:31.770  1114  3500 I ActivityManager: Recipient 6835
,07-12 11:35:31.840  3450  3799 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,07-12 11:35:31.840  3450  3799 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-12 11:35:31.850  3376  3376 D Nfc-Utils: isNxpCodebase: isNxp=false
,07-12 11:35:31.850  1114  2949 I ActivityManager: Delay finish: com.google.android.gm/.GmailReceiver
07-12 11:35:31.850  1114  1133 D PMS     : acquireWL(27d59957): PARTIAL_WAKE_LOCK  Icing 0x1 6474 10020 WorkSource{10020 com.google.android.gms}
,07-12 11:35:31.860  1114  3717 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=6474, uid=10020, userID:0
,07-12 11:35:31.860  7777  7834 I Gmail   : getAccountsCursor
07-12 11:35:31.860  1114  2949 D PMS     : releaseWL(27d59957): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,07-12 11:35:31.860  4250  4250 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:35:31.870  7777  7864 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.,
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
,07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.W(SourceFile:999),
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:98)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-12 11:35:31.870  7777  7864 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:35:31.870  1114  1134 D PMS     : acquireWL(329396ae): PARTIAL_WAKE_LOCK  Icing 0x1 6474 10020 WorkSource{10095 com.google.android.gm}
07-12 11:35:31.870  7777  7864 E Gmail   : Error handling intent Intent { act=com.android.mail.action.update_notification typ=application/gmail-ls flg=0x10 cmp=com.google.android.gm/.GmailIntentService (has extras) }
07-12 11:35:31.870  7777  7864 E Gmail   : android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 11:35:31.870  7777  7864 E Gmail   : ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at com.google.android.gm.provider.MailEngine.W(SourceFile:999)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:98)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.os.Looper.loop(Looper.java:155)
07-12 11:35:31.870  7777  7864 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:35:31.880  1114  1133 D Process : killProcessQuiet, pid=6864
07-12 11:35:31.880  1114  1133 I ActivityManager: Killing 6864:com.htc.WifiRouter/u0a134 (adj 15): empty #17
07-12 11:35:31.880  1114  1133 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-12 11:35:32.050  1114  3446 I ActivityManager: Recipient 6864
,07-12 11:35:32.050  1114  2940 D WifiService: Client connection lost with reason: 4,
,07-12 11:35:32.110  4250  4250 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:35:32.140  7777  7870 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.,
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at com.google.android.gm.provider.ax.run(SourceFile:1023)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-12 11:35:32.140  7777  7870 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:35:32.150  7777  7870 W GAV2    : Thread[MailEngine creation,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
07-12 11:35:32.150  7777  7870 E AndroidRuntime: FATAL EXCEPTION: MailEngine creation
07-12 11:35:32.150  7777  7870 E AndroidRuntime: Process: com.google.android.gm, PID: 7777
07-12 11:35:32.150  7777  7870 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.app.C,ontextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at com.google.android.gm.provider.ax.run(SourceFile:1023)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-12 11:35:32.150  7777  7870 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:35:32.150  1114  3446 E ActivityManager: App crashed! Process: com.google.android.gm
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: Can't write: system_app_crash
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 11:35:32.170  1114  7872 E DropBoxManagerService: 	... 5 more
07-12 11:35:32.170  7777  7835 I Gmail   : getAccountsCursor
07-12 11:35:32.190  6474  6613 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
07-12 11:35:32.190  1114  2928 V AlarmManager: sending alarm PendingIntent{316a8f37: PendingIntentRecord{3d8beca4 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1468316132188, Int=0
07-12 11:35:32.190  4250  4250 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 11:35:32.190   573   711 W HTCLOG  : use specified tag [ThermalEngine], func [0].
07-12 11:35:32.200  1114  3247 I ActivityManager: Killing 7026:com.android.vending/u0a57 (adj 15): empty #17
07-12 11:35:32.190   573   711 W HTCLOG  : mask=0x18
07-12 11:35:32.200  1114  3247 D Process : killProcessQuiet, pid=7026
07-12 11:35:32.200  1114  3247 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,07-12 11:35:32.220  1114  1147 D StatusBarManagerService: setSystemUiVisibility(0xc0000000)
07-12 11:35:32.220  3068  3068 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-12 11:35:32.220  1114  1147 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2661c85b u0 Application Error: com.google.android.gm}
07-12 11:35:32.220  3068  3068 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-12 11:35:32.220  1114  1147 D StatusBarManagerService: hiding MENU key
07-12 11:35:32.230  3407  3634 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
07-12 11:35:32.230  3407  3634 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,07-12 11:35:32.330  1114  3717 I ActivityManager: Recipient 7026
,07-12 11:35:32.410  6474  7868 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-12 11:35:32.410  6474  7868 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-12 11:35:32.410  6474  7868 W HTCLOG  : mask=0x18
07-12 11:35:32.410  6474  7868 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/icing_contacts.db, handle: 0x557ed7fc50
,07-12 11:35:32.440  1114  2928 I ActivityManager: Start proc 7873:com.htc.mobiledata:remote/u0a39 for service com.htc.mobiledata/.MobileDataService
07-12 11:35:32.440  1114  2928 V AlarmManager: sending alarm PendingIntent{4de2c3c: PendingIntentRecord{367b4dc5 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=54849, Int=0
,07-12 11:35:32.470  6474  7868 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQor84Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
07-12 11:35:32.470  6474  7868 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjMgKDI4Njc2MzctMDQ4KRjgq-AR
07-12 11:35:32.470  6474  7868 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsKvgEQ
07-12 11:35:32.470  6474  7868 I GCore-Chimera-Crash: ==
,07-12 11:35:32.470  6474  7868 I GCore-Chimera-Crash: GCore-Chimera-Crash
,07-12 11:35:32.480  6474  7868 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
07-12 11:35:32.480  6474  7868 E AndroidRuntime: Process: com.google.android.gms, PID: 6474
07-12 11:35:32.480  6474  7868 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at pdg.a(:com.google.android.gms:290)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at pdg.b(:com.google.android.gms:138)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at pen.a(:com.google.android.gms:382)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at com.google.android.gms.icing.proxy.InternalIcingCorporaChimeraProvider.update(:com.google.android.gms:247)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at com.google.android.chimera.container.ContentProviderProxy.update(:com.google.android.gms:457)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at pfk.call(:com.google.android.gms:1333)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at pfl.call(:com.google.android.gms:1266)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at com.google.android.gms.icing.proxy.UpdateIcingCorporaChimeraService.a(:com.google.android.gms:244)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at com.google.android.gms.icing.proxy.UpdateIcingCorporaChimeraService.onHandleIntent(:com.google.android.gms:2177)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: ,	at bdz.handleMessage(:com.google.android.gms:65)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-12 11:35:32.480  6474  7868 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:35:32.480  7873  7873 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 11:35:32.480  7873  7873 W HTCLOG  : mask=0x18
07-12 11:35:32.480  1114  3500 E ActivityManager: App crashed! Process: com.google.android.gms
,07-12 11:35:32.480  1114  7889 E DropBoxManagerService: Can't write: system_app_crash
07-12 11:35:32.480  1114  7889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
07-12 11:35:32.480  1114  7889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 11:35:32.480  1114  7889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 11:35:32.480  1114  7889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 11:35:32.480  1114  7889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-12 11:35:32.480  1114  7889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-12 11:35:32.480  1114  7889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-12 11:35:32.480  1114  7889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 11:35:32.480  1114  7889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 11:35:32.480  1114  7889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 11:35:32.480  1114  7889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 11:35:32.480  1114  7889 E DropBoxManagerService: 	... 5 more
,07-12 11:35:32.480  6474  6613 E Icing   : Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,07-12 11:35:32.480  1114  2949 D PMS     : releaseWL(329396ae): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,07-12 11:35:32.490  1114  3437 I ActivityManager: Resuming delayed broadcast
,07-12 11:35:32.500  1114  3436 I ActivityManager: Delay finish: com.google.android.gm/.GmailReceiver
,07-12 11:35:32.510  7777  7895 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235),
,07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.W(SourceFile:999)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:98)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: ,	at android.os.Looper.loop(Looper.java:155)
07-12 11:35:32.510  7777  7895 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:35:32.510  7777  7895 E Gmail   : Error handling intent Intent { act=com.android.mail.action.update_notification typ=application/gmail-ls flg=0x10 cmp=com.google.android.gm/.GmailIntentService (has extras) }
07-12 11:35:32.510  7777  7895 E Gmail   : android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at com.google.android.gm.provider.MailEngine.W(SourceFile:999)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:98)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.os.Looper.loop(Looper.java:155)
07-12 11:35:32.510  7777  7895 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:35:32.510  1114  3895 I ActivityManager: Resuming delayed broadcast
,07-12 11:35:32.520  7415  7415 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-12 11:35:32.530  1114  3437 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
07-12 11:35:32.530  7415  7899 I DFPI.ApkInstallService: onHandleIntent
07-12 11:35:32.530  7415  7899 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-12 11:35:32.540  7415  7899 I DFPI.SystemPropertiesUtil: value = HTC__102
07-12 11:35:32.540  7415  7899 I DFPI.ApkInstallService: deviceCID = HTC__102
07-12 11:35:32.550  1114  2949 I ActivityManager: Resuming delayed broadcast,
07-12 11:35:32.540  7415  7899 D DFPI.ApkInstallService: check CID = HTC__102
07-12 11:35:32.540  7415  7899 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-12 11:35:32.550  1114  3436 I ActivityManager: Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,07-12 11:35:32.570  1114  1134 I ActivityManager: Start proc 7902:com.htc.mobiledata/u0a39 for content provider com.htc.mobiledata/.MobileDataProvider
,07-12 11:35:32.580  7902  7902 W HTCLOG  : use specified tag [FDManager], func [0].
07-12 11:35:32.580  7902  7902 W HTCLOG  : mask=0x18
,07-12 11:35:32.590  1114  1146 I ActivityManager: Waited long enough for: ServiceRecord{19842703 u0 com.htc.backup/.notifications.contextual.ContextualReminderControlService}
07-12 11:35:32.590  1114  1146 I ActivityManager: Resuming delayed broadcast
,07-12 11:35:32.600  7568  7568 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-12 11:35:32.610  7568  7568 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-12 11:35:32.610  1114  3895 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,07-12 11:35:32.610  7568  7923 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,07-12 11:35:32.610  7568  7923 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-12 11:35:32.610  7568  7923 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-12 11:35:32.610  7568  7923 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-12 11:35:32.610  7568  7923 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-12 11:35:32.610  7568  7923 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
,07-12 11:35:32.610  7568  7923 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-12 11:35:32.610  7568  7923 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
,07-12 11:35:32.610  7568  7923 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 11:35:32.610  1114  3247 I ActivityManager: Resuming delayed broadcast
07-12 11:35:32.610  7568  7923 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-12 11:35:32.610  7568  7923 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-12 11:35:32.610  7568  7923 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-12 11:35:32.610  7568  7923 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-12 11:35:32.610  7568  7923 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-12 11:35:32.610  7568  7923 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-12 11:35:32.610  7568  7923 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-12 11:35:32.610  7568  7923 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-12 11:35:32.610  7568  7923 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-12 11:35:32.610  7568  7923 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-12 11:35:32.610  7568  7923 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-12 11:35:32.610  7568  7923 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-12 11:35:32.610  7568  7923 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-12 11:35:32.610  7568  7923 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-12 11:35:32.610  7568  7923 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-12 11:35:32.610  7568  7923 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-12 11:35:32.610  7568  7923 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
,07-12 11:35:32.620  7337  7413 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
,07-12 11:35:32.620  1114  3722 I ActivityManager: Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,07-12 11:35:32.640  7902  7926 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.mobiledata/shared_prefs/sp_BOOTUP.xml to backup file /data/user/0/com.htc.mobiledata/shared_prefs/sp_BOOTUP.xml.bak
,07-12 11:35:32.650  7873  7900 D MdScBoot: [538.1.] 30@-093502 -> 40
,07-12 11:35:32.650  7873  7900 D MdScBootUi: [538.1.2.] boot 118 warn0
,07-12 11:35:32.670  7337  7924 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
07-12 11:35:32.670  7337  7924 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-12 11:35:32.670  7337  7924 W HTCLOG  : mask=0x18
07-12 11:35:32.670  7337  7924 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.music/databases/music.db, handle: 0x557ed6f290
,07-12 11:35:32.670  7873  7928 D MdScSimSt: [538.1.2.] qry 118: 0+1 running 0
,07-12 11:35:32.680  7337  7924 E AndroidRuntime: FATAL EXCEPTION: MediaStoreImportService
07-12 11:35:32.680  7337  7924 E AndroidRuntime: Process: com.google.android.music:main, PID: 7337
07-12 11:35:32.680  7337  7924 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at com.google.android.music.store.BaseStore.beginWriteTxn(BaseStore.java:58)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at com.google.android.music.store.Store.beginWriteTxn(Store.java:226)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at com.google.android.music.store.MediaStoreImporter.importAudioFiles(MediaStoreImporter.java:504)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at com.google.android.music.store.MediaStoreImporter.importNow(MediaStoreImporter.java:307)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:222)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at com.google.android.music.store.Store.importMediaStore(Store.java:9978)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-12 11:35:32.680  7337  7924 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:35:32.680  1114  1134 E ActivityManager: App crashed! Process: com.google.android.music:main
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: Can't write: system_app_crash
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456),
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 11:35:32.680  1114  7929 E DropBoxManagerService: 	... 5 more
,07-12 11:35:32.810   498   498 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-12 11:35:32.810   498   498 E qdoverlay: Bad ov dump:  mdp_overlay z=4 alpha=255 mask=-1 flags=0x220000 id=8
07-12 11:35:32.810   498   498 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
,07-12 11:35:32.810   498   498 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 11:35:32.810   498   498 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 11:35:32.810   498   498 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-12 11:35:32.810   498   498 E qdoverlay: Bad ov dump:  mdp_overlay z=3 alpha=255 mask=-1 flags=0x220000 id=8
07-12 11:35:32.810   498   498 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-12 11:35:32.810   498   498 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 11:35:32.810   498   498 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 11:35:32.810   498   498 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown,
07-12 11:35:32.810   498   498 E qdoverlay: Bad ov dump:  mdp_overlay z=2 alpha=255 mask=-1 flags=0x220000 id=8
07-12 11:35:32.810   498   498 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-12 11:35:32.810   498   498 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 11:35:32.810   498   498 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 11:35:32.810   498   498 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-12 11:35:32.810   498   498 E qdoverlay: Bad ov dump:  mdp_overlay z=1 alpha=255 mask=-1 flags=0x220000 id=8,
07-12 11:35:32.810   498   498 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-12 11:35:32.810   498   498 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 11:35:32.810   498   498 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 11:35:32.810   498   498 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-12 11:35:32.810   498   498 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=8
07-12 11:35:32.810   498   498 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888,
07-12 11:35:32.810   498   498 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 11:35:32.810   498   498 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-12 11:35:32.810   498   498 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-12 11:35:32.810   498   498 E qdoverlay: MdpCtrl close error in unset
,07-12 11:35:32.820   499   499 W HTCLOG  : use specified tag [TPD], func [0].,
07-12 11:35:32.820   499   499 W HTCLOG  : mask=0x18
07-12 11:35:32.820   499   499 E TPD     : [TPD][ERR] can't open /proc/808/status...
,07-12 11:35:32.850  7873  7928 D MdScSimSt: [538.1.2.] resp 118: 0+1 remain 0+1
,07-12 11:35:32.880   498   825 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=0 : Cannot send after transport endpoint shutdown,
07-12 11:35:32.880   498   825 E SurfaceFlinger: eventControl(0, 0) failed Cannot send after transport endpoint shutdown
,07-12 11:35:33.000   498   498 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown,
07-12 11:35:33.000   498   498 E qdoverlay: MdpCtrl close error in unset
07-12 11:35:33.000   498   498 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-12 11:35:33.000   498   498 E qdoverlay: MdpCtrl close error in unset
07-12 11:35:33.000   498   498 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-12 11:35:33.000   498   498 E qdoverlay: MdpCtrl close error in unset
07-12 11:35:33.000   498   498 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-12 11:35:33.000   498   498 E qdoverlay: MdpCtrl close error in unset

```
