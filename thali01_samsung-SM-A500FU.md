#### Test 62509094c3227b2_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/dex2oat ( 4138): ----------------------------------------------------
I/dex2oat ( 4138): <SS>: S T A R T I N G . . .
I/dex2oat ( 4138): <SS>: Zip is absent. Canceled.
I/dex2oat ( 4138): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=45 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
--------- beginning of system
I/ActivityManager( 1016): Killing 3349:com.dropbox.android/u0a92 (adj 15): empty #31
I/CrashAnrDetector( 1016): onPackageAdded : com.test.thalitest
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3948): took 0.523698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93bd410 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93bd5d0 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3948): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/AMMetaDataParserService( 3948): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3948): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3948): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131034112
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/AMMetaDataParserService( 3948): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3948): getResourceTypeNamexml
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3948): took 0.590729ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93b7a88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93bd5d0 counterpartCT=4 counterpartW=96 counterparth=96
V/GLSActivity( 1821): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3948): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Babel_StickerModule( 4042): App launched.
I/DBG_POLICYDM( 4122): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
I/DBG_POLICYDM( 4122): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3948): took 0.694635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93b7a88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb939f310 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3948): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
D/Finsky  ( 3931): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/GCoreNlp( 1821): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
V/Babel   ( 4042): babel boot account: SMS
W/Babel   ( 4042): EsDatabaseHelper.static should not be called on main thread [called on main thread]
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3948): took 0.635052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb939f638 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9395708 counterpartCT=4 counterpartW=96 counterparth=96
W/Babel   ( 4042): java.lang.Exception
W/Babel   ( 4042): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4042): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 4042): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4042): 	at ckh.a(SourceFile:67)
W/Babel   ( 4042): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4042): 	at bhn.a(SourceFile:301)
W/Babel   ( 4042): 	at bhn.a(SourceFile:137)
W/Babel   ( 4042): 	at bhn.a(SourceFile:126)
W/Babel   ( 4042): 	at bhn.a(SourceFile:159)
W/Babel   ( 4042): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4042): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4042): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4042): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4042): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4042): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4042): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4042): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4042): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4042): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4042): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/Babel   ( 4042): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
W/Babel   ( 4042): java.lang.Exception
W/Babel   ( 4042): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4042): 	at aes.a(SourceFile:145)
W/Babel   ( 4042): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4042): 	at ckh.a(SourceFile:67)
W/Babel   ( 4042): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4042): 	at bhn.a(SourceFile:301)
W/Babel   ( 4042): 	at bhn.a(SourceFile:137)
W/Babel   ( 4042): 	at bhn.a(SourceFile:126)
W/Babel   ( 4042): 	at bhn.a(SourceFile:159)
W/Babel   ( 4042): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4042): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4042): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4042): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4042): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4042): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4042): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4042): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4042): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4042): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4042): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/AMMetaDataParserService( 3948): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
I/DBG_POLICYDM( 4122): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
W/libprocessgroup( 1016): failed to open /acct/uid_10086/pid_3261/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3349/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1016): applying state to connected service
I/DBG_POLICYDM( 4122): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3948): took 0.640103ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93bca98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9382d50 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3948): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
W/InstanceID/Rpc( 2067): Found 10012
I/DBG_POLICYDM( 4122): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 4122): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131034113
D/Finsky  ( 3931): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/AMMetaDataParserService( 3948): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3948): getResourceTypeNamexml
I/DBG_POLICYDM( 4122): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3948): took 1.063073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb939e710 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb93bc0e0 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
V/Babel   ( 4042): babel boot account: thalitester@gmail.com
I/AMMetaDataParserService( 3948): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
W/Babel   ( 4042): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
W/Babel   ( 4042): java.lang.Exception
W/Babel   ( 4042): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4042): 	at aes.a(SourceFile:145)
W/Babel   ( 4042): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4042): 	at ckh.a(SourceFile:67)
W/Babel   ( 4042): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4042): 	at bhn.a(SourceFile:301)
W/Babel   ( 4042): 	at bhn.a(SourceFile:137)
W/Babel   ( 4042): 	at bhn.a(SourceFile:126)
W/Babel   ( 4042): 	at bhn.a(SourceFile:159)
W/Babel   ( 4042): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4042): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4042): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4042): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4042): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4042): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4042): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4042): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4042): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4042): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4042): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 4149): 
D/AndroidRuntime( 4149): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4149): CheckJNI is OFF
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/AndroidRuntime( 4149): readGMSProperty: start
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 4149): readGMSProperty: already setted!!
D/AndroidRuntime( 4149): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4149): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4149): readGMSProperty: end
D/AndroidRuntime( 4149): addProductProperty: start
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 3200): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
I/GFX raster( 3948): took 0.925104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb939e710 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb939f310 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3948): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
I/DBG_POLICYDM( 4122): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 4122): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 4122): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 4122): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 4122): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3948): took 0.610364ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9395538 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9395708 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/AMMetaDataParserService( 3948): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3948): took 0.608750ms for 96*96 texture 0
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93b7a88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9382d50 counterpartCT=4 counterpartW=96 counterparth=96
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3948): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
E/Zygote  ( 4171): MountEmulatedStorage()
I/libpersona( 4171): KNOX_SDCARD checking this for 10035
E/Zygote  ( 4171): v2
I/libpersona( 4171): KNOX_SDCARD not a persona
I/SELinux ( 4171): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4171): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4171): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4171 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  282): getCameraInfo: X
E/AffinityControl( 4149): AffinityControl: registerfunction enter
W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  282): getCameraInfo: X
I/ActivityManager( 1016): Killing 3416:com.fmm.dm/1000 (adj 15): empty #31
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 4149): Calling main entry com.android.commands.am.Am
E/Zygote  ( 4185): MountEmulatedStorage()
E/Zygote  ( 4185): v2
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/libpersona( 4185): KNOX_SDCARD checking this for 1000
I/libpersona( 4185): KNOX_SDCARD not a persona
I/GFX raster( 3948): took 0.851250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9395708 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93bf818 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 4185): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4185): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4185): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SSRM:n  ( 1016): SIOP:: AP = 360
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4185 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4122): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
D/TimaKeyStoreProvider( 4171): TimaSignature is unavailable
D/ActivityThread( 4171): Added TimaKeyStore provider
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/DBG_POLICYDM( 4122): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/TimaKeyStoreProvider( 4185): TimaSignature is unavailable
I/DBG_POLICYDM( 4122): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
D/ActivityThread( 4185): Added TimaKeyStore provider
I/DBG_POLICYDM( 4122): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
I/AMMetaDataParserService( 3948): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
I/art     (  303): Explicit concurrent mark sweep GC freed 8731(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 37.285ms
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 18.389ms
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : -2122120936
W/VideoCapabilities( 4042): Unrecognized profile 2130706433 for video/avc
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
D/InputDispatcher( 1016): Focus left window: 1489
W/art     ( 3547): Suspending all threads took: 13.555ms
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, uhalitest
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/Launcher.HomeView( 1489): onPause
D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/GCM     ( 2067): COMPAT: Multi user not supported
D/AndroidRuntime( 4149): Shutting down VM
I/DBG_POLICYDM( 4122): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 942us total 20.478ms
W/AudioCapabilities( 4042): Unsupported mime audio/evrc
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3416/cgroup.procs: No such file or directory
I/GFX raster( 3948): took 0.688802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93bca98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb939f310 counterpartCT=4 counterpartW=96 counterparth=96
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
I/AMMetaDataParserService( 3948): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
W/AudioCapabilities( 4042): Unsupported mime audio/qcelp
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3948): took 0.687396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93bc128 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93bc0e0 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/AudioCapabilities( 4042): Unsupported mime audio/mpeg-L1
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/AudioCapabilities( 4042): Unsupported mime audio/mpeg-L2
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3948): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
D/GCM     ( 1821): COMPAT: Multi user not supported
I/DBG_POLICYDM( 4122): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/AudioCapabilities( 4042): Unsupported mime audio/x-ms-wma
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 4122): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4211 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/libpersona( 4211): KNOX_SDCARD checking this for 10155
I/GFX raster( 3948): took 0.522709ms for 96*96 texture 0
I/libpersona( 4211): KNOX_SDCARD not a persona
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93bd410 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9382d50 counterpartCT=4 counterpartW=96 counterparth=96
E/Zygote  ( 4211): MountEmulatedStorage()
E/Zygote  ( 4211): v2
I/SELinux ( 4211): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/AudioCapabilities( 4042): Unsupported mime audio/x-ima
I/DBG_POLICYDM( 4122): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
D/SensorService( 1016): [SO] activate (ident=0xb98228f0, enabled=0)
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 4122): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 4211): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/AudioCapabilities( 4042): Unsupported mime audio/qcelp
E/SELinux ( 4211): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/AudioCapabilities( 4042): Unsupported mime audio/evrc
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/ActivityThread( 1489): updateVisibility : ActivityRecord{1640423d token=android.os.BinderProxy@183a3c4f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/AMMetaDataParserService( 3948): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SensorManager( 1016): unregisterListener ::   
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
I/GCoreUlr( 2067): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
D/SensorService( 1016): [SO] changed settle time [1]
D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb98228f0, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
I/DBG_POLICYDM( 4122): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 4122): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/TimaKeyStoreProvider( 4211): TimaSignature is unavailable
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityThread( 4211): Added TimaKeyStore provider
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4122): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
I/DBG_POLICYDM( 4122): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/Launcher.HomeView( 1489): onStop
V/ActivityThread( 1489): updateVisibility : ActivityRecord{1640423d token=android.os.BinderProxy@183a3c4f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/DBG_POLICYDM( 4122): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
I/DBG_POLICYDM( 4122): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/14/06:43:32
I/DBG_POLICYDM( 4122): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 4122): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
I/DBG_POLICYDM( 4122): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 4122): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 4122): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.searchable
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
I/DBG_POLICYDM( 4122): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 4122): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 4122): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 4122): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
W/VideoCapabilities( 4042): Unsupported mime video/wvc1
W/VideoCapabilities( 4042): Unsupported mime video/x-ms-wmv
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1016): isKioskContainerExistOnDevice
I/DBG_POLICYDM( 4122): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
W/art     ( 4149): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948,): Resource data:2131165203
,D/Launcher( 1489): onTrimMemory. Level: 20
,W/VideoCapabilities( 4042): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/ResourcesManager( 3948): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3948): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/VideoCapabilities( 4042): Unsupported mime video/wvc1
,W/VideoCapabilities( 4042): Unsupported mime video/x-ms-wmv
,D/SensorService( 1016): [SO] currT = 44990082064, prevT = 44640258939, diff = 349823125, [0.115 0.383 10.132]
,I/DBG_POLICYDM( 4122): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] ,
D/SensorService( 1016): [SO] 0.115 0.383 10.132
D/SensorService( 1016): [SO] [100 -> 255]
,I/AMMetaDataParserService( 3948): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3948): getResourceTypeNamexml
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/DBG_POLICYDM( 4122): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,D/BootCompletedReceiver( 2067): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2067): Got an BootCompleted event.
,W/VideoCapabilities( 4042): Unsupported mime video/x-ms-wmv7
,I/GFX construct_block_size_descriptor_2d second part( 3948): took 3.102083ms for 0*0 texture 0
,I/CheckinService( 2067): Disabling old GoogleServicesFramework version
,W/VideoCapabilities( 4042): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 4042): Unsupported mime video/mp43
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,E/SPPClientService( 4171): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SPPClientService( 4171): ============PushLog. commonIsShipBuild. stop!
W/VideoCapabilities( 4042): Unsupported mime video/sorenson
,E/SPPClientService( 4171): [PushClientApplication] Push log off : This is Ship build version
,I/GFX generate_partition_tables( 3948): took 10.358645ms for 0*0 texture 0
,I/GFX raster( 3948): took 14.300936ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb956fa60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb956f0b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BootCompletedReceiver( 2067): Will NOT schedule AdAttestation signal task because it's disabled.
,I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4231 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/SystemUpdateService( 2067): onCreate
,E/Zygote  ( 4231): MountEmulatedStorage(),
E/Zygote  ( 4231): v2
I/libpersona( 4231): KNOX_SDCARD checking this for 1000,
I/libpersona( 4231): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Killing 3297:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31,
I/SELinux ( 4231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WebViewFactory( 4211): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/SPPClientService( 4171): PushLog.txt file is not deleted.
,D/SPPClientService( 4171): PushLog.txt file is not deleted.
,W/VideoCapabilities( 4042): Unsupported mime video/mp4v-esdp
,D/SPPClientService( 4171): ============PushLog. stop!
,I/LibraryLoader( 4211): Time to load native libraries: 3 ms (timestamps 5199-5202)
I/LibraryLoader( 4211): Expected native library version number "",actual native library version number ""
,D/TimaKeyStoreProvider( 4231): TimaSignature is unavailable
,D/ActivityThread( 4231): Added TimaKeyStore provider
D/SystemUpdateService( 2067): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/WebViewChromiumFactoryProvider( 4211): Binding Chromium to main looper Looper (main, tid 1) {14f87bca}
I/LibraryLoader( 4211): Expected native library version number "",actual native library version number ""
I/chromium( 4211): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4211): Initializing chromium process, singleProcess=true
,W/art     ( 4211): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4211): ApplicationContext is null in ApplicationStatus
,I/DBG_POLICYDM( 4122): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3948): took 0.757135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93b9828 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb93bbcd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4122): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3948): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,E/Zygote  ( 4256): MountEmulatedStorage()
E/Zygote  ( 4256): v2
I/libpersona( 4256): KNOX_SDCARD checking this for 10041
I/libpersona( 4256): KNOX_SDCARD not a persona
,I/SELinux ( 4256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_3297/cgroup.procs: No such file or directory
,I/SELinux ( 4256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,V/AuthZen ( 2067): Handling intent: android.intent.action.BOOT_COMPLETED,
,I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4256 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3453:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,E/SELinux ( 4256): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/chromium( 4211): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 4211): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 4211): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 4211): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4211): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4211): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4211): Local Branch: 
I/Adreno-EGL( 4211): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4211): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4211):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/CheckinService( 2067): Checking schedule, now: 1457934212767 next: 1458246240395
I/CheckinService( 2067): active receiver: disabled
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaKeyStoreProvider( 4256): TimaSignature is unavailable
,I/GFX raster( 3948): took 0.834115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93b9828 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb93bbcd0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityThread( 4256): Added TimaKeyStore provider
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/8)
,I/AMMetaDataParserService( 3948): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,D/AuthZenEventHandler( 2067): Handling event: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 3200): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,D/KnoxSetupWizardDbHelper( 4231): dbMigrationFlag : false
,I/VideoCapabilities( 4042): Unsupported profile 4 for video/mp4v-es
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.776042ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93b9828 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb93bbcd0 counterpartCT=4 counterpartW=96 counterparth=96
,W/BaseAppContext( 2067): Using Auth Proxy for data requests.
,I/SystemUpdateService( 2067): cancelUpdate (empty URL)
I/SystemUpdateService( 2067): active receiver: disabled
,D/ShortcutReceiver( 4231):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_3453/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3948): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,D/KnoxShortcutUtil( 4231): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4231):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 4231):  shortcut migration not required 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4287): MountEmulatedStorage()
E/Zygote  ( 4287): v2
I/libpersona( 4287): KNOX_SDCARD checking this for 1000
I/libpersona( 4287): KNOX_SDCARD not a persona
,I/SELinux ( 4287): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4287): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4287): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4287 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3484:com.fmm.ds/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4287): TimaSignature is unavailable
,D/ActivityThread( 4287): Added TimaKeyStore provider
,W/chromium( 4211): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,I/SecDataIO(  256): Write to block
,I/SA      ( 4256): [SSP] onCreated
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 2653): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/DBG_DM  ( 3200): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.627552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93bbcd0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb938a1a0 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_DM  ( 3200): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
E/DBG_DM  ( 3200): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3484/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3948): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/Process ( 2653): Sending signal. PID: 2653 SIG: 9
,I/DBG_DM  ( 3200): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.782292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93bbcd0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb938b470 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3948): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/DBG_POLICYDM( 4122): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4122): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,W/art     ( 4211): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager( 1016): Process com.sec.android.app.sysscope (pid 2653)(adj 0) has died(36,1165)
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/SA      ( 4256): [TPM] There is no property file
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/KnoxSetupWizardClient( 4287): isShipMode : 1
I/KnoxSetupWizardClient( 4287): onReceive : android.intent.action.BOOT_COMPLETED
,V/EmergencyMode( 1427): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1427): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2686): Disconnected process message: 10
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/AwContents( 4211): onDetachedFromWindow called when already detached. Ignoring
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SA      ( 4256): [SCU] isHaveSA() - false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SA      ( 4256): [TPM] getModelProperty : null
I/SA      ( 4256): [TPM] getCSCProperty : null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/PhoneWindow( 4211): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4211): *FMB* installDecor flags : -2139027200
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131099648
,I/SA      ( 4256): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4256): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4256): [DM] TFT FEATURE: false
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/BaseAppContext( 2067): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/SystemWebViewEngine( 4211): CordovaWebView is running on device made by: samsung
,W/ResourcesManager( 3948): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3948): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3948): getResourceTypeNamexml
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/Zygote  ( 4320): MountEmulatedStorage()
,E/Zygote  ( 4320): v2
I/libpersona( 4320): KNOX_SDCARD checking this for 10107
I/libpersona( 4320): KNOX_SDCARD not a persona
,I/SELinux ( 4320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4320): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4320 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3497:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,W/art     ( 4211): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 4211): Attempt to remove local handle scope entry from IRT, ignoring
,I/GFX raster( 3948): took 9.484530ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb98c4750 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb98c4a28 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4256): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/SA      ( 4256): [DM] init START
,I/AMMetaDataParserService( 3948): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4320): TimaSignature is unavailable
,I/SA      ( 4256): [DM] This device is not a Vodafone
,D/ActivityThread( 4320): Added TimaKeyStore provider
,W/ResourceType( 4256): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4256): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4256): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,I/AuthZen ( 2067): Fetching signing key...
,W/ResourceType( 4256): No package identifier when getting value for resource number 0x00000000
,W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3497/cgroup.procs: No such file or directory
,W/ResourceType( 4256): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,D/OpenGLRenderer( 4211): Render dirty regions requested: true
,W/ResourceType( 4256): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4256): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4256): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4256): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,W/System.err( 4287): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 4287): 	at android.os.Parcel.readException(Parcel.java:1544)
D/PhoneWindow( 4211): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 4211): *FMB* isFloatingMenuEnabled return false
W/System.err( 4287): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4287): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4287): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 4287): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4287): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/SystemUpdateService( 2067): onDestroy
,I/SA      ( 4256): [SCU] isHaveSA() - false
I/SA      ( 4256): support phone number id : false
I/SA      ( 4256): [DM] Supports Ref Jpn : true
,I/SA      ( 4256): [DM] init END
,I/SA      ( 4256): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4256): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
I/SA      ( 4256): [OR] onReceive END
D/InputDispatcher( 1016): Focus entered window: 4211
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SRIB_DCS( 4211): log_dcs ThreadedRenderer::initialize entered! 
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/OpenGLRenderer( 4211): Initialized EGL, version 1.4
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/OpenGLRenderer( 4211): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4211): Enabling debug mode 0
,I/ActivityManager( 1016): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4343 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4343): MountEmulatedStorage()
,E/Zygote  ( 4343): v2
I/libpersona( 4343): KNOX_SDCARD checking this for 10042
I/libpersona( 4343): KNOX_SDCARD not a persona
,I/SELinux ( 4343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4343): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/SA      ( 4256): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4256): [ODM] queryOpenData(key= GEO_IP )
,D/TimaKeyStoreProvider( 4343): TimaSignature is unavailable
D/ActivityThread( 4343): Added TimaKeyStore provider
,I/art     ( 1644): Explicit concurrent mark sweep GC freed 5324(220KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.165ms total 35.108ms
,W/SQLiteConnectionPool( 1644): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/SA      ( 4256): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4256): [LBE] REF_JPN : true
,I/SA      ( 4256): [BDC] create
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1191): Icon Only
D/PanelView( 1191): There is/are notification(s) 
W/dex2oat ( 4138): Verification of boolean com.google.android.gms.ads.internal.l.a(com.google.android.gms.ads.internal.client.AdRequestParcel, maps.bc.a, boolean) took 105.846ms
,I/Timeline( 4211): Timeline: Activity_idle id: android.os.BinderProxy@3fcb8307 time:46129
,I/ActivityManager( 1016): Displayed Component not be shown by security: +1s357ms
,I/SamsungIME( 1803): getCurrentCandidateView
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{11a6f5b6 u0 com.test.thalitest/.MainActivity t12} time:46143
W/ActivityManager( 1016): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
W/ResourcesManager( 4343): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/SQLiteLog( 4042): (284) automatic index on conversation_participants_view(conversation_id)
,I/CalendarProvider2( 4343): CalendarProvider2.onCreate() called
,I/SurfaceFlinger(  257): id=10 Removed uhalitest (7/8)
,I/SurfaceFlinger(  257): id=10 Removed uhalitest (-2/8)
,I/AuthZen ( 2067): Signing key fetched successfully!
,W/dex2oat ( 4138): Verification of void com.google.android.gms.common.f$bx$2.<init>(byte[]) took 154.086ms
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 48720(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 27MB/40MB, paused 2.725ms total 199.535ms
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,I/GCoreUlr( 1821): DispatchingService.onCreate()
,I/SA      ( 4256): [DBMV2] getEmailID
,I/SA      ( 4256): [DBMV2] getDataV02ForItems
I/SA      ( 4256): [SSP] query invoked
,D/GCM     ( 1821): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3948): took 2.563072ms for 0*0 texture 0
,I/SA      ( 4256): [SCU] get signed id from samsung account2.0 DB.
,E/SQLiteLog( 4042): (284) automatic index on conversation_participants_view(conversation_id)
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,I/SA      ( 4256): [SCU] get signed id from samsung account1.0 DB.
,E/SQLiteLog( 4042): (284) automatic index on conversation_participants_view(conversation_id)
,I/DBG_DM  ( 3200): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/SA      ( 4256): [BDC] destroy
,I/GFX generate_partition_tables( 3948): took 8.860991ms for 0*0 texture 0
,I/GFX raster( 3948): took 12.403126ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93c0370 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb93bffe8 counterpartCT=4 counterpartW=96 counterparth=96
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/ActivityManager( 1016): Killing 3515:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,W/BaseAppContext( 2067): Using Auth Proxy for data requests.
,I/DBG_DM  ( 3200): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3200): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3200): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,W/BindingManager( 4211): Cannot call determinedVisibility() - never saw a connection for the pid: 4211
,I/AMMetaDataParserService( 3948): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/SQLiteLog( 4042): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.823333ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb956fa60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9380180 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/DBG_DM  ( 3200): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,E/SQLiteLog( 4042): (284) automatic index on conversation_participants_view(conversation_id)
,W/libprocessgroup( 1016): failed to open /acct/uid_10060/pid_3515/cgroup.procs: No such file or directory
,D/a       ( 2067): Opening database auth.proximity.permit_store...
,I/ActivityManager( 1016): Killing 3547:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/JsMessageQueue( 4211): Set native->JS mode to OnlineEventsBridgeMode
,D/AuthZenTransactionCache( 2067): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2067): Clearing transaction cache
,I/DBG_DM  ( 3200): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3200): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,W/dex2oat ( 4138): Verification of void com.google.maps.api.android.lib6.gmm6.streetview.f.g() took 103.223ms
,W/dex2oat ( 4138): Verification of void com.google.maps.api.android.lib6.gmm6.streetview.ag.a(long) took 211.447ms
W/dex2oat ( 4138): Verification of void maps.ab.a.<init>(int, int, int, int) took 100.364ms
,I/DBG_DM  ( 3200): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,W/libprocessgroup( 1016): failed to open /acct/uid_10062/pid_3547/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.644115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9382d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb939e710 counterpartCT=4 counterpartW=96 counterparth=96
,E/SMD     (  287): DCD OFF,
,I/DBG_DM  ( 3200): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,W/Auth    ( 1821): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/AlarmManager( 1016): waitForAlarm result :4
,W/dex2oat ( 4138): Verification of void maps.ab.d.<init>(maps.ab.c, maps.ab.b, maps.av.a) took 104.336ms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1821): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AMMetaDataParserService( 3948): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/GCM     ( 1821): GCM config loaded
,W/dex2oat ( 4138): Verification of void maps.ab.i.a(java.lang.String[], int, int, java.util.PriorityQueue) took 159.909ms
,I/DBG_DM  ( 3200): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/art     ( 1821): Explicit concurrent mark sweep GC freed 21548(1257KB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 12MB/21MB, paused 11.768ms total 115.185ms
,I/ActivityManager( 1016): Killing 3324:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,I/DBG_DM  ( 3200): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,W/dex2oat ( 4138): Verification of maps.bu.a maps.ah.g$a$a.g() took 137.370ms
,W/dex2oat ( 4138): Verification of void maps.ai.m.a(maps.bi.b, java.util.Map) took 119.868ms
,I/DBG_DM  ( 3200): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.656250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb8fde570 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93bb630 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3200): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3200): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3200): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/AMMetaDataParserService( 3948): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/dex2oat ( 4138): Verification of boolean maps.ai.x.a(java.lang.String) took 125.972ms
,D/PersistentNotificationBroadcastReceiver( 1821): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/DBG_DM  ( 3200): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,I/DBG_DM  ( 3200): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,W/libprocessgroup( 1016): failed to open /acct/uid_10009/pid_3324/cgroup.procs: No such file or directory
,W/GCoreFlp( 1821): No location to return for getLastLocation()
,W/FusedLocationProvider( 1821): location=null
,D/SamsungIME( 1803): Dismiss ExpandCandiate
,D/jxcore_app_log( 4211): JniHelper::setJavaVM(0xb8fe3450), pthread_self() = -1185637072,
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.726928ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb939e710 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93b75b8 counterpartCT=4 counterpartW=96 counterparth=96
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4211): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4211):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4211):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4211):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4211):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4211): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@218bf182 added. We now have 1 listener(s)
,I/DBG_DM  ( 3200): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3948): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1821): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211): setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4211): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4211): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4211): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4211): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211):     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10cb60c9 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4211): addListener: New listener added - the number of listeners is now 1
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131099648
,I/AMMetaDataParserService( 3948): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3948): getResourceTypeNamexml
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.685521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9397488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93b7510 counterpartCT=4 counterpartW=96 counterparth=96
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4211): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/DBG_DM  ( 3200): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211): setDiscoveryMode: Discovery mode BLE is supported
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211): setAdvertiseTxPowerLevel: 2 -> 3
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4211): setScanMode: 1 -> 2
,I/AMMetaDataParserService( 3948): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/GCoreFlp( 1821): No location to return for getLastLocation()
,W/FusedLocationProvider( 1821): location=null
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/chromium( 4211): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/DBG_DM  ( 3200): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5,
,I/DBG_DM  ( 3200): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842,
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.676823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb938c728 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb93bf818 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519,
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3200): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1016): Killing 3573:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.618594ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93bffe8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb93bfe40 counterpartCT=4 counterpartW=96 counterparth=96
,I/iu.UploadsManager( 2067): End new media; added: 0, uploading: 0, time: 417 ms
,D/StrictMode( 4320): StrictMode policy violation; ~duration=1246 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4320): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4320): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4320): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4320): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4320): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4320): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4320): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4320): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4320): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4320): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4320): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4320): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4320): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 4320): StrictMode policy violation; ~duration=1238 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4320): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4320): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4320): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4320): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4320): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4320): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4320): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4320): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4320): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4320): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4320): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 4320): StrictMode policy violation; ~duration=1161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4320): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4320): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4320): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4320): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4320): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4320): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4320): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4320): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4320): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4320): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4320): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4320): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4320): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4320): StrictMode policy violation; ~duration=1160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4320): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4320): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4320): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4320): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4320): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4320): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4320): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4320): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4320): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4320): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4320): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4320): StrictMode policy violation; ~duration=1159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4320): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4320): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4320): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4320): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4320): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4320): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4320): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4320): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4320): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4320): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4320): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4320): StrictMode policy violation; ~duration=1155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4320): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4320): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4320): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4320): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4320): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4320): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4320): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4320): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4320): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4320): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4320): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4320): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4320): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4320): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4320): 	at com.google.b.a.ca.a(PG:125)
D/St,rictMode( 4320): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4320): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4320): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4320): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4320): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4320): StrictMode policy violation; ~duration=1153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4320): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4320): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4320): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4320): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4320): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4320): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4320): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4320): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4320): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4320): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4320): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4320): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4320): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4320): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4320): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4320): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4320): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4320): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4320): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4320): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4320): StrictMode policy violation; ~duration=1111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4320): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4320): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4320): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4320): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4320): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4320): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4320): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4320): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4320): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4320): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4320): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4320): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4320): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
D/StrictMode( 4320): StrictMode policy violation; ~duration=1110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4320): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4320): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4320): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4320): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4320): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4320): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4320): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4320): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4320): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4320): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4403): MountEmulatedStorage()
E/Zygote  ( 4403): v2
I/libpersona( 4403): KNOX_SDCARD checking this for 1000
I/libpersona( 4403): KNOX_SDCARD not a persona
I/SELinux ( 4403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4403): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4403 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3589:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
D/TimaKeyStoreProvider( 4403): TimaSignature is unavailable
D/ActivityThread( 4403): Added TimaKeyStore provider
,I/DBG_DM  ( 3200): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3200): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 3835): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{f104cc7 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,I/AMMetaDataParserService( 3948): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,I/DBG_DM  ( 3200): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 3200): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,I/DBG_DM  ( 3200): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,E/DBG_DM  ( 3200): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,E/DBG_DM  ( 3200): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@cb54f5
,D/StatusChecker( 4403): onReceive : android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3200): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/StatusChecker( 4403): onReceive : net.mt.init : DONE
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3948): took 0.639115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9382d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9395538 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4423): MountEmulatedStorage()
E/Zygote  ( 4423): v2
I/libpersona( 4423): KNOX_SDCARD checking this for 10116
I/libpersona( 4423): KNOX_SDCARD not a persona
,I/SELinux ( 4423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4423): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4423 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/AMMetaDataParserService( 3948): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
I/ActivityManager( 1016): Killing 3393:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.649844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb8fde570 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93bdf90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/DBG_DM  ( 3200): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/TimaKeyStoreProvider( 4423): TimaSignature is unavailable
,D/ActivityThread( 4423): Added TimaKeyStore provider
,I/DBG_DM  ( 3200): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,W/ContextImpl( 3200): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,D/SettingsProvider( 1016): name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.723020ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb939e710 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93b75b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/SecKeyguardClockSingleView( 1191): Ignore. Because it is same clock text
,I/AMMetaDataParserService( 3948): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/PageBuddyNotiSvc( 4423): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3200): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131099648
,W/ContextImpl( 4423): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,I/AMMetaDataParserService( 3948): getResourceName:com.android.mms:xml/assistant_messaging
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3948): getResourceTypeNamexml
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,I/GFX raster( 3948): took 0.738385ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9397488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93bdf90 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/DBG_DM  ( 3200): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/AMMetaDataParserService( 3948): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,I/PageBuddyNotiSvc( 4423): onCreate mCpBitFlag=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4440): MountEmulatedStorage()
E/Zygote  ( 4440): v2
I/libpersona( 4440): KNOX_SDCARD checking this for 10125
I/libpersona( 4440): KNOX_SDCARD not a persona
,I/SELinux ( 4440): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4440 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 4440): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4440): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1016): failed to open /acct/uid_10014/pid_3589/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4440): TimaSignature is unavailable
,D/ActivityThread( 4440): Added TimaKeyStore provider
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3573/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_3393/cgroup.procs: No such file or directory
I/GFX raster( 3948): took 0.644219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb938c728 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb93bf818 counterpartCT=4 counterpartW=96 counterparth=96
,I/SamsungIME( 1803): getDebugLevel  : 0x4f4c
,I/GCoreUlr( 1821): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/AMMetaDataParserService( 3948): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.628021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93bffe8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb93b75b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
W/ResourcesManager( 4440): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4440): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4440): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1016): mCursor = null
,D/PowerManagerService( 1016): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,W/ResourcesManager( 1191): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3200): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1016): mCursor = null
,D/lights  ( 1016): lcd : 42 +
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/lights  ( 1016): lcd : 42 -
,D/lights  ( 1016): lcd : 19 +
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset,
D/SecContentProvider2( 1016): mCursor = null
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.663073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9382d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb93bfe40 counterpartCT=4 counterpartW=96 counterparth=96
,D/lights  ( 1016): lcd : 19 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/GCoreUlr( 1821): Unbound from all location providers
I/GCoreUlr( 1821): Place inference reporting - stopped
,I/DBG_DM  ( 3200): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/AMMetaDataParserService( 3948): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/KnoxNotification( 1191): ----- inflateViews : modified publicViewLocal -----
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/KnoxNotification( 1191): ----- inflateViews : modified KnoxViewLocal -----
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1016): mCursor = null
,D/PersonaManager( 1191): PersonaID is invalid or persona doesn't exists. : 0
,I/SamsungIME( 1803): getDebugLevel  : 0x4f4c
,I/DBG_DM  ( 3200): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3200): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 3200): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,D/PersonaManager( 1191): isKioskContainerExistOnDevice
,D/PersonaManager( 1191): isKioskContainerExistOnDevice
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.632657ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb8fde570 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93b7510 counterpartCT=4 counterpartW=96 counterparth=96
,I/PhoneStatusBar( 1191): Icon Only
,I/StatusBar( 1191): Icon Only
,D/PanelView( 1191): There is/are notification(s) 
D/PanelView( 1191): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1191): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1191): Icon Only
I/StatusBar( 1191): Icon Only
,D/PanelView( 1191): There is/are notification(s) 
D/PanelView( 1191): kidsfalse mQsExpansionEnabled:true
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/GCoreUlr( 1821): DispatchingService.onDestroy()
I/GCoreUlr( 1821): Stopping handler for UlrDispSvcFast
,I/AMMetaDataParserService( 3948): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/QuickConnect( 4440): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4440): Util.setSCRunningSetting - [value]0
,I/SamsungIME( 1803): KeybaordView init() : load resources
,D/SettingsProvider( 1016): name = scon_is_running
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
,D/SettingsProvider( 1016): selectionArgs: 10125
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1016): ret = -1
,I/GCoreUlr( 1821): Unbound from all location providers
,I/GCoreUlr( 1821): Place inference reporting - stopped
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/SecKeyguardClockSingleView( 1191): Ignore. Because it is same clock text
,I/QuickConnect( 4440): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,D/OpenGLRenderer( 3200): Render dirty regions requested: true
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/PanelView( 1191): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/GFX raster( 3948): took 0.720729ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb939e710 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9395538 counterpartCT=4 counterpartW=96 counterparth=96
,I/QuickConnect( 4440): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3948): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=4, Uoast
,E/Zygote  ( 4458): MountEmulatedStorage(),
E/Zygote  ( 4458): v2
I/libpersona( 4458): KNOX_SDCARD checking this for 10131,
I/libpersona( 4458): KNOX_SDCARD not a persona
,I/SELinux ( 4458): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4458 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 4458): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4458): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 60 -> 60
D/DisplayPowerController( 1016): animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,D/SRIB_DCS( 3200): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 3200): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3200): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3200): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3200): Local Branch: 
I/Adreno-EGL( 3200): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3200): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3200):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/OpenGLRenderer( 3200): Initialized EGL, version 1.4
D/TimaKeyStoreProvider( 4458): TimaSignature is unavailable
,D/ActivityThread( 4458): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131099648
,D/lights  ( 1016): lcd : 45 +
,I/AMMetaDataParserService( 3948): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3948): getResourceTypeNamexml
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.700104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9397488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93b7510 counterpartCT=4 counterpartW=96 counterparth=96
,D/OpenGLRenderer( 3200): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3200): Enabling debug mode 0
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 60 -> 60
D/DisplayPowerController( 1016): animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1016): lcd : 45 -
,D/lights  ( 1016): lcd : 60 +
,I/SamsungIME( 1803): getCurrentKeyboard
I/SamsungIME( 1803): getTextKeyboard
,W/ResourcesManager( 4458): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4458): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4458): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4458): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/lights  ( 1016): lcd : 60 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 60 -> 60
D/DisplayPowerController( 1016): animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/AMMetaDataParserService( 3948): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_POLICYDM( 4122): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4122): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4122): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,D/SamsungIME( 1803): [SwiftkeyWrapper] currentLangauge : 1701729619
I/DBG_POLICYDM( 4122): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4122): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4122): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4122): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.635156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb938c728 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb93b75b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.634635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93bffe8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb93bfe40 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/art     ( 1803): Suspending all threads took: 10.591ms
,D/SBrowserFeatureFlag( 4458): initialized in static block : loadCscFeatureValue() succeed! 
,D/ManifestProvider( 4458): onCreate()
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.737396ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9382d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9395538 counterpartCT=4 counterpartW=96 counterparth=96
,E/NetworkSettingsReceiver( 4458): onReceive: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3948): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityThread( 4320): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/System.out( 4320): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 4320): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4320): (HTTPLog)-Static: isShipBuild true
I/System.out( 4320): (HTTPLog)-Thread-645-1022734358: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4320): (HTTPLog)-Static: isSBSettingEnabled false
,I/GFX raster( 3948): took 0.685885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb8fde570 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93b7510 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/SBrowserFeatureFlag( 4458): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@330a8a96
,D/SBrowserFeatureFlag( 4458): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 4458): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.844896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb939e710 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93b75b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/EnterpriseController(  277): uids 10107
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10107
,I/AMMetaDataParserService( 3948): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4485): MountEmulatedStorage()
I/libpersona( 4485): KNOX_SDCARD checking this for 10135
E/Zygote  ( 4485): v2
I/libpersona( 4485): KNOX_SDCARD not a persona
,I/SELinux ( 4485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131099648
,I/AMMetaDataParserService( 3948): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3948): getResourceTypeNamexml
I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4485 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3948): took 0.724895ms for 96*96 texture 0
I/ActivityManager( 1016): Killing 3613:com.wssnps/1000 (adj 15): empty #31
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9397488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93b7510 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4485): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CalendarProvider2( 4343): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/AMMetaDataParserService( 3948): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/art     (  303): Explicit concurrent mark sweep GC freed 8738(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 36.389ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 19.336ms
,W/dex2oat ( 4138): Verification of void maps.k.b$h.a(byte[], byte[]) took 102.679ms
,D/TimaKeyStoreProvider( 4485): TimaSignature is unavailable
D/ActivityThread( 4485): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 2814:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3948): took 0.628125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb938c728 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb93bfe40 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 20.857ms
,I/AMMetaDataParserService( 3948): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ResourcesManager( 4485): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4485): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4485): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.634687ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93bffe8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9395538 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/System.out( 4320): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/com.google.a.a.b.d.a( 4320): Application name is not set. Call Builder#setApplicationName.
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.814375ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9382d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb93b75b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3948): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.735521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb8fde570 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93b7510 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.933073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb939e710 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93bfe40 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4505 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,E/Zygote  ( 4505): MountEmulatedStorage()
E/Zygote  ( 4505): v2
I/libpersona( 4505): KNOX_SDCARD checking this for 10139
I/libpersona( 4505): KNOX_SDCARD not a persona
,I/SELinux ( 4505): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4505): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4505): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 4211): Initializing JXcore engine
,W/jxcore-log( 4211): JXcore engine is ready
,D/TimaKeyStoreProvider( 4505): TimaSignature is unavailable
,D/ActivityThread( 4505): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3948): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131099648
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3948): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3948): getResourceTypeNamexml
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.697553ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9397488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93b7510 counterpartCT=4 counterpartW=96 counterparth=96
,E/audit   ( 1932): type=1400 msg=audit(1457934216.481:205): avc:  denied  { ioctl } for  pid=4398 comm="Thread-639" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1932):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1932): type=1300 msg=audit(1457934216.481:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9bfef8f8 items=0 ppid=303 ppcomm=main pid=4398 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-639" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1932): type=1320 msg=audit(1457934216.481:205): 
,I/AMMetaDataParserService( 3948): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ResourcesManager( 4505): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4505): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4505): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4505): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4505): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/jxcore-log( 4211): Starting JXcore engine
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.641042ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb938c728 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9395538 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_2814/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3613/cgroup.procs: No such file or directory
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.621093ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb93bffe8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb93b75b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/ActivityManager( 1016): Killing 3689:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.638489ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9382d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb93bfe40 counterpartCT=4 counterpartW=96 counterparth=96
,W/jxcore-log( 4211): Platform android
W/jxcore-log( 4211): 
W/jxcore-log( 4211): Process ARCH arm
W/jxcore-log( 4211): 
,I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4523 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/Zygote  ( 4523): MountEmulatedStorage(),
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/Zygote  ( 4523): v2
I/libpersona( 4523): KNOX_SDCARD checking this for 10145
,I/AMMetaDataParserService( 3948): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522,
I/libpersona( 4523): KNOX_SDCARD not a persona,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 4523): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4523): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4523): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.631823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb8fde570 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93b7510 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4523): TimaSignature is unavailable
,D/ActivityThread( 4523): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10022/pid_3689/cgroup.procs: No such file or directory
,W/ResourcesManager( 4523): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4523): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4523): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4523): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4523): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3948): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.734011ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb939e710 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9395538 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3948): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
,I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131165197
,W/ResourcesManager( 3948): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3948): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3948): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3948): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3948): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3948): getResourceTypeNamexml
,I/AMMetaDataParserService( 3948): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3948): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/ActivityManager( 1016): Killing 3723:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3948): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3948): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131165197
,I/AMMetaDataParserService( 3948): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3948): getResourceTypeNamexml
,I/dex2oat ( 4138): dex2oat took 5.552s (threads: 4)
,I/AMMetaDataParserService( 3948): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3723/cgroup.procs: No such file or directory
,D/DexOptUtils( 2067): Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
,D/DexOptUtils( 2067): Set odex to world readable.
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/DexOptUtils( 2067): Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
,I/ActivityManager( 1016): Killing 3732:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,I/AMMetaDataParserService( 3948): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,E/Watchdog( 1016): !@Sync 1
,I/AMMetaDataParserService( 3948): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/SettingsProvider( 1016): name = audio_safe_volume_state
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 26256(1360KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 26MB/40MB, paused 2.700ms total 154.704ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10094/pid_3732/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3948): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131165197
,I/AMMetaDataParserService( 3948): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3948): getResourceTypeNamexml
,I/AMMetaDataParserService( 3948): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3948): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,V/Herrevad( 2067): NQAS connected
,I/AMMetaDataParserService( 3948): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3948): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/jxcore-log( 4211): JXcore Cordova bridge is ready!
I/jxcore-log( 4211): 
,W/jxcore-log( 4211): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4211): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 4211): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131099648
,W/ResourcesManager( 3948): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3948): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3948): getResourceTypeNamexml
,I/art     ( 2067): WaitForGcToComplete blocked for 59.045ms for cause Explicit
,D/SamsungIME( 1803): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/AMMetaDataParserService( 3948): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,E/SMD     (  287): DCD OFF
,E/jxcore  ( 4211): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4211): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/AMMetaDataParserService( 3948): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,I/chromium( 4211): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 4211): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,D/FocusedStackFrame( 1016): Set to : 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 4211
D/RCPManagerService( 1016): exchangeData() failure , invalid userId
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (184 us)
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
I/art     ( 2067): Explicit concurrent mark sweep GC freed 476(36KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 11MB/15MB, paused 5.338ms total 52.577ms
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/PluginManager( 4211): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 53ms. Plugin should use CordovaInterface.getThreadPool().
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4548): MountEmulatedStorage()
,E/Zygote  ( 4548): v2
I/libpersona( 4548): KNOX_SDCARD checking this for 10072
I/libpersona( 4548): KNOX_SDCARD not a persona,
I/SELinux ( 4548): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4548): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4548 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/SELinux ( 4548): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
W/ActivityManager( 1016): mDVFSHelper.acquire()
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/TimaKeyStoreProvider( 4548): TimaSignature is unavailable
D/ActivityThread( 4548): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startService callerProcessName:com.android.email, calleePkgName: com.android.email
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/SensorService( 1016): [SO] activate (ident=0xb98228f0, enabled=0)
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/Launcher( 1489): onRestart, Launcher: 856328854
,D/Launcher( 1489): onStart, Launcher: 856328854
D/Launcher.HomeView( 1489): onStart
,D/Launcher( 1489): onResume, Launcher: 856328854
,D/SettingsProvider( 1016): name = kids_home_mode
D/SensorManager( 1016): unregisterListener ::   
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 200000000(ns)
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10007
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/Launcher.HomeView( 1489): onResume
D/SensorService( 1016): [SO] changed settle time [0]
D/SensorService( 1016): [SO] setDelay [200000000]
D/SensorService( 1016): [SO] activate (ident=0xb98228f0, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/MenuAppsGridFragment( 1489): onResume
,D/ActivityManager( 1016): handle home activity for 0
I/WallpaperManagerService( 1016): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1016): post home show event for user 0
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/WallpaperManagerService( 1016):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1016): handleHomeShow for 0 and current 0,
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,I/SurfaceFlinger(  257): id=13 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1016): Focus entered window: 1489
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1489): log_dcs ThreadedRenderer::initialize entered! 
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:assistant
I/AMMetaDataParserService( 3948): Resource data:2131165220
,D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ResourcesManager( 3948): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3948): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3948): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3948): getResourceTypeNamexml
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GFX raster( 3948): took 0.727032ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9abbcd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9abba08 counterpartCT=4 counterpartW=96 counterparth=96
,I/StatusBar( 1191): Icon Only
D/PanelView( 1191): There is/are notification(s) 
,W/IInputConnectionWrapper( 4211): showStatusIcon on inactive InputConnection
,D/BadgeProvider( 4548): onCreate
,D/BadgeProvider( 4548): DatabaseHelper
D/SamsungIME( 1803): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/AMMetaDataParserService( 3948): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,D/BadgeProvider( 4548): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/Timeline( 1489): Timeline: Activity_idle id: android.os.BinderProxy@183a3c4f time:50100
,E/Zygote  ( 4578): MountEmulatedStorage()
,E/Zygote  ( 4578): v2
I/libpersona( 4578): KNOX_SDCARD checking this for 10146,
I/libpersona( 4578): KNOX_SDCARD not a persona
,I/SELinux ( 4578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/PersonaManager( 1016): isKioskContainerExistOnDevice,
,I/SELinux ( 4578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4578): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4578 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 3435:com.sec.pcw.device/1000 (adj 15): empty #31
,E/        ( 3948): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3948): took 0.719687ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3948): Bitmap=0xb9abbb28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9aceeb0 counterpartCT=4 counterpartW=96 counterparth=96
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1016): Displayed Component not be shown by security: +199ms
,D/BadgeProvider( 4548): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4548): sendNotify, [notify] : null
D/Launcher.Model( 1489): reloadBadges entered.
D/BadgeProvider( 4548): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4548): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4548): update, [UpdateCount] : 1
,I/AMMetaDataParserService( 3948): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,D/TimaKeyStoreProvider( 4578): TimaSignature is unavailable
,D/ActivityThread( 4578): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 4578): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiSe,ttingsForSetupWizardXL
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
,I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserServic,e( 3948): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3435/cgroup.procs: No such file or directory,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/ActivityManager( 1016): Killing 3770:com.sec.factory.camera/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
,I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
,I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
,I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity,
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.BatteryInfo
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.RadioInfo
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ProxySelector
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
,I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
,I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
,W/ActivityManager( 1016): getTasks: caller 10145 does not hold GET_TASKS; limiting output
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROF,ILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDa,taParserService( 3948): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourceP,ackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3770/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3948): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
I/ConfigService( 1821): onCreate
I/Process ( 4523): Sending signal. PID: 4523 SIG: 9
D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
D/AndroidRuntime( 4554): 
D/AndroidRuntime( 4554): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 4554): CheckJNI is OFF
D/AndroidRuntime( 4554): readGMSProperty: start
D/AndroidRuntime( 4554): readGMSProperty: already setted!!
D/AndroidRuntime( 4554): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4554): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4554): readGMSProperty: end
D/AndroidRuntime( 4554): addProductProperty: start
E/Zygote  ( 4597): MountEmulatedStorage()
E/Zygote  ( 4597): v2
I/libpersona( 4597): KNOX_SDCARD checking this for 1000
I/libpersona( 4597): KNOX_SDCARD not a persona
I/SELinux ( 4597): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4597 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4597): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Process com.android.email (pid 4523)(adj 9) has died(36,1139)
E/SELinux ( 4597): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.exchange, calleePkgName: com.android.email
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4597): TimaSignature is unavailable
D/ActivityThread( 4597): Added TimaKeyStore provider
,E/Zygote  ( 4610): MountEmulatedStorage()
E/Zygote  ( 4610): v2
I/libpersona( 4610): KNOX_SDCARD checking this for 10145
I/libpersona( 4610): KNOX_SDCARD not a persona
I/SELinux ( 4610): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4610 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 4610): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4610): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SensorService( 1016): [SO] currT = 50410083520, prevT = 49970099145, diff = 439984375, [0.115 0.383 10.132]
D/SensorService( 1016): [SO] 0.115 0.383 10.132
D/SensorService( 1016): [SO] [100 -> 255]
,D/TimaKeyStoreProvider( 4610): TimaSignature is unavailable
D/ActivityThread( 4610): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3786:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1016): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
W/ResourcesManager( 4610): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4610): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4610): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4610): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4610): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4635): MountEmulatedStorage()
,I/libpersona( 4635): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4635): v2
I/libpersona( 4635): KNOX_SDCARD not a persona
I/SELinux ( 4635): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4635 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3797:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
I/SELinux ( 4635): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4635): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4635): TimaSignature is unavailable
D/ActivityThread( 4635): Added TimaKeyStore provider
,E/AffinityControl( 4554): AffinityControl: registerfunction enter
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/AndroidRuntime( 4554): Calling main entry com.android.commands.pm.Pm
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3786/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_3797/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1016): START PACKAGE DELETE: observer{997646728}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{2}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{1545f16b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:50559
,D/PackageManager( 1016): !@killApplicatoin: 10155, uninstall pkg
,I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1016): Killing 4211:com.test.thalitest/u0a155 (adj 9): stop com.test.thalitest cause uninstall pkg
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (7/9)
I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/9)
,D/SecurityLogAgent( 4635): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4635): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4635): StateMachine : Current State = 1
D/SecurityLogAgent( 4635): BootReceiver : completed task. Failed to return wakelock . 
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/BadgeProvider( 4548): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,I/Hs20UtilService( 2619): Starting #3
,I/Hs20UtilService( 2619): Message received 5011
,E/WifiStateMachine( 1016): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1016): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1016): invaild command id : 215
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1803): mOCRHelper is null
,W/GeofencerStateMachine( 1821): Ignoring removeGeofence because network location is disabled.
,D/SecurityLogAgent( 4635): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4635): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4635): StateMachine : Current State = 1
,D/SecurityLogAgent( 4635): StateMachine : Changed Current State = 1
,D/RegisteredComponentCache( 1451): Collect Tech packages for Knox
,D/BadgeProvider( 4548): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4548): sendNotify, [notify] : null
D/BadgeProvider( 4548): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4548): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4548): update, [UpdateCount] : 1
,V/NetworkStats( 1016): removeUidsLocked() for UIDs [10155]
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x3)
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,V/NetworkStats( 1016): performPollLocked() took 10ms
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/PersonaManager( 1451): isKioskContainerExistOnDevice
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.example.hello, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4662): MountEmulatedStorage(),
,E/Zygote  ( 4662): v2
,I/libpersona( 4662): KNOX_SDCARD checking this for 10174
I/libpersona( 4662): KNOX_SDCARD not a persona,
,I/SELinux ( 4662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1016): Start proc com.example.hello for broadcast com.example.hello/io.jxcore.node.ConnectivityChangeListener: pid=4662 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3850:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,I/SELinux ( 4662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4662): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,D/TimaKeyStoreProvider( 4662): TimaSignature is unavailable
,D/ActivityThread( 4662): Added TimaKeyStore provider
,I/Process ( 4578): Sending signal. PID: 4578 SIG: 9
,D/RCPManagerService( 1016): PackageReceiver onReceive()
,I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1016): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1016): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1016): DBIntegrity::getInstance - New instance created
,D/OTPFW   ( 1016): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0,
D/PersonaManager( 1451): isKioskContainerExistOnDevice
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/OTPFW   ( 1016): ProvisionData::getAllEntries Enter
,D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
E/OTPFW   ( 1016): ProvisionData::getAllEntries Table is empty
D/RegisteredServicesCache( 1451): empty dynamic service
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/AlarmManagerEXT( 1016): com.test.thalitest(10155) is removed.
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/jxcore_app_log( 4662): JniHelper::setJavaVM(0xb8fe3450), pthread_self() = -1224819000
,E/JX-Cordova( 4662): JXcore wasn't initialized yet
,I/ActivityManager( 1016): Killing 3670:com.samsung.android.sm/1000 (adj 15): empty #31
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,I/ActivityManager( 1016): Process com.android.exchange (pid 4578)(adj 13) has died(96,1138)
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4681): MountEmulatedStorage()
,I/libpersona( 4681): KNOX_SDCARD checking this for 10068
E/Zygote  ( 4681): v2
I/libpersona( 4681): KNOX_SDCARD not a persona,
I/SELinux ( 4681): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4681): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4681): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4681 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 4681): TimaSignature is unavailable
,D/ActivityThread( 4681): Added TimaKeyStore provider
,W/ResourcesManager( 4681): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/FileShare-Client( 4681): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 4681): ClientBroadcastReceiver.onReceive - disconnected
,D/FileShare-Client( 4681): Outbound.stopDelayTimer - 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 45161(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 30MB/45MB, paused 3.113ms total 429.640ms
,E/Zygote  ( 4697): MountEmulatedStorage()
E/Zygote  ( 4697): v2
I/libpersona( 4697): KNOX_SDCARD checking this for 10069
I/libpersona( 4697): KNOX_SDCARD not a persona
,I/SELinux ( 4697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4697): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4697 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PackageManager( 1016): delete codoeFile: 
,D/AASAuninstall( 1016): userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,I/AASA_removePackage( 1016): UID=10155 Target=com.test.thalitest
D/TaskPersister( 1016): removeObsoleteFile: deleting file=12_task.xml
D/TaskPersister( 1016): removeObsoleteFile: deleting file=12_task_thumbnail.png
,D/PackageManager( 1016): result of delete: 1{997646728}
,D/TimaKeyStoreProvider( 4697): TimaSignature is unavailable
,D/ActivityThread( 4697): Added TimaKeyStore provider
,D/AndroidRuntime( 4554): Shutting down VM
,D/Launcher.Model( 1489): reloadBadges entered.
,D/WallpaperManager( 1489): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/PackageManager( 1016): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 1016): userId{-1}
D/PackageManager( 1016): andCode{true}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,D/WallpaperManager( 1489): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1489): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/FileShare-Server( 4697): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 3818:com.vlingo.midas/u0a31 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1821): callingUid 10012, callindPid: 1821
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1016): no available spell checker services found
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/MDM     ( 1821): [246] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2067): Restart initialization of location
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{38da5095 u0 com.samsung.android.providers.context/.ContextService}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1821): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1821): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/GCoreFlp( 1821): No location to return for getLastLocation()
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/FusedLocationProvider( 1821): location=null
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 2619): Starting #4
,I/Hs20UtilService( 2619): Message received 5007
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2619): Starting #5
,I/Hs20UtilService( 2619): Message received 5007
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{ee62077 u0 com.android.settings/.wifi.WifiCredService}
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/Hs20UtilService( 2619): Starting #6
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 2619): Message received 5007
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/art     ( 4554): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 2619): Starting #7
,I/Hs20UtilService( 2619): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/WifiStateMachine( 1016): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1016): mCursor = null
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1016): mCursor = null
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1016): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1016): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_3850/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3670/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10031/pid_3818/cgroup.procs: No such file or directory
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1016): mCursor = null
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4719): MountEmulatedStorage(),
E/Zygote  ( 4719): v2
I/libpersona( 4719): KNOX_SDCARD checking this for 1000
I/libpersona( 4719): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4719 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4719): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/art     (  303): Explicit concurrent mark sweep GC freed 8728(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 26.179ms
,D/TimaKeyStoreProvider( 4719): TimaSignature is unavailable
D/ActivityThread( 4719): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3905:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 608us total 16.900ms
,I/PCWCLIENTTRACE_LOG( 4719): DEFAULT_LOGON : true,
I/PCWCLIENTTRACE_LOG( 4719): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 4719): new DMDBOpenHelper instance,
E/SQLiteLog( 4719): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 646us total 16.873ms,
E/SQLiteDatabase( 4719): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase( 4719): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4719): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 4719): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4719): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase( 4719): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 4719): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 4719): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 4719): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 4719): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 4719): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 4719): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 4719): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4719): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4719): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 4719): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4719): 	at java.lang.reflect.Method.invoke(Method.java:372),
E/SQLiteDatabase( 4719): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 4719): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 4719): Shutting down VM
E/AndroidRuntime( 4719): FATAL EXCEPTION: main
E/AndroidRuntime( 4719): Process: com.sec.pcw.device, PID: 4719
E/AndroidRuntime( 4719): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4719): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
E/AndroidRuntime( 4719): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/AndroidRuntime( 4719): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/AndroidRuntime( 4719): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/AndroidRuntime( 4719): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/AndroidRuntime( 4719): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4719): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4719): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 4719): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4719): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4719): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4719): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4719): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 4719): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 4719): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4719): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime( 4719): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/AndroidRuntime( 4719): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
,E/AndroidRuntime( 4719): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/AndroidRuntime( 4719): 	... 11 more
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
E/DropBoxManagerService( 1016): Can't write: system_app_crash
E/DropBoxManagerService( 1016): java.io.FileNotFoundException: /data/system/dropbox/drop169.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1016): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1016): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1016): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15989)
E/DropBoxManagerService( 1016): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1016): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1016): 	... 5 more
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4735): MountEmulatedStorage()
,E/Zygote  ( 4735): v2
I/libpersona( 4735): KNOX_SDCARD checking this for 10111
I/libpersona( 4735): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4735 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 4735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/android.os.Debug( 1016): ro.product_ship = true
E/android.os.Debug( 1016): ro.debug_level = 0x4f4c
,D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 1016): *FMB* installDecor flags : 8519682
I/SELinux ( 4735): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4735): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4735): TimaSignature is unavailable
,D/ActivityThread( 4735): Added TimaKeyStore provider
,D/InputDispatcher( 1016): Focus left window: 1489
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/InputDispatcher( 1016): Focus entered window: 1016
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_3905/cgroup.procs: No such file or directory
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 51680,
D/PowerManagerService( 1016): [s] UserActivityState : 2 -> 1
D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
,D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{1000}) (elapsedTime=3407)
,I/ActivityManager( 1016): Killing 3366:com.google.android.youtube/u0a166 (adj 15): empty #31
,E/SQLiteLog( 1821): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 1821): (10) POSIX Error : 9 SQLite Error : 3850
,D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=14 createSurf (97x97),1 flag=4, eevice

```
