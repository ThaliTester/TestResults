#### Test 625481247d7767b_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
03-15 15:00:56.723  4213  4213 E Zygote  : MountEmulatedStorage()
03-15 15:00:56.723  4213  4213 E Zygote  : v2
03-15 15:00:56.723  4213  4213 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 15:00:56.723  4213  4213 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 15:00:56.723  4213  4213 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-15 15:00:56.733  4195  4195 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
03-15 15:00:56.733  4195  4195 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-15 15:00:56.743  4195  4195 I DBG_POLICYDM: [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
03-15 15:00:56.743  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-15 15:00:56.743  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:56.743  3682  3734 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:56.743  3682  3734 I AMMetaDataParserService: Resource data:2131099648
03-15 15:00:56.743  4213  4213 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:56.743  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:56.743  1019  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:56.743  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-15 15:00:56.743  4213  4213 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:56.743  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
--------- beginning of system
03-15 15:00:56.743  1019  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 15:00:56.753  3682  3734 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 15:00:56.753  3682  3734 I AMMetaDataParserService: getResourceTypeNamexml
03-15 15:00:56.753  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:56.753  3682  3734 I GFX raster: took 0.751249ms for 96*96 texture 0
03-15 15:00:56.753  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b60258 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb863e9f0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:56.763  3682  3734 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
03-15 15:00:56.793  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:56.793  3682  3734 I GFX raster: took 0.627917ms for 96*96 texture 0
03-15 15:00:56.803  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8661598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb863e4d8 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:56.803  3682  3734 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
03-15 15:00:56.823  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:56.823  3682  3734 I GFX raster: took 0.624323ms for 96*96 texture 0
03-15 15:00:56.823  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb863e528 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb863fb68 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:56.823  3682  3734 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-15 15:00:56.833  4213  4235 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
03-15 15:00:56.833  4213  4235 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
03-15 15:00:56.833  4213  4213 E SPPClientService: [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
03-15 15:00:56.833  4213  4213 E SPPClientService: [SystemStateMoniter] Current Time : 43709
03-15 15:00:56.843  1019  2777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
03-15 15:00:56.853  4213  4235 D SPPClientService: PushLog.txt file is not deleted.
03-15 15:00:56.853  4213  4235 D SPPClientService: PushLog.txt file is not deleted.
03-15 15:00:56.853  4213  4235 D SPPClientService: ============PushLog. stop!
03-15 15:00:56.853  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3536/cgroup.procs: No such file or directory
03-15 15:00:56.873  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:56.873  3682  3734 I GFX raster: took 0.628854ms for 96*96 texture 0
03-15 15:00:56.873  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865e960 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb865f8a0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:56.883  3682  3734 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
03-15 15:00:56.883  1019  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.883  1019  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.883  1019  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.883  1019  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.893  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:56.893  3682  3734 I GFX raster: took 0.641614ms for 96*96 texture 0
03-15 15:00:56.893  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb828d510 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86617f0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:56.893  3682  3734 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
03-15 15:00:56.893  4239  4239 E Zygote  : MountEmulatedStorage()
03-15 15:00:56.893  4239  4239 E Zygote  : v2
03-15 15:00:56.893  4239  4239 I libpersona: KNOX_SDCARD checking this for 10166
03-15 15:00:56.903  4239  4239 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:56.903  4239  4239 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 15:00:56.903  1019  1553 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4239 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 15:00:56.903  1019  1553 I ActivityManager: Killing 3520:com.fmm.ds/1000 (adj 15): empty #31
03-15 15:00:56.903  4239  4239 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 15:00:56.903  4239  4239 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 15:00:56.923  4239  4239 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:56.923  4239  4239 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:56.933  1019  2777 D SSRM:n  : SIOP:: AP = 410
03-15 15:00:56.943  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:56.943  3682  3734 I GFX raster: took 0.769010ms for 96*96 texture 0
03-15 15:00:56.943  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8626288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8619d10 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:56.953  3682  3734 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
03-15 15:00:56.983  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-15 15:00:56.983  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:56.983  3682  3734 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:56.983  3682  3734 I AMMetaDataParserService: Resource data:2131099648
03-15 15:00:56.983  3682  3734 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 15:00:56.983  3682  3734 I AMMetaDataParserService: getResourceTypeNamexml
03-15 15:00:56.983  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:56.983  3682  3734 I GFX raster: took 0.698177ms for 96*96 texture 0
03-15 15:00:56.983  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b60258 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86617f0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:56.993  3682  3734 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
03-15 15:00:57.023  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3520/cgroup.procs: No such file or directory
03-15 15:00:57.043  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 15:00:57.043  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 15:00:57.043  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:00:57.043  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:00:57.043  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:00:57.043  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:00:57.043  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:57.053  3682  3734 I GFX raster: took 0.724011ms for 96*96 texture 0
03-15 15:00:57.053  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8661598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb863e9f0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:57.053  1019  2830 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-15 15:00:57.063  3682  3734 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
03-15 15:00:57.073  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:57.073  3682  3734 I GFX raster: took 0.612656ms for 96*96 texture 0
03-15 15:00:57.073  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb863e528 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb863fb68 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:57.073  3682  3734 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-15 15:00:57.093  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:57.093  3682  3734 I GFX raster: took 0.644271ms for 96*96 texture 0
03-15 15:00:57.093  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865e960 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb863fb68 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:57.103  3682  3734 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
03-15 15:00:57.113  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:57.113  3682  3734 I GFX raster: took 0.630833ms for 96*96 texture 0
03-15 15:00:57.113  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb828d510 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8619d10 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:57.113  3682  3734 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
03-15 15:00:57.183  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:57.183  3682  3734 I GFX raster: took 0.804583ms for 96*96 texture 0
03-15 15:00:57.183  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8626288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb863e9f0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:57.193  3682  3734 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
03-15 15:00:57.223  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
03-15 15:00:57.223  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:57.223  3682  3734 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:57.223  3682  3734 I AMMetaDataParserService: Resource data:2131099648
03-15 15:00:57.223  3682  3734 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 15:00:57.223  3682  3734 I AMMetaDataParserService: getResourceTypeNamexml
03-15 15:00:57.223  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:57.223  3682  3734 I GFX raster: took 0.688333ms for 96*96 texture 0
03-15 15:00:57.223  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b60258 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8652290 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:57.233  3682  3734 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
03-15 15:00:57.243  4195  4220 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-15 15:00:57.243  4195  4195 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
03-15 15:00:57.243  4195  4220 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
03-15 15:00:57.243  4239  4254 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 15:00:57.243  4239  4254 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-15 15:00:57.253  4195  4220 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
03-15 15:00:57.253  4195  4195 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
03-15 15:00:57.263  4195  4195 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
03-15 15:00:57.263  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:57.263  1731  1731 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
03-15 15:00:57.263  3682  3734 I GFX raster: took 0.655625ms for 96*96 texture 0
03-15 15:00:57.263  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8661598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b5ffb8 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:57.273  3682  3734 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
03-15 15:00:57.283  4195  4195 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
03-15 15:00:57.283  4195  4195 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
03-15 15:00:57.283  4195  4195 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
03-15 15:00:57.283  4195  4195 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
03-15 15:00:57.283  4195  4195 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
03-15 15:00:57.283  4195  4195 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-15 15:00:57.283  4237  4237 D AndroidRuntime: 
03-15 15:00:57.283  4237  4237 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-15 15:00:57.293  4237  4237 D AndroidRuntime: CheckJNI is OFF
03-15 15:00:57.293  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:57.293  4237  4237 D AndroidRuntime: readGMSProperty: start
03-15 15:00:57.293  4237  4237 D AndroidRuntime: readGMSProperty: already setted!!
03-15 15:00:57.293  4237  4237 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-15 15:00:57.293  3682  3734 I GFX raster: took 0.643281ms for 96*96 texture 0
03-15 15:00:57.293  4237  4237 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-15 15:00:57.293  4237  4237 D AndroidRuntime: readGMSProperty: end
03-15 15:00:57.293  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb863e528 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb863e9f0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:57.293  4237  4237 D AndroidRuntime: addProductProperty: start
03-15 15:00:57.303  4195  4195 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
03-15 15:00:57.303  3682  3734 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-15 15:00:57.313  4195  4195 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
03-15 15:00:57.313  4195  4195 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
03-15 15:00:57.313  4195  4195 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
03-15 15:00:57.323  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.323  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.323  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.323  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.343  4259  4259 E Zygote  : MountEmulatedStorage()
03-15 15:00:57.343  4259  4259 I libpersona: KNOX_SDCARD checking this for 10041
03-15 15:00:57.343  4259  4259 E Zygote  : v2
03-15 15:00:57.343  4259  4259 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:57.343  4259  4259 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 15:00:57.343  4259  4259 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 15:00:57.343  1019  1032 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4259 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 15:00:57.343  4259  4259 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-15 15:00:57.343  1019  1032 I ActivityManager: Killing 3189:com.google.android.gms:car/u0a12 (adj 15): empty #31
03-15 15:00:57.343  4195  4220 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-15 15:00:57.353  4239  4254 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
03-15 15:00:57.353  4195  4220 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-15 15:00:57.363  4195  4220 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
03-15 15:00:57.363  4195  4220 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
03-15 15:00:57.363  4195  4220 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
03-15 15:00:57.363  4259  4259 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:57.363  4259  4259 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:57.373  4195  4220 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
03-15 15:00:57.393  4195  4220 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
03-15 15:00:57.403  4195  4220 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
03-15 15:00:57.403   254   254 E lowmemorykiller: Error writing /proc/3189/oom_score_adj; errno=22
03-15 15:00:57.403  4195  4220 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
03-15 15:00:57.403  4195  4222 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-15 15:00:57.403  1019  1309 W ActivityManager: ProcessRecord{3c3cf006 3189:com.google.android.gms:car/u0a12} is already killed
03-15 15:00:57.403  4195  4220 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
03-15 15:00:57.403  1019  1309 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
03-15 15:00:57.403  4195  4222 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-15 15:00:57.403  1019  1309 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
03-15 15:00:57.413  4239  4254 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-15 15:00:57.413  4239  4254 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8bf1c7b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 15:00:57.413  4239  4254 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-15 15:00:57.413  4195  4222 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
03-15 15:00:57.413  4195  4220 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/18/13:15:33
03-15 15:00:57.413  4195  4222 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
03-15 15:00:57.423  4195  4220 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/15/15:00:57
03-15 15:00:57.423  4195  4222 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
03-15 15:00:57.423  4195  4220 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
03-15 15:00:57.423  4195  4220 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
03-15 15:00:57.423  4195  4222 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
03-15 15:00:57.423  4195  4222 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
03-15 15:00:57.433  4195  4222 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
03-15 15:00:57.433  4195  4222 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
03-15 15:00:57.433  4195  4222 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
03-15 15:00:57.453  1019  1309 W ActivityManager: Exception when unbinding service com.google.android.gms/.car.CarService
03-15 15:00:57.453  1019  1309 W ActivityManager: android.os.TransactionTooLargeException
03-15 15:00:57.453  1019  1309 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
03-15 15:00:57.453  1019  1309 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:511)
03-15 15:00:57.453  1019  1309 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:1029)
03-15 15:00:57.453  1019  1309 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1997)
03-15 15:00:57.453  1019  1309 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:1050)
03-15 15:00:57.453  1019  1309 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:19124)
03-15 15:00:57.453  1019  1309 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:973)
03-15 15:00:57.453  1019  1309 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
03-15 15:00:57.453  1019  1309 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:461)
03-15 15:00:57.453  1019  1309 W ActivityManager: ProcessRecord{3c3cf006 3189:com.google.android.gms:car/u0a12} is already killed
03-15 15:00:57.463  1019  1043 W libprocessgroup: failed to open /acct/uid_10012/pid_3189/cgroup.procs: No such file or directory
03-15 15:00:57.503  4195  4222 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
03-15 15:00:57.543  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:57.543  3682  3734 I GFX raster: took 0.655625ms for 96*96 texture 0
03-15 15:00:57.543  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8659718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8626288 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:57.553  4259  4259 I SA      : [SSP] onCreated
03-15 15:00:57.553  4195  4222 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
03-15 15:00:57.553  3682  3734 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
03-15 15:00:57.573  4195  4220 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
03-15 15:00:57.603  4259  4259 I SA      : [TPM] There is no property file
03-15 15:00:57.603  4259  4259 I SA      : [SCU] isHaveSA() - false
03-15 15:00:57.603  4259  4259 I SA      : [TPM] getModelProperty : null
03-15 15:00:57.603  4259  4259 I SA      : [TPM] getCSCProperty : null
03-15 15:00:57.603  4259  4259 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-15 15:00:57.603  4259  4259 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-15 15:00:57.603  4259  4259 I SA      : [DM] TFT FEATURE: false
03-15 15:00:57.613  4259  4259 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
03-15 15:00:57.613  4259  4259 I SA      : [DM] init START
03-15 15:00:57.613  4259  4259 I SA      : [DM] This device is not a Vodafone
03-15 15:00:57.623  4259  4259 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
03-15 15:00:57.623  4259  4259 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
03-15 15:00:57.623  4259  4259 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
03-15 15:00:57.623  4259  4259 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
03-15 15:00:57.623  4259  4259 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
03-15 15:00:57.623  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:57.623  4259  4259 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
03-15 15:00:57.623  4259  4259 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
03-15 15:00:57.623  3682  3734 I GFX raster: took 0.651562ms for 96*96 texture 0
03-15 15:00:57.623  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb828d510 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86617f0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:57.623  4259  4259 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-15 15:00:57.633  4259  4259 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
03-15 15:00:57.633  4259  4259 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
03-15 15:00:57.633  4259  4259 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
03-15 15:00:57.633  4259  4259 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
03-15 15:00:57.633  4259  4259 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
03-15 15:00:57.633  4259  4259 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
03-15 15:00:57.633  4259  4259 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
03-15 15:00:57.633  4259  4259 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
03-15 15:00:57.633  4259  4259 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
03-15 15:00:57.633  4259  4259 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
03-15 15:00:57.633  4259  4259 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
03-15 15:00:57.633  4259  4259 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
03-15 15:00:57.643  4259  4259 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
03-15 15:00:57.643  4259  4259 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
03-15 15:00:57.643  4259  4259 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
03-15 15:00:57.643  4259  4259 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
03-15 15:00:57.643  4259  4259 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
03-15 15:00:57.643  3682  3734 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
03-15 15:00:57.653  4259  4259 I SA      : [SCU] isHaveSA() - false
03-15 15:00:57.663  4259  4259 I SA      : support phone number id : false
03-15 15:00:57.663  4259  4259 I SA      : [DM] Supports Ref Jpn : true
03-15 15:00:57.663  4259  4259 I SA      : [DM] init END
03-15 15:00:57.663  4259  4259 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
03-15 15:00:57.663  4259  4259 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
03-15 15:00:57.663  1019  1553 D ActivityManager: retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
03-15 15:00:57.663  1019  1553 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:57.663  1019  1553 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-15 15:00:57.663  1019  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
03-15 15:00:57.673  4259  4259 I SA      : [OR] onReceive END
03-15 15:00:57.683  4195  4220 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
03-15 15:00:57.693  4195  4220 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
03-15 15:00:57.693  4259  4259 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-15 15:00:57.693  4259  4259 I SA      : [ODM] queryOpenData(key= GEO_IP )
03-15 15:00:57.713  4259  4259 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-15 15:00:57.713  4259  4259 I SA      : [LBE] REF_JPN : true
03-15 15:00:57.713  4259  4259 I SA      : [BDC] create
03-15 15:00:57.743  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
03-15 15:00:57.753  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:57.753  3682  3734 I GFX raster: took 0.741406ms for 96*96 texture 0
03-15 15:00:57.753  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8619d10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb862cb60 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:57.763  4237  4237 E AffinityControl: AffinityControl: registerfunction enter
03-15 15:00:57.763  4259  4259 I SA      : [DBMV2] getEmailID
03-15 15:00:57.763  3682  3734 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
03-15 15:00:57.773  4259  4259 I SA      : [DBMV2] getDataV02ForItems
03-15 15:00:57.773  4259  4259 I SA      : [SSP] query invoked
03-15 15:00:57.773  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-15 15:00:57.773  4259  4259 I SA      : [SCU] get signed id from samsung account2.0 DB.
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-15 15:00:57.783  4259  4259 I SA      : [SCU] get signed id from samsung account1.0 DB.
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-15 15:00:57.783  4259  4259 I SA      : [BDC] destroy
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-15 15:00:57.783  3682  3734 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-15 15:00:57.783  1019  1487 I ActivityManager: Killing 3147:com.android.vending/u0a28 (adj 15): empty #31
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
,03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-15 15:00:57.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
03-15 15:00:57.793  4195  4222 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
03-15 15:00:57.793  4237  4237 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-15 15:00:57.803  1019  1143 E PersonaManagerService: inState():  stateMachine is null !!
03-15 15:00:57.803  1019  1143 I PersonaManagerService: PersonaId don't exist
03-15 15:00:57.803  1019  1143 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-15 15:00:57.813  1019  1143 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 15:00:57.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-15 15:00:57.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:57.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:57.813  3682  3734 I AMMetaDataParserService: Resource data:2131165197
03-15 15:00:57.813  3682  3734 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 15:00:57.813  3682  3734 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:00:57.813  3682  3734 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 15:00:57.813  3682  3734 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:00:57.813  3682  3734 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 15:00:57.813  3682  3734 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-15 15:00:57.813  4195  4222 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
03-15 15:00:57.813  3682  3734 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-15 15:00:57.813  3682  3734 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 15:00:57.823  3682  3734 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 15:00:57.823  3682  3734 I AMMetaDataParserService: getResourceTypeNamexml
03-15 15:00:57.823  3682  3734 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
03-15 15:00:57.833  4195  4222 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
03-15 15:00:57.833  1019  1143 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-15 15:00:57.833  1019  1143 W ActivityManager: mDVFSHelper.acquire()
03-15 15:00:57.843  1019  1143 D FocusedStackFrame: Set to : 0
03-15 15:00:57.843  3682  3734 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
03-15 15:00:57.843  1490  1490 D Launcher.HomeView: onPause
03-15 15:00:57.843  1019  1143 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 15:00:57.843  1019  1143 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 15:00:57.843  1019  1143 D InputDispatcher: Focused application set to: xxxx
03-15 15:00:57.843  1019  1143 D InputDispatcher: Focus left window: 1490
03-15 15:00:57.843  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-15 15:00:57.843  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-15 15:00:57.853  4293  4293 I dex2oat : ----------------------------------------------------
03-15 15:00:57.853  4293  4293 I dex2oat : <SS>: S T A R T I N G . . .
03-15 15:00:57.853  4293  4293 I dex2oat : <SS>: Zip is absent. Canceled.
03-15 15:00:57.853  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-15 15:00:57.853  4293  4293 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-2096234451.jar --oat-fd=25 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-2096234451.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
03-15 15:00:57.853  4237  4237 D AndroidRuntime: Shutting down VM
03-15 15:00:57.853  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 15:00:57.853  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-15 15:00:57.863  1019  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.863  1019  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.863  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-15 15:00:57.863  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-15 15:00:57.863  1019  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.863  1019  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.863   257   257 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-15 15:00:57.873  3682  3734 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
03-15 15:00:57.893  4305  4305 E Zygote  : MountEmulatedStorage()
03-15 15:00:57.893  4305  4305 E Zygote  : v2
03-15 15:00:57.893  4305  4305 I libpersona: KNOX_SDCARD checking this for 10174
03-15 15:00:57.893  4293  4293 I dex2oat : dex2oat took 43.177ms (threads: 4)
03-15 15:00:57.893  4305  4305 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 15:00:57.893  4305  4305 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:57.893  4305  4305 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 15:00:57.893  4305  4305 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-15 15:00:57.903  1019  1309 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4305 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-15 15:00:57.913  1019  1043 W libprocessgroup: failed to open /acct/uid_10028/pid_3147/cgroup.procs: No such file or directory
03-15 15:00:57.913  1019  1791 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 15:00:57.923  1019  1791 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:57.923  1019  1791 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:57.923  1019  1791 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
03-15 15:00:57.933  4305  4305 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:57.933  4305  4305 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:57.933  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{9b8d1bd token=android.os.BinderProxy@27e7f5e1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-15 15:00:57.933  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 15:00:57.933  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:57.933  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:57.933  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
03-15 15:00:57.933  4239  4239 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
03-15 15:00:57.943  1019  1553 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 15:00:57.943  1019  1553 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-15 15:00:57.943  1019  1553 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 15:00:57.943  1490  1490 D Launcher.HomeView: onStop
03-15 15:00:57.943  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{9b8d1bd token=android.os.BinderProxy@27e7f5e1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-15 15:00:57.943  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 15:00:57.953  1019  1553 D PersonaManager: isKioskContainerExistOnDevice
03-15 15:00:57.953  3682  3734 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
03-15 15:00:57.993  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-15 15:00:57.993  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:57.993  3682  3734 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:00:57.993  3682  3734 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:57.993  3682  3734 I AMMetaDataParserService: Resource data:2131165197
03-15 15:00:57.993  3682  3734 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 15:00:57.993  3682  3734 I AMMetaDataParserService: getResourceTypeNamexml
03-15 15:00:57.993  1490  1490 D Launcher: onTrimMemory. Level: 20
03-15 15:00:58.003  3682  3734 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
03-15 15:00:58.023  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-15 15:00:58.023  1019  1019 D SensorService: [SO] activate (ident=0xb8952600, enabled=0)
03-15 15:00:58.023  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-15 15:00:58.033  1019  1019 D SensorManager: unregisterListener ::   
03-15 15:00:58.033  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-15 15:00:58.033  1019  1019 D SensorService: [SO] changed settle time [1]
03-15 15:00:58.033  1019  1019 D SensorService: [SO] setDelay [66000000]
03-15 15:00:58.033  1019  1019 D SensorService: [SO] activate (ident=0xb8952600, enabled=1)
03-15 15:00:58.033  1019  1019 D SensorService: [SO] AR_init
03-15 15:00:58.033  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-15 15:00:58.043  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-15 15:00:58.043  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 15:00:58.043  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 15:00:58.043  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:00:58.053  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:00:58.053  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:00:58.053  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:00:58.063  4237  4237 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-15 15:00:58.103   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-15 15:00:58.103   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:00:58.103  4239  4239 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-15 15:00:58.113  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 15:00:58.113  4305  4305 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,03-15 15:00:58.133  4305  4305 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 5002-5008)
03-15 15:00:58.133  4305  4305 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 15:00:58.163  4305  4305 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {18ae6ab5}
,03-15 15:00:58.163  4305  4305 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 15:00:58.163  4305  4305 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-15 15:00:58.183  1019  1041 D SensorService: [SO] 0.192 0.402 10.247
,03-15 15:00:58.183  1019  1041 D SensorService: [SO] [100 -> 255]
,03-15 15:00:58.203  4305  4305 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-15 15:00:58.203  4305  4305 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:00:58.203  4305  4305 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-15 15:00:58.213  3682  3734 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 15:00:58.223  4305  4305 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-15 15:00:58.223  4305  4305 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-15 15:00:58.223  4305  4305 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-15 15:00:58.223  4305  4305 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 15:00:58.223  4305  4305 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 15:00:58.223  4305  4305 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 15:00:58.223  4305  4305 I Adreno-EGL: Local Branch: 
03-15 15:00:58.223  4305  4305 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 15:00:58.223  4305  4305 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 15:00:58.223  4305  4305 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 15:00:58.233  1019  1309 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-15 15:00:58.243  1019  1309 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:00:58.243  1019  1309 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:58.243  1019  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-15 15:00:58.263  3682  3734 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 15:00:58.283  3682  3734 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 15:00:58.303  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
03-15 15:00:58.303  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-15 15:00:58.303  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.303  3682  3734 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:58.303  3682  3734 I AMMetaDataParserService: Resource data:2131165197
,03-15 15:00:58.313  3682  3734 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 15:00:58.313  3682  3734 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:00:58.323  3682  3734 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-15 15:00:58.333  3682  3734 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 15:00:58.363  3682  3734 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 15:00:58.403   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-15 15:00:58.403   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:00:58.403  4239  4239 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-15 15:00:58.403   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-15 15:00:58.403   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:00:58.403  4239  4239 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-15 15:00:58.403   257  1059 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,03-15 15:00:58.413   257  1109 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-15 15:00:58.413   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-15 15:00:58.413   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:00:58.413  4239  4239 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-15 15:00:58.413  4239  4239 W InstanceID/Rpc: Found 10012
,03-15 15:00:58.423  1019  1309 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:00:58.423  1019  1309 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:00:58.423  1019  1309 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:58.423  1019  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-15 15:00:58.453  3682  3734 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-15 15:00:58.483  3682  3734 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:58.483  3682  3734 I AMMetaDataParserService: Resource data:2131099648
03-15 15:00:58.493   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-15 15:00:58.493   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
03-15 15:00:58.493  4239  4239 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
03-15 15:00:58.493  3682  3734 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-15 15:00:58.493  3682  3734 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 15:00:58.493  3682  3734 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 15:00:58.493  3682  3734 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-15 15:00:58.493  3682  3734 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 15:00:58.493  3682  3734 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-15 15:00:58.493  3682  3734 I AMMetaDataParserService: getResourceTypeNamexml
03-15 15:00:58.493  4305  4305 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-15 15:00:58.503  3682  3734 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
03-15 15:00:58.513  1019  1143 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
03-15 15:00:58.513  1019  1143 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:58.513  4305  4305 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-15 15:00:58.513  1019  1143 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:58.513  1019  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-15 15:00:58.513  3682  3734 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
03-15 15:00:58.523  4305  4305 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-15 15:00:58.523  4305  4305 D PhoneWindow: *FMB* installDecor flags : -2139027200
03-15 15:00:58.533  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-15 15:00:58.533  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-15 15:00:58.533  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-15 15:00:58.533  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
03-15 15:00:58.533  3682  3734 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 15:00:58.533  4305  4305 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
03-15 15:00:58.543  4305  4305 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-15 15:00:58.543  4305  4305 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:00:58.603  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-15 15:00:58.603  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:58.603  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:58.603  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-15 15:00:58.613  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-15 15:00:58.613  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.613  3682  3734 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:58.613  3682  3734 I AMMetaDataParserService: Resource data:2131165220
,03-15 15:00:58.623  3682  3734 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-15 15:00:58.623  3682  3734 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 15:00:58.623  3682  3734 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 15:00:58.623  3682  3734 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:00:58.623  3682  3734 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:00:58.623  3682  3734 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-15 15:00:58.623  3682  3734 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-15 15:00:58.623  3682  3734 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:00:58.693  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:58.693  3682  3734 I GFX raster: took 0.707812ms for 96*96 texture 0
03-15 15:00:58.693  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8d5a680 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d5a448 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:58.703  3682  3734 I AMMetaDataParserService: Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,03-15 15:00:58.703  4305  4392 D OpenGLRenderer: Render dirty regions requested: true
,03-15 15:00:58.713  1019  1143 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-15 15:00:58.713  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-15 15:00:58.713  1019  1143 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 15:00:58.713  1019  1143 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-15 15:00:58.713  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-15 15:00:58.713  4305  4350 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
03-15 15:00:58.713  4239  4388 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
03-15 15:00:58.713  4239  4388 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-15 15:00:58.723  4305  4305 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-15 15:00:58.723  4305  4305 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-15 15:00:58.723  3682  3734 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:58.723  3682  3734 I GFX raster: took 0.596927ms for 96*96 texture 0
03-15 15:00:58.723  3682  3734 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8d5a528 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d6d850 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:58.733  3682  3734 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
03-15 15:00:58.743  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
03-15 15:00:58.743  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:58.743  1019  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:58.743  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-15 15:00:58.743   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
03-15 15:00:58.743  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
03-15 15:00:58.743  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:58.743  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:58.753  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-15 15:00:58.753  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
03-15 15:00:58.753  4239  4388 I System.out: Thread-706(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
03-15 15:00:58.753  1019  1032 D InputDispatcher: Focus entered window: 4305
,03-15 15:00:58.753  4239  4388 I System.out: Thread-706(ApacheHTTPLog):isSBSettingEnabled false
03-15 15:00:58.753  4239  4388 I System.out: Thread-706(ApacheHTTPLog):isShipBuild true
03-15 15:00:58.753  4239  4388 I System.out: Thread-706(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-15 15:00:58.753  4239  4388 I System.out: Thread-706(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-15 15:00:58.753   278   970 D EnterpriseController: uids 10166
03-15 15:00:58.753   278   970 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 15:00:58.753   278   970 D Netd    : getNetworkForDns: using netid 502 for uid 10166
,03-15 15:00:58.763  4305  4305 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 15:00:58.763  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 15:00:58.763  4305  4392 I OpenGLRenderer: Initialized EGL, version 1.4
,03-15 15:00:58.763  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 15:00:58.773  1019  1553 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-15 15:00:58.773  1019  1553 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:58.773  4305  4392 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-15 15:00:58.773  4305  4392 D OpenGLRenderer: Enabling debug mode 0
,03-15 15:00:58.773  1019  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:58.773  1019  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-15 15:00:58.773  1019  1791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-15 15:00:58.773  1019  1791 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-15 15:00:58.773  1019  1791 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
03-15 15:00:58.773  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-15 15:00:58.783  1019  1019 I MotionRecognitionService: Plugged
03-15 15:00:58.783  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.,settings.wifi.WifiSecSetupActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.783  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-15 15:00:58.783  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.a,ndroid.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
,03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:00:58.793  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.793  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
,03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
,03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.813  3682  3734 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDat,aParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-1,5 15:00:58.783  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-15 15:00:58.783  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  2683  2683 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-15 15:00:58.793  2683  2779 D HeadsetStateMachine: Disconnected process message: 10
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.823  1019  1487 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4398 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.823  1019  1098 V AlarmManager: waitForAlarm result :4
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-15 15:00:58.793  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.833  4398  4398 I libpersona: KNOX_SDCARD checking this for 10101
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.833  4398  4398 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-15 15:00:58.833  1019  1098 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-15 15:00:58.803  3682  3734 I AMMetaDataP,arserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.853  1019  1791 I ActivityManager: Killing 3582:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I A,MMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.863  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{fa9decf u0 com.samsung.hs20settings/.WifiHs20UtilityService}
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.andro,id.settings.personalpage.PersonalPageSettings
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
,03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity,
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
,03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-15 15:00:58.803  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMet,aDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-15 15:00:58.913  1019  1049 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.913  1019  1049 W ActivityManager: mDVFSHelper.release()
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.913  1019  4410 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
,03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
,03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
,03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-15 15:00:58.813  3682  3734 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
,03-15 15:00:58.833  4398  4398 E Zygote  : MountEmulatedStorage()
03-15 15:00:58.833  4398  4398 E Zygote  : v2
03-15 15:00:58.833  4398  4398 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 15:00:58.833  4398  4398 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 15:00:58.853  4398  4398 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 15:00:58.853   306   306 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 33.438ms
03-15 15:00:58.853  1019  1554 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-15 15:00:58.893   306   306 I art     : Explicit concurrent mark sweep GC freed 4(112B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 30.192ms
03-15 15:00:58.903  1019  1049 I ActivityManager: Displayed Component not be shown by security: +1s51ms
03-15 15:00:58.913  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c7a70f2 u0 com.test.thalitest/.MainActivity t236} time:45781
,03-15 15:00:58.923   306   306 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 30.612ms
,03-15 15:00:58.923  4398  4398 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:58.923  4398  4398 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:58.933  1180  1180 D PanelView: There is/are notification(s) 
,03-15 15:00:58.933  1832  1832 I SamsungIME: getCurrentCandidateView
,03-15 15:00:58.953  4305  4305 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@35cce687 time:45829
,03-15 15:00:58.963  1019  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-15 15:00:58.973  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:58.973  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
03-15 15:00:58.973  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:58.973  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-15 15:00:58.983  4305  4305 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4305
,03-15 15:00:59.003  1019  1043 W libprocessgroup: failed to open /acct/uid_10069/pid_3582/cgroup.procs: No such file or directory
,03-15 15:00:59.033  1832  1832 D SamsungIME: Dismiss ExpandCandiate
,03-15 15:00:59.043  1986  4405 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 188 ms
,03-15 15:00:59.053  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 15:00:59.053  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 15:00:59.053  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:00:59.053  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:00:59.053  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:00:59.053  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:00:59.063  1019  1487 I ActivityManager: Killing 3566:com.android.calendar/u0a135 (adj 15): empty #31
,03-15 15:00:59.083  1832  1832 I SamsungIME: getDebugLevel  : 0x4f4c
,03-15 15:00:59.093  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{1051205c u0 com.google.android.gms/.gcm.GcmService}
,03-15 15:00:59.133  1019  1043 W libprocessgroup: failed to open /acct/uid_10135/pid_3566/cgroup.procs: No such file or directory
,03-15 15:00:59.133  1832  1832 I SamsungIME: getDebugLevel  : 0x4f4c
,03-15 15:00:59.143   257  1109 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-15 15:00:59.143   257  1059 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-15 15:00:59.193  1832  1832 I SamsungIME: KeybaordView init() : load resources
,03-15 15:00:59.233  1832  1832 I SamsungIME: getCurrentKeyboard
03-15 15:00:59.233  1832  1832 I SamsungIME: getTextKeyboard
,03-15 15:00:59.253  4305  4305 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-15 15:00:59.263  1832  1832 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-15 15:00:59.263  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-15 15:00:59.363  4239  4388 I System.out: Thread-706 calls detatch()
,03-15 15:00:59.383  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
03-15 15:00:59.383  1019  1031 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,03-15 15:00:59.433  4305  4394 D jxcore_app_log: JniHelper::setJavaVM(0xb8285450), pthread_self() = -1200729328
,03-15 15:00:59.443  4305  4394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-15 15:00:59.443  4305  4394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-15 15:00:59.443  4305  4394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-15 15:00:59.443  4305  4394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-15 15:00:59.443  4305  4394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-15 15:00:59.443  4305  4394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e2ab02 added. We now have 1 listener(s)
,03-15 15:00:59.453  4305  4394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:51:18:22
,03-15 15:00:59.453  4305  4394 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
,03-15 15:00:59.453  4305  4394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
03-15 15:00:59.453  4305  4394 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-15 15:00:59.453  4305  4394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-15 15:00:59.463  4305  4394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-15 15:00:59.463  4305  4394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-15 15:00:59.463  4305  4394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-15 15:00:59.463  4305  4394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:51:18:22
03-15 15:00:59.463  4305  4394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-15 15:00:59.463  4305  4394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-15 15:00:59.463  4305  4394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-15 15:00:59.463  4305  4394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-15 15:00:59.463  4305  4394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-15 15:00:59.463  4305  4394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-15 15:00:59.463  4305  4394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bd68849 added. We now have 1 listener(s)
,03-15 15:00:59.463  4305  4394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-15 15:00:59.473  4305  4394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-15 15:00:59.473  4305  4394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-15 15:00:59.473  4305  4394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-15 15:00:59.473  4305  4394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-15 15:00:59.473  4305  4394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-15 15:00:59.473  4305  4394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-15 15:00:59.473  4305  4394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:51:18:22
,03-15 15:00:59.483  4305  4394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-15 15:00:59.483  4305  4394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-15 15:00:59.483  4305  4394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-15 15:00:59.483  4305  4394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-15 15:00:59.483  4305  4394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-15 15:00:59.483  4305  4394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-15 15:00:59.483  4305  4394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-15 15:00:59.483  4305  4394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-15 15:00:59.483  4305  4394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-15 15:00:59.483  4305  4394 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-15 15:00:59.493  4305  4305 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 15:00:59.503  4305  4305 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 15:00:59.513   291   291 E SMD     : DCD OFF
,03-15 15:00:59.533  4305  4305 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-15 15:00:59.553  4398  4429 I Gmail   : getAccountsCursor
,03-15 15:00:59.553  1019  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 15:00:59.563  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-15 15:00:59.583  4398  4398 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-15 15:00:59.623  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,03-15 15:00:59.623  1019  1554 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-15 15:00:59.643  1019  1553 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,03-15 15:00:59.643  1019  1553 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:00:59.643  1019  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:59.643  1019  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-15 15:00:59.653  1019  1143 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 15:00:59.653  1019  1143 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-15 15:00:59.663  4398  4437 I Gmail   : Observing account changes for notifications
,03-15 15:00:59.663  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,03-15 15:00:59.663  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:00:59.663  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:59.663  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-15 15:00:59.673  1019  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:00:59.673  1019  1559 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-15 15:00:59.703  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,03-15 15:00:59.703  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:00:59.703  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:59.703  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-15 15:00:59.703  4398  4439 E Gmail   : Error finding the version of the Email provider.....
03-15 15:00:59.703  4398  4439 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-15 15:00:59.703  4398  4439 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-15 15:00:59.703  4398  4439 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
03-15 15:00:59.703  4398  4439 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
03-15 15:00:59.703  4398  4439 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-15 15:00:59.703  4398  4439 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 15:00:59.703  4398  4439 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-15 15:00:59.703  4398  4439 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 15:00:59.703  4398  4439 W EmailMigration: We do not support migrating this version of the Email provider.
,03-15 15:00:59.713  4398  4441 I Gmail   : getAccountsCursor
,03-15 15:00:59.713  1019  1282 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 15:00:59.723  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:00:59.723  1019  1556 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-15 15:00:59.723  1019  1556 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:00:59.723  1019  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:00:59.723  1019  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-15 15:00:59.733  1019  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.733  1019  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.733  1019  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.733  1019  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:59.743  4445  4445 E Zygote  : MountEmulatedStorage()
03-15 15:00:59.743  4445  4445 E Zygote  : v2
03-15 15:00:59.743  4445  4445 I libpersona: KNOX_SDCARD checking this for 10092
03-15 15:00:59.743  4445  4445 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:59.743  4445  4445 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:00:59.753  4445  4445 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:00:59.753  4445  4445 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-15 15:00:59.753  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,03-15 15:00:59.763  1019  1554 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=4445 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:00:59.763  1019  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 15:00:59.763  1019  1559 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-15 15:00:59.763  1019  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 15:00:59.773  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:00:59.783  1019  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 15:00:59.783  1019  1487 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-15 15:00:59.823  4445  4445 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:59.823  4445  4445 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:59.863  4398  4442 E SQLiteLog: (283) recovered 40 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-15 15:00:59.983  4398  4442 E File    : fail readDirectory() errno=2
,03-15 15:00:59.983  1019  1098 V AlarmManager: waitForAlarm result :8
,03-15 15:00:59.993  1019  1501 I art     : Explicit concurrent mark sweep GC freed 41540(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 3.007ms total 198.232ms
,03-15 15:00:59.993  1019  1309 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 15:01:00.003  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:01:00.013  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-15 15:01:00.013  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
,03-15 15:01:00.013  4398  4458 I Gmail   : notifyAccountChanged
,03-15 15:01:00.033  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-15 15:01:00.033  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1
,03-15 15:01:00.043  4398  4458 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 15:01:00.053  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 15:01:00.053  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-15 15:01:00.053  1180  1180 I KeyguardEffectViewController: *** don't update sliding image ***
,03-15 15:01:00.063  4398  4458 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 15:01:00.063  1608  1608 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,03-15 15:01:00.063  1608  1608 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-15 15:01:00.063  1608  1608 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-15 15:01:00.073  1608  1608 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,03-15 15:01:00.073  1608  1608 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-15 15:01:00.073  4398  4398 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@31992d76 that was originally bound here
03-15 15:01:00.073  4398  4398 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@31992d76 that was originally bound here
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at com.android.emailcommon.service.ak.a(SourceFile:181)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at com.android.emailcommon.service.ak.e(SourceFile:224)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:177)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:198)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:142)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-15 15:01:00.073  4398  4398 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-15 15:01:00.073  1608  1608 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,03-15 15:01:00.073  1608  1608 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,03-15 15:01:00.073  1608  1608 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,03-15 15:01:00.073  1608  1608 D accuweather: [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,03-15 15:01:00.073  1019  1554 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@25c339e6
,03-15 15:01:00.073  1608  1608 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 01
,03-15 15:01:00.093  4398  4429 I Gmail   : getAccountsCursor
,03-15 15:01:00.113  1019  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 15:01:00.113  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:01:00.133  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 15:01:00.133  4398  4458 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-15 15:01:00.143  4398  4458 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-15 15:01:00.143  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 15:01:00.143  4398  4442 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
,03-15 15:01:00.143  1019  1143 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-15 15:01:00.143  1019  1143 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:00.143  1019  1143 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:00.143  1019  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-15 15:01:00.143  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 15:01:00.153  4398  4442 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,03-15 15:01:00.183  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 15:01:00.183  4398  4442 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
,03-15 15:01:00.183  1019  1554 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:00.193  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:00.193  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:00.193  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:00.203  1019  1282 I ActivityManager: Killing 3628:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-15 15:01:00.253  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:00.253  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:00.263  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:00.263  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:00.283  1019  1051 D PowerManagerService: [s] UserActivityState : 1 -> 2
,03-15 15:01:00.283  1019  1051 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-15 15:01:00.283  1019  1051 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-15 15:01:00.283  1019  1051 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-15 15:01:00.283  1019  1163 D lights  : lcd : 26 +
,03-15 15:01:00.303  1019  1051 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-15 15:01:00.303  1019  1051 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-15 15:01:00.303  1019  1163 D lights  : lcd : 26 -
03-15 15:01:00.303  1019  1163 D lights  : lcd : 19 +
,03-15 15:01:00.313  1019  1163 D lights  : lcd : 19 -
,03-15 15:01:00.323  1019  1051 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-15 15:01:00.323  1019  1051 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 15:01:00.323  1019  1043 W libprocessgroup: failed to open /acct/uid_10139/pid_3628/cgroup.procs: No such file or directory
,03-15 15:01:00.333  4398  4430 I Gmail   : getAccountsCursor
,03-15 15:01:00.333  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 15:01:00.333  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:01:00.393  1019  1309 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-15 15:01:00.393  1019  1309 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:00.393  1019  1309 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-15 15:01:00.393  1019  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-15 15:01:00.393  1019  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.393  1019  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:00.393  1019  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.393  1019  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.413  4469  4469 E Zygote  : MountEmulatedStorage()
03-15 15:01:00.413  4469  4469 I libpersona: KNOX_SDCARD checking this for 10092
03-15 15:01:00.413  4469  4469 E Zygote  : v2
03-15 15:01:00.413  4469  4469 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:00.413  4469  4469 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-15 15:01:00.413  4469  4469 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-15 15:01:00.413  1019  1309 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=4469 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 15:01:00.413  4469  4469 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-15 15:01:00.433  4469  4469 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:00.433  4469  4469 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:00.483  4445  4445 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-15 15:01:00.503  4445  4445 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-15 15:01:00.543  1019  1501 I ActivityManager: Killing 3313:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,03-15 15:01:00.563  4445  4445 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_9807ade0d39f04306c7e28de04204d1f53ae2228_armv7a
,03-15 15:01:00.563  4445  4445 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-15 15:01:00.573  4445  4445 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_b492ffd532b8b6365d97439f842c164c3c90fd4e_armv7a
,03-15 15:01:00.573  4445  4445 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_e16babc055b114839529ea959e1ce06f2a593b63_armv7a
,03-15 15:01:00.613  1019  1043 W libprocessgroup: failed to open /acct/uid_10009/pid_3313/cgroup.procs: No such file or directory
,03-15 15:01:00.683  4445  4445 I libDropboxSync.so: Setting global terminate handler.
,03-15 15:01:00.703  4195  4220 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 15:01:00.723  4445  4445 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_aa417f8c60b792b71fc3cef90fc4bb8ddba4ea56_armv7a
,03-15 15:01:00.733  4195  4220 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-15 15:01:00.733  4195  4220 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-15 15:01:00.733  4195  4220 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-15 15:01:00.743  4195  4220 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-15 15:01:00.743  4195  4220 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-15 15:01:00.743  4195  4220 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-15 15:01:00.753  4195  4220 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-15 15:01:00.753  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-15 15:01:00.783  4445  4445 I com.dropbox.sync.android.L: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-15 15:01:00.803  4445  4445 I com.dropbox.sync.android.L: Removing unclaimed file/directory in cache: "local-dbapp_noauth"
,03-15 15:01:00.813  4445  4445 I com.dropbox.sync.android.bf: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/3.0.2 DropboxSync/3.1+dev (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-15 15:01:00.823  4445  4445 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:01:00.823  4445  4445 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:01:00.853  4445  4445 I com.dropbox.sync.android.aS: Created NativeDbappNoAuthClientProvider
,03-15 15:01:00.853  1019  1553 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.sync.android.DbxSyncService; callingUser = 0; userId(target) = 0
,03-15 15:01:00.863  1019  1553 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:00.863  1019  1553 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-15 15:01:00.863  1019  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-15 15:01:00.893  4445  4492 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
03-15 15:01:00.893  4445  4492 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-15 15:01:00.893  4445  4492 I System.out: (HTTPLog)-Static: isShipBuild true
03-15 15:01:00.893  4445  4492 I System.out: (HTTPLog)-Thread-677-909036184: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-15 15:01:00.893  4445  4492 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-15 15:01:00.893   278   970 D EnterpriseController: uids 10092
03-15 15:01:00.893   278   970 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 15:01:00.893   278   970 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-15 15:01:00.983  4445  4492 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-15 15:01:01.023  4445  4445 I com.dropbox.sync.android.DbxSyncService: DbxSyncService starting.
,03-15 15:01:01.023  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:01.023  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:01.023  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.023  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:01.043  4504  4504 E Zygote  : MountEmulatedStorage()
03-15 15:01:01.043  4504  4504 E Zygote  : v2
03-15 15:01:01.043  4504  4504 I libpersona: KNOX_SDCARD checking this for 10057
03-15 15:01:01.043  4504  4504 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:01.043  4504  4504 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:01:01.043  1019  1559 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4504 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-15 15:01:01.043  4504  4504 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:01.043  4504  4504 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 15:01:01.053  1019  1791 I ActivityManager: Killing 3646:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,03-15 15:01:01.073  4504  4504 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:01.073  4504  4504 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:01.093  4305  4428 W jxcore-log: Initializing JXcore engine
03-15 15:01:01.093  4305  4428 W jxcore-log: JXcore engine is ready
,03-15 15:01:01.143  1904  1904 E audit   : type=1400 msg=audit(1458050461.143:205): avc:  denied  { ioctl } for  pid=4428 comm="Thread-684" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-15 15:01:01.143  1904  1904 E audit   :  SEPF_SM-A500FU_5.0.2_0027
03-15 15:01:01.143  1904  1904 E audit   : type=1300 msg=audit(1458050461.143:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9c2ef8f8 items=0 ppid=306 ppcomm=main pid=4428 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-684" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-15 15:01:01.143  1904  1904 E audit   : type=1320 msg=audit(1458050461.143:205): 
,03-15 15:01:01.163  4305  4428 W jxcore-log: Starting JXcore engine
,03-15 15:01:01.163  1019  1043 W libprocessgroup: failed to open /acct/uid_10014/pid_3646/cgroup.procs: No such file or directory
,03-15 15:01:01.193  4445  4492 I com.dropbox.sync.android.aF: Created new socket: SSL socket over Socket[address=api.dropbox.com/108.160.172.237,port=443,localPort=51020]
,03-15 15:01:01.273  4305  4428 W jxcore-log: Platform android
03-15 15:01:01.273  4305  4428 W jxcore-log: 
03-15 15:01:01.273  4305  4428 W jxcore-log: Process ARCH arm
03-15 15:01:01.273  4305  4428 W jxcore-log: 
,03-15 15:01:01.293  1019  1790 D LocationManagerService: getProviders()=[passive]
,03-15 15:01:01.363  1019  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-15 15:01:01.363  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.363  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 15:01:01.363  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-15 15:01:01.403  1019  1553 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,03-15 15:01:01.403  1019  1553 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.403  1019  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 15:01:01.413  1019  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-15 15:01:01.423  1019  1553 I splitIntent: Queue : backgroundsplit_2 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-15 15:01:01.433  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.433  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.433  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:01.443  3848  3848 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-15 15:01:01.443  3848  3848 D SecurityLogAgent:  SeDenialReceiver : File path = /data/misc/audit/audit.old
,03-15 15:01:01.443  3848  3848 D SecurityLogAgent:  SeDenialReceiver : Start file Zipping Service 
,03-15 15:01:01.443  3848  3848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,03-15 15:01:01.443  1019  1309 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
,03-15 15:01:01.453  1019  1309 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.453  1019  1309 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 15:01:01.453  1019  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,03-15 15:01:01.473  1019  1790 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.473  1019  1790 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.473  1019  1790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:01.473  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.473  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.473  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,03-15 15:01:01.483  3848  4536 D SecurityLogAgent: FileZippingService : onHandleIntent 
,03-15 15:01:01.483  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-15 15:01:01.483  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-15 15:01:01.483  3848  4536 D SecurityLogAgent: FileZippingService : file path =  /data/misc/audit/audit.old
03-15 15:01:01.483  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.483  3848  4536 D SecurityLogAgent: FileZippingService : onPremise disabled. Zipping..  
,03-15 15:01:01.493  3848  4536 D SecurityLogAgent: DenialLogFileZipCreator : createZip
,03-15 15:01:01.493  3848  4536 D SecurityLogAgent: DenialLogFileZipCreator : Not empty 
,03-15 15:01:01.493  3848  4536 D SecurityLogAgent: DenialLogFileZipCreator : Files exceeded the max limit 
,03-15 15:01:01.493  3848  4536 D SecurityLogAgent: DenialLogFileZipCreator File existence : true audit.old file size 631
,03-15 15:01:01.503  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.503  3848  4536 D SecurityLogAgent: DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
,03-15 15:01:01.503  3848  4536 D SecurityLogAgent: FileZippingService : completed task. Returning wakelock . 
,03-15 15:01:01.503  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-15 15:01:01.513  1292  1292 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true,
,03-15 15:01:01.523  1292  1292 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-15 15:01:01.523  1292  1292 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-15 15:01:01.523  1292  1292 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-15 15:01:01.523  1292  1292 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-15 15:01:01.523  1292  1292 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-15 15:01:01.523  1292  1292 D daemonapp: [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,03-15 15:01:01.533  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-15 15:01:01.533  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-15 15:01:01.543  4445  4461 W art     : Suspending all threads took: 8.096ms
,03-15 15:01:01.603  1292  1292 D daemonapp: [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,03-15 15:01:01.603  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:1058 [0:0] chkNW: true
,03-15 15:01:01.603  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:750 [0:0] Cncl30MinRftAl
,03-15 15:01:01.613  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:1058 [0:0] chkNW: true
,03-15 15:01:01.613  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.613  1019  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:01.623  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.623  1019  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:01.623  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-15 15:01:01.633  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-15 15:01:01.633  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-15 15:01:01.633  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-15 15:01:01.643  1019  1282 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:01.643  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:1056 [0:0] == cityListItem Size : 0
,03-15 15:01:01.643  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:175 [0:0] ============== Start refreshType : 3
03-15 15:01:01.643  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.643  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:206 [0:0] checkCuL:0, mCityDataList : 0
,03-15 15:01:01.643  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:904 [0:0] MR pcknme : Manual systemui
,03-15 15:01:01.643  1019  1282 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.643  1019  1282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 15:01:01.643  1019  1282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:01.653  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-15 15:01:01.653  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-15 15:01:01.653  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:257 [0:0] == rCL 1458050461664
,03-15 15:01:01.663  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-15 15:01:01.663  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-15 15:01:01.663  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-15 15:01:01.663  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-15 15:01:01.673  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-15 15:01:01.673  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-15 15:01:01.673  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:273 [0:0] EUR
,03-15 15:01:01.673  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.683  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:278 [0:0] checkCuL:0, getRefreshType():3
,03-15 15:01:01.683  1292  1292 D daemonapp: [MSC_Daemon]>>> WMCL:455 [0:0] MCL pfGetCL@NP:false
03-15 15:01:01.683  1292  1292 D daemonapp: [MSC_Daemon]>>> WMCL:461 [0:0] MCL pfL set:t
,03-15 15:01:01.683  1292  1292 D daemonapp: [MSC_Daemon]>>> WMCL:1895 [0:0] MCL getLLoc@
03-15 15:01:01.683  1292  1292 D daemonapp: [MSC_Daemon]>>> WMCL:244 [0:0] MCL getCPrvdr@
,03-15 15:01:01.683  1292  1292 D daemonapp: [MSC_Daemon]>>> WMCL:1954 [0:0] PrvdrErr!!
,03-15 15:01:01.683  1292  1292 D daemonapp: [MSC_Daemon]>>> WMCL:1956 [0:0] PrvdrErr getPerformLoc:true
03-15 15:01:01.683  1292  1292 D daemonapp: [MSC_Daemon]>>> WMCL:1958 [0:0] MCL pfL set:f
03-15 15:01:01.683  1292  1292 D daemonapp: [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
03-15 15:01:01.683  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,03-15 15:01:01.693  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1458050461705
,03-15 15:01:01.693  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1458072061699
03-15 15:01:01.693  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
03-15 15:01:01.693  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,03-15 15:01:01.703  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1458072060000
,03-15 15:01:01.703  1292  1292 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458072060000
03-15 15:01:01.703  4504  4537 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-15 15:01:01.703  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
03-15 15:01:01.703  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1458072060000
03-15 15:01:01.703  1292  1292 D daemonapp: [MSC_Daemon]>>> AWCLRH:43 [0:0] ==============rLH=====================
,03-15 15:01:01.703  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-15 15:01:01.703  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-15 15:01:01.703  1019  1143 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:01.703  1019  1143 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.713  1019  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 15:01:01.713  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:1314 [0:0] CL@AtRfr = 3
03-15 15:01:01.713  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-15 15:01:01.713  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:1321 [0:0]  AR_lasttime: 1458072060000
03-15 15:01:01.713  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:1615 [0:0] util getnext by widget 1458072060000
03-15 15:01:01.713  1292  1292 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458072060000
03-15 15:01:01.713  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:01.713  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.713  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 15:01:01.723  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
03-15 15:01:01.723  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:1332 [0:0] NextTime       :1458072060000
03-15 15:01:01.723  1292  1292 D daemonapp: [MSC_Daemon]>>> AWCLRH:242 [0:0] rLH /on rciclf
03-15 15:01:01.723  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:1480 [0:0]  retryCityIdCurrentlocationfail getRefreshType : 3
03-15 15:01:01.723  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:1491 [0:0] send broad cast error to clock
03-15 15:01:01.723  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:01.723  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.723  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 15:01:01.723  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:01.723  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.723  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 15:01:01.733  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-15 15:01:01.733  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-15 15:01:01.733  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-15 15:01:01.743  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.743  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 15:01:01.743  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
03-15 15:01:01.743  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 15:01:01.743  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.743  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.743  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.743  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 15:01:01.743  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,03-15 15:01:01.743  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-15 15:01:01.753  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:01.753  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.753  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:01.753  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.753  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.753  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.753  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:01.753  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.753  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.763  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:01.763  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-15 15:01:01.763  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,03-15 15:01:01.773  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.773  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 15:01:01.773  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:01.773  4305  4428 I jxcore-log: JXcore Cordova bridge is ready!
03-15 15:01:01.773  4305  4428 I jxcore-log: 
03-15 15:01:01.773  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.773  4305  4428 W jxcore-log: JXcore engine is started
,03-15 15:01:01.773  1019  1309 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-15 15:01:01.773  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.783  4504  4537 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8649-8653)
03-15 15:01:01.783  4504  4537 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 15:01:01.783  4305  4394 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-15 15:01:01.783  1019  1309 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.783  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.783  1019  1309 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 15:01:01.783  1019  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 15:01:01.793  2579  2579 I Hs20UtilService: Starting #3
,03-15 15:01:01.793  2579  2594 I Hs20UtilService: Message received 5011
,03-15 15:01:01.793  1019  1135 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-15 15:01:01.793  1019  1135 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-15 15:01:01.793  1019  1135 E WifiNative-wlan0: invaild command id : 215
,03-15 15:01:01.803  4305  4428 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-15 15:01:01.803  4305  4428 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
03-15 15:01:01.803  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.803  3848  3848 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-15 15:01:01.803  3848  3848 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 15:01:01.803  3848  3848 D SecurityLogAgent: StateMachine : Current State = 1
,03-15 15:01:01.803  3848  3848 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-15 15:01:01.803  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:01.803  1019  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.803  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-15 15:01:01.803  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-15 15:01:01.803  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.813  4305  4305 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-15 15:01:01.813  1019  1556 D FocusedStackFrame: Set to : 0
,03-15 15:01:01.813  1019  1556 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 15:01:01.813  1019  1556 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 15:01:01.813  1019  1556 D InputDispatcher: Focused application set to: xxxx
,03-15 15:01:01.823  1019  1556 D InputDispatcher: Focus left window: 4305
,03-15 15:01:01.823  1731  1748 I art     : Explicit concurrent mark sweep GC freed 7737(414KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 1.178ms total 86.484ms
,03-15 15:01:01.823  4504  4537 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:01:01.823  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.833  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 15:01:01.833  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 15:01:01.833  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,03-15 15:01:01.833  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.833  1463  4544 D SIP     : [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,03-15 15:01:01.833  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.833   257  1059 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (182 us)
,03-15 15:01:01.843  1463  4544 E File    : fail readDirectory() errno=2
03-15 15:01:01.843  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,03-15 15:01:01.843  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
03-15 15:01:01.843  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,03-15 15:01:01.873  4305  4394 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 61ms. Plugin should use CordovaInterface.getThreadPool().
,03-15 15:01:01.883  1334  1334 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,03-15 15:01:01.883  1019  1556 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-15 15:01:01.883  1019  1556 W ActivityManager: mDVFSHelper.acquire()
,03-15 15:01:01.893  1019  1556 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 15:01:01.893  1019  1556 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-15 15:01:01.893  1019  1556 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-15 15:01:01.893  1334  1334 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-15 15:01:01.893  1334  1334 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-15 15:01:01.893  1334  1334 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-15 15:01:01.893  1334  1334 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,03-15 15:01:01.893  1334  1334 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 15:01:01.903  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,03-15 15:01:01.903  1292  1292 E daemonapp: [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
03-15 15:01:01.903  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
,03-15 15:01:01.903  1180  1180 D AdaptiveEventManager: action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
03-15 15:01:01.903  1180  1180 D AdaptiveEventManager: currentCityId is null
03-15 15:01:01.903  1180  1180 D AdaptiveEventManager: NetWork disabled : Don't refresh weather info : 201
03-15 15:01:01.903  1180  1180 D AdaptiveEventManager: WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
03-15 15:01:01.903  1180  1180 D AdaptiveEventManager: Weather Visibility: Previous= 0 >> Now= 0
03-15 15:01:01.903  1180  1180 D AdaptiveEventManager: Widget Count: Previous= 0 >> Now= 0
03-15 15:01:01.903  1180  1180 D AdaptiveEventManager: mWeatherInfo is not reliable
,03-15 15:01:01.903  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.903  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.903  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.903  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:01.903  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,03-15 15:01:01.913  1490  1490 D Launcher: onRestart, Launcher: 185828824
,03-15 15:01:01.913  4550  4550 E Zygote  : MountEmulatedStorage()
,03-15 15:01:01.913  4550  4550 E Zygote  : v2
03-15 15:01:01.923  4550  4550 I libpersona: KNOX_SDCARD checking this for 10068
03-15 15:01:01.923  4550  4550 I libpersona: KNOX_SDCARD not a persona
03-15 15:01:01.923  1019  1501 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4550 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:01:01.923  4550  4550 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:01:01.923  4550  4550 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:01.923  4550  4550 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:01:01.923  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:01.923  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:01.923  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
,03-15 15:01:01.933  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
,03-15 15:01:01.933  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.933  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.933  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.933  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:01.933  1292  1292 E daemonapp: [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,03-15 15:01:01.933  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
,03-15 15:01:01.933  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,03-15 15:01:01.943  4563  4563 E Zygote  : MountEmulatedStorage(),
03-15 15:01:01.943  4563  4563 E Zygote  : v2
03-15 15:01:01.943  4563  4563 I libpersona: KNOX_SDCARD checking this for 10135
03-15 15:01:01.943  4563  4563 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:01.943  4563  4563 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-15 15:01:01.943  1019  1044 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=4563 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
03-15 15:01:01.953  1019  1019 D SensorService: [SO] activate (ident=0xb8952600, enabled=0)
03-15 15:01:01.953  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-15 15:01:01.953  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-15 15:01:01.953  4563  4563 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 15:01:01.953  1490  1490 D Launcher: onStart, Launcher: 185828824
03-15 15:01:01.953  1490  1490 D Launcher.HomeView: onStart
03-15 15:01:01.953  1490  1490 D Launcher: onResume, Launcher: 185828824
03-15 15:01:01.953  1019  1791 D SettingsProvider: name = kids_home_mode
,03-15 15:01:01.953  1019  1791 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 15:01:01.953  1019  1791 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
03-15 15:01:01.953  1019  1791 D SettingsProvider: selectionArgs: false
03-15 15:01:01.953  1019  1791 D SettingsProvider: selectionArgs: 10007
03-15 15:01:01.953  1019  1791 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-15 15:01:01.953  1019  1791 D SettingsProvider: ret = -1
,03-15 15:01:01.953  4550  4550 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:01:01.953  1490  1490 D Launcher.HomeView: onResume
03-15 15:01:01.953  4550  4550 D ActivityThread: Added TimaKeyStore provider
03-15 15:01:01.953  4563  4563 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:01:01.963  1019  1019 D SensorManager: unregisterListener ::   
03-15 15:01:01.963  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
03-15 15:01:01.963  1019  1019 D SensorService: [SO] changed settle time [0]
03-15 15:01:01.963  1019  1019 D SensorService: [SO] setDelay [200000000]
03-15 15:01:01.963  1019  1019 D SensorService: [SO] activate (ident=0xb8af54a8, enabled=1)
03-15 15:01:01.963  1019  1019 D SensorService: [SO] AR_init
03-15 15:01:01.963  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-15 15:01:01.963  1292  1292 D daemonapp: [MSC_Daemon]>>> WDBH:4086 [0:0] ud SLS false
03-15 15:01:01.963  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-15 15:01:01.963  1490  1490 D MenuAppsGridFragment: onResume
03-15 15:01:01.963  1019  1791 D ActivityManager: handle home activity for 0
03-15 15:01:01.963  1019  1791 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-15 15:01:01.963  1019  1791 D KnoxTimeoutHandler: post home show event for user 0
03-15 15:01:01.963  1019  1791 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-15 15:01:01.963  1019  1791 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 15:01:01.963  1019  1791 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-15 15:01:01.973  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,03-15 15:01:01.973  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:1344 [0:0] RhTy : 3, ResponseCount :1, Listsize : 0
03-15 15:01:01.973  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:1349 [0:0] =======RefreshType:1 End RetThd Current===========
03-15 15:01:01.973  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:1236 [0:0] resetRefreshThread : 0
03-15 15:01:01.973  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:01.973  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
03-15 15:01:01.973  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,03-15 15:01:01.973  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-15 15:01:01.973  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-15 15:01:01.973  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-15 15:01:01.973  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:1441 [0:0] getBManualRefreshState : false, checkCurrentLocation : 0
03-15 15:01:01.973  1292  1292 D daemonapp: [MSC_Daemon]>>> RM:1353 [0:0] send broad cast to clock Cur
,03-15 15:01:01.983   257   257 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-15 15:01:01.983  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 15:01:01.993  1019  1309 D InputDispatcher: Focus entered window: 1490
,03-15 15:01:01.993  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 15:01:01.993  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 15:01:01.993  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 15:01:01.993  1490  1490 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 15:01:02.013  4563  4563 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:02.013  4563  4563 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:02.023  4550  4550 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-15 15:01:02.023  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-15 15:01:02.033  1019  1501 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-15 15:01:02.033  1180  1180 D PanelView: There is/are notification(s) 
03-15 15:01:02.033  1019  4582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 15:01:02.043  4563  4563 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-15 15:01:02.043  4563  4563 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:01:02.043  4305  4305 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-15 15:01:02.043  4563  4563 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 15:01:02.043  1832  1832 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-15 15:01:02.053  4550  4550 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-15 15:01:02.053  1019  1377 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.053  1019  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
03-15 15:01:02.053  1019  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.053  1019  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.063  4550  4550 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
03-15 15:01:02.063  1019  2830 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 15:01:02.073  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:02.073  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.073  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.073  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.083  1490  1787 W OpenGLRenderer: SFEffectCache::get: create texture(0x9fac8724): name, size, mSize = 39, 135420, 308112
,03-15 15:01:02.093  4504  4537 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:01:02.093  1490  1490 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@27e7f5e1 time:48963
,03-15 15:01:02.093  1019  1049 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:02.113  1292  1708 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:02.113  1019  1049 I ActivityManager: Displayed Component not be shown by security: +223ms
,03-15 15:01:02.113  1019  1282 I ActivityManager: Killing 3682:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-15 15:01:02.123  4550  4550 D FileShare-Client: Outbound.stopDelayTimer - 
,03-15 15:01:02.123  1731  1748 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,03-15 15:01:02.123  1731  1748 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-15 15:01:02.123  1731  1748 I GLSUser : [GLSUser] Extracting token using key: Auth
03-15 15:01:02.123  1731  1748 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-15 15:01:02.133  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:02.133  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:02.133  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:02.133  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-15 15:01:02.143  4588  4588 E Zygote  : MountEmulatedStorage()
,03-15 15:01:02.143  4588  4588 E Zygote  : v2
03-15 15:01:02.143  4588  4588 I libpersona: KNOX_SDCARD checking this for 10069
03-15 15:01:02.143  4588  4588 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:02.143  4588  4588 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:01:02.153  4588  4588 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:02.153  4588  4588 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:02.153  1019  1032 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4588 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:01:02.153  1019  1032 I ActivityManager: Killing 3786:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,03-15 15:01:02.163  1731  1748 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:01:02.163  1019  1553 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-15 15:01:02.163  1019  1553 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.163  1019  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.163  1019  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.173  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 15:01:02.183  4588  4588 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:02.183  4588  4588 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:02.193   278   970 D EnterpriseController: uids 10057
03-15 15:01:02.193   278   970 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 15:01:02.193   278   970 D Netd    : getNetworkForDns: using netid 502 for uid 10057
,03-15 15:01:02.203  1019  1556 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-15 15:01:02.203  1019  1556 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-15 15:01:02.203  1019  1019 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-15 15:01:02.213  4504  4527 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at com.google.android.gms.auth.b.c(Unknown Source)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
03-15 15:01:02.213  4504  4527 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,03-15 15:01:02.213  4504  4529 E VelvetNetworkClient: Failed to get auth token
,03-15 15:01:02.213  1180  1180 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-15 15:01:02.223  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:02.223  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:02.223  1180  1180 D PanelView: There is/are notification(s) 
,03-15 15:01:02.223  1180  1180 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 15:01:02.223  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:02.223  1180  1180 D PanelView: There is/are notification(s) 
,03-15 15:01:02.223  1180  1180 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 15:01:02.223  4588  4588 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-15 15:01:02.233  1019  1501 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.233  1019  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.233  1019  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.233  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3682/cgroup.procs: No such file or directory
,03-15 15:01:02.233  1019  1043 W libprocessgroup: failed to open /acct/uid_10022/pid_3786/cgroup.procs: No such file or directory
03-15 15:01:02.233  1019  1501 I ActivityManager: Killing 3808:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-15 15:01:02.243  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.243  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.243  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.243  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.243  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.243  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.243  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.243  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.243  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.253  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.253  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.253  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.253  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.253  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.253  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.253  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.263  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.263  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.263  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.263  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.263  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 15:01:02.263  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.263  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.263  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.273  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.273  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.273  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.273  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.273  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.273  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.273  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.273  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.273  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.273  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.273  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.273  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.283  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.283  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.283  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.283  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.283  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.283  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:02.283  1019  1019 W ActivityManager: userId = 0, bbcId = -10000,
03-15 15:01:02.283  1019  1019 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.283  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.293  1019  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-15 15:01:02.293  1180  1180 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
03-15 15:01:02.293  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.293  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3808/cgroup.procs: No such file or directory
03-15 15:01:02.293  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.293  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.293  1019  1556 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-15 15:01:02.293  1019  1556 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-15 15:01:02.293  1019  1556 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
03-15 15:01:02.293  1019  1556 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-15 15:01:02.293  1019  1556 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.293  1019  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.293  1019  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.293  1731  4610 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-15 15:01:02.303  1019  1377 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.303  1019  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.303  1019  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.303  1731  1731 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 15:01:02.303  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.303  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.303  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.313  1019  1501 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.313  1019  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.313  1019  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.313  1986  1986 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-15 15:01:02.313  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-15 15:01:02.313  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.313  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.313  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.323  1019  1143 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.323  1019  1143 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.323  1019  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.323  1019  1791 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.323  1019  1791 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.323  1019  1791 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.333  1019  1791 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.333  1019  1791 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.333  1019  1791 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.343  1019  1791 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.343  1019  1791 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.343  1019  1791 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.343  1019  1377 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
03-15 15:01:02.343  1019  1377 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.343  1019  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.343  1019  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:01:02.353  1019  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:02.353  1019  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:02.353  1019  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:02.353  1019  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:02.363  4612  4612 E Zygote  : MountEmulatedStorage()
03-15 15:01:02.363  4612  4612 E Zygote  : v2
,03-15 15:01:02.363  4612  4612 I libpersona: KNOX_SDCARD checking this for 10012
03-15 15:01:02.363  4612  4612 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:02.363  4612  4612 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-15 15:01:02.373  4612  4612 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 15:01:02.373  1019  1377 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4612 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-15 15:01:02.373  1019  1041 D SensorService: [SO] currT = 49241547000, prevT = 48761074000, diff = 480473000, [0.172 0.402 10.228],
03-15 15:01:02.373  1019  1041 D SensorService: [SO] 0.172 0.402 10.228
03-15 15:01:02.373  1019  1041 D SensorService: [SO] [100 -> 255]
03-15 15:01:02.373  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.373  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.373  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.373  4612  4612 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 15:01:02.383  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.383  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.383  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.383  1019  1143 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:02.383  1019  1044 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
03-15 15:01:02.383  1019  1143 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.383  1019  1143 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.383  1019  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.383  1019  1044 W ActivityManager: mDVFSHelper.release()
,03-15 15:01:02.383  1019  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-15 15:01:02.393  1019  1282 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.393  1019  1282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.393  1019  1791 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
03-15 15:01:02.393  1019  1282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.393  1019  1791 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.393  1019  1791 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.393  1019  1791 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.393  1986  4622 D LocationInitializer: Restart initialization of location
,03-15 15:01:02.393  1019  1282 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.393  1019  1282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.393  1019  1282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.403  1019  1309 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-15 15:01:02.403  1019  1309 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.403  1019  1309 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.403  1019  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.413  4612  4612 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:02.413  4612  4612 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:02.423  1019  1791 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-15 15:01:02.423  1019  1791 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.423  1019  1791 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.423  1019  1791 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-15 15:01:02.423  1019  1032 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-15 15:01:02.423  1019  1032 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-15 15:01:02.423  1019  1032 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
03-15 15:01:02.423  1019  1032 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-15 15:01:02.433  1019  1790 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:02.433  1019  1790 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.433  1019  1790 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.433  4612  4612 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 15:01:02.433  1019  1790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-15 15:01:02.433  4612  4612 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-15 15:01:02.433  1731  1731 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 15:01:02.443  1731  4629 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-15 15:01:02.443  1986  1986 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-15 15:01:02.443  1019  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-15 15:01:02.443  1019  1377 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.443  1019  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.443  1019  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.463  4612  4612 I MultiDex: VM with version 2.1.0 has multidex support
03-15 15:01:02.463  4612  4612 I MultiDex: install
03-15 15:01:02.463  4612  4612 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-15 15:01:02.483  4612  4612 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
03-15 15:01:02.483  1019  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:02.493  1019  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.493  1019  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.493  1019  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.503  1019  1553 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-15 15:01:02.503  1019  1553 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.503  1019  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.503  1019  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.503  1986  4631 D LocationInitializer: Restart initialization of location
,03-15 15:01:02.503  1019  1309 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-15 15:01:02.503  1019  1309 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.503  1019  1309 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:02.503  1019  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.513   291   291 E SMD     : DCD OFF
,03-15 15:01:02.533  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3fc27064 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t235} time:49409
,03-15 15:01:02.543  4612  4612 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-15 15:01:02.543  4612  4612 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fd515b9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 15:01:02.543  4612  4612 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 15:01:02.553   257   458 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-15 15:01:02.553   257  1059 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
03-15 15:01:02.553  1019  1044 I ActivityManager: Killing 3827:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-15 15:01:02.573  1019  1556 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-15 15:01:02.573  1019  1556 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.573  1019  1556 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.573  1019  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 15:01:02.573  2579  2579 I Hs20UtilService: Starting #4
,03-15 15:01:02.573  2579  2594 I Hs20UtilService: Message received 5007
,03-15 15:01:02.583  1334  1334 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 15:01:02.583  1334  1334 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-15 15:01:02.583  1334  1334 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-15 15:01:02.583  4612  4612 D WearableService: callingUid 10012, callindPid: 4612
,03-15 15:01:02.583  1334  1334 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-15 15:01:02.583  1334  1334 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-15 15:01:02.583  1334  1334 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 15:01:02.593  1019  1501 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-15 15:01:02.603  1019  1501 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:02.603  1019  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.603  1019  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 15:01:02.603  2579  2579 I Hs20UtilService: Starting #5
,03-15 15:01:02.603  1334  1334 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 15:01:02.613  1334  1334 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 15:01:02.613  2579  2594 I Hs20UtilService: Message received 5007
,03-15 15:01:02.623  4305  4305 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@954754e that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 15:01:02.623  4305  4305 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@954754e that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 15:01:02.623  4305  4305 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@3d07e66f that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 15:01:02.623  4305  4305 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@3d07e66f that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-15 15:01:02.623  4305  4305 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 15:01:02.623  1019  1556 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-15 15:01:02.623  1019  1556 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.623  1019  1556 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:02.633  1019  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 15:01:02.633  2579  2579 I Hs20UtilService: Starting #6
,03-15 15:01:02.633  2579  2594 I Hs20UtilService: Message received 5007
,03-15 15:01:02.633  1334  1334 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 15:01:02.633  1334  1334 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-15 15:01:02.643  1334  1334 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-15 15:01:02.643  1683  4611 E MDM     : [182] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-15 15:01:02.643  1334  1334 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-15 15:01:02.643  1334  1334 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-15 15:01:02.643  1334  1334 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 15:01:02.653  1019  1282 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
03-15 15:01:02.653  1683  4634 E MDM     : [183] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-15 15:01:02.653  1019  1282 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.653  1019  1282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 15:01:02.653  1019  1282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 15:01:02.653  2579  2579 I Hs20UtilService: Starting #7
,03-15 15:01:02.663  1334  1334 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 15:01:02.663  2579  2594 I Hs20UtilService: Message received 5007
,03-15 15:01:02.663  1334  1334 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 15:01:02.663  1019  1487 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,03-15 15:01:02.673  1019  1487 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
03-15 15:01:02.673  1019  1487 D SecContentProvider2: mCursor = null
,03-15 15:01:02.673  1019  1554 I ActivityManager: Killing 3728:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,03-15 15:01:02.673  1019  1143 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-15 15:01:02.673  1019  1143 D SecContentProvider2: mCursor = null
,03-15 15:01:02.683  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3827/cgroup.procs: No such file or directory
,03-15 15:01:02.683  1019  1282 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
03-15 15:01:02.683  1019  1282 D SecContentProvider2: mCursor = null
,03-15 15:01:02.683  1019  1553 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,03-15 15:01:02.683  1019  1553 D SecContentProvider2: mCursor = null
,03-15 15:01:02.683  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-15 15:01:02.693  1019  1377 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-15 15:01:02.693  1019  1377 D SecContentProvider2: mCursor = null
,03-15 15:01:02.693  1019  1031 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,03-15 15:01:02.693  1019  1031 D SecContentProvider2: mCursor = null
,03-15 15:01:02.693  1019  1098 V AlarmManager: waitForAlarm result :4
,03-15 15:01:02.703  3468  3468 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-15 15:01:02.703  3468  3468 I PCWCLIENTTRACE_PushUtil: sales region : global
03-15 15:01:02.703  3468  3468 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,03-15 15:01:02.703  3468  3468 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-15 15:01:02.703  1019  1282 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
03-15 15:01:02.703  1019  1282 I splitIntent: base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
03-15 15:01:02.703  1019  1282 I splitIntent: other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
03-15 15:01:02.703  1019  1282 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,03-15 15:01:02.713  1019  1282 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:02.713  1019  1282 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:02.713  1019  1282 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:02.713  1019  1282 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:02.723  4638  4638 E Zygote  : MountEmulatedStorage()
,03-15 15:01:02.723  4638  4638 E Zygote  : v2
,03-15 15:01:02.723  4638  4638 I libpersona: KNOX_SDCARD checking this for 10111
03-15 15:01:02.723  4638  4638 I libpersona: KNOX_SDCARD not a persona
03-15 15:01:02.723   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
03-15 15:01:02.723  4638  4638 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 15:01:02.723  1019  1282 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4638 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:01:02.723  4638  4638 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:02.733  4638  4638 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 15:01:02.733  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3728/cgroup.procs: No such file or directory
,03-15 15:01:02.733  1019  1553 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
03-15 15:01:02.733  1019  1051 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
03-15 15:01:02.733  1019  1051 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-15 15:01:02.733  1019  1051 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-15 15:01:02.743  1180  1180 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 15:01:02.743  1019  1327 E Watchdog: !@Sync 1
,03-15 15:01:02.753  4638  4638 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:02.753  4638  4638 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:02.753  1019  1163 D lights  : lcd : 32 +
03-15 15:01:02.753  1019  1051 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
03-15 15:01:02.753  1019  1051 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 15:01:02.763  1019  1142 D SettingsProvider: name = audio_safe_volume_state
,03-15 15:01:02.763  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,03-15 15:01:02.773  1019  1163 D lights  : lcd : 32 -
,03-15 15:01:02.773  1019  1051 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
03-15 15:01:02.773  1019  1051 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 15:01:02.973  4638  4638 I MusicStore: Database version: 120
,03-15 15:01:03.053  1019  1282 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-15 15:01:03.063  1019  1282 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:03.063  1019  1282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:03.063  1019  1282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 15:01:03.093   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 15:01:03.093   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:03.093  4638  4638 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-15 15:01:03.123  1019  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,03-15 15:01:03.123  1019  1501 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:03.123  1019  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:03.123  1019  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 15:01:03.153  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{29812750 u0 com.samsung.android.providers.context/.ContextService}
,03-15 15:01:03.183   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 15:01:03.183   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:03.183  4638  4638 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-15 15:01:03.193   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 15:01:03.193   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:03.193  4638  4638 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files,
,03-15 15:01:03.243  4638  4638 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-15 15:01:03.243  4638  4638 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 15:01:03.283  4638  4638 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-15 15:01:03.353  4638  4638 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-15 15:01:03.353  4638  4638 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1256e8a4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 15:01:03.353  4638  4638 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-15 15:01:03.353  4638  4638 D AndroidMusic: GMSCore installation verified
,03-15 15:01:03.353  4638  4638 I ConfigStore: Config Database version: 1
,03-15 15:01:03.413  1019  1553 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,03-15 15:01:03.413  1019  1553 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:03.423  1019  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:03.423  1019  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 15:01:03.433  1019  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,03-15 15:01:03.433  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:03.433  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:03.433  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 15:01:03.453  1019  1553 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 15:01:03.453  1019  1377 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 15:01:03.463  1019  1501 I AudioService: getStreamVolume 3 index 0
,03-15 15:01:03.463  4638  4638 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-15 15:01:03.463  4638  4638 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-15 15:01:03.473  4638  4638 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-15 15:01:03.493  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-15 15:01:03.493  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:03.493  1019  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:03.493  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 15:01:03.493  1019  1556 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,03-15 15:01:03.503  1019  1556 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:03.503  1019  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:03.503  1019  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 15:01:03.503  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,03-15 15:01:03.503  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:03.503  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:03.503  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 15:01:03.513  1019  1143 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 15:01:03.523  4638  4638 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-15 15:01:03.523  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.523  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.523  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.523  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.543  4665  4665 E Zygote  : MountEmulatedStorage(),
03-15 15:01:03.543  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4665 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:01:03.543  4665  4665 E Zygote  : v2
03-15 15:01:03.543  4665  4665 I libpersona: KNOX_SDCARD checking this for 10002,
03-15 15:01:03.543  4665  4665 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 15:01:03.543  4665  4665 I libpersona: KNOX_SDCARD not a persona,
,03-15 15:01:03.543  4665  4665 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:03.553  4665  4665 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:03.553  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{3505e8ac u0 com.android.settings/.wifi.WifiCredService}
,03-15 15:01:03.563  4665  4665 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:03.573  4665  4665 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:03.573  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:03.573  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:03.573  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:03.573  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-15 15:01:03.583  4638  4638 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,03-15 15:01:03.583  1019  1556 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-15 15:01:03.583  1019  1556 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:03.583  1019  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:03.583  1019  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-15 15:01:03.593  4638  4638 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-15 15:01:03.593  1019  1282 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-15 15:01:03.593  1019  1282 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:03.593  1019  1282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:03.593  1019  1282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 15:01:03.613  1019  1553 I ActivityManager: Killing 3880:com.android.email/u0a145 (adj 15): empty #31
,03-15 15:01:03.643  1019  1487 I ActivityManager: Killing 3901:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-15 15:01:03.653  1019  1282 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.653  1019  1282 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.653  1019  1282 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.653  1019  1282 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.663  4684  4684 E Zygote  : MountEmulatedStorage(),
03-15 15:01:03.663  4684  4684 E Zygote  : v2
03-15 15:01:03.663  4684  4684 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:01:03.663  4684  4684 I libpersona: KNOX_SDCARD not a persona,
03-15 15:01:03.663  4684  4684 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:01:03.663  1019  1282 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4684 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-15 15:01:03.663  4684  4684 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-15 15:01:03.663  4684  4684 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-15 15:01:03.683  4684  4684 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:03.683  4684  4684 D ActivityThread: Added TimaKeyStore provider,
,03-15 15:01:03.713  4684  4684 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-15 15:01:03.763  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,03-15 15:01:03.823  4684  4684 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-15 15:01:03.833  4684  4684 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,03-15 15:01:03.833  4684  4684 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-15 15:01:03.833  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3901/cgroup.procs: No such file or directory
,03-15 15:01:03.833  4684  4684 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-15 15:01:03.833  4684  4684 I DIAGMON_AGENT: ./extraInfo: "NG700"
03-15 15:01:03.833  1019  1043 W libprocessgroup: failed to open /acct/uid_10145/pid_3880/cgroup.procs: No such file or directory
,03-15 15:01:03.833  4684  4684 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-15 15:01:03.913  4195  4203 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 15:01:03.923  4195  4203 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 15:01:03.923  4195  4203 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-15 15:01:03.923  4195  4204 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 15:01:03.923  4195  4204 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 15:01:03.923  4195  4204 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-15 15:01:03.933  1019  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.933  1019  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.933  1019  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.933  1019  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.943  4701  4701 E Zygote  : MountEmulatedStorage(),
03-15 15:01:03.943  4701  4701 I libpersona: KNOX_SDCARD checking this for 10009
,03-15 15:01:03.943  4701  4701 E Zygote  : v2
03-15 15:01:03.943  4701  4701 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:03.943  4701  4701 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:01:03.953  4701  4701 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:03.953  1019  1556 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4701 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:01:03.953  4701  4701 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-15 15:01:03.973  4701  4701 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:03.973  4701  4701 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:03.973   306   306 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 750us total 26.570ms
,03-15 15:01:04.003   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 759us total 20.710ms
,03-15 15:01:04.023   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 601us total 22.143ms
,03-15 15:01:04.043  1019  1309 I ActivityManager: Killing 3922:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,03-15 15:01:04.053  4701  4701 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-15 15:01:04.063  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 15:01:04.063  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 15:01:04.063  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:01:04.063  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:01:04.063  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:01:04.063  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:01:04.073  4701  4701 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-15 15:01:04.073  1019  1553 I ActivityManager: Killing 3980:com.sec.modem.settings/1000 (adj 15): empty #31
,03-15 15:01:04.083  3746  3746 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 15 15:01:04 GMT+01:00 2016
,03-15 15:01:04.083  1019  1143 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-15 15:01:04.083  1019  1143 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:04.083  1019  1143 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.083  1019  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-15 15:01:04.093  3746  3746 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-15 15:01:04.103  3746  3746 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-15 15:01:04.103  3746  3746 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-15 15:01:04.103  3746  3746 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-15 15:01:04.103  4195  4195 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,03-15 15:01:04.113  4195  4719 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 15:01:04.113  4195  4719 I DBG_POLICYDM: [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,03-15 15:01:04.113  4259  4259 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,03-15 15:01:04.113  4259  4259 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-15 15:01:04.113  4259  4259 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-15 15:01:04.113  3746  4718 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
03-15 15:01:04.113  4195  4719 E DBG_POLICYDM: [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,03-15 15:01:04.113  4259  4259 I SA      : [SLFUCHKMGR] constructor called
,03-15 15:01:04.113  3746  4718 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-15 15:01:04.123  4259  4259 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-15 15:01:04.123  4259  4259 I SA      : [OR] == isSIMCardReady false ==
,03-15 15:01:04.123  4259  4259 I SA      : [SCU] == networkStateCheck == true
,03-15 15:01:04.123  4259  4259 I SA      : [DM] getCountryCodeFromCSC : PL
,03-15 15:01:04.123  4195  4719 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-15 15:01:04.123  4259  4259 I SA      : isChinaCountryCode : false
,03-15 15:01:04.123  4259  4259 I SA      : [SCU] is ChinestModel Data Restricted   : false
,03-15 15:01:04.123  4259  4259 I SA      : [OR] == networkStateCheck true ==
,03-15 15:01:04.123  3746  4718 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
03-15 15:01:04.123  3746  4718 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,03-15 15:01:04.133  4259  4259 I SA      : [OR] GetMyCountryZoneTask
,03-15 15:01:04.133  4259  4259 I SA      : [OR] onReceive END
,03-15 15:01:04.133  3746  4718 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,03-15 15:01:04.133  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
03-15 15:01:04.133  4259  4721 I SA      : [SRS] prepareGetMyCountryZone
,03-15 15:01:04.143  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,03-15 15:01:04.143  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.143  3746  4718 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,03-15 15:01:04.143  1019  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.143  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-15 15:01:04.143  3746  4718 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,03-15 15:01:04.143  4195  4719 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-15 15:01:04.143  4259  4721 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-15 15:01:04.143  4259  4721 I SA      : [SSP] query invoked
03-15 15:01:04.143  4195  4719 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-15 15:01:04.153  4195  4719 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-15 15:01:04.153  4195  4719 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-15 15:01:04.153  3746  3746 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-15 15:01:04.153  4195  4719 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-15 15:01:04.153  4195  4719 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-15 15:01:04.153  4195  4719 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-15 15:01:04.153  1608  1608 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-15 15:01:04.153  4195  4719 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-15 15:01:04.153  4195  4719 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-15 15:01:04.163  1019  1060 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,03-15 15:01:04.163  4195  4719 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,03-15 15:01:04.163  1019  1043 W libprocessgroup: failed to open /acct/uid_10152/pid_3922/cgroup.procs: No such file or directory
,03-15 15:01:04.163  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3980/cgroup.procs: No such file or directory
,03-15 15:01:04.173  1292  1301 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,03-15 15:01:04.173  4195  4719 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 15:01:04.193  4195  4719 I DBG_POLICYDM: [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,03-15 15:01:04.193  1019  1106 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-15 15:01:04.193  3403  3403 I PageBuddyNotiSvc: mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,03-15 15:01:04.203  1608  1608 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-15 15:01:04.203  1608  1608 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,03-15 15:01:04.203  1608  1608 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-15 15:01:04.203  1608  1608 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-15 15:01:04.223  1448  1448 D RegisteredComponentCache: Collect Tech packages for Knox
,03-15 15:01:04.223  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:04.233  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:04.243  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.243  1448  1448 D RegisteredServicesCache: empty dynamic service
,03-15 15:01:04.253  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.253  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.263  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.343  1019  1559 I art     : Explicit concurrent mark sweep GC freed 41484(2MB) AllocSpace objects, 4(84KB) LOS objects, 33% free, 30MB/46MB, paused 2.912ms total 184.143ms
,03-15 15:01:04.343  1019  1031 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-15 15:01:04.343  1490  1490 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-15 15:01:04.353  1019  1487 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-15 15:01:04.353  1019  1487 D SecContentProvider2: mCursor = null
03-15 15:01:04.353  1019  1031 D SecContentProvider2: mCursor = null
,03-15 15:01:04.353  1490  1490 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-15 15:01:04.353  1608  1608 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-15 15:01:04.353  1608  1608 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-15 15:01:04.353  1019  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:04.353  1019  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:04.353  1019  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:04.353  1019  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:04.363  4259  4721 I SA      : [TPMU] GetMccFromDB : null
03-15 15:01:04.363  1019  1098 V AlarmManager: waitForAlarm result :8
03-15 15:01:04.363  4259  4721 I SA      : [SCU] getMccFromPreferece mcc = 260
03-15 15:01:04.363  4259  4721 I SA      : [TPM] isNoProxy(default) : true
,03-15 15:01:04.373  4725  4725 E Zygote  : MountEmulatedStorage()
03-15 15:01:04.373  4725  4725 E Zygote  : v2
03-15 15:01:04.373  4725  4725 I libpersona: KNOX_SDCARD checking this for 10125
03-15 15:01:04.373  4725  4725 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:04.373  4725  4725 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:01:04.373  4725  4725 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 15:01:04.373  1019  1143 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4725 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-15 15:01:04.373  4725  4725 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:01:04.373  1019  1098 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:04.393  4259  4721 E File    : fail readDirectory() errno=2
,03-15 15:01:04.393  4725  4725 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:04.393  4725  4725 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:04.413  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-15 15:01:04.413  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.423  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.423  4725  4725 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 15:01:04.423  4725  4725 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-15 15:01:04.423  4725  4725 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-15 15:01:04.423  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.433  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 15:01:04.433  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:01:04.433  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 15:01:04.433  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.453  4725  4725 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-15 15:01:04.453  4725  4725 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,03-15 15:01:04.463  4725  4725 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-15 15:01:04.463  1019  1790 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:04.463  1019  1790 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:04.463  1019  1790 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:04.463  1019  1790 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:04.483  4740  4740 E Zygote  : MountEmulatedStorage()
,03-15 15:01:04.483  4740  4740 E Zygote  : v2
,03-15 15:01:04.483  4740  4740 I libpersona: KNOX_SDCARD checking this for 10145
03-15 15:01:04.483  4740  4740 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:04.483  4740  4740 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:01:04.483  4740  4740 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:04.483  4740  4740 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:04.483  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.493  1019  1790 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=4740 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
03-15 15:01:04.493  1019  1790 I ActivityManager: Killing 3938:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-15 15:01:04.493  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.513  4740  4740 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:04.513  4740  4740 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:04.513  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 15:01:04.513  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-15 15:01:04.513  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.523  1019  1019 W IntentResolver: resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,03-15 15:01:04.523  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 15:01:04.523  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-15 15:01:04.523  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-15 15:01:04.523  1019  1019 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 15:01:04.523  4740  4740 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-15 15:01:04.533  4740  4740 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:01:04.533  4740  4740 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-15 15:01:04.533  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 15:01:04.533  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-15 15:01:04.533  4740  4740 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:01:04.533  4740  4740 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 15:01:04.533  1019  1019 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 15:01:04.533  1019  1019 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,03-15 15:01:04.533  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.553  1019  1019 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 15:01:04.553  1019  1019 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2b5efd10
,03-15 15:01:04.553  1019  1043 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-15 15:01:04.553  1019  1043 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-15 15:01:04.563  1019  1043 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-15 15:01:04.563  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3938/cgroup.procs: No such file or directory
,03-15 15:01:04.593  1019  1143 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-15 15:01:04.593  1019  1143 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:04.593  1019  1143 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:04.593  1019  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-15 15:01:04.603  1019  1559 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:04.613  4398  4433 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-15 15:01:04.613  1019  1043 D LocationProviderProxy: applying state to connected service
,03-15 15:01:04.613  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:04.623  1019  1791 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:04.623  1019  1143 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:04.663  1019  1377 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:04.663  1019  1790 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:04.673  1623  1641 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-15 15:01:04.673  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:04.673  1019  1790 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:04.683  3848  3848 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 15:01:04.683  3848  3848 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 15:01:04.683  3848  3848 D SecurityLogAgent: StateMachine : Current State = 1
,03-15 15:01:04.683  3848  3848 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-15 15:01:04.693  1019  1791 I ActivityManager: Killing 4003:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-15 15:01:04.703  1490  1490 D Launcher.Model: reloadBadges entered.
,03-15 15:01:04.703  1623  1638 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-15 15:01:04.703  1623  1638 D BadgeProvider: sendNotify, [notify] : null
03-15 15:01:04.703  1623  1638 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-15 15:01:04.703  1623  1638 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-15 15:01:04.703  1623  1638 D BadgeProvider: update, [UpdateCount] : 1
,03-15 15:01:04.723  1019  1143 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-15 15:01:04.733  1019  1143 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:04.733  1019  1143 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 15:01:04.733  1019  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:04.763  1986  4770 I iu.SyncManager: SYNC; picasa accounts
,03-15 15:01:04.773  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 13 sec
,03-15 15:01:04.793  1986  1986 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-15 15:01:04.793  1986  1986 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-15 15:01:04.803  1986  4770 I iu.UploadsManager: num queued entries: 0
,03-15 15:01:04.803  1986  4770 I iu.UploadsManager: num updated entries: 0
,03-15 15:01:04.803  1986  4770 I iu.SyncManager: NEXT; no task
,03-15 15:01:04.813  1019  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,03-15 15:01:04.813  1019  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:04.813  1019  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 15:01:04.813  1019  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:04.813  1019  1043 W libprocessgroup: failed to open /acct/uid_1101/pid_4003/cgroup.procs: No such file or directory
,03-15 15:01:04.823  1986  1986 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-15 15:01:04.823  1986  1986 I Kids    : [GCoreUtils] Current gmscore version, 7899436 is smaller than the required version 8400000
,03-15 15:01:04.833  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,03-15 15:01:04.833  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.833  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:04.833  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-15 15:01:04.843  1019  1790 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,03-15 15:01:04.843  1019  1790 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.843  1019  1790 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:04.843  1019  1790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-15 15:01:04.843  4213  4213 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,03-15 15:01:04.843  4213  4213 E SPPClientService: [SystemStateMoniter] Current Time : 51719
,03-15 15:01:04.853  4213  4213 E SPPClientService: [SystemStateMoniter] No Connect : false
,03-15 15:01:04.863  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:04.863  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:04.863  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:04.863  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:04.873  4096  4773 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager,
03-15 15:01:04.873  4096  4773 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-15 15:01:04.873  4096  4773 I System.out: (HTTPLog)-Static: isShipBuild true,
03-15 15:01:04.873  4096  4773 I System.out: (HTTPLog)-Thread-631-668367499: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-15 15:01:04.873  4096  4773 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
03-15 15:01:04.873   278   970 D EnterpriseController: uids 10104
03-15 15:01:04.873   278   970 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 15:01:04.873   278   970 D Netd    : getNetworkForDns: using netid 502 for uid 10104
,03-15 15:01:04.873  4775  4775 E Zygote  : MountEmulatedStorage(),
03-15 15:01:04.873  4775  4775 I libpersona: KNOX_SDCARD checking this for 10113
03-15 15:01:04.873  4775  4775 E Zygote  : v2,
,03-15 15:01:04.873  4775  4775 I libpersona: KNOX_SDCARD not a persona
03-15 15:01:04.883  4775  4775 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:01:04.883  1019  1559 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4775 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 15:01:04.883  4775  4775 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 15:01:04.883  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-15 15:01:04.883  4775  4775 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 15:01:04.883  1019  1032 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-15 15:01:04.883  1019  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-15 15:01:04.893  1019  1553 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0,
,03-15 15:01:04.903  4775  4775 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:04.903  4775  4775 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:04.933  4096  4773 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-15 15:01:05.053  4096  4773 I Babel   : connection state changed from UNKNOWN to CONNECTED,
03-15 15:01:05.063  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
03-15 15:01:05.063  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 15:01:05.063  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:01:05.063  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:01:05.063  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:01:05.063  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:01:05.163  4259  4721 I SA      : [RC New] Execute method=[GET] start
,03-15 15:01:05.203  4259  4721 I SA      : [RC New] Security=[true]
,03-15 15:01:05.203  4259  4721 I System.out: Thread-660(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-15 15:01:05.203  4259  4721 I System.out: Thread-660(ApacheHTTPLog):isSBSettingEnabled false
03-15 15:01:05.203  4259  4721 I System.out: Thread-660(ApacheHTTPLog):isShipBuild true
03-15 15:01:05.203  4259  4721 I System.out: Thread-660(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-15 15:01:05.203  4259  4721 I System.out: Thread-660(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-15 15:01:05.203   278   970 D EnterpriseController: uids 10041
03-15 15:01:05.203   278   970 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 15:01:05.203   278   970 D Netd    : getNetworkForDns: using netid 502 for uid 10041
,03-15 15:01:05.293   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-15 15:01:05.293   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:05.293  4775  4797 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-15 15:01:05.303   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-15 15:01:05.303   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:05.303  4775  4797 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-15 15:01:05.303  4775  4775 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-15 15:01:05.303  4775  4775 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-15 15:01:05.303  4775  4775 I GAv4    :   adb logcat -s GAv4
,03-15 15:01:05.323   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-15 15:01:05.323   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:05.323  4775  4798 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-15 15:01:05.323   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-15 15:01:05.323   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:05.333  4775  4798 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-15 15:01:05.333  4775  4775 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-15 15:01:05.343  4775  4775 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-15 15:01:05.353  4775  4800 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-15 15:01:05.513   291   291 E SMD     : DCD OFF,
,03-15 15:01:05.553  1019  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:05.553  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:05.553  1019  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:05.553  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-15 15:01:05.583  4775  4775 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,03-15 15:01:05.603  4775  4775 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2469-2471)
03-15 15:01:05.603  4775  4775 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 15:01:05.643  4775  4775 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {de5cc0a}
,03-15 15:01:05.643  4775  4775 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 15:01:05.643  4775  4775 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-15 15:01:05.653  4775  4775 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-15 15:01:05.653  4775  4775 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:01:05.653  4775  4775 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-15 15:01:05.673  4775  4775 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-15 15:01:05.673  4775  4775 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-15 15:01:05.673  4775  4775 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-15 15:01:05.683  4775  4775 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 15:01:05.683  4775  4775 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 15:01:05.683  4775  4775 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 15:01:05.683  4775  4775 I Adreno-EGL: Local Branch: 
03-15 15:01:05.683  4775  4775 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 15:01:05.683  4775  4775 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 15:01:05.683  4775  4775 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 15:01:05.743  4775  4775 I NSApplication: Starting up...
,03-15 15:01:05.743  4775  4828 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-15 15:01:05.753  1019  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:05.753  1019  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:05.753  1019  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:05.753  1019  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:05.763  4833  4833 E Zygote  : MountEmulatedStorage()
,03-15 15:01:05.763  4833  4833 E Zygote  : v2
03-15 15:01:05.763  4833  4833 I libpersona: KNOX_SDCARD checking this for 10081
03-15 15:01:05.763  4833  4833 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:05.763  1019  1377 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4833 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:01:05.773  4833  4833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:01:05.773  1019  1377 I ActivityManager: Killing 4054:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
03-15 15:01:05.773  4833  4833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:05.773  4833  4833 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-15 15:01:05.773  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 14 sec
,03-15 15:01:05.793  4833  4833 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:05.793  4833  4833 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:05.903  4259  4721 I SA      : [RC New] [v2liruge] api execute + 708
,03-15 15:01:05.903  4259  4721 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,03-15 15:01:05.913  4259  4721 I System.out: AsyncTask #1 calls detatch()
,03-15 15:01:05.923  1019  1043 W libprocessgroup: failed to open /acct/uid_10157/pid_4054/cgroup.procs: No such file or directory
,03-15 15:01:05.933  4259  4721 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,03-15 15:01:05.953  4259  4721 I SA      : [OCP] update openData : PL
,03-15 15:01:05.953  4259  4721 I SA      : [TPMU] getNetworkMcc : 
,03-15 15:01:05.953  4259  4721 I SA      : [SCU] saveMccToPreferece Start
03-15 15:01:05.953  4259  4721 I SA      : [SCU] RegionMCC : 260
03-15 15:01:05.953  4259  4721 I SA      : [SSP] query invoked
,03-15 15:01:05.953  4259  4721 I SA      : [TPMU] GetMccFromDB : null
,03-15 15:01:05.953  4259  4721 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-15 15:01:05.963  4259  4721 I SA      : [SCU] saveMccToPreferece End
,03-15 15:01:05.963  4259  4721 I SA      : [RC New] executeRequest [v2liruge] end. 794
03-15 15:01:05.963  4259  4721 I SA      : [RC New] Execute end
,03-15 15:01:05.963  4259  4259 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-15 15:01:05.963  4259  4259 I SA      : [OR] GetMyCountryZoneTask Success
,03-15 15:01:06.013  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:06.013  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:06.013  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:06.013  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:06.033  4850  4850 E Zygote  : MountEmulatedStorage(),
03-15 15:01:06.033  4850  4850 I libpersona: KNOX_SDCARD checking this for 10120,
03-15 15:01:06.033  4850  4850 E Zygote  : v2
03-15 15:01:06.033  4850  4850 I libpersona: KNOX_SDCARD not a persona,
03-15 15:01:06.033  4850  4850 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 15:01:06.033  4850  4850 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-15 15:01:06.033  4850  4850 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 15:01:06.033  1019  1501 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4850 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-15 15:01:06.043  1019  1501 I ActivityManager: Killing 3957:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-15 15:01:06.053  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{27b5f9e8 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,03-15 15:01:06.063  4850  4850 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:06.063  4850  4850 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:06.073  4850  4850 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 15:01:06.093  4445  4501 I System.out: Thread-685(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-15 15:01:06.093  4445  4501 I System.out: Thread-685(ApacheHTTPLog):isSBSettingEnabled false
03-15 15:01:06.093  4445  4501 I System.out: Thread-685(ApacheHTTPLog):isShipBuild true
03-15 15:01:06.093  4445  4501 I System.out: Thread-685(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-15 15:01:06.093  4445  4501 I System.out: Thread-685(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-15 15:01:06.093   278   970 D EnterpriseController: uids 10092
03-15 15:01:06.093   278   970 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 15:01:06.093   278   970 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-15 15:01:06.153  1019  1043 W libprocessgroup: failed to open /acct/uid_10031/pid_3957/cgroup.procs: No such file or directory
,03-15 15:01:06.213  1019  1556 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1019) eventTime = 53086,
,03-15 15:01:06.213  1019  1556 D PowerManagerService: [s] UserActivityState : 2 -> 1
,03-15 15:01:06.213  1019  1556 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019 (0x0)
03-15 15:01:06.213  1019  1556 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1019, ws=WorkSource{10054}) (elapsedTime=3482)
,03-15 15:01:06.523   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-15 15:01:06.643  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:06.643  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:06.643  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:06.643  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:06.653  4874  4874 E Zygote  : MountEmulatedStorage(),
03-15 15:01:06.653  4874  4874 E Zygote  : v2
,03-15 15:01:06.653  4874  4874 I libpersona: KNOX_SDCARD checking this for 10010
03-15 15:01:06.653  4874  4874 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:06.663  1019  1791 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4874 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-15 15:01:06.663  1019  1791 I ActivityManager: Killing 1577:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-15 15:01:06.663  4874  4874 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-15 15:01:06.663  4874  4874 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:06.663  4874  4874 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-15 15:01:06.693  4874  4874 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:06.693  4874  4874 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:06.723  1019  1043 W libprocessgroup: failed to open /acct/uid_10004/pid_1577/cgroup.procs: No such file or directory
,03-15 15:01:06.753   257   458 I SurfaceFlinger: id=13 Removed Uoast (8/8)
,03-15 15:01:06.753   257  1109 I SurfaceFlinger: id=13 Removed Uoast (-2/8)
,03-15 15:01:06.783  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 15 sec
,03-15 15:01:06.883  4874  4874 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-15 15:01:06.933  4874  4874 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-15 15:01:06.933  1019  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:06.943  1019  1487 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-15 15:01:06.973  1019  2777 D SSRM:n  : SIOP:: AP = 410
,03-15 15:01:07.063  1019  2830 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 15:01:07.083  4445  4501 I System.out: Thread-685(ApacheHTTPLog):isSBSettingEnabled false
,03-15 15:01:07.083  4445  4501 I System.out: Thread-685(ApacheHTTPLog):isShipBuild true
03-15 15:01:07.083  4445  4501 I System.out: Thread-685(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-15 15:01:07.083  4445  4501 I System.out: Thread-685(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-15 15:01:07.093  1019  1553 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,03-15 15:01:07.093  1019  1553 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:07.093  1019  1553 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-15 15:01:07.093  1019  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-15 15:01:07.103  4874  4874 D hcjo    : AutoUpdateManager:IDLE:execute
,03-15 15:01:07.103  1019  1019 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
03-15 15:01:07.103  1019  1019 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-15 15:01:07.113  4874  4874 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-15 15:01:07.113  4874  4874 D InitializeManagerStateMachine: exit::IDLE
03-15 15:01:07.113  4874  4874 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-15 15:01:07.113  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.113  4874  4874 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
03-15 15:01:07.113  4874  4874 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-15 15:01:07.113  4874  4874 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-15 15:01:07.113  4874  4874 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-15 15:01:07.113  4874  4874 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-15 15:01:07.113  4874  4874 D InitializeManagerStateMachine: entry::SUCCESS
03-15 15:01:07.113  4874  4874 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-15 15:01:07.113  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.113  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.113  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.133  1019  1044 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4894 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:01:07.133  4894  4894 E Zygote  : MountEmulatedStorage()
03-15 15:01:07.133  4894  4894 I libpersona: KNOX_SDCARD checking this for 10062
03-15 15:01:07.133  4894  4894 E Zygote  : v2
03-15 15:01:07.133  4894  4894 I libpersona: KNOX_SDCARD not a persona
03-15 15:01:07.133  4894  4894 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 15:01:07.133  4874  4874 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,03-15 15:01:07.133  4894  4894 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:07.143  4894  4894 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:01:07.143  4701  4701 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-15 15:01:07.143  4874  4874 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
03-15 15:01:07.143  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
03-15 15:01:07.143  4874  4874 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,03-15 15:01:07.143  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:07.143  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:07.143  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-15 15:01:07.153  4874  4874 D InitializeManagerStateMachine: exit::SUCCESS
03-15 15:01:07.153  4874  4874 D InitializeManagerStateMachine: entry::IDLE
,03-15 15:01:07.153  4701  4701 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-15 15:01:07.153  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-15 15:01:07.153  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-15 15:01:07.163  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:07.163  3746  3746 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Mar 15 15:01:07 GMT+01:00 2016
,03-15 15:01:07.163  1019  1501 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-15 15:01:07.163  1019  1501 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:07.163  1019  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:07.163  1019  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-15 15:01:07.173  4894  4894 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:01:07.173  4894  4894 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:07.173  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings,
03-15 15:01:07.173  3746  3746 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-15 15:01:07.173  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-15 15:01:07.183  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-15 15:01:07.183  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:07.183  1019  1554 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:07.183  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
03-15 15:01:07.183  1292  1292 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
03-15 15:01:07.183  1292  1292 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-15 15:01:07.183  1292  1292 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-15 15:01:07.183  3746  3746 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
03-15 15:01:07.183  1292  1292 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-15 15:01:07.183  1292  1292 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-15 15:01:07.183  1292  1292 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-15 15:01:07.183  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-15 15:01:07.183  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-15 15:01:07.183  4259  4259 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,03-15 15:01:07.183  3746  3746 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-15 15:01:07.193  3848  3848 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 15:01:07.193  3848  3848 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 15:01:07.193  3848  3848 D SecurityLogAgent: StateMachine : Current State = 1
,03-15 15:01:07.193  3746  3746 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-15 15:01:07.193  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-15 15:01:07.193  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-15 15:01:07.193  1292  1292 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-15 15:01:07.193  3746  4913 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-15 15:01:07.203  1292  1292 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-15 15:01:07.203  1292  1292 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-15 15:01:07.213  3746  4913 I KLMS-2.5.183: : KLMSIntentService(): TIME_CHANGED
,03-15 15:01:07.213  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.213  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.213  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.213  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.223  3746  4913 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().START : Tue Mar 15 15:01:07 GMT+01:00 2016,
,03-15 15:01:07.233  3746  4913 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().END,
,03-15 15:01:07.233  4915  4915 E Zygote  : MountEmulatedStorage()
,03-15 15:01:07.233  4915  4915 E Zygote  : v2
,03-15 15:01:07.233  4915  4915 I libpersona: KNOX_SDCARD checking this for 10157
03-15 15:01:07.233  4915  4915 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:07.233  4915  4915 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 15:01:07.233  1019  1791 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4915 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,03-15 15:01:07.243  4894  4894 I ExternalOEMControlProvider: onCreate
,03-15 15:01:07.253  4915  4915 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:07.253  4915  4915 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:01:07.253  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.253  3746  3746 I KLMS-2.5.183: : KLMSIntentService(): onDestroy(),
03-15 15:01:07.253  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.253  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.253  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.253  1292  1292 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
03-15 15:01:07.253  1292  1292 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-15 15:01:07.273  1019  1791 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4928 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,03-15 15:01:07.273  4928  4928 E Zygote  : MountEmulatedStorage()
03-15 15:01:07.273  4928  4928 E Zygote  : v2
03-15 15:01:07.273  4928  4928 I libpersona: KNOX_SDCARD checking this for 10046
03-15 15:01:07.273  4928  4928 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:07.273  4928  4928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:01:07.283  4928  4928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:07.283  4928  4928 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-15 15:01:07.293  4915  4915 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:07.293  4915  4915 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:07.303  1019  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-15 15:01:07.303  1608  1608 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-15 15:01:07.303  1608  1608 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
03-15 15:01:07.303  1019  1377 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:07.303  1019  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:07.303  1019  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:07.313  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.313  4928  4928 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:07.313  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.313  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.313  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.313  4928  4928 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:07.323  4894  4936 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-15 15:01:07.323  4947  4947 E Zygote  : MountEmulatedStorage()
,03-15 15:01:07.323  4947  4947 E Zygote  : v2
03-15 15:01:07.323  4947  4947 I libpersona: KNOX_SDCARD checking this for 10085
,03-15 15:01:07.323  4947  4947 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:07.323  4947  4947 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-15 15:01:07.333  1019  1501 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4947 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 15:01:07.333  4915  4915 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 15:01:07.333  1019  1282 I ActivityManager: Killing 4239:com.google.android.youtube/u0a166 (adj 15): empty #31
,03-15 15:01:07.333  4947  4947 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 15:01:07.333  4947  4947 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:07.353  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.353  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.353  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.353  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.363  4928  4928 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-15 15:01:07.363  4928  4928 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:01:07.363  4928  4928 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 15:01:07.363  4928  4928 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:01:07.363  4928  4928 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 15:01:07.363  4928  4928 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-15 15:01:07.363  4947  4947 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:01:07.363  4947  4947 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:07.373  4962  4962 E Zygote  : MountEmulatedStorage()
03-15 15:01:07.373  4962  4962 E Zygote  : v2
03-15 15:01:07.373  4962  4962 I libpersona: KNOX_SDCARD checking this for 1000,
03-15 15:01:07.373  4962  4962 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:07.373  4962  4962 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-15 15:01:07.373  4962  4962 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:07.373  4962  4962 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:07.393  1019  1501 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4962 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-15 15:01:07.403   306   306 I art     : Explicit concurrent mark sweep GC freed 8713(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 23.808ms
,03-15 15:01:07.413  4962  4962 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:07.413  4962  4962 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:07.423   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 17.446ms
,03-15 15:01:07.443   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 718us total 17.167ms
,03-15 15:01:07.443  4947  4947 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 15:01:07.443  4947  4947 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-15 15:01:07.443  4947  4947 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:01:07.443  4947  4947 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 15:01:07.443  4947  4947 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:01:07.443  4947  4947 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-15 15:01:07.443  1019  1790 I ActivityManager: Killing 4398:com.google.android.gm/u0a101 (adj 15): empty #31
,03-15 15:01:07.453  1019  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-15 15:01:07.453  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:07.453  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:07.453  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:07.463  4928  4928 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,03-15 15:01:07.483  4962  4962 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458050467497,
03-15 15:01:07.483  4962  4962 D         : TimeServiceNative: User Time to be set is 1458050467497
03-15 15:01:07.483  4962  4962 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-15 15:01:07.483  4962  4962 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-15 15:01:07.483  4962  4962 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458050467497
,03-15 15:01:07.483  4962  4962 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!,
03-15 15:01:07.483   319   437 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-15 15:01:07.493   319  4978 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458050467497
03-15 15:01:07.493   319  4978 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458050467497, operation = 0
03-15 15:01:07.493   319  4978 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/6/70 5:14:44
03-15 15:01:07.493   319  4978 D QC-time-services: Daemon:Value read from RTC seconds = 21446084000
03-15 15:01:07.493   319  4978 D QC-time-services: Daemon:new time 1458050467497 
03-15 15:01:07.493   319  4978 D QC-time-services: Daemon: delta 1436604383497 genoff 1436604383497 
03-15 15:01:07.493   319  4978 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436604383497 to memory
03-15 15:01:07.493   319  4978 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-15 15:01:07.493   319  4978 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-15 15:01:07.493  1019  1309 I ActivityManager: Killing 4469:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,03-15 15:01:07.513   319  4978 D QC-time-services: Updating the TOD offset
03-15 15:01:07.513   319  4978 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436604383497 to memory
03-15 15:01:07.513   319  4978 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-15 15:01:07.513   319  4978 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-15 15:01:07.513   319  4978 E QC-time-services: Daemon:Update to modem bit set
03-15 15:01:07.513   319  4978 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-15 15:01:07.513   319  4978 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120639583497
,03-15 15:01:07.513  4962  4962 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-15 15:01:07.513   319   435 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-15 15:01:07.513   319   437 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-15 15:01:07.523  1019  1043 W libprocessgroup: failed to open /acct/uid_10166/pid_4239/cgroup.procs: No such file or directory
,03-15 15:01:07.523  1019  1143 I ActivityManager: Killing 4445:com.dropbox.android/u0a92 (adj 15): empty #31
,03-15 15:01:07.533   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-15 15:01:07.543  1019  1043 W libprocessgroup: failed to open /acct/uid_10101/pid_4398/cgroup.procs: No such file or directory
,03-15 15:01:07.573  1019  1553 D SettingsProvider: name = next_alarm_formatted
,03-15 15:01:07.573  1019  1553 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-15 15:01:07.573  1019  1553 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-15 15:01:07.573  1019  1553 D SettingsProvider: selectionArgs: false
03-15 15:01:07.573  1019  1553 D SettingsProvider: selectionArgs: 10085
03-15 15:01:07.573  1019  1553 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-15 15:01:07.573  1019  1553 D SettingsProvider: ret = -1
,03-15 15:01:07.603  4928  4928 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 127.010ms
,03-15 15:01:07.613  1019  1043 W libprocessgroup: failed to open /acct/uid_10092/pid_4445/cgroup.procs: No such file or directory
03-15 15:01:07.613  1019  1043 W libprocessgroup: failed to open /acct/uid_10092/pid_4469/cgroup.procs: No such file or directory
,03-15 15:01:07.653  1019  1309 I ActivityManager: Killing 3700:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-15 15:01:07.673  4947  4947 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 101.333ms
,03-15 15:01:07.673  4928  4979 D Mms/ArtClassLoader: init before art
,03-15 15:01:07.673  4928  4928 D Mms/TelephonyPermission: start operation mode monitor
,03-15 15:01:07.683  4928  4928 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 15:01:07.693  4928  4928 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-15 15:01:07.693  4928  4928 D Mms/TelephonyPermission: isDefault true
,03-15 15:01:07.693  4928  4928 D Mms/MmsApp: onCreate() com.android.mms
,03-15 15:01:07.703  4928  4928 D Mms/MmsApp: [start]    initCountryIso consume time = 248.849583
,03-15 15:01:07.713  1019  1501 D CountryDetector: The first listener is added
,03-15 15:01:07.713  3468  3468 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,03-15 15:01:07.713  1019  1043 W libprocessgroup: failed to open /acct/uid_10015/pid_3700/cgroup.procs: No such file or directory
,03-15 15:01:07.713  1019  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.713  1019  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.713  1019  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.713  1019  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.723  3468  4981 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account,
,03-15 15:01:07.733  4928  4928 D Mms/MmsApp: [end]    initCountryIso consume time = 20.43375
03-15 15:01:07.733  4928  4928 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.116719
,03-15 15:01:07.733  1019  1143 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4983 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-15 15:01:07.733  4928  4928 D Mms/MmsConfig: before partial update
,03-15 15:01:07.743  4983  4983 E Zygote  : MountEmulatedStorage()
03-15 15:01:07.743  1019  1143 I ActivityManager: Killing 4504:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
03-15 15:01:07.743  4983  4983 E Zygote  : v2
03-15 15:01:07.743  4983  4983 I libpersona: KNOX_SDCARD checking this for 10094
,03-15 15:01:07.743  4983  4983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 15:01:07.743  4983  4983 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:07.743  3468  4981 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-15 15:01:07.743  3468  4981 I ReactiveServiceManager: Supported : 1
,03-15 15:01:07.743  4983  4983 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 15:01:07.743  1019  1377 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-15 15:01:07.743  1019  1377 D QSEECOMAPI: : App is not loaded in QSEE
03-15 15:01:07.743  4983  4983 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:07.763  1019  1377 D QSEECOMAPI: : Loaded image: APP id = 11
,03-15 15:01:07.763  4928  4928 D Mms/MmsConfig: Load Resize quality : 80
,03-15 15:01:07.773  4035  4749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-15 15:01:07.773  3101  3101 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,03-15 15:01:07.773  1019  1377 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-15 15:01:07.773  1019  1377 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,03-15 15:01:07.773  1019  1377 E terrier : handleString: Failed to handle string(-4)
03-15 15:01:07.773  1019  1377 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-15 15:01:07.773  3468  4981 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-15 15:01:07.773  3468  4981 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-15 15:01:07.773  3468  4981 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-15 15:01:07.773  3468  4981 I PCWCLIENTTRACE_PushUtil: sales region : global
03-15 15:01:07.773  3468  4981 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-15 15:01:07.773  3468  4981 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-15 15:01:07.773  3101  3101 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,03-15 15:01:07.783  3101  3101 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,03-15 15:01:07.783  4983  4983 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:07.783  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 16 sec
,03-15 15:01:07.783  4983  4983 D ActivityThread: Added TimaKeyStore provider
03-15 15:01:07.783  4928  4928 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-15 15:01:07.783  4928  4928 D EasySignUpManager_1.0.1: isAuth is false
,03-15 15:01:07.783  4928  4928 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-15 15:01:07.783  3101  3168 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
03-15 15:01:07.783  3101  3101 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-15 15:01:07.793  3101  3168 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-15 15:01:07.793  3101  3168 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,03-15 15:01:07.813  3101  3168 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-15 15:01:07.823  1463  1844 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4928,
,03-15 15:01:07.823  1463  1844 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.281 ms
,03-15 15:01:07.823  3101  3168 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-15 15:01:07.833  4928  4928 D EasySignUpManager_1.0.1: isAuth is false
03-15 15:01:07.833  4928  4928 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-15 15:01:07.833  4928  4928 E CscParser: mps_code.dat does not exist
03-15 15:01:07.833  4928  4928 E CscParser: customer_path =/system/csc/customer.xml
03-15 15:01:07.833  4928  4928 E CscParser: fileName + /system/csc/customer.xml
,03-15 15:01:07.833  3101  3168 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,03-15 15:01:07.843  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,03-15 15:01:07.843  3101  3168 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,03-15 15:01:07.843  3101  3169 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,03-15 15:01:07.853  3101  3169 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,03-15 15:01:07.853  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
03-15 15:01:07.853  4928  4928 E CscParser: mps_code.dat does not exist
03-15 15:01:07.853  4928  4928 E CscParser: customer_path =/system/csc/customer.xml
03-15 15:01:07.853  4928  4928 E CscParser: fileName + /system/csc/customer.xml
,03-15 15:01:07.863  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:07.863  1019  1559 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-15 15:01:07.863  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-15 15:01:07.863  3101  3168 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,03-15 15:01:07.863  4983  4983 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,03-15 15:01:07.863  4983  4983 D elm:15183: ELMEngine.ELMEngine( context ).
,03-15 15:01:07.863  3101  3168 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,03-15 15:01:07.863  4983  4983 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-15 15:01:07.863  3101  3168 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-15 15:01:07.873  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-15 15:01:07.873  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:07.873  3101  3168 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
03-15 15:01:07.873  1019  1554 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:07.873  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-15 15:01:07.873  4983  4983 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-15 15:01:07.873  3101  3169 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:387678779
,03-15 15:01:07.873  3101  3169 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,03-15 15:01:07.873  1019  1043 W libprocessgroup: failed to open /acct/uid_10057/pid_4504/cgroup.procs: No such file or directory
,03-15 15:01:07.883  1019  1060 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-15 15:01:07.883  4928  4928 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-15 15:01:07.883  4983  4983 D elm:15183: ElmAgentService : onCreate()
,03-15 15:01:07.883  4983  5000 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,03-15 15:01:07.893  4983  5000 D elm:15183: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,03-15 15:01:07.893  4983  4983 D elm:15183: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,03-15 15:01:07.893  4983  4983 D elm:15183: ModuleBase.ModifySetAlarm()
03-15 15:01:07.893  4983  4983 D elm:15183: MDMBridge.getInstance()
03-15 15:01:07.893  4983  4983 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-15 15:01:07.893  3101  3169 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,03-15 15:01:07.903  1019  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.903  4928  4928 D Mms/MmsConfig:  enable multiwindow = true
,03-15 15:01:07.903  1019  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.903  1019  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:07.903  1019  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:07.913  5002  5002 E Zygote  : MountEmulatedStorage()
,03-15 15:01:07.913  5002  5002 E Zygote  : v2
,03-15 15:01:07.913  5002  5002 I libpersona: KNOX_SDCARD checking this for 10134
03-15 15:01:07.913  5002  5002 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:07.923  5002  5002 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-15 15:01:07.923  3101  3169 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
03-15 15:01:07.923  1019  1309 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5002 uid=10134 gids={50134, 9997} abi=armeabi-v7a
03-15 15:01:07.923  4928  4928 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-15 15:01:07.923  4928  4928 E Mms/MessageUtils: updateCountryIso : update country iso info ,
,03-15 15:01:07.923  5002  5002 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 15:01:07.923  5002  5002 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-15 15:01:07.933  4983  4983 D elm:15183: ElmAgentService : onDestroy().
,03-15 15:01:07.943  1019  1791 I ActivityManager: Killing 4550:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,03-15 15:01:07.943  3101  3169 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,03-15 15:01:07.943  4928  4928 D Mms/MmsConfig: [end]    init() consume time = 215.24401
,03-15 15:01:07.943  3101  3169 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 718127389
,03-15 15:01:07.943  4928  4928 D Mms/Contact: [start]    init() consume time = 0.771198
,03-15 15:01:07.943  3101  3101 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,03-15 15:01:07.953  3101  3101 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-15 15:01:07.953  3101  3101 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,03-15 15:01:07.963  1463  1486 D TP/MmsSmsProvider: query,matched:13, calling pid = 4928
,03-15 15:01:07.963  1463  1486 D TP/MmsSmsProvider: match 13:Elapsed time : 2.007 ms
,03-15 15:01:07.973  5002  5002 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:07.973  5002  5002 D ActivityThread: Added TimaKeyStore provider
03-15 15:01:07.973  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,03-15 15:01:07.973  3101  3101 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,03-15 15:01:07.973  3101  3169 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,03-15 15:01:07.983  1019  1487 I art     : Explicit concurrent mark sweep GC freed 30969(1751KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 30MB/45MB, paused 2.729ms total 187.454ms
,03-15 15:01:07.983  4035  4035 I Process : Sending signal. PID: 4035 SIG: 9
,03-15 15:01:07.983  3101  3101 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,03-15 15:01:07.993  3101  3101 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@265495f
,03-15 15:01:07.993  3101  3169 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-15 15:01:08.003  3101  3101 I DBG_DM  : [com.wssyncmldm.XDMService(755/lllllIIlIIIlIlIIIllI)] UI_id:223
,03-15 15:01:08.003  5002  5002 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:01:08.003  5002  5002 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-15 15:01:08.003  4928  4928 D Mms/Contact: [end]    init consume time = 57.873958
,03-15 15:01:08.003  1019  1043 W libprocessgroup: failed to open /acct/uid_10068/pid_4550/cgroup.procs: No such file or directory
03-15 15:01:08.003  3101  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 com.wssyncmldm.llIIllllIIlllIIIIlll.handleMessage:1090 
,03-15 15:01:08.003  3101  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 
,03-15 15:01:08.013  4928  5024 D Mms/DraftCache: [start]    rebuildCache consume time = 6.414011
,03-15 15:01:08.013  3101  3101 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:54882
,03-15 15:01:08.013  1019  1377 E PersonaManagerService: inState():  stateMachine is null !!
03-15 15:01:08.013  1019  1377 I PersonaManagerService: PersonaId don't exist
03-15 15:01:08.013  1019  1377 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-15 15:01:08.013  4928  4928 D Mms/MethodReflector: getSubId is called
03-15 15:01:08.013  4928  4928 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
03-15 15:01:08.013  1463  1844 D TP/MmsSmsProvider: query,matched:12, calling pid = 4928
,03-15 15:01:08.013  4928  4928 D Mms/MethodReflector: getTelephonyProperty is called,
03-15 15:01:08.013  4928  4928 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-15 15:01:08.013  4928  4928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-15 15:01:08.013  4928  4928 D Mms/DownloadManager: auto download without roaming -> true
03-15 15:01:08.013  4928  4928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,03-15 15:01:08.013  4928  4928 D Mms/MethodReflector: getSubId is called
03-15 15:01:08.013  1463  1844 D TP/MmsSmsProvider: match 12:Elapsed time : 2.025 ms
,03-15 15:01:08.013  1019  1377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 15:01:08.013  4928  4928 D Mms/MethodReflector: getDefaultSmsSubId is called
03-15 15:01:08.013  4928  4928 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-15 15:01:08.013  4928  4928 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
,03-15 15:01:08.023  4928  4928 D Mms/MethodReflector: getTelephonyProperty is called
03-15 15:01:08.023  1019  1377 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.023  1019  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:08.023  1019  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-15 15:01:08.023  4928  4928 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-15 15:01:08.023  4928  4928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-15 15:01:08.023  4928  4928 D Mms/DownloadManager: auto download without roaming -> true
,03-15 15:01:08.023  1019  1377 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 15:01:08.023  4928  4928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-15 15:01:08.023  4928  4928 D Mms/DownloadManager: auto download during roaming secondary -> false
03-15 15:01:08.023  4928  4928 D Mms/DownloadManager: mAutoDownload ------> true
03-15 15:01:08.023  4928  4979 D Mms/ArtClassLoader: init [DONE] art
,03-15 15:01:08.023  1019  1377 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-15 15:01:08.023  1019  1377 W ActivityManager: mDVFSHelper.acquire()
,03-15 15:01:08.023  1019  1377 D FocusedStackFrame: Set to : 0
,03-15 15:01:08.033  1019  1377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 15:01:08.033  1019  1377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 15:01:08.033  1019  1377 D InputDispatcher: Focused application set to: xxxx
03-15 15:01:08.033  1019  1377 D InputDispatcher: Focus left window: 1490
,03-15 15:01:08.033  1490  1490 D Launcher.HomeView: onPause
,03-15 15:01:08.033  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-15 15:01:08.033  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 15:01:08.033  4928  4928 D ComposerPerformance: 1458050468049 ms / [DONE] Composer constructor
,03-15 15:01:08.033  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 15:01:08.043  4928  5026 D Mms/Conversation: [start]    init() consume time = 35.075833
,03-15 15:01:08.043  4928  5024 D Mms/DraftCache: [end]    rebuildCache consume time = 4.086146,
,03-15 15:01:08.053  1019  1559 I ActivityManager: Killing 4588:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,03-15 15:01:08.053  1463  1486 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-15 15:01:08.053  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-15 15:01:08.053  1019  1019 D SensorService: [SO] activate (ident=0xb8af54a8, enabled=0)
03-15 15:01:08.053  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-15 15:01:08.063  1463  1486 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,03-15 15:01:08.063  1463  1486 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-15 15:01:08.063  4928  4928 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
03-15 15:01:08.063  4928  4928 I Mms/ReservationManager: ReservationManager()
,03-15 15:01:08.063  4928  4928 I Mms/ReservationManager: resetAfterConnected()
,03-15 15:01:08.063  1463  1486 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-15 15:01:08.063  1463  1486 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 15:01:08.063  1463  1486 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 15:01:08.063  1463  1486 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 15:01:08.063  1463  1486 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 15:01:08.063  1463  1486 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 15:01:08.063  1463  1486 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-15 15:01:08.063  1019  1019 D SensorManager: unregisterListener ::   
,03-15 15:01:08.063  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-15 15:01:08.073  1019  1019 D SensorService: [SO] changed settle time [1]
,03-15 15:01:08.073  1463  1844 D TP/MmsSmsProvider: query,matched:7, calling pid = 4928
03-15 15:01:08.073  1019  1019 D SensorService: [SO] setDelay [66000000]
,03-15 15:01:08.073  1019  1019 D SensorService: [SO] activate (ident=0xb8af54a8, enabled=1)
03-15 15:01:08.073  1019  1019 D SensorService: [SO] AR_init
03-15 15:01:08.073  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-15 15:01:08.073  1463  1844 D TP/MmsSmsProvider: match 7:Elapsed time : 3.225 ms
,03-15 15:01:08.073  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2153/onResume)] 
,03-15 15:01:08.073  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-15 15:01:08.073  1463  1486 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-15 15:01:08.073  1463  1486 D TP/MmsSmsProvider: need read changed broadcast:false
,03-15 15:01:08.083  4928  5026 D Mms/Conversation: [end]    init consume time = 31.104635
,03-15 15:01:08.083  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2195/lllIlIlIIIllIIlIllIl)] id 223
,03-15 15:01:08.083  4928  5026 D Mms/MessagingNotification: [start]    init() consume time = 1.205521
,03-15 15:01:08.083  1019  1143 I ActivityManager: Process com.sec.android.app.sysscope (pid 4035)(adj 0) has died(75,1083)
,03-15 15:01:08.093  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 15:01:08.093  4928  5026 D Mms/MessagingNotification: [end]    init consume time = 11.662969
,03-15 15:01:08.093  4928  4928 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-15 15:01:08.093  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 16
,03-15 15:01:08.093  4928  4928 D Mms/MmsApp: [end]    onCreate() consume time = 5.604791
,03-15 15:01:08.103  1019  1556 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,03-15 15:01:08.103  4928  4928 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,03-15 15:01:08.103  4928  4928 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,03-15 15:01:08.103  4928  5027 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 3.360105
03-15 15:01:08.103  1019  1556 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.103  1019  1556 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:08.103  1019  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-15 15:01:08.103  1019  1556 I ActivityManager: Killing 4305:com.test.thalitest/u0a174 (adj 15): empty #31
,03-15 15:01:08.103  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 15:01:08.103  4928  4928 D Mms/MethodReflector: getSubId is called
03-15 15:01:08.103  4928  4928 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-15 15:01:08.113  1463  1486 D TP/MmsSmsProvider: query,matched:400, calling pid = 4928
,03-15 15:01:08.113  4928  4928 D Mms/MethodReflector: getTelephonyProperty is called
03-15 15:01:08.113  4928  4928 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-15 15:01:08.113  4928  4928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-15 15:01:08.113  4928  4928 D Mms/DownloadManager: auto download without roaming -> true
03-15 15:01:08.113  4928  4928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-15 15:01:08.113  4928  4928 D Mms/DownloadManager: mAutoDownload ------> true
03-15 15:01:08.113  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:08.113  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 15:01:08.113  1463  1810 D TP/MmsSmsProvider: query,matched:0, calling pid = 4928
,03-15 15:01:08.113  1463  1810 V TP/MmsSmsProvider: getSimpleConversations entered.
03-15 15:01:08.113  3101  3101 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:54986
,03-15 15:01:08.113  1019  1377 E PersonaManagerService: inState():  stateMachine is null !!
03-15 15:01:08.113  4928  5028 D Mms/Synchronizer: [start]    doSync consume time = 14.543385
03-15 15:01:08.113  1019  1377 I PersonaManagerService: PersonaId don't exist
,03-15 15:01:08.113  1019  1377 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-15 15:01:08.113  1463  1810 D TP/MmsSmsProvider: match 0:Elapsed time : 1.769 ms
,03-15 15:01:08.123  1019  1377 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.123  1019  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:08.123  1019  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-15 15:01:08.123  1019  1377 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,03-15 15:01:08.123  1019  1377 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-15 15:01:08.123  1019  1377 W ActivityManager: mDVFSHelper.acquire()
,03-15 15:01:08.123  1019  1377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 15:01:08.123  1019  1377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-15 15:01:08.123  1019  1377 D InputDispatcher: Focused application set to: xxxx
,03-15 15:01:08.133  1019  1553 D ActivityManager: retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,03-15 15:01:08.133  1019  1553 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:08.133  1019  1553 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:08.133  1019  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-15 15:01:08.143  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 15:01:08.143  4928  5027 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 25.461354
,03-15 15:01:08.143  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.143  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.143  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.143  1019  1790 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-15 15:01:08.143  1019  1790 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.143  1019  1790 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 15:01:08.143  1019  1790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.143  1019  1556 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-15 15:01:08.143  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.IIllIIIlIllIIIllIIlI(252/llllIIIllIlIIIIllllI)] 
03-15 15:01:08.143  1019  1556 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
,03-15 15:01:08.143  1019  1556 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,03-15 15:01:08.153  1019  1556 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-15 15:01:08.153  1019  1556 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.153  1019  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.153  1019  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.153  1019  1559 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
03-15 15:01:08.153  1019  1559 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 15:01:08.153  1019  1559 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-15 15:01:08.153  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-15 15:01:08.153  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-15 15:01:08.153  1019  1019 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,03-15 15:01:08.153  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2145/onPause)] 
,03-15 15:01:08.153  1731  5030 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-15 15:01:08.153  1019  1309 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 15:01:08.153  1019  1309 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-15 15:01:08.153  1019  1309 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-15 15:01:08.163  1019  1556 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.163  1019  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.163  1019  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.173  1731  1731 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 15:01:08.173  1019  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:08.173  1019  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.173  1019  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.183  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.183  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.183  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.183  1986  1986 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-15 15:01:08.183  1463  1486 D TP/MmsSmsProvider: update, matched:300, calling pid = 4928
03-15 15:01:08.183  1463  1486 V TP/MmsSmsProvider: syncDBData start
,03-15 15:01:08.183  1463  1486 V TP/MmsSmsProvider: syncDBData sms end
,03-15 15:01:08.183  1463  1486 V TP/MmsSmsProvider: syncDBData mms end
,03-15 15:01:08.183  1463  1486 V TP/MmsSmsProvider: syncDBData end
03-15 15:01:08.183  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 16
,03-15 15:01:08.183  4928  5026 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-15 15:01:08.193  4928  5028 D Mms/Synchronizer: [end]    doSync consume time = 47.494063
,03-15 15:01:08.193  1463  1810 D TP/SmsProvider: query,matched:26, calling pid = 4928
,03-15 15:01:08.193  1019  1309 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0,
03-15 15:01:08.193  1019  1309 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:08.193  1019  1309 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.193  1019  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:01:08.193  1463  1810 D TP/SmsProvider: match 26:Elapsed time : 1.467 ms
,03-15 15:01:08.193  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:08.193  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.193  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 15:01:08.193  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.203  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:08.203  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.203  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.213  1019  1041 D SensorService: [SO] 0.192 0.402 10.228
03-15 15:01:08.213  1019  1041 D SensorService: [SO] [100 -> 255]
,03-15 15:01:08.213  1463  1844 D TP/MmsSmsProvider: query,matched:6, calling pid = 4928
,03-15 15:01:08.213  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:08.213  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.213  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.213  1463  1844 D TP/MmsSmsProvider: match 6:Elapsed time : 5.028 ms
,03-15 15:01:08.223  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 15:01:08.223  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.223  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.223  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.223  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(75/onCreate)] Postpone Count : 16
,03-15 15:01:08.223  1019  1556 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:08.223  1019  1556 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:08.223  1019  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.223  1019  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.233  1019  1553 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.233  1019  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.233  1019  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.233  4612  4612 D WearableService: callingUid 10012, callindPid: 4612
,03-15 15:01:08.253  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.253  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.253  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.263  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:08.263  1683  5031 E MDM     : [184] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-15 15:01:08.263  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.263  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.263  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.263  3101  3101 D PhoneWindow: *FMB* installDecor mIsFloating : false,
03-15 15:01:08.263  3101  3101 D PhoneWindow: *FMB* installDecor flags : -2139029248
,03-15 15:01:08.263  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:08.263  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:08.263  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:08.263  1019  1791 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:08.283  5033  5033 E Zygote  : MountEmulatedStorage()
03-15 15:01:08.283  5033  5033 I libpersona: KNOX_SDCARD checking this for 10025
03-15 15:01:08.283  5033  5033 E Zygote  : v2
03-15 15:01:08.283  5033  5033 I libpersona: KNOX_SDCARD not a persona
03-15 15:01:08.283  5033  5033 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 15:01:08.283  1019  1791 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5033 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,03-15 15:01:08.283  5033  5033 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 15:01:08.283  5033  5033 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:08.293  1019  1143 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.293  1019  1143 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.293  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
03-15 15:01:08.293  1019  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.293  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.293  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.293  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:01:08.293  1986  5032 D LocationInitializer: Restart initialization of location
03-15 15:01:08.293  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-15 15:01:08.303  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:08.303  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.303  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.313  1019  1143 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.313  1019  1143 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.313  1019  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.313  5033  5033 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:08.313  5033  5033 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:08.323  1019  1143 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.323  1019  1143 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.323  1019  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,03-15 15:01:08.323  1019  1553 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 15:01:08.323  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-15 15:01:08.323  1019  1043 W libprocessgroup: failed to open /acct/uid_10069/pid_4588/cgroup.procs: No such file or directory
,03-15 15:01:08.323  1019  1553 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.333  1019  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.333  1019  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.333  5033  5033 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 15:01:08.333  3101  3101 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-15 15:01:08.343  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-15 15:01:08.353  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 15:01:08.363  1019  1043 W libprocessgroup: failed to open /acct/uid_10174/pid_4305/cgroup.procs: No such file or directory
,03-15 15:01:08.373  1019  1032 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,03-15 15:01:08.373  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 15:01:08.373  1019  1019 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-15 15:01:08.373  1019  1019 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-15 15:01:08.383  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:08.383  1180  3018 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 15:01:08.383  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 16
03-15 15:01:08.383  5033  5033 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
03-15 15:01:08.393  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 15:01:08.393  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 15:01:08.393  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 15:01:08.403  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:08.403  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{f8431d8 u0 com.sec.bcservice/.BroadcastService}
,03-15 15:01:08.403  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 15:01:08.413  4928  5026 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-15 15:01:08.413  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 16
,03-15 15:01:08.423  1019  1019 I ValidateNoPeople: mEvictionCount: 0
,03-15 15:01:08.423  4928  4928 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-15 15:01:08.423  4928  4928 D Mms/Contact: performUpdate:widgetCount=0
,03-15 15:01:08.423  4928  5050 D Mms/ContactsCache: [start]    invalidate() consume time = 237.059062
,03-15 15:01:08.423  4928  5050 D Mms/ContactsCache: [end]    invalidate() consume time = 0.400417
,03-15 15:01:08.423  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 15:01:08.433  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-15 15:01:08.433  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,03-15 15:01:08.433  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-15 15:01:08.433  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:08.433  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
03-15 15:01:08.433  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-15 15:01:08.433  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-15 15:01:08.443  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-15 15:01:08.443  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,03-15 15:01:08.443  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,03-15 15:01:08.443  1180  1180 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-15 15:01:08.443  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-15 15:01:08.443  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 16
,03-15 15:01:08.443  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-15 15:01:08.443  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-15 15:01:08.443  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-15 15:01:08.453  5033  5033 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-15 15:01:08.453  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 15:01:08.453  1180  1180 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-15 15:01:08.453  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:08.463  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 15:01:08.463  1180  1180 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
,03-15 15:01:08.463  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
03-15 15:01:08.463  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:08.463  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,03-15 15:01:08.463  1180  1180 D PanelView: There is/are notification(s) 
03-15 15:01:08.463  1180  1180 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 15:01:08.463  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:08.463  1180  1180 D PanelView: There is/are notification(s) 
03-15 15:01:08.463  1180  1180 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 15:01:08.473  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 16
,03-15 15:01:08.473  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 15:01:08.483  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:08.483  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 16
,03-15 15:01:08.493  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:08.493  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:08.493  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-15 15:01:08.493  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:08.493  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:08.503  5051  5051 E Zygote  : MountEmulatedStorage(),
03-15 15:01:08.503  5051  5051 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:01:08.503  5051  5051 E Zygote  : v2,
03-15 15:01:08.503  5051  5051 I libpersona: KNOX_SDCARD not a persona
03-15 15:01:08.503  5051  5051 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:01:08.513  5051  5051 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-15 15:01:08.513  1019  1031 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5051 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-15 15:01:08.513  5051  5051 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:08.513  3101  3101 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-15 15:01:08.513   291   291 E SMD     : DCD OFF
,03-15 15:01:08.523  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-15 15:01:08.533   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-15 15:01:08.533  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 15:01:08.533  1180  1180 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-15 15:01:08.533  5051  5051 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:08.533  5051  5051 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:08.553  1019  1791 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,03-15 15:01:08.553  1019  1791 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 15:01:08.553  1019  1019 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-15 15:01:08.553  1180  1180 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-15 15:01:08.563  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 16
,03-15 15:01:08.563  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:08.563  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:08.563  1180  1180 D PanelView: There is/are notification(s) 
,03-15 15:01:08.563  1180  1180 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 15:01:08.563  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:08.563  1180  1180 D PanelView: There is/are notification(s) 
,03-15 15:01:08.563  1180  1180 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 15:01:08.563  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 15:01:08.563  5051  5051 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-15 15:01:08.573  1019  1559 D SecContentProvider2: uri = 14 selection = getSealedState
03-15 15:01:08.573  1019  1559 D SecContentProvider2: mCursor = null
,03-15 15:01:08.573  1019  1501 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-15 15:01:08.573  1019  1501 D SecContentProvider2: mCursor = null
,03-15 15:01:08.573  5051  5051 V MTPRx   : sealedState: false
,03-15 15:01:08.573  5051  5051 V MTPRx   : sealedUsbMassStorageState: false
,03-15 15:01:08.573  5051  5051 E MTPRx   : check value of boot_completed is1
03-15 15:01:08.573  5051  5051 E MTPRx   : check booting is completed_sys.boot_completed
03-15 15:01:08.573  3101  3101 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:08.573  3101  3101 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 15:01:08.573  3101  3101 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,03-15 15:01:08.573  3101  3101 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,03-15 15:01:08.583  5051  5051 E MTPRx   : Sd-Card path/storage/extSdCard
,03-15 15:01:08.583  5051  5051 E MTPRx   : Status for mount/Unmount :removed
03-15 15:01:08.583  5051  5051 E MTPRx   : SDcard is not available
,03-15 15:01:08.583  5051  5051 W MTPRx   : value of connected istrue
03-15 15:01:08.583  5051  5051 W MTPRx   : value of configured istrue
03-15 15:01:08.583  5051  5051 W MTPRx   : value of mtpEnabled istrue
03-15 15:01:08.583  5051  5051 W MTPRx   : value of ptpEnabled isfalse
,03-15 15:01:08.593  5051  5051 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-15 15:01:08.593  5051  5051 E MTPRx   : mFirstTime: false
,03-15 15:01:08.593  3101  5066 D OpenGLRenderer: Render dirty regions requested: true
,03-15 15:01:08.603  1019  1309 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-15 15:01:08.603  1019  1309 D KnoxTimeoutHandler: postActiveUserChange for user 0
,03-15 15:01:08.603  1019  1309 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-15 15:01:08.603  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-15 15:01:08.603  5051  5051 D         : MTP: reading debug level property
,03-15 15:01:08.603  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-15 15:01:08.603  5051  5051 E MTPJNIInterface: Getting CryptionKey from JAVA
03-15 15:01:08.603  5051  5051 E MTPRx   : currentUserId is 0
,03-15 15:01:08.603  5051  5051 E MTPRx   : Start observing USB_STATE_MATCH 
,03-15 15:01:08.613  5051  5051 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
,03-15 15:01:08.613  5051  5051 E MTPRx   : is_Privatemode is NOT 1
,03-15 15:01:08.613  3101  3101 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-15 15:01:08.613  3101  3101 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-15 15:01:08.613  1019  1309 D SettingsProvider: name = boot_time_connected
,03-15 15:01:08.613  5051  5051 E MTPRx   : Sending NORMAL_BOOT to stack
03-15 15:01:08.613  5051  5051 E MTPJNIInterface: noti = 17
,03-15 15:01:08.623  1019  1377 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 15:01:08.623  1019  1556 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-15 15:01:08.623  5051  5051 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-15 15:01:08.623  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-15 15:01:08.623  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:08.623  1019  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:08.623  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-15 15:01:08.623  1019  1487 D SettingsProvider: name = mtp_running_status
,03-15 15:01:08.633  1180  1180 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-15 15:01:08.643  1019  1309 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 15:01:08.643  5051  5051 E MTPRx   : else part ... so first time!!!
03-15 15:01:08.643  5051  5051 E MTPPlaObsrvr: inside setContext()
03-15 15:01:08.643  5051  5051 E MTPPlaObsrvr:  inside createplafiles
,03-15 15:01:08.643  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{2269e0fa u0 com.google.android.gms/.config.ConfigFetchService}
,03-15 15:01:08.643   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, YUIInstallC
,03-15 15:01:08.653  1180  1180 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-15 15:01:08.653  5051  5051 E MTPPlaObsrvr: playlist count is0
,03-15 15:01:08.653  5051  5051 E MTPPlaObsrvr:  inside try branch createplafiles
,03-15 15:01:08.653  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 15:01:08.653  5051  5051 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-15 15:01:08.653  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 15:01:08.653  5051  5051 E MTPPlaObsrvr: Inside registerContentObserver
,03-15 15:01:08.663  5051  5051 E MtpAdbObserver: inside setContext()
,03-15 15:01:08.663  5051  5051 E MtpAdbObserver: Inside registerContentObserver
,03-15 15:01:08.663  5051  5051 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-15 15:01:08.663  1019  1377 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-15 15:01:08.663  1019  1377 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:08.663  1019  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:08.663  1019  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-15 15:01:08.663  1019  1309 D SettingsProvider: name = mtp_running_status
,03-15 15:01:08.663  1019  1556 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 15:01:08.673  1019  1559 D InputDispatcher: Focus entered window: 3101
03-15 15:01:08.673  5051  5051 E MtpService: onCreate.
,03-15 15:01:08.673  1019  1282 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-15 15:01:08.673  1019  1282 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.673  1019  1282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:08.673  1019  1282 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-15 15:01:08.673  5051  5069 V MtpMediaDBManager: inside deleteAllDB
,03-15 15:01:08.673  3101  3101 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 15:01:08.683  5051  5051 E MtpService: < MTP > Registering BroadCast receiver :::::
03-15 15:01:08.683  3101  5066 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 15:01:08.683  3101  5066 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 15:01:08.683  3101  5066 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 15:01:08.683  3101  5066 I Adreno-EGL: Local Branch: 
03-15 15:01:08.683  3101  5066 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 15:01:08.683  3101  5066 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 15:01:08.683  3101  5066 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 15:01:08.683  3101  5066 I OpenGLRenderer: Initialized EGL, version 1.4
,03-15 15:01:08.683  1227  1227 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-15 15:01:08.683  5051  5051 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-15 15:01:08.683  5051  5051 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-15 15:01:08.693  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 15:01:08.693  5051  5051 E MtpService: onStartCommand.
,03-15 15:01:08.693  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 15:01:08.693  5051  5051 W MTPRx   : calling native method
03-15 15:01:08.693  5051  5051 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-15 15:01:08.693  5051  5070 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-15 15:01:08.693  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:08.693  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:08.693  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:08.693  1019  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:08.693  5051  5069 V MtpMediaDBManager: inside Thread updateDB
,03-15 15:01:08.703  3101  5066 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-15 15:01:08.703  3101  5066 D OpenGLRenderer: Enabling debug mode 0
03-15 15:01:08.703  5071  5071 E Zygote  : MountEmulatedStorage()
03-15 15:01:08.703  5071  5071 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:01:08.703  5071  5071 E Zygote  : v2
03-15 15:01:08.703  5071  5071 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:08.703  5071  5071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 15:01:08.713  5071  5071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-15 15:01:08.713  1019  1501 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5071 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 15:01:08.713  5071  5071 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:01:08.713  5051  5069 E MtpMediaDBManager: count : 27
03-15 15:01:08.713  5051  5051 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-15 15:01:08.713  5051  5051 E MTPJNIInterface: noti = 10
03-15 15:01:08.713  5051  5051 E MtpService: onStartCommand.
03-15 15:01:08.713  5051  5051 W MTPRx   : calling native method
03-15 15:01:08.713  5051  5051 E MTPRx   : Checking the driver time out
03-15 15:01:08.713  5051  5051 E MTPJNIInterface: noti = 2
03-15 15:01:08.713  5051  5051 D         : deleting sockets before message queue initialization
03-15 15:01:08.713  5051  5051 D         : event handler thread is created, so set the flag
,03-15 15:01:08.713  5051  5051 E MTPRx   : called native method
03-15 15:01:08.713  5051  5051 E MTPJNIInterface: setting Media scanner status0
03-15 15:01:08.713  5051  5051 E MTPJNIInterface: After setting Media scanner status0
03-15 15:01:08.723  5051  5070 E MtpService: handleMessage. msg= { when=-3ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-15 15:01:08.723  5051  5051 W MTPRx   : notification from stack 1
,03-15 15:01:08.723  5051  5080 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-15 15:01:08.723  5051  5080 E MTPJNIInterface: Getting media scanner status0
,03-15 15:01:08.723  5051  5080 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A5)
,03-15 15:01:08.733  5071  5071 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:08.733  5071  5071 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:08.743  5051  5069 W MtpMediaDBManager: sending db update complete noti to stack
03-15 15:01:08.743  5051  5069 E MTPJNIInterface: noti = 29
,03-15 15:01:08.763  5051  5080 E MTPJNIInterface: Status for mount/Unmount :removed
03-15 15:01:08.763  5051  5080 E MTPJNIInterface: SDcard is not available
,03-15 15:01:08.783  1019  1041 D SensorService: [SO] 0.192 0.402 10.209
,03-15 15:01:08.783  1019  1282 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,03-15 15:01:08.783  1019  1049 D PersonaManager: isKioskContainerExistOnDevice,
,03-15 15:01:08.793  5051  5080 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-15 15:01:08.793  1019  5088 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-15 15:01:08.793  1180  1180 D PanelView: There is/are notification(s) 
,03-15 15:01:08.803  1019  1049 I ActivityManager: Displayed Component not be shown by security: +643ms (total +764ms)
,03-15 15:01:08.803  5051  5080 E MTPJNIInterface: Status for mount/Unmount :removed
,03-15 15:01:08.803  5051  5080 E MTPJNIInterface: SDcard is not available
03-15 15:01:08.803  5051  5080 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 15:01:08.803  5051  5080 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-15 15:01:08.803  5051  5080 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 15:01:08.803  5051  5080 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-15 15:01:08.803  5051  5080 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 15:01:08.803  5051  5080 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-15 15:01:08.803  5051  5080 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 15:01:08.803  5051  5080 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-15 15:01:08.803  5051  5051 W MTPRx   : notification from stack 2
,03-15 15:01:08.813  5051  5090 D         : [mtp_init_device] Library open with 32 bits.
03-15 15:01:08.813  5051  5090 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
03-15 15:01:08.813  5051  5090 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-15 15:01:08.813  5051  5090 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-15 15:01:08.813  5051  5090 E         :  [sua_support_present:1287] returning false 
03-15 15:01:08.813  5051  5090 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,03-15 15:01:08.813  5071  5071 D TMNetworkReceiver: TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
03-15 15:01:08.813  5071  5071 D TMNetworkReceiver: TMNetworkReceiver.onReceive() Enter
,03-15 15:01:08.813  5071  5071 D TMNetworkReceiver: MirrorLink feauture level: using UEvent
,03-15 15:01:08.813  1832  1832 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-15 15:01:08.813  3101  3101 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@138ff247 time:55688
,03-15 15:01:08.813  1019  1501 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:08.813  1019  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:08.813  1019  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings

```
