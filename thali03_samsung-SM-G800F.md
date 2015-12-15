#### Test 5038801913f4183_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/TimaKeyStoreProvider( 5190): in addTimaSignatureService
D/TimaKeyStoreProvider( 5190): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5190): Added TimaKesytore provider
W/ApplicationsProvider( 2973): Could not fetch usage stats
W/ApplicationsProvider( 2973): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2973): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2973): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2973): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2973): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2973): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2973): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2973): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2973): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2973): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2973): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/dalvikvm( 5190): GC_CONCURRENT freed 3007K, 30% free 9564K/13548K, paused 3ms+2ms, total 21ms
D/dalvikvm( 5190): WAIT_FOR_CONCURRENT_GC blocked 12ms
I/SELinux ( 5206): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5206):  
--------- beginning of /dev/log/system
I/ActivityManager( 2418): Killing 4058:com.gameloft.android.GloftPSHU/u0a181 (adj 15): empty #43
I/SELinux ( 5206): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5206):  
I/SELinux ( 5206):  
I/SELinux ( 5206): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5206): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5206): >>>>> Normal User
E/dalvikvm( 5206): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
E/SELinux ( 5206): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5206): in addTimaSignatureService
D/TimaKeyStoreProvider( 5206): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5206): Added TimaKesytore provider
D/dalvikvm( 5206): GC_CONCURRENT freed 2999K, 30% free 9565K/13544K, paused 3ms+1ms, total 20ms
D/dalvikvm( 5206): WAIT_FOR_CONCURRENT_GC blocked 15ms
E/PersonaManagerService( 2418): returning null in  getPersonasForUser
I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 3 sec
I/SELinux ( 5218): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5218):  
I/ActivityManager( 2418): Killing 4101:com.n7mobile.muzodajnia:main/u0a184 (adj 15): empty #43
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 5163): Resource data:2131165197
I/AMMetaDataParserService( 5163): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
I/AMMetaDataParserService( 5163): Resource data:2131165194
I/AMMetaDataParserService( 5163): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/SELinux ( 5218): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5218):  
I/SELinux ( 5218):  
I/SELinux ( 5218): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5218): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5218): >>>>> Normal User
E/dalvikvm( 5218): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
E/SELinux ( 5218): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/        ( 5163): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 5163): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
D/TimaKeyStoreProvider( 5218): in addTimaSignatureService
D/TimaKeyStoreProvider( 5218): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5218): Added TimaKesytore provider
D/        ( 5163): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 5163): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
D/dalvikvm( 5218): GC_CONCURRENT freed 2991K, 30% free 9581K/13548K, paused 3ms+1ms, total 18ms
D/dalvikvm( 5218): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 5163): GC_FOR_ALLOC freed 521K, 12% free 11979K/13544K, paused 23ms, total 23ms
D/        ( 5163): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 5163): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
D/        ( 5163): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 5163): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
I/AMMetaDataParserService( 5163): Resource data:2131165194
I/AMMetaDataParserService( 5163): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
W/BackupManagerService( 2418): dataChanged but no participant pkg='com.android.providers.settings' uid=10088
D/        ( 5163): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 5163): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
D/        ( 5163): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 5163): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
D/        ( 5163): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 5163): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
I/SELinux ( 5231): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5231):  
D/        ( 5163): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 5163): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
I/ActivityManager( 2418): Killing 4127:com.google.android.configupdater/u0a3 (adj 15): empty #43
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 5163): Resource data:2131165195
I/AMMetaDataParserService( 5163): getResourceName:com.sec.android.gallery3d:xml/device_filter
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 5163): Resource data:2131165204
I/AMMetaDataParserService( 5163): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 5163): Resource data:2131165204
I/AMMetaDataParserService( 5163): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 5163): Resource data:2131165204
I/AMMetaDataParserService( 5163): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/SELinux ( 5231): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5231):  
I/SELinux ( 5231):  
I/SELinux ( 5231): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5231): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5231): >>>>> Normal User
E/dalvikvm( 5231): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
E/SELinux ( 5231): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5231): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5231): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5231): Added TimaKesytore provider
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 5163): Resource data:2131099676
I/AMMetaDataParserService( 5163): getResourceName:com.android.mms:xml/spellscroll
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/AMMetaDataParserService( 5163): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
I/AMMetaDataParserService( 5163): Resource data:2131099648
I/AMMetaDataParserService( 5163): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
D/dalvikvm( 5231): GC_CONCURRENT freed 3000K, 30% free 9566K/13544K, paused 3ms+2ms, total 22ms
D/dalvikvm( 5231): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
I/SELinux ( 5245): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5245):  
I/ActivityManager( 2418): Killing 4183:com.sec.dsm.system/1000 (adj 15): empty #43
D/dalvikvm( 1921): GC_EXPLICIT freed 44K, 10% free 9502K/10524K, paused 3ms+3ms, total 37ms
I/SELinux ( 5245): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5245):  
I/SELinux ( 5245):  
I/SELinux ( 5245): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5245): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5245): >>>>> Normal User
E/dalvikvm( 5245): >>>>> com.dropbox.android [ userId:0 | appId:10095 ]
E/SELinux ( 5245): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5245): in addTimaSignatureService
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9502K/10524K, paused 3ms+3ms, total 28ms
D/TimaKeyStoreProvider( 5245): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5245): Added TimaKesytore provider
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9502K/10524K, paused 2ms+3ms, total 25ms
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
D/dalvikvm( 5245): GC_CONCURRENT freed 2998K, 30% free 9572K/13548K, paused 3ms+1ms, total 20ms
D/dalvikvm( 5245): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
I/GAV2    ( 3612): Thread[GAThread,5,main]: No campaign data found.
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
D/SSRMv2:SIOP( 2418): SIOP:: AP = 380, Delta = 10
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
I/AMMetaDataParserService( 5163): Resource data:2131099648
I/AMMetaDataParserService( 5163): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
D/AndroidRuntime( 5243): 
D/AndroidRuntime( 5243): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5243): CheckJNI is OFF
D/AndroidRuntime( 5243): setted country_code = Poland
D/AndroidRuntime( 5243): setted countryiso_code = PL
D/AndroidRuntime( 5243): setted sales_code = PLS
D/AndroidRuntime( 5243): readGMSProperty: start
D/AndroidRuntime( 5243): readGMSProperty: already setted!!
D/AndroidRuntime( 5243): readGMSProperty: end
D/AndroidRuntime( 5243): addProductProperty: start
D/dalvikvm( 5243): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5243): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5243): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5243): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5243): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
D/PackageManager( 2418): [MSG] MCS_UNBIND
I/PackageManager( 2418): calling disconnectService()
D/PackageManager( 2418): Trying to unbind to DefaultContainerService
I/ActivityManager( 2418): Killing 4201:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
I/com.dropbox.android.service.DropboxNetworkReceiver( 5245): Setting receiver enabled: false
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
I/com.dropbox.sync.android.a( 5245): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 4 sec
E/memtrack( 5243): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5243): failed to load memtrack module: -2
I/com.dropbox.sync.android.aa( 5245): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800F armeabi-v7a; en_US))
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
D/dalvikvm( 5243): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
I/AMMetaDataParserService( 5163): Resource data:2131099648
I/AMMetaDataParserService( 5163): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/SELinux ( 5275): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5275):  
I/ActivityManager( 2418): Killing 4214:com.sec.factory/1000 (adj 15): empty #43
I/SELinux ( 5275): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5275):  
I/SELinux ( 5275):  
I/SELinux ( 5275): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5275): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5275): >>>>> Normal User
E/dalvikvm( 5275): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux ( 5275): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/AndroidRuntime( 5243): Calling main entry com.android.commands.am.Am
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
D/TimaKeyStoreProvider( 5275): in addTimaSignatureService
D/TimaKeyStoreProvider( 5275): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5275): Added TimaKesytore provider
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
V/ApplicationPolicy( 2418): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/SurfaceFlinger( 1920): id=14 createSurf (16x16),-1 flag=20004, EimLayer
D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2418): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=15 createSurf (16x16),-1 flag=20004, EimLayer
D/Launcher.HomeView( 2786): onPause
D/StatusBarManagerService( 2418): tr p:2418,o:f
D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/AndroidRuntime( 5243): Shutting down VM
I/SurfaceFlinger( 1920): id=16 createSurf (1x1),1 flag=404, iello
D/dalvikvm( 5243): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
D/dalvikvm( 5275): GC_CONCURRENT freed 2916K, 29% free 9575K/13472K, paused 3ms+24ms, total 58ms
D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2418): tr p:2786,o:f
D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
I/SELinux ( 5290): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5290):  
D/elm:14132( 5275): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5275): ELMEngine.ELMEngine( context ).
D/elm:14132( 5275): MDMBridge.setEnterpriseBridge()
I/SELinux ( 5290): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5290):  
I/SELinux ( 5290):  
I/SELinux ( 5290): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/elm:14132( 5275): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/SELinux ( 5290): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5290): >>>>> Normal User
E/dalvikvm( 5290): >>>>> com.example.hello [ userId:0 | appId:10549 ]
E/SELinux ( 5290): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/elm:14132( 5275): ElmAgentService : onCreate()
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
D/elm:14132( 5275): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5275): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:14132( 5275): BootCompletedState : startBootCompleted() call
I/SELinux ( 5302): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5302):  
D/elm:14132( 5275): ModuleBase.resetCalllogAPIAlarm()
D/TimaKeyStoreProvider( 5290): in addTimaSignatureService
D/TimaKeyStoreProvider( 5290): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5290): Added TimaKesytore provider
D/elm:14132( 5275): MDMBridge.getAllLicenseInfoFromSDK()
I/elm:14132( 5275): Get License : 0
D/elm:14132( 5275): ElmAgentService : onDestroy().
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
I/SELinux ( 5302): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5302):  
I/SELinux ( 5302):  
I/SELinux ( 5302): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5302): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5302): >>>>> Normal User
E/dalvikvm( 5302): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
E/SELinux ( 5302): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/WindowOrientationListener( 2418): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 2418): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 2418): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
D/TimaKeyStoreProvider( 5302): in addTimaSignatureService
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/TimaKeyStoreProvider( 5302): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5302): Added TimaKesytore provider
I/ActivityManager( 2418): Killing 3144:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #43
D/Launcher.HomeView( 2786): onStop
D/Launcher( 2786): onTrimMemory. Level: 20
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(20)
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
,D/dalvikvm( 5290): GC_CONCURRENT freed 2994K, 30% free 9565K/13540K, paused 5ms+1ms, total 24ms
,D/dalvikvm( 5290): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/AMMetaDataParserService( 5163): Resource data:2131099648
I/AMMetaDataParserService( 5163): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,V/WebViewChromium( 5290): Binding Chromium to the background looper Looper (main, tid 1) {42242358}
,I/chromium( 5290): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5290): Initializing chromium process, renderers=0
,W/chromium( 5290): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/System.out( 5245): Thread-383(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/libEGL  ( 5290): loaded /system/lib/egl/libEGL_mali.so
,I/System.out( 5245): Thread-383(ApacheHTTPLog):isShipBuild true
,I/System.out( 5245): Thread-383(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/libEGL  ( 5290): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 5290): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 5290): Mali API Version : 401
,I/Mali    ( 5290): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
D/dalvikvm( 5302): GC_CONCURRENT freed 3004K, 30% free 9565K/13544K, paused 10ms+10ms, total 40ms
,D/dalvikvm( 5302): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 5334): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5334):  
,I/ActivityManager( 2418): Killing 4302:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,I/dalvikvm( 5290): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 5290): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5290): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5290): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
,W/dalvikvm( 5290): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5290): VFY: replacing opcode 0x6e at 0x0008
D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2418): tr p:5290,o:f
,W/dalvikvm( 5290): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 5290): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5290): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5290): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5290): VFY: replacing opcode 0x6f at 0x001a
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
W/dalvikvm( 5290): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5290): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5290): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5290): VFY: replacing opcode 0x6e at 0x000d
I/SELinux ( 5334): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5334):  
I/SELinux ( 5334):  
I/SELinux ( 5334): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/dalvikvm( 5290): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5290): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
E/SELinux ( 5334): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5334): >>>>> Normal User
E/dalvikvm( 5334): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
D/dalvikvm( 5290): VFY: replacing opcode 0x6e at 0x0000
,E/SELinux ( 5334): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (7/10)
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
D/SystemWebViewEngine( 5290): CordovaWebView is running on device made by: samsung
,D/TimaKeyStoreProvider( 5334): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5334): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5334): Added TimaKesytore provider
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2418): semi p:5290,o:f
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SurfaceFlinger( 1920): id=17 createSurf (1x1),1 flag=404, NainActivit
,D/dalvikvm( 5334): GC_CONCURRENT freed 3001K, 30% free 9572K/13548K, paused 3ms+2ms, total 36ms
,D/dalvikvm( 5334): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 5290): EGLImpl-HWUI Protected EGL context created
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/OpenGLRenderer( 5290): Enabling debug mode 0
,W/AwContents( 5290): nativeOnDraw failed; clearing to background color.
,I/CameraApp( 5334): CameraApp.onCreate()... mFeature : null
,I/testFeature( 5334): Feature.Feature(context)
I/testFeature( 5334): Feature.readInternalDefaultXml()
,I/testFeature( 5334): ResetFeatureValue
,I/CameraFirmware_broadcast( 5334): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 5334): CameraApp.getAppFeature()...
,I/SELinux ( 5359): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5359):  
,I/ActivityManager( 2418): Killing 4364:com.fmm.dm/1000 (adj 15): empty #43
,D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@4
W/AwContents( 5290): nativeOnDraw failed; clearing to background color.
,W/ActivityManager( 2418): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@8
,I/SELinux ( 5359): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5359):  
I/SELinux ( 5359):  
,I/SELinux ( 5359): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
E/SELinux ( 5359): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5359): >>>>> Normal User
E/dalvikvm( 5359): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
E/SELinux ( 5359): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 5 sec
,D/TimaKeyStoreProvider( 5359): in addTimaSignatureService
,D/        ( 5163): PNG_doEncode true 106, 106
,D/TimaKeyStoreProvider( 5359): Cannot add TimaSignature Service, License check Failed
,I/AMMetaDataParserService( 5163): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,D/ActivityThread( 5359): Added TimaKesytore provider
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
,I/AMMetaDataParserService( 5163): Resource data:2131099648
,I/AMMetaDataParserService( 5163): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/dalvikvm( 5359): GC_CONCURRENT freed 3006K, 30% free 9558K/13544K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 5359): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/PackageIntentReceiver( 5359): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 5359): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager( 2418): Killing 4347:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
,I/SurfaceFlinger( 1920): id=16 Removed iello (9/10)
,I/SurfaceFlinger( 1920): id=16 Removed iello (-2/10)
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 302, prevStep = 4, currStep = 4
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 5377): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5377):  
,I/SELinux ( 5377): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5377):  
I/SELinux ( 5377):  
,I/SELinux ( 5377): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5377): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5377): >>>>> Normal User
E/dalvikvm( 5377): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 5377): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5377): in addTimaSignatureService
,D/        ( 5163): PNG_doEncode true 106, 106
,D/TimaKeyStoreProvider( 5377): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 5163): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/ActivityThread( 5377): Added TimaKesytore provider
,I/chromium( 5290): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,E/AndroidProtocolHandler( 5290): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/HarmonyEASService( 2418): Updating for all 1
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/dalvikvm( 5377): GC_CONCURRENT freed 2991K, 30% free 9569K/13540K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 5377): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/JsMessageQueue( 5290): Set native->JS mode to OnlineEventsBridgeMode
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
,I/AMMetaDataParserService( 5163): Resource data:2131099648
I/AMMetaDataParserService( 5163): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 5391): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5391):  
I/ActivityManager( 2418): Killing 4398:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,D/        ( 5163): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 5163): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515,
,I/SELinux ( 5391): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 5391):  
I/SELinux ( 5391):  
,I/SELinux ( 5391): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5391): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 5391): >>>>> Normal User
,E/dalvikvm( 5391): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
,E/SELinux ( 5391): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/TimaKeyStoreProvider( 5391): in addTimaSignatureService
,I/chromium( 5290): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/TimaKeyStoreProvider( 5391): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5391): Added TimaKesytore provider
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/chromium( 5290): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/libGLESv2( 5290): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 5290): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/dalvikvm( 5290): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x4223a8c8
D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/dalvikvm( 5290): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x4223a8c8
,D/jxcore_app_log( 5290): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2024315240
,D/JX-Cordova( 5290): jxcore cordova android initializing
,D/dalvikvm( 5391): GC_CONCURRENT freed 3002K, 30% free 9568K/13548K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 5391): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 5163): Resource data:2131099671
W/ContextImpl( 5391): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
I/AMMetaDataParserService( 5163): getResourceName:com.android.mms:xml/searchable
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/knox    ( 5391): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 5391): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
,I/knox    ( 5391): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 5391): KNOXAgentService : onCreate()
D/knox    ( 5391): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 5391): KNOXAgentService. startJobThread() start
D/knox    ( 5391): KNOXAgentService. JobThread()
I/SELinux ( 5405): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5405):  
I/ActivityManager( 2418): Waited long enough for: ServiceRecord{42f95cc8 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,I/SELinux ( 5405): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5405):  
I/SELinux ( 5405):  
,I/SELinux ( 5405): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5405): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5405): >>>>> Normal User
,E/dalvikvm( 5405): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
,E/SELinux ( 5405): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/knox    ( 5391): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5391): KNOXAgentService. startJobThread() wait
,D/TimaKeyStoreProvider( 5405): in addTimaSignatureService
,D/knox    ( 5391): mKnoxAgentEngine.ELMEngine( context , reStart:true).
,D/knox    ( 5391): ELMEngine.ServiceHandler.handleMessage( DEFAULT ).
,D/TimaKeyStoreProvider( 5405): Cannot add TimaSignature Service, License check Failed
,D/knox    ( 5391): KNOXAgentService : onDestroy().
,D/knox    ( 5391): ModuleBase.cancelAllAlarmManageModule()
,D/ActivityThread( 5405): Added TimaKesytore provider
,D/dalvikvm( 5163): GC_CONCURRENT freed 1818K, 19% free 12212K/15004K, paused 6ms+3ms, total 60ms
,D/dalvikvm( 5163): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/SensorService( 2418):   0.3 -0.0 9.9
,D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@8
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.GridSettings
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 6 sec
W/jxcore-log( 5290): Initializing JXcore engine
,W/jxcore-log( 5290): JXcore engine is ready
I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
,I/AMMetaDataParserService( 5163): Resource data:2131165216
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
,W/jxcore-log( 5290): Starting JXcore engine
D/dalvikvm( 5405): GC_CONCURRENT freed 3000K, 30% free 9565K/13540K, paused 2ms+2ms, total 42ms
,D/dalvikvm( 5405): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/        ( 5163): PNG_doEncode true 80, 80
,I/AMMetaDataParserService( 5163): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,E/KnoxSetupWizardClient( 5405): isShipMode : 1
,I/KnoxSetupWizardClient( 5405): onReceive : android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 5245): GC_FOR_ALLOC freed 1946K, 23% free 10511K/13548K, paused 48ms, total 50ms
,I/dalvikvm-heap( 5245): Grow heap (frag case) to 11.339MB for 131088-byte allocation
,D/ShortcutReceiver2( 5405):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,W/System.err( 5405): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 5405): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 5405): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 5405): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 5405): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 5405): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
,W/System.err( 5405): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
W/System.err( 5405): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
W/System.err( 5405): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 5405): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 5405): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 5405): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 5405): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
W/System.err( 5405): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
,W/System.err( 5405): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/yash    ( 5405): setDisableWidget>size:0
,D/dalvikvm( 5245): GC_FOR_ALLOC freed <1K, 23% free 10639K/13680K, paused 37ms, total 37ms
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SubSettings
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/SELinux ( 5418): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5418):  
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429086
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131296695
,I/ActivityManager( 2418): Killing 3399:com.sec.android.app.mss/u0a21 (adj 15): empty #43
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429086
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429071
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429071
I/SELinux ( 5418): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5418):  
I/SELinux ( 5418):  
,I/SELinux ( 5418): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5418): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5418): >>>>> Normal User
E/dalvikvm( 5418): >>>>> com.LocalFota [ userId:0 | appId:10113 ]
I/System.out( 5245): pool-4-thread-1 calls detatch()
,E/SELinux ( 5418): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429071
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131297114
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ApnSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429073
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/bluetooth_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429073
,D/TimaKeyStoreProvider( 5418): in addTimaSignatureService
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/bluetooth_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
,D/TimaKeyStoreProvider( 5418): Cannot add TimaSignature Service, License check Failed
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
,D/ActivityThread( 5418): Added TimaKesytore provider
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429095
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/mirror_link_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429086
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131296695
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.TetherSettings
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429086
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131296695
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429071
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131297114
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429086
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131296695
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429086
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131296695
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429086,
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE,
,I/AMMetaDataParserService( 5163): Resource data:2131296695,
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 5163): getResourceTypeNamestring
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429086
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131296695
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429086
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131296695
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429146
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429118
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429118
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429118
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429118
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429118
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429118
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131298419
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429118
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131298419
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429118
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131298419
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429103
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/sound_settings
D/dalvikvm( 5418): GC_CONCURRENT freed 2997K, 30% free 9565K/13540K, paused 6ms+6ms, total 43ms
D/dalvikvm( 5418): WAIT_FOR_CONCURRENT_GC blocked 37ms
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429103
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429100
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429100
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429099
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429099
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429109
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429100
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429113
I/DBG_WSS_LF( 5418): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429113
I/DBG_WSS_LF( 5418): [20.0040.140326][Line:27][<init>] First call
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429100
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 5163): Resource data:2131297804
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429100
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429155
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.users.UserOptions
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429055
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429055
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429055
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.LaunchApplication
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429054
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429054
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429055
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429055
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429055
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429080
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429151
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429151
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131296750
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429151
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429050
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/privacy_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429151
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/ActivityManager( 2418): Killing 4415:com.sec.android.app.msa/u0a23 (adj 15): empty #43
I/AMMetaDataParserService( 5163): Resource data:2131296750
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/security_settings_title
,I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429151
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131296750
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/security_settings_title
,I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429114
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429114
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131298587
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429114
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131298587
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429118
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429107
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/driving_mode
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429150
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429152
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429086
,I/DBG_WSS_LF( 5418): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED
I/DBG_WSS_LF( 5418): [20.0040.140326][Line:31][onReceive] *** boot complete ***
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131296695
I/DBG_WSS_LF( 5418): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429092
,I/DBG_WSS_LF( 5418): [20.0040.140326][Line:41][onReceive] nStatus : -1
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429152
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/development_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429150
,I/SELinux ( 5434): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5434):  
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/ActivityManager( 2418): Killing 4429:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
I/AMMetaDataParserService( 5163): Resource data:2131297938
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429150
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 5163): Resource data:2131297938
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429088
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429090
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDa,taParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429094
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 5163): Resource data:2131296695
W/jxcore-log( 5290): Platform android
W/jxcore-log( 5290): 
W/jxcore-log( 5290): Process ARCH arm
W/jxcore-log( 5290): 
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429148
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429148
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429046
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.AccountMenu
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429144
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.CryptKeeper
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429151
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429151
I/SELinux ( 5434): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5434):  
I/SELinux ( 5434):  
I/SELinux ( 5434): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
E/SELinux ( 5434): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
E/dalvikvm( 5434): >>>>> Normal User
I/AMMetaDataParserService( 5163): Resource data:2131429151
E/dalvikvm( 5434): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
E/SELinux ( 5434): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 5163): Resource data:2131429086
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429100
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid,
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429135
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429213
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429151
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429128
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429112
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429112
D/TimaKeyStoreProvider( 5434): in addTimaSignatureService
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 5163): getResourceTypeNameid,
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 5163): Resource data:2131299843
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/power_saving_mode_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429112
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429112
D/TimaKeyStoreProvider( 5434): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
D/ActivityThread( 5434): Added TimaKesytore provider
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429149
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/power_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429113
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 5163): getResour,ceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 5163): Resource data:1
W/ResourceType( 5163): No package identifier when getting name for resource number 0x00000001
W/System.err( 5163): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 5163): 	at android.content.res.Resources.getResourceName(Resources.java:2988)
W/System.err( 5163): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 5163): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 5163): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5163): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5163): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 5163): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429126
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 5163): Resource data:2131301070
,V/AlarmManager( 2418): waitForAlarm result :4
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429100
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 5163): Resource data:2131297804
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429130
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429120
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429121
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429133
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/,AMMetaDataParserService( 5163): Resource data:2131300118
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429123
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429187
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429124
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429218
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429155
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429126
I/jxcore-log( 5290): JXcore Cordova bridge is ready!
I/jxcore-log( 5290): 
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/pen_settings_menu
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
W/jxcore-log( 5290): JXcore engine is started
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429126
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429126
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429126
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/pen_settings_menu
I/Choreographer( 5290): Skipped 48 frames!  The application may be doing too much work on its main thread.
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.PhoneVibration
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$OneHandEditMenuActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429100
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/display_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429100
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429100
E/libGLESv2( 5290): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
E/libGLESv2( 5290): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/display_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429212
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429099
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 5163): Resource data:2131301505
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429130
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429130
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131302906
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429106
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2130838226
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 5163): getResourceTypeNamedrawable
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429143
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429136
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429136
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429104
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429139
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429140
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/easy_mode_app_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429080
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/location_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131302078
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429080
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131302078
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/myplace_title
,I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429080
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 5163): Resource data:2131302107
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429086
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
D/dalvikvm( 5434): GC_CONCURRENT freed 3001K, 30% free 9573K/13548K, paused 3ms+8ms, total 35ms
D/dalvikvm( 5434): WAIT_FOR_CONCURRENT_GC blocked 26ms
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429086
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429044
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/bua_plus
,E/jxcore-log( 5290): >> samsung-SM-G800F
E/jxcore-log( 5290): 
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429049
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/jxcore-log( 5290): Total memory 1319530496
I/jxcore-log( 5290): 
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/jxcore-log( 5290): Free memory 39882752
I/jxcore-log( 5290): 
I/AMMetaDataParserService( 5163): Resource data:2131429122
,I/jxcore-log( 5290): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5290): 
,I/jxcore-log( 5290): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5290): 
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/smart_screen
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131297804
,D/StatusChecker( 5434): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429078
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429131
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429131
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429122
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2130838278
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 5163): getResourceTypeNamedrawable
,I/jxcore-log( 5290): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5290): 
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2130838278
,I/jxcore-log( 5290): Size 720 1280
I/jxcore-log( 5290): 
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 5163): getResourceTypeNamedrawable
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429129
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429129
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 5163): Resource data:2131165371
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:xml/searchable
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/jxcore-log( 5290): Screen Brightness 134
I/jxcore-log( 5290): 
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429051
E/jxcore-log( 5290): Dummy Error Log.
E/jxcore-log( 5290): 
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429114
,I/SELinux ( 5449): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5449):  
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 5163): Resource data:2131298587
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 5163): getResourceTypeNamestring
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429125
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/ActivityManager( 2418): Killing 4446:com.android.onetimeinitializer/u0a28 (adj 15): empty #43
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,D/dalvikvm( 1921): GC_EXPLICIT freed 44K, 10% free 9502K/10524K, paused 3ms+3ms, total 33ms
,I/AMMetaDataParserService( 5163): Resource data:2131429185
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/active_key_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429147
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429147
I/SELinux ( 5449): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5449):  
I/SELinux ( 5449):  
,I/SELinux ( 5449): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/safetycare_settings
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
E/SELinux ( 5449): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 5163): Resource data:2131429203
E/dalvikvm( 5449): >>>>> Normal User
,E/dalvikvm( 5449): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10135 ]
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9502K/10524K, paused 2ms+3ms, total 27ms
I/AMMetaDataParserService( 5163): Resource data:2131429203
,E/SELinux ( 5449): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/safetycare_help
,I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429075
,I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429169
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429138
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2130838226
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 5163): getResourceTypeNamedrawable
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 5163): Resource data:2131429119
I/AMMetaDataParserService( 5163): getResourceName:com.android.settings:id/fingerprint_settings
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9502K/10524K, paused 2ms+3ms, total 27ms
I/AMMetaDataParserService( 5163): getResourceTypeNameid
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
,D/TimaKeyStoreProvider( 5449): in addTimaSignatureService
V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/TimaKeyStoreProvider( 5449): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5449): Added TimaKesytore provider
V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 5163): Resource data:2131034120
,I/AMMetaDataParserService( 5163): getResourceName:com.android.contacts:xml/searchable
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
,I/AMMetaDataParserService( 5163): Resource data:2131034113
I/AMMetaDataParserService( 5163): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
,D/        ( 5163): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 5163): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531,
,D/dalvikvm( 5449): GC_CONCURRENT freed 3006K, 30% free 9559K/13544K, paused 2ms+2ms, total 20ms,
,D/dalvikvm( 5449): WAIT_FOR_CONCURRENT_GC blocked 13ms,
,D/dalvikvm( 2721): GC_EXPLICIT freed 387K, 32% free 9918K/14440K, paused 4ms+7ms, total 51ms,
,D/QuickConnect( 5449): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED,
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
W/BackupManagerService( 2418): dataChanged but no participant pkg='com.android.providers.settings' uid=10135
,I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 7 sec,
,D/        ( 5163): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 5163): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528,
,D/        ( 5163): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 5163): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530,
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity,
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:assistant,
,I/AMMetaDataParserService( 5163): Resource data:2131034113
I/AMMetaDataParserService( 5163): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/dalvikvm( 2418): GC_EXPLICIT freed 3930K, 19% free 24514K/30044K, paused 6ms+16ms, total 187ms
,D/QuickConnect( 5449): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 5449): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,V/QuickConnect( 5449): SconnectManager.getInstance - () return existing instance null
,D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,W/ContextImpl( 5449): Implicit intents with startService are not safe: Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } android.content.ContextWrapper.startServiceAsUser:517 android.content.ContextWrapper.startServiceAsUser:517 com.samsung.android.sconnect.periph.PeriphStartReceiver.onReceive:30 
,I/QuickConnect( 5449): PeriphService.onCreate - [START]
,I/SELinux ( 5464): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5464):  
,I/QuickConnect( 5449): PeriphService.onCreate - [START] USER_OWNER
,D/QuickConnect( 5449): PeriphService.setProcessForeground - Build.VERSION.SDK_INT = 19
I/QuickConnect( 5449): PeriphService.setProcessForeground - true of JB_MR2 complete 
I/QuickConnect( 5449): PeriphService.setState - 0 >> 1
,V/QuickConnect( 5449): PeriphService.runService - 
,I/iu.UploadsManager( 3280): End new media; added: 0, uploading: 0, time: 360 ms
,I/QuickConnect[1.1][2] ( 5449): SconnectManager.SconnectManager - initiate from com.samsung.android.sconnect.periph.PeriphService@42254e78
,I/QuickConnect[1.1][2] ( 5449): SconnectManager.SconnectManager - set getApplicationContext android.app.Application@42243b58
,D/QuickConnect[1.1][2] ( 5449): SconnectManager.registerBroadcast - --
,D/QuickConnect[1.1][2] ( 5449): SconnectManager.SconnectManager - REQUEST_ID :  1
,D/QuickConnect[1.1][2] ( 5449): ScanThread.ScanThread - created!
,V/QuickConnect[1.1][2] ( 5449): BluetoothHelper.BluetoothHelper - 
,D/        ( 5163): PNG_doEncode true 106, 106,
I/SELinux ( 5464): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5464):  
I/SELinux ( 5464):  
,I/SELinux ( 5464): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5464): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5464): >>>>> Normal User
,E/dalvikvm( 5464): >>>>> com.sec.android.service.bezel [ userId:0 | appId:1000 ]
,E/SELinux ( 5464): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,I/AMMetaDataParserService( 5163): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530,
,D/TimaKeyStoreProvider( 5464): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 5464): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5464): Added TimaKesytore provider
,D/dalvikvm( 5163): GC_CONCURRENT freed 1882K, 19% free 12266K/15124K, paused 3ms+3ms, total 34ms
,I/AMMetaDataParserService( 5163): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 5163): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
,I/AMMetaDataParserService( 5163): Resource data:2131034112
,I/AMMetaDataParserService( 5163): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
,D/QuickConnect[1.1][2] ( 5449): BluetoothHelper.registerBluetoothAdapterReceiver - mIsBluetoothAdapterReceiver = false
,V/QuickConnect[1.1][2] ( 5449): BleHelper.BleHelper - Constructor
,I/jxcore-log( 5290): getBuffer is called!!!!
I/jxcore-log( 5290): 
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
,E/QuickConnect[1.1][2] ( 5449): BleHelper.startScan - not isGattServiceReady. Try to BLE On calling addLeRadioReference()
,D/BluetoothRadioManager( 5449): addLeRadioReference: Add CB  com.samsung.android.sconnect.common.net.BleHelper$GattServiceStateChangeCallback@42269710
D/BluetoothRadioManager( 5449):  addRadioReference enabled = false
,D/BluetoothRadioManager( 5449):  BLE Radio count is : 1
,D/BluetoothRadioManager( 5449): addRadioReference()  registerRadioClient mUUID = c1f1d22c-0d8c-4cf0-a73d-ca6877826c52
,D/        ( 5163): PNG_doEncode true 106, 106
D/BluetoothManagerService( 2418): foregroundUser: 0
,I/AMMetaDataParserService( 5163): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
,D/dalvikvm( 5464): GC_CONCURRENT freed 2996K, 30% free 9565K/13540K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 5464): WAIT_FOR_CONCURRENT_GC blocked 19ms
,E/BluetoothManagerService( 2418): Package is exist.
,D/BluetoothRadioManager( 5449): addLeRadioReference: isRadioEnabled() =  false
,V/QuickConnect[1.1][2] ( 5449): BleHelper.mSearchWearable - true
,I/bluedroid( 3999): update_radio_count
D/BluetoothAdapterState( 3999): CURRENT_STATE=ON, MSG = USER_TURN_ON_RADIO
I/BluetoothAdapterState( 3999): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=false
D/BluetoothAdapterState( 3999): CURRENT_STATE=PENDING, MSG = BEGIN_ENABLE_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
,I/bluedroid( 3999): enable
E/bt-btif ( 3999): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 3999): btif_sock_init, radio_req:1, rfc_init:1, vhci_init:1
,D/BluetoothAdapterState( 3999): CURRENT_STATE=PENDING, MSG = ENABLED_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
I/BluetoothAdapterState( 3999): Bluetooth adapter radio state changed: 14
D/BluetoothAdapterService( 3999): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3999): updateAdapterState state is 14
,D/BluetoothAdapterService( 3999): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3999): Autoconnection is available 
,D/BluetoothManagerService( 2418): Broadcasting Radio() to 1 Radio Mgr receivers.
D/BluetoothAdapterService( 3999): updateAdapterState prevState = 12newState = 14
,D/BluetoothRadioManager( 5449): onBTRadioStateChange:  up = true
,I/BluetoothAdapterState( 3999): Entering On State from state = 12
D/BezelQuickConnect( 5464): BezelBroadcastReceiver - onReceive : android.intent.action.BOOT_COMPLETED
,D/BezelQuickConnect( 5464): BezelBroadcastReceiver - StartBezelInteractionService
,D/BezelQuickConnect( 5464): BezelManagerService - setProcessForeground, Build.VERSION.SDK_INT = 19
,I/BezelQuickConnect( 5464): BezelManagerService - setProcessForeground, true of JB_MR2 complete 
D/BezelQuickConnect( 5464): BezelBroadcastReceiver - onReceive : Send to quickpanel - service.ENABLED
,E/QuickConnect[1.1][2] ( 5449): BleHelper.onGattServiceStateChange - up = true, BluetoothGatt is android.bluetooth.IBluetoothGatt$Stub$Proxy@422bbe00
,E/QuickConnect[1.1][2] ( 5449): BleHelper.onGattServiceStateChange - Radio turned on
,V/PhoneStatusBar( 2579): onReceive: Intent { act=com.sec.android.sconnect.service.ENABLED flg=0x10 }mQconnectEnable = true
,W/ContextImpl( 5464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.android.service.bezel.BezelBroadcastReceiver.onReceive:40 android.app.ActivityThread.handleReceiver:2698 
V/QuickConnect[1.1][2] ( 5449): UpnpHelper.UpnpHelper - 
,V/QuickConnect[1.1][2] ( 5449): JmdnsHelper.JmdnsHelper - Constructor
V/QuickConnect[1.1][2] ( 5449): P2pHelper.P2pHelper - EXEC
,D/STATUSBAR-PhoneStatusBar( 2579): showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
D/QuickConnect[1.1][2] ( 5449): p2pHelperWorkThread.p2pHelperWorkThread - created!
E/NetworkSettingsReceiver( 3229): onReceive: android.intent.action.BOOT_COMPLETED
D/QuickConnect[1.1][2] ( 5449): WifiHelper.WifiHelper -  -- 
D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
,I/QuickConnect[1.1][2] ( 5449): CentralActionManager.CentralActionManager - EXEC
,D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
V/QuickConnect[1.1][2] ( 5449): BluetoothOppActionHelper.BluetoothOppActionHelper - 
V/QuickConnect[1.1][2] ( 5449): GroupVoiceTalkActionHelper.GroupVoiceTalkActionHelper -  --
V/QuickConnect[1.1][2] ( 5449): SmartHomeActionHelper.SmartHomeActionHelper - --
V/QuickConnect[1.1][2] ( 5449): ScreenMirrorActionHelper.ScreenMirrorActionHelper - 
,V/QuickConnect[1.1][2] ( 5449): BluetoothActionHelper.BluetoothActionHelper - 
W/BroadcastQueue( 2418): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.android.calendar/.magazine.CalendarUpdateRelatedDataReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
,I/SELinux ( 5481): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5481):  
,E/BluetoothHeadset( 5449): BTStateChangeCB is registed
,E/BluetoothHeadset( 5449): BluetoothHeadset service is binded
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/QuickConnect[1.1][2] ( 5449): SconnectManager.getInstance - make new instance com.samsung.android.sconnect.SconnectManager@42257a20
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 5163): Resource data:Lo,op for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
I/AMMetaDataParserService( 5163): Resource data:2131034113
I/AMMetaDataParserService( 5163): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 5163): getResourceTypeNamexml
,V/QuickConnect[1.1][2] ( 5449): SconnectManager.getInstance - return existing instance com.samsung.android.sconnect.SconnectManager@42257a20
V/QuickConnect[1.1][2] ( 5449): PreDiscoveryHelper.PreDiscoveryHelper -  -- 
,D/QuickConnect[1.1][2] ( 5449): PreDiscoveryHelper.setVisibilityFromSystemDb - --
,D/QuickConnect[1.1][2] ( 5449): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,D/QuickConnect[1.1][2] ( 5449): Utils.getFromDb -  Key[quick_connect_contact_only], isEnabled [1] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 5449): PreDiscoveryHelper.setVisibilityFromSystemDb - isAllowToConnect : false, isContactOnly : true, visibilitySetting : 2
D/QuickConnect[1.1][2] ( 5449): PreDiscoveryHelper.changeResponseSetting - changed: 2
V/QuickConnect[1.1][2] ( 5449): PreDiscoveryHelper.updateAdvData - 
,V/QuickConnect[1.1][2] ( 5449): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42257a20
,D/QuickConnect[1.1][2] ( 5449): WifiHelper.isEnableMobileAP - HOTSPOT Disabled
,V/QuickConnect[1.1][2] ( 5449): PreDiscoveryHelper.updateRespTarget - 
,D/QuickConnect[1.1][2] ( 5449): PreDiscoveryHelper.initializeAdvData - 
,V/QuickConnect[1.1][2] ( 5449): PreDiscoveryHelper.initializeAdvData - name: S5mini-1(8)
D/QuickConnect[1.1][2] ( 5449): PreDiscoveryHelper.initializeAdvData - name selected: S5mini-1(8)
V/QuickConnect[1.1][2] ( 5449): CONTACT_Info.getMyMobileNumber - 
,D/        ( 5163): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 5163): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
I/SELinux ( 5481): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5481):  
I/SELinux ( 5481):  
,I/SELinux ( 5481): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5481): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5481): >>>>> Normal User
,E/dalvikvm( 5481): >>>>> com.sec.android.app.camera [ userId:0 | appId:10149 ]
,E/SELinux ( 5481): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/QuickConnect[1.1][2] ( 5449): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 5449): CONTACT_Info.getMyMobileNumber - null 
,D/TimaKeyStoreProvider( 5481): in addTimaSignatureService
,D/QuickConnect[1.1][2] ( 5449): NetUtil.getP2pMacFromWifiMac - ($)
,V/QuickConnect[1.1][2] ( 5449): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42257a20
W/QuickConnect[1.1][2] ( 5449): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.emeeting.b2c.hancom
,D/QuickConnect[1.1][2] ( 5449): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.emeeting
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
D/QuickConnect[1.1][2] ( 5449): AppPackageUtil.isStubApk - but Stub version[2.7.025] of com.samsung.groupcast
W/QuickConnect[1.1][2] ( 5449): AppPackageUtil.isAppInstalled - this is Stub - com.samsung.groupcast
,D/QuickConnect[1.1][2] ( 5449): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.samsung.groupcast
,D/TimaKeyStoreProvider( 5481): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5481): Added TimaKesytore provider
W/QuickConnect[1.1][2] ( 5449): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 5449): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 5449): PeriphService.registerUserReceiver - mIsUserReceiver == false
,I/QuickConnect[1.1][2] ( 5449): PeriphService.onStartCommand - USER_OWNER
,I/QuickConnect[1.1][2] ( 5449): PeriphService.onStartCommand - Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } flags[0] startId[1]
,I/QuickConnect[1.1][2] ( 5449): PeriphService.onStartCommand - Action: com.samsung.android.sconnect.periph.START_SERVICE
,D/QuickConnect[1.1][2] ( 5449): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,D/QuickConnect[1.1][2] ( 5449): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 5449): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/BluetoothA2dp( 5449): Proxy object connected
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,D/QuickConnect[1.1][2] ( 5449): A2dpProfile.onServiceConnected - Bluetooth service connected
D/WifiP2pService( 2418): InactiveState{ what=139287 }
D/WifiP2pService( 2418): P2pEnabledState{ what=139287 }
,D/WifiP2pService( 2418): DefaultState{ what=139287 }
D/QuickConnect[1.1][2] ( 5449): HeadsetProfile.onServiceConnected - Bluetooth service connected
D/BluetoothInputDevice( 5449): Proxy object connected
D/QuickConnect[1.1][2] ( 5449): HidProfile.onServiceConnected - Bluetooth service connected
D/QuickConnect[1.1][2] ( 5449): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 5163): Resource data:2131034116
I/AMMetaDataParserService( 5163): getResourceName:com.android.contacts:xml/findo_searchable
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 5163): Resource data:2131099668
D/dalvikvm( 5481): GC_CONCURRENT freed 2994K, 30% free 9566K/13540K, paused 3ms+3ms, total 27ms
,D/dalvikvm( 5481): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/dalvikvm( 5481): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,I/AMMetaDataParserService( 5163): getResourceName:com.sec.android.app.sbrowser:xml/searchable
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/AMMetaDataParserService( 5163): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 5163): Resource data:2131099650
,I/AMMetaDataParserService( 5163): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
D/PowerManagerService( 2418): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 2418): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2418): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/RampAnimator( 2418): Light Animator Finished currentValue=2
D/lights  ( 2418): lcd : 2 +
,D/        ( 5163): PNG_doEncode true 106, 106
,D/dalvikvm( 5290): GC_CONCURRENT freed 2379K, 25% free 10213K/13568K, paused 3ms+4ms, total 33ms
,D/lights  ( 2418): lcd : 2 -
,I/AMMetaDataParserService( 5163): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,I/QuickConnect[1.1][2] ( 5449): BleAdvertiser.BleAdvertiser - Constructor
,D/BluetoothGattServer( 5449): registerCallback()
,D/BluetoothGattServer( 5449): registerCallback() - UUID=579c497f-8d89-4850-8b5f-17f2f488a2db
,D/BtGatt.GattService( 3999): registerServer() - UUID=579c497f-8d89-4850-8b5f-17f2f488a2db
D/BtGatt.btif( 3999): btif_gatts_register_app
D/BtGatt.btif( 3999): btgatts_handle_event: Event 2000
E/bt-btif ( 3999): register application first_unuse rcb_idx = 0
D/BtGatt.btif( 3999): btapp_gatts_handle_cback: Event 0
,D/BtGatt.GattService( 3999): onServerRegistered() - UUID=579c497f-8d89-4850-8b5f-17f2f488a2db, serverIf=5
,D/BluetoothGattServer( 5449): onServerRegistered() - status=0 serverIf=5
,I/ActivityManager( 2418): Killing 4468:com.sec.pcw.device/1000 (adj 15): empty #43
V/QuickConnect[1.1][2] ( 5449): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5449): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5449): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42257a20
V/QuickConnect[1.1][2] ( 5449): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42257a20
V/QuickConnect[1.1][2] ( 5449): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5449): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42257a20
V/QuickConnect[1.1][2] ( 5449): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42257a20
V/QuickConnect[1.1][2] ( 5449): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42257a20
D/QuickConnect[1.1][2] ( 5449): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5449): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5449): BleHelper.startScan - shouldScanBleBg = false
D/QuickConnect[1.1][2] ( 5449): BleHelper.startScan - shouldScanBleFg = false
,I/SELinux ( 5497): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5497):  
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/        ( 5163): PNG_doEncode true 106, 106
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
I/AMMetaDataParserService( 5163): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
I/SELinux ( 5497): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5497):  
I/SELinux ( 5497):  
I/SELinux ( 5497): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5497): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5497): >>>>> Normal User
E/dalvikvm( 5497): >>>>> com.android.email [ userId:0 | appId:10157 ]
E/SELinux ( 5497): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 5163): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
,D/TimaKeyStoreProvider( 5497): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 5497): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard,
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts,
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
,D/ActivityThread( 5497): Added TimaKesytore provider
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAutoDiscover
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
,I/AMMetaDataParserService( 5163): Resource data:2131099667,
,I/AMMetaDataParserService( 5163): getResourceName:com.android.email:xml/email_assistant_menu,
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml,
,D/        ( 5163): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 5163): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559
,D/dalvikvm( 5497): GC_CONCURRENT freed 2991K, 30% free 9574K/13544K, paused 3ms+1ms, total 21ms,
,D/dalvikvm( 5497): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/        ( 5163): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 5163): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558,
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
D/dalvikvm( 5163): GC_FOR_ALLOC freed 1189K, 21% free 12104K/15256K, paused 47ms, total 49ms
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 8 sec
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 5163): Resource data:2131099689
I/AMMetaDataParserService( 5163): getResourceName:com.android.email:xml/spellscroll
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 5163): Resource data:2131099685
I/AMMetaDataParserService( 5163): getResourceName:com.android.email:xml/searchable
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
I/AMMetaDataParserService( 5163): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 5163): Resource data:Inside bundle  check
I/AMMetaDataParserService( 5163): getResourcePackageName:com.android.keyguard.layout
,I/AMMetaDataParserService( 5163): Resource data:2130903052
,I/AMMetaDataParserService( 5163): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
I/AMMetaDataParserService( 5163): getResourceTypeNamelayout
I/AMMetaDataParserService( 5163): getResourcePackageName:assistant
,I/AMMetaDataParserService( 5163): Resource data:2131034112
D/BadgeProvider( 4899): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/AMMetaDataParserService( 5163): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 5163): getResourceTypeNamexml
,D/BadgeProvider( 4899): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4899): sendNotify, [notify] : null
D/BadgeProvider( 4899): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4899): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4899): update, [UpdateCount] : 1
,D/Launcher.Model( 2786): reloadBadges entered.
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,W/ActivityManager( 2418): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/        ( 5163): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 5163): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
,I/SELinux ( 5521): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5521):  
,I/ActivityManager( 2418): Killing 4522:com.vlingo.midas/u0a34 (adj 15): empty #43
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 5163): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,I/ActivityManager( 2418): Killing 4565:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/SELinux ( 5521): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5521):  
I/SELinux ( 5521):  
,I/SELinux ( 5521): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5521): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5521): >>>>> Normal User
,E/dalvikvm( 5521): >>>>> com.android.exchange [ userId:0 | appId:10158 ]
,E/SELinux ( 5521): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/ActivityManager( 2418): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 5521): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5521): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5521): Added TimaKesytore provider
,I/Process ( 5497): Sending signal. PID: 5497 SIG: 9
,I/ActivityManager( 2418): Process com.android.email (pid 5497) (adj 9) has died.
,D/dalvikvm( 5521): GC_CONCURRENT freed 2995K, 30% free 9574K/13544K, paused 4ms+2ms, total 25ms
,D/dalvikvm( 5521): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/SELinux ( 5535): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5535):  
,I/SELinux ( 5539): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5539):  
,I/SELinux ( 5535): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5535):  
I/SELinux ( 5535):  
,I/SELinux ( 5535): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5535): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5535): >>>>> Normal User
,E/dalvikvm( 5535): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 5535): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5535): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5535): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5535): Added TimaKesytore provider
,I/SELinux ( 5539): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5539):  
I/SELinux ( 5539):  
,I/SELinux ( 5539): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5539): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5539): >>>>> Normal User
,E/dalvikvm( 5539): >>>>> com.android.email [ userId:0 | appId:10157 ]
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
E/SELinux ( 5539): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5539): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5539): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5539): Added TimaKesytore provider
,I/ActivityManager( 2418): Killing 4765:com.policydm/1000 (adj 15): empty #43
,D/dalvikvm( 5535): GC_CONCURRENT freed 2999K, 30% free 9568K/13544K, paused 8ms+2ms, total 41ms
,D/dalvikvm( 5535): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 5539): GC_CONCURRENT freed 2985K, 30% free 9578K/13540K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 5539): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/SELinux ( 5561): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5561):  
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
I/ActivityManager( 2418): Killing 4749:com.google.android.apps.magazines/u0a115 (adj 15): empty #43
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,I/SELinux ( 5561): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5561):  
I/SELinux ( 5561):  
,I/SELinux ( 5561): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5561): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5561): >>>>> Normal User
,E/dalvikvm( 5561): >>>>> com.sec.modem.settings [ userId:0 | appId:1000 ]
,E/SELinux ( 5561): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5561): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5561): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5561): Added TimaKesytore provider
,I/Process ( 5521): Sending signal. PID: 5521 SIG: 9
,I/ActivityManager( 2418): Process com.android.exchange (pid 5521) (adj 9) has died.
D/BadgeProvider( 4899): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2786): reloadBadges entered.
D/BadgeProvider( 4899): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4899): sendNotify, [notify] : null
D/BadgeProvider( 4899): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4899): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4899): update, [UpdateCount] : 1
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/dalvikvm( 5561): GC_CONCURRENT freed 2995K, 30% free 9565K/13540K, paused 4ms+2ms, total 41ms
,D/dalvikvm( 5561): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/SELinux ( 5580): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5580):  
W/ActivityManager( 2418): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5580): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5580):  
I/SELinux ( 5580):  
,I/SELinux ( 5580): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5580): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5580): >>>>> Normal User
,E/dalvikvm( 5580): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 5580): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 9 sec
,D/TimaKeyStoreProvider( 5580): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5580): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5580): Added TimaKesytore provider
,D/dalvikvm( 5580): GC_CONCURRENT freed 3011K, 30% free 9558K/13548K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 5580): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/NotiRemoteService( 5580): action com.peel.widget.notification.SETUP_SERVICE_CONNECTION
,D/NotiRemoteService( 5580): connectToPeelService 0
,I/SELinux ( 5599): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5599):  
,W/ContextImpl( 5580): Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:529 tv.peel.samsung.widget.a.c.<init>:68 tv.peel.samsung.widget.NotiRemoteService.a:554 
,D/SensorService( 2418):   0.3 0.0 9.8
,D/NotiRemoteService( 5580): onServiceOn() mServiceState = 1
D/NotiRemoteService( 5580): Send action to self com.peel.widget.notification.SERVICE_BINDED
D/NotiRemoteService( 5580): action com.peel.widget.notification.SERVICE_BINDED
D/NotiRemoteService( 5580): feature is Off. Stop service
,D/NotiRemoteService( 5580): Send action to self com.peel.widget.notification.STOP_PROCESS
,D/NotiRemoteService( 5580): action com.peel.widget.notification.STOP_PROCESS
,D/NotiRemoteService( 5580): onDestroy()
,D/NotiRemoteService( 5580): mOrientationChangeReceier was not registered
,I/SELinux ( 5599): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5599):  
I/SELinux ( 5599):  
,I/SELinux ( 5599): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5599): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5599): >>>>> Normal User
,E/dalvikvm( 5599): >>>>> org.simalliance.openmobileapi.service [ userId:0 | appId:1101 ]
,E/SELinux ( 5599): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5599): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5599): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5599): Added TimaKesytore provider
,D/dalvikvm( 5599): GC_CONCURRENT freed 2997K, 30% free 9566K/13540K, paused 4ms+2ms, total 24ms
,D/dalvikvm( 5599): WAIT_FOR_CONCURRENT_GC blocked 19ms
,V/SmartcardService( 5599): main Received broadcast
,V/SmartcardService( 5599): Starting smartcard service after boot completed
,I/ActivityManager( 2418): Killing 4816:com.osp.app.signin/u0a44 (adj 15): empty #43
,I/SELinux ( 5612): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5612):  
,I/SELinux ( 5612): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5612):  
I/SELinux ( 5612):  
,I/SELinux ( 5612): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5612): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5612): >>>>> Normal User
,E/dalvikvm( 5612): >>>>> com.sec.android.app.sysscope [ userId:0 | appId:1000 ]
,E/SELinux ( 5612): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5612): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5612): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5612): Added TimaKesytore provider
,D/dalvikvm( 5612): GC_CONCURRENT freed 3007K, 30% free 9558K/13544K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 5612): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/ContextImpl( 5612): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 5625): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5625):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 10% free 9502K/10524K, paused 4ms+5ms, total 47ms,
,I/SELinux ( 5625): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5625):  
I/SELinux ( 5625):  
,I/SELinux ( 5625): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5625): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5625): >>>>> Normal User
,E/dalvikvm( 5625): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 5625): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9502K/10524K, paused 3ms+4ms, total 41ms
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
D/TimaKeyStoreProvider( 5625): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5625): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5625): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9502K/10524K, paused 3ms+4ms, total 33ms
,D/dalvikvm( 5625): GC_CONCURRENT freed 3005K, 30% free 9559K/13544K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 5625): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/SELinux ( 5637): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5637):  
I/ActivityManager( 2418): Killing 4281:com.android.chrome/u0a85 (adj 15): empty #43
,I/SELinux ( 5637): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5637):  
I/SELinux ( 5637):  
,I/SELinux ( 5637): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5637): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5637): >>>>> Normal User
,E/dalvikvm( 5637): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 5637): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5637): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5637): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5637): Added TimaKesytore provider
,I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 10 sec
,D/dalvikvm( 5637): GC_CONCURRENT freed 2990K, 30% free 9576K/13544K, paused 4ms+2ms, total 32ms
,D/dalvikvm( 5637): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/Intent to TravelDirActivity( 5637): inside TravelBroadcastReceiver
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,I/SELinux ( 5650): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5650):  
I/ActivityManager( 2418): Killing 4864:com.android.mms/u0a49 (adj 15): empty #43
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/CountryDetector( 2418): No listener is left
,I/SELinux ( 5650): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5650):  
I/SELinux ( 5650):  
,I/SELinux ( 5650): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5650): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5650): >>>>> Normal User
,E/dalvikvm( 5650): >>>>> com.sec.android.daemonapp [ userId:0 | appId:10173 ]
,E/SELinux ( 5650): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5650): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5650): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5650): Added TimaKesytore provider
,D/dalvikvm( 5650): GC_CONCURRENT freed 2994K, 30% free 9578K/13548K, paused 3ms+2ms, total 27ms,
,D/dalvikvm( 5650): WAIT_FOR_CONCURRENT_GC blocked 24ms,
,D/comsamsungapp( 5650): [MSC_Daemon]>>> KWCP:218 [0:0] KWeather Provider Created,
,D/comsamsungapp( 5650): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62,
,D/comsamsungapp( 5650): [MSC_Daemon]>>> WCP:1080 [0:0] Provider Created,
,D/comsamsungapp( 5650): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62,
D/comsamsungapp( 5650): [MSC_Daemon]>>> CCP:223 [0:0] CmaWeather Provider Created
,D/comsamsungapp( 5650): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5650): [MSC_Daemon]>>> WNCP:204 [0:0] WeatherNewsJP Provider Created
,D/comsamsungapp( 5650): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5650): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/comsamsungapp( 5650): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/comsamsungapp( 5650): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 5650): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,D/comsamsungapp( 5650): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionBOOT_COMPLETED, run:false
,D/comsamsunglog( 5650): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5650): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5650): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5650): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5650): [MSC_Daemon]>>> WDSM:48 [0:0] WeatherClockService start : 
,D/daemonapp( 5650): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5650): [MSC_Daemon]>>> WDSM:87 [0:0] ABOOTCOPLD
,W/BackupManagerService( 2418): dataChanged but no participant pkg='com.android.providers.settings' uid=10173
D/daemonapp( 5650): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5650): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5650): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5650): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5650): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5650): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5650): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5650): [MSC_Daemon]>>> WU:1761 [0:0] [boot]now           :1450199049451
,D/daemonapp( 5650): [MSC_Daemon]>>> WU:1762 [0:0] [boot]NUT :1450210920000
D/daemonapp( 5650): [MSC_Daemon]>>> WU:1763 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 5650): [MSC_Daemon]>>> WU:1764 [0:0] [boot]NUT - now :true
,D/daemonapp( 5650): [MSC_Daemon]>>> WDBH:2157 [0:0] ud NT1450210920000
,D/daemonapp( 5650): [MSC_Daemon]>>> WCP:1212 [0:0] cp update : count : 1, pt : 8
,D/daemonapp( 5650): [MSC_Daemon]>>> WU:1774 [0:0] Boot set AR_nexttime :1450210920000
,D/daemonapp( 5650): [MSC_Daemon]>>> WCS:40 [0:0] onStartcommand()
,D/daemonapp( 5650): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5650): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5650): [MSC_Daemon]>>> WCS:63 [0:0] CP Name cp_eng
,D/daemonapp( 5650): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 2418): GC_EXPLICIT freed 1251K, 19% free 24392K/30044K, paused 8ms+14ms, total 213ms
,D/daemonapp( 5650): [MSC_Daemon]>>> WCS:82 [0:0] td null
,D/comdaemonstockapp( 5650): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 5650): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/SELinux ( 5665): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5665):  
,I/SELinux ( 5665): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5665):  
I/SELinux ( 5665):  
,I/SELinux ( 5665): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5665): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5665): >>>>> Normal User
,E/dalvikvm( 5665): >>>>> com.gameloft.android.GloftGF2H [ userId:0 | appId:10179 ]
,E/SELinux ( 5665): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5665): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5665): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5665): Added TimaKesytore provider
,I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 11 sec
,D/dalvikvm( 5665): GC_CONCURRENT freed 2998K, 30% free 9566K/13540K, paused 3ms+2ms, total 34ms
,D/dalvikvm( 5665): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/SELinux ( 5678): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5678):  
,I/ActivityManager( 2418): Killing 4903:com.sec.android.app.safetyassurance/u0a51 (adj 15): empty #43
,I/SELinux ( 5678): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5678):  
I/SELinux ( 5678):  
,I/SELinux ( 5678): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5678): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5678): >>>>> Normal User
,E/dalvikvm( 5678): >>>>> com.gameloft.android.GloftKLMF [ userId:0 | appId:10180 ]
,E/SELinux ( 5678): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5678): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5678): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5678): Added TimaKesytore provider
,D/dalvikvm( 5678): GC_CONCURRENT freed 3002K, 30% free 9568K/13544K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 5678): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/SELinux ( 5691): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5691):  
I/ActivityManager( 2418): Killing 4930:com.android.settings/1000 (adj 15): empty #43
,I/SELinux ( 5691): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5691):  
I/SELinux ( 5691):  
,I/SELinux ( 5691): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5691): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5691): >>>>> Normal User
,E/dalvikvm( 5691): >>>>> com.gameloft.android.GloftPSHU [ userId:0 | appId:10181 ]
,E/SELinux ( 5691): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5691): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5691): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5691): Added TimaKesytore provider
,D/dalvikvm( 5691): GC_CONCURRENT freed 3006K, 30% free 9561K/13544K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 5691): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/SELinux ( 5704): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5704):  
,I/ActivityManager( 2418): Killing 4954:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 5704): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5704):  
I/SELinux ( 5704):  
,I/SELinux ( 5704): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5704): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5704): >>>>> Normal User
,E/dalvikvm( 5704): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 5704): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5704): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5704): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5704): Added TimaKesytore provider
,D/dalvikvm( 5704): GC_CONCURRENT freed 3002K, 30% free 9569K/13548K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 5704): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/dalvikvm( 5704): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 5704): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x0008
,D/BluetoothAdapterService(1109640352)( 3999): unRegister RemoteMessageListener
,D/HeadsetService( 3999): registerMessageListener
D/HeadsetStateMachine( 3999): Disconnected process message: 80
,D/HeadsetStateMachine( 3999): processUnRegisterMessageListener : 2
D/BluetoothAdapterState( 3999): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,I/BluetoothAdapterState( 3999): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3999): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3999): updateAdapterState state is 13
,I/WifiManager( 5290): packageName : com.example.hello
,I/WifiManager( 5290): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=5290, uid=10549
,I/BluetoothPbapService( 3999): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 3999): Broadcasting updateAdapterState() to 1 receivers.
,E/bt-btif ( 3999): bta_jv_rfcomm_stop_server
D/BluetoothAdapterService( 3999): Autoconnection is available 
,D/BluetoothAdapterService( 3999): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 3999): terminating service from this receiver
,W/ContextImpl( 3999): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
W/InputMethodManagerService( 2418): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2418): [BT Setting State] State =13
,D/PhoneApp( 2751): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,I/SamsungIME( 2959): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,E/bt-btif ( 3999): bta_jv_rfcomm_stop_server
,I/QuickConnect[1.1][2] ( 5449): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
,I/jxcore-log( 5290): ****TEST TOOK:  5251  ms ****
I/jxcore-log( 5290): 
,I/jxcore-log( 5290): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5290): 
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
I/BluetoothAdapterState( 3999): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterState( 3999): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(336), More:false, Req:false Child:2
E/bt-btif ( 3999): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 3999): cmd socket is not created
D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3965): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3965): wlan0: Setting scan request: 0 sec 0 usec
,W/Settings( 2418): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3965): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2418): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2418): InactiveState{ what=143375 }
D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/dalvikvm( 5704): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
D/dalvikvm( 5704): VFY: replacing opcode 0x22 at 0x0000
D/CommandListener( 1915): Clearing all IP addresses on wlan0
,D/IOP_DB_BT( 3999): db_close: nbr users 0
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,D/IOP_DB_BT( 3999): db_close: free database
D/ConnectivityService( 2418): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2418): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2418): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2418): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2418): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2418): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2418): Attempting to switch to mobile
,D/ConnectivityService( 2418): Attempting to switch to BLUETOOTH_TETHER
E/WifiStateMachine( 2418): Error! unhandled message{ when=-5ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 2418): InactiveState{ what=131204 }
D/WifiP2pService( 2418): P2pEnabledState{ what=131204 }
D/STATUSBAR-IconMerger( 2579): checkOverflow(384), More:false, Req:false Child:2
,I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 12 sec
,D/WifiP2pService( 2418): sending p2p connection changed broadcast: FAILED
,W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2418): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2418): onP2pDisconnected
D/IpRemoteDisplayController( 2418): disconnectWfdBridgeServer
,D/QuickConnect[1.1][2] ( 5449): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/IpRemoteDisplayController( 2418): WfdBridgeServer is already null
D/QuickConnect[1.1][2] ( 5449): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,E/WifiStateMachine( 2418): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/QuickConnect[1.1][2] ( 5449): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
D/QuickConnect[1.1][2] ( 5449): P2pHelper.cancelConnectPeer -  mTargetList clear all 
,D/QuickConnect[1.1][2] ( 5449): P2pHelper.removeP2pConfirm - skip: false
D/WifiDisplayController( 2418): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 2418): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2418): disconnect
D/WifiDisplayController( 2418): updateConnection
D/WifiDisplayController( 2418): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/QuickConnect[1.1][2] ( 5449): CentralActionManager.removeHoldingIntentAll - all request done.
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 5449): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiP2pService( 2418): sending p2p connection changed broadcast: DISCONNECTED
W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiP2pService( 2418): P2pDisablingState
D/WifiP2pService( 2418): P2pDisablingState{ what=139287 }
,D/WifiP2pService( 2418): DefaultState{ what=139287 }
,W/NetworkManagementService( 2418): route cmd failed: 
W/NetworkManagementService( 2418): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '33 route del src v6 2' failed with '400 33 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2418): '
W/NetworkManagementService( 2418): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2418): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2418): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2418): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2418): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2418): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/QuickConnect[1.1][2] ( 5449): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
D/WifiDisplayController( 2418): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2418): onP2pDisconnected
D/IpRemoteDisplayController( 2418): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 2418): WfdBridgeServer is already null
D/WifiP2pService( 2418): P2pDisablingState{ what=147458 }
D/WifiP2pService( 2418): p2p socket connection lost
,D/WifiP2pService( 2418): P2pDisabledState
D/QuickConnect[1.1][2] ( 5449): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 5449): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/WifiP2pService( 2418): P2pDisabledState{ what=139376 }
,D/QuickConnect[1.1][2] ( 5449): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService( 2418): DefaultState{ what=139376 }
E/WifiP2pService( 2418): Unhandled message { what=139376 }
D/WifiP2pService( 2418): P2pDisabledState{ what=139287 }
,D/WifiP2pService( 2418): DefaultState{ what=139287 }
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
E/dalvikvm( 5704): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
D/dalvikvm( 5704): VFY: replacing opcode 0x22 at 0x0037
D/BluetoothAdapterState( 3999): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 3999): isSecureModeOn:false
W/BluetoothAdapterService( 3999): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3999): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3999): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3999): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/HeadsetService( 3999): Received stop request...Stopping profile...
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,D/NetUtils( 2418): android_net_utils_resetConnections in env=0x782cd250 clazz=0x4ce00001 iface=wlan0 mask=0x3
,D/ConnectivityService( 2418): resetConnections(wlan0, 3)
D/QuickConnect[1.1][2] ( 5449): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
W/BluetoothAdapterService( 3999): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3999): Not skipping com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3999): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 3999): Not skipping com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 3999): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 3999): Not skipping com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 3999): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 3999): Not skipping com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 3999): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3999): Not skipping com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3999): check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 3999): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 3999): Stopping profile services that were post enabled
,D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3999): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHeadsetServiceJni( 3999): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3999): Cleaning up Bluetooth Handsfree callback object
,D/A2dpService( 3999): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3999): Exit Disconnected: -1
,D/MediaFocusControl( 2418): <<< unregisterRemoteControlDisplay
,D/Avrcp   ( 3999): Unregistering previous receiver
,D/BluetoothA2dp( 2418): Proxy object disconnected
D/BluetoothA2dp( 5449): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 5449): A2dpProfile.onServiceConnected - Bluetooth service disconnected
D/HidService( 3999): Received stop request...Stopping profile...
,D/HidService( 3999): Stopping Bluetooth HidService
D/BluetoothInputDevice( 5449): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 5449): HidProfile.onServiceDisconnected - Bluetooth service disconnected
,D/HealthService( 3999): Received stop request...Stopping profile...
,D/PanService( 3999): Received stop request...Stopping profile...
,D/BluetoothPan( 2418): BluetoothPAN Proxy object disconnected
,D/BluetoothMapService( 3999): Received stop request...Stopping profile...
D/SapService( 3999): Received stop request...Stopping profile...
,D/SapService( 3999): Stopping Bluetooth SapService
D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3999): Profile still running: com.broadcom.bt.service.sap.SapService
,I/GKI_LINUX( 3999): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3999): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 3999): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3999): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHidServiceJni( 3999): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 3999): Cleaning up Bluetooth GID callback object
D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3999): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHealthServiceJni( 3999): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 3999): Cleaning up Bluetooth Health object
,D/BluetoothA2dp( 4159): Proxy object disconnected
D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3999): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 3999): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3999): Cleaning up Bluetooth PAN callback object
D/BtSettings.ProfileConfig( 3999): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3999): Profile still running: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3999): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
W/BluetoothSAPServiceJni( 3999): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,W/BluetoothSAPServiceJni( 3999): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterState( 3999): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 3999): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3999): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3999): updateAdapterState state is 10
,D/BluetoothAdapterService( 3999): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothInputDevice( 5449): onBluetoothStateChange: up=false
D/BluetoothAdapterService( 3999): Autoconnection is available 
D/BluetoothAdapterService( 3999): updateAdapterState prevState = 13newState = 10
,I/BluetoothAdapterState( 3999): Entering OffState
,D/BluetoothA2dp( 5449): onBluetoothStateChange: up=false
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothA2dp( 2418): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 4159): onBluetoothStateChange: up=false
,W/InputMethodManagerService( 2418): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2418): [BT Setting State] State =10
,I/InputMethodManagerService( 2418): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/PhoneApp( 2751): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
,I/SamsungIME( 2959): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/QuickConnect[1.1][2] ( 5449): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
,D/WifiNative( 2418): callSECApiBoolean - ID [13]
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,I/wpa_supplicant( 3965): USE_NETWORK : USE_NETWORK OFF
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-8ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-9ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-3ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,W/dalvikvm( 5704): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5704): Link of class 'Ldqp;' failed
,W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 5704): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5704): Link of class 'Ldqp;' failed
I/dalvikvm( 5704): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x0000
,D/AndroidRuntime( 5719): 
D/AndroidRuntime( 5719): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5719): CheckJNI is OFF
,D/AndroidRuntime( 5719): setted country_code = Poland
,D/AndroidRuntime( 5719): setted countryiso_code = PL
D/AndroidRuntime( 5719): setted sales_code = PLS
D/AndroidRuntime( 5719): readGMSProperty: start
,D/AndroidRuntime( 5719): readGMSProperty: already setted!!
D/AndroidRuntime( 5719): readGMSProperty: end
,D/AndroidRuntime( 5719): addProductProperty: start
,E/dalvikvm( 5704): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 5704): VFY: replacing opcode 0x22 at 0x0000
W/dalvikvm( 5704): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5704): Link of class 'Ldqp;' failed
,W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 5704): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5704): Link of class 'Ldqp;' failed
I/dalvikvm( 5704): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x0008
,D/dalvikvm( 5719): Trying to load lib libjavacore.so 0x0
E/dalvikvm( 5704): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 5704): VFY: replacing opcode 0x1c at 0x0026
,D/dalvikvm( 5719): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5719): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5719): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5719): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,W/dalvikvm( 5704): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5704): Link of class 'Ldqp;' failed
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 5704): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5704): Link of class 'Ldqp;' failed
I/dalvikvm( 5704): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 5704): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 5704): Link of class 'Lax;' failed
E/dalvikvm( 5704): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 5704): VFY: replacing opcode 0x22 at 0x0006,
W/dalvikvm( 5704): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 5704): Link of class 'Laz;' failed
,E/dalvikvm( 5704): Could not find class 'az', referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 5704): VFY: replacing opcode 0x22 at 0x002c,
I/dalvikvm( 5704): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x0008,
D/Tethering( 2418): interfaceLinkStateChanged p2p0, true
D/Tethering( 2418): interfaceStatusChanged p2p0, true,
,I/wpa_supplicant( 3965): p2p0: CTRL-EVENT-TERMINATING 
D/BluetoothTethering( 2418): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering( 2418): attempted to stop reverse tether with nothing tethered
D/Tethering( 2418): interfaceLinkStateChanged p2p0, false
,D/Tethering( 2418): interfaceStatusChanged p2p0, false
,V/NetworkStats( 2418): updateIfacesLocked()
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,V/NetworkStats( 2418): performPollLocked(flags=0x1),
I/dalvikvm( 5704): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x000c,
,I/dalvikvm( 5704): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x0006
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit,
,V/NetworkStats( 2418): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/dalvikvm( 5704): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 5704): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 5704): VFY: replacing opcode 0x72 at 0x0000
I/wpa_supplicant( 3965): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/dalvikvm( 5704): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 5704): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 5704): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
D/dalvikvm( 5704): VFY: replacing opcode 0x72 at 0x0000
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
D/Tethering( 2418): interfaceStatusChanged wlan0, true
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
D/Tethering( 2418): interfaceStatusChanged wlan0, true
W/dalvikvm( 5704): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 5704): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 5704): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
D/dalvikvm( 5704): VFY: replacing opcode 0x23 at 0x0005
,V/NetworkStats( 2418): performPollLocked() took 32ms
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
I/dalvikvm( 5704): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 5704): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x0009
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,W/dalvikvm( 5704): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 5704): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 5704): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 5704): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 5704): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 5704): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 5704): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 5704): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 5704): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5704): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5704): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 5704): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 5704): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
D/dalvikvm( 5704): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 5704): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
D/dalvikvm( 5704): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 5704): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 5704): Link of class 'Lax;' failed
D/dalvikvm( 5704): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 5704): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 5704): Link of class 'Laz;' failed
D/dalvikvm( 5704): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
D/dalvikvm( 5704): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
D/dalvikvm( 5704): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
D/Tethering( 2418): interfaceStatusChanged wlan0, true
D/dalvikvm( 5704): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42249a88
D/dalvikvm( 5704): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42249a88
E/memtrack( 5719): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5719): failed to load memtrack module: -2
D/SensorService( 2418):   0.3 -0.0 9.9
D/dalvikvm( 5719): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/dalvikvm( 5704): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 5704): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x0076
I/Babel_SMS( 5704): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5704): MmsConfig.loadMmsSettings
I/Babel_SMS( 5704): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
I/Babel_SMS( 5704): MmsConfig.loadFromDatabase
I/wpa_supplicant( 3965): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering( 2418): interfaceLinkStateChanged wlan0, false
D/Tethering( 2418): interfaceStatusChanged wlan0, false
D/Tethering( 2418): InitialState.processMessage what=4
E/Tethering( 2418): No numeric data
D/Tethering( 2418): sendTetherStateChangedBroadcast 0, 0, 0
I/ConnectivityService( 2418): defaultVal : 1, tetherEnabledInSettings : true
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): performPollLocked(flags=0x1)
D/WifiStateMachine( 2418): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): performPollLocked() took 18ms
D/AndroidRuntime( 5719): Calling main entry com.android.commands.pm.Pm
E/Babel_SMS( 5704): canonicalizeMccMnc: invalid mccmnc 
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/Babel_SMS( 5704): MmsConfig.loadFromResources
E/Babel_SMS( 5704): canonicalizeMccMnc: invalid mccmnc nullnull
W/Settings( 2733): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_SMS( 5704): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/PackageManager( 2418): START PACKAGE DELETE: observer{1122058688}
D/PackageManager( 2418): pkg{<packageName>}
D/PackageManager( 2418): user{0}
D/PackageManager( 2418): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2418): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2418): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2418): deletePackageX- pkg:com.example.hello, userId:0
D/PackageManager( 2418): [MSG] DELETE_PACKAGE_AS_USER
W/dalvikvm( 5704): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 5704): Link of class 'Lfzc;' failed
E/dalvikvm( 5704): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 5704): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
D/dalvikvm( 5704): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 5704): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 5704): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
D/dalvikvm( 5704): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 5704): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 5704): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 5704): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 5704): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 5704): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 5704): Link of class 'Lfzc;' failed
D/PackageManager( 2418): !@killApplicatoin: 10549, uninstall pkg
I/ActivityManager( 2418): Killing 5290:com.example.hello/u0a549 (adj 0): stop com.example.hello
D/dalvikvm( 5704): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
I/SurfaceFlinger( 1920): id=17 Removed NainActivit (8/9)
I/SurfaceFlinger( 1920): id=17 Removed NainActivit (-2/9)
I/WindowState( 2418): WIN DEATH: Window{43137b20 u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger( 1920): id=17 Removed NainActivit (-2/9)
D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
D/dalvikvm( 5704): GC_CONCURRENT freed 1761K, 21% free 10873K/13608K, paused 2ms+3ms, total 33ms
W/PackageSettings( 2418): Skipping PackageSetting{429f1848 com.test.thalitest/10548} due to missing metadata
D/PackageManager( 2418): checkUidPermission - Execution time: 130 ms
D/PackageManager( 2418): queryIntentReceivers - Execution time: 134 ms
W/ServiceManager( 2418): Permission failure: com.samsung.permission.SSENSOR from uid=10109 pid=5704
D/PermissionCache( 2418): checking com.samsung.permission.SSENSOR for uid=10109 => denied (129750 us)
E/SensorService( 2418): Permission Denial : SEC Private Sensor 
E/SensorService( 2418): Permission Denial : SEC Private Sensor 
W/ActivityManager( 2418): Force removing ActivityRecord{433acf30 u0 com.example.hello/.MainActivity t3}: app died, no saved state
I/SurfaceFlinger( 1920): id=15 Removed EimLayer (6/8)
I/SurfaceFlinger( 1920): id=14 Removed EimLayer (5/7)
I/SurfaceFlinger( 1920): id=15 Removed EimLayer (-2/7)
I/SurfaceFlinger( 1920): id=14 Removed EimLayer (-2/7)
D/PackageManager( 2418): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10549, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/WifiStateMachine( 2418): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
I/SQLiteSecureOpenHelper( 4159): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4159): getDatabaseLocked(b,b,pwd)...
D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2418): mDVFSHelper.acquire()
V/WindowOrientationListener( 2418): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 2418): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 2418): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
D/Launcher( 2786): onRestart, Launcher: 1113657800
D/Launcher( 2786): onStart, Launcher: 1113657800
D/Launcher.HomeView( 2786): onStart
D/Launcher( 2786): onResume, Launcher: 1113657800
D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/Launcher.HomeView( 2786): onResume
D/StatusBarManagerService( 2418): semi p:2786,o:f
D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2418): tr p:2786,o:f
D/StatusBarManagerService( 2418): semi p:2786,o:f
W/Settings( 5704): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PackageManager( 2418): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10549, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/Babel_Crash( 5704): startup - clean
D/Tethering( 2418): Tethering got CONNECTIVITY_ACTION
D/Tethering( 2418): MasterInitialState.processMessage what=3
I/ApplicationPolicy( 2418): updateDataUsageMap
D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
I/DBG_DM  ( 4966): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
D/CaptivePortalTracker( 2418): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2418): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/dalvikvm( 2973): GC_EXPLICIT freed 1425K, 26% free 10067K/13540K, paused 3ms+6ms, total 54ms
I/FPMS_FingerprintManagerService( 2599): onReceive: android.intent.action.PACKAGE_REMOVED
E/SamsungIME( 2959): mOCRHelper is null
W/GeofencerStateMachine( 2733): Ignoring removeGeofence because network location is disabled.
I/InputReader( 2418): Reconfiguring input devices.  changes=0x00000010
D/QuickConnect[1.1][2] ( 5449): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.example.hello
I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 13 sec
D/MenuAppsGridFragment( 2786): onResume
I/SurfaceFlinger( 1920): id=18 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/RegisteredServicesCache( 2761): empty dynamic service
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "sms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2418): tr p:2786,o:f
D/StatusBarManagerService( 2418): semi p:2786,o:f
D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "smsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/dalvikvm( 5704): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 5704): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x000d
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "mms"
D/dalvikvm( 5704): GC_CONCURRENT freed 906K, 14% free 11992K/13896K, paused 7ms+4ms, total 95ms
D/dalvikvm( 5704): WAIT_FOR_CONCURRENT_GC blocked 54ms
I/Babel   ( 5704): deleted: false for 0
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "mmsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "sms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2761): GC_CONCURRENT freed 1185K, 27% free 10638K/14436K, paused 7ms+2ms, total 56ms
D/dalvikvm( 2761): WAIT_FOR_CONCURRENT_GC blocked 34ms
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "smsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2418): PackageReceiver onReceive()
I/HarmonyEASService( 2418): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/dalvikvm( 5704): GC_FOR_ALLOC freed 983K, 19% free 12235K/14976K, paused 59ms, total 59ms
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "mms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "mmsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 5704): GC_FOR_ALLOC freed 1467K, 20% free 13006K/16256K, paused 24ms, total 24ms
D/dalvikvm( 2418): GC_EXPLICIT freed 2356K, 18% free 24652K/30044K, paused 6ms+21ms, total 372ms
D/PackageManager( 2418): delete sourFile : 
W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2418): Got RemoteException sending setActive(false) notification to pid 5290 uid 10549
D/PackageManager( 2418): delete native library directory: 
D/PackageManager( 2418): return delete result to caller: 1122058688
D/PackageManager( 2418): returnCode: 1
D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@4
D/AndroidRuntime( 5719): Shutting down VM
W/ActivityManager( 2418): mDVFSHelper.release()
D/dalvikvm( 5719): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 4ms
D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 5704): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 5704): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 5704): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 5704): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
D/dalvikvm( 5704): VFY: replacing opcode 0x22 at 0x0071
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
D/EnterpriseDeviceManagerService( 2418): Package has changed for user 0
E/dalvikvm( 5704): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 5704): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
D/dalvikvm( 5704): VFY: replacing opcode 0x1f at 0x0021
W/dalvikvm( 5704): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
D/dalvikvm( 5704): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "sms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "smsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 2418): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 2418): removePackageParticipantsLocked: uid=10549 #1
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "mms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "mmsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/display ( 1920): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(4)
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PowerManagerService( 2418): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2418): Nap time...
,D/PowerManagerService( 2418): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2418): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2418): Going to sleep due to screen timeout...
,D/PowerManagerService( 2418): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2418): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2418): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/DisplayPowerController( 2418): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,I/DisplayPowerController( 2418): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/SurfaceFlinger( 1920): id=19 createSurf (720x1280),-1 flag=20004, FlectronBea
,D/SensorManager( 2418): unregisterListener ::   
,D/DisplayPowerController( 2418): !@ElectronBeam entry
I/Sensors ( 2418): HAL:resetDataRates mEnabled=4
,D/SensorManager( 2418): unregisterListener ::   
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/dalvikvm( 5704): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/dalvikvm( 5704): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 5704): VFY: replacing opcode 0x6e at 0x0074,
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 370, Delta = -10,
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
E/dalvikvm( 5704): Could not find class 'android.content.pm.LauncherApps', referenced from method cbk.a
W/dalvikvm( 5704): VFY: unable to resolve check-cast 469 (Landroid/content/pm/LauncherApps;) in Lcbk;,
,D/dalvikvm( 5704): VFY: replacing opcode 0x1f at 0x0014
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
I/vclib   ( 5704): onServiceConnected,
,W/Babel   ( 5704): Attempted to change video mute state without an active call.
,I/SELinux ( 5757): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 5757):  
,I/ActivityManager( 2418): Killing 3968:com.google.android.apps.docs/u0a94 (adj 15): empty #43
,I/SELinux ( 5757): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5757):  
I/SELinux ( 5757):  
,I/SELinux ( 5757): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5757): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5757): >>>>> Normal User
,E/dalvikvm( 5757): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 5757): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/SQLiteDatabase( 2733): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 2733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 2733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 2733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 2733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 2733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 2733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 2733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 2733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2733): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2733): 	at com.google.android.gms.playlog.store.r.b(SourceFile:421)
E/SQLiteDatabase( 2733): 	at com.google.android.gms.playlog.store.r.a(SourceFile:303)
E/SQLiteDatabase( 2733): 	at com.google.android.gms.playlog.service.d.a(SourceFile:123)
E/SQLiteDatabase( 2733): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/SQLiteDatabase( 2733): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2733): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2733): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 2733): 	at java.lang.Thread.run(Thread.java:841)
,E/PlayLogIntentService( 2733): not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 2733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 2733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PlayLogIntentService( 2733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PlayLogIntentService( 2733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PlayLogIntentService( 2733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PlayLogIntentService( 2733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PlayLogIntentService( 2733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PlayLogIntentService( 2733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PlayLogIntentService( 2733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PlayLogIntentService( 2733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PlayLogIntentService( 2733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PlayLogIntentService( 2733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 2733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 2733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PlayLogIntentService( 2733): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PlayLogIntentService( 2733): 	at com.google.android.gms.playlog.store.r.b(SourceFile:421)
E/PlayLogIntentService( 2733): 	at com.google.android.gms.playlog.store.r.a(SourceFile:303)
E/PlayLogIntentService( 2733): 	at com.google.android.gms.playlog.service.d.a(SourceFile:123)
E/PlayLogIntentService( 2733): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/PlayLogIntentService( 2733): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/PlayLogIntentService( 2733): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/PlayLogIntentService( 2733): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/PlayLogIntentService( 2733): 	at java.lang.Thread.run(Thread.java:841)
,D/TimaKeyStoreProvider( 5757): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5757): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5757): Added TimaKesytore provider
,I/display ( 1920): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(59)
,D/lights  ( 2418): lcd : 0 +
,D/lights  ( 2418): lcd : 0 -
,D/MISC PowerHAL( 2418): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2418): sysfs_write +: /sys/class/input/input1/enabled: 0
,D/MISC PowerHAL( 2418): sysfs_write -: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2418): blankAllDisplays() is called.
D/PowerManagerService( 2418): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2418): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2418): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2418): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2418): sysfs_write +: /sys/class/input/input0/enabled: 0
V/WindowOrientationListener( 2418): WindowOrientationListener disabled
D/MISC PowerHAL( 2418): sysfs_write -: /sys/class/input/input0/enabled: 0
D/KeyguardViewMediator( 2579): onScreenTurnedOff(3)
D/MISC PowerHAL( 2418): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2418): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SensorService( 2418): AutoRotationSensor::activate (ident=0x79886c98, enabled=0)
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
I/Sensors ( 2418): HAL: batch Dry Run is complete
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SurfaceFlinger( 1920): Screen released, type=0 flinger=0x41a3d550
,D/PowerManagerService( 2418): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SensorManager( 2418): unregisterListener ::   
D/InputDispatcher( 2418): setInputDispatchMode: enabled=0, frozen=0
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/LockPatternUtils( 2579): isPcwEnable = 10
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KeyguardViewMediator( 2579): setting alarm to turn off keyguard, seq = 1
,D/LightsService( 2418): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2418) 
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
,D/LightsService( 2418): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors ( 2418): LightSensor setDelay = 200000000
D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
D/Sensors ( 2418): LightSensor enableSensor = 1
,D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2418): turn on LED for fully charged
D/VibratorService( 2418): JNI vibratorOff()
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,D/Launcher.HomeView( 2786): onPause
,D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2418): tr p:2786,o:f
,D/STATUSBAR-NotificationService( 2418): ACTION_SCREEN_OFF
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
D/LightsService( 2418): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2418) 
,D/LightsService( 2418): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/Launcher.HomeView( 2786): onStop
I/SecExternalDisplayIntents_Java( 2418): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/IpRemoteDisplayController( 2418): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2418): Bridge Server is not available
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/PersonaManagerService( 2418): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2418): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2579):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2579): makeExpandedInvisible
D/PhoneStatusBarView( 2579): marqueeStatusBar:121, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2579):      ACTION_SCREEN_OFF is finished!!!! 
,I/CrashAnrDetector( 2418): onPackageRemoved : com.example.hello
D/UsbSettingsManager( 2418): clearDefaults: com.example.hello
,I/NfcService( 2761): applyRouting return - 2 
,I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 14 sec
,W/System.err( 4966): java.io.IOException: write failed: EBADF (Bad file number)
,E/NfcService( 2761): callback == null
W/System.err( 4966): 	at libcore.io.IoBridge.write(IoBridge.java:455)
W/System.err( 4966): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
,W/System.err( 4966): 	at java.io.OutputStream.write(OutputStream.java:82)
W/System.err( 4966): 	at com.wssyncmldm.agent.XDMDebug.xdmSaveLog(XDMDebug.java:322)
,W/System.err( 4966): 	at com.wssyncmldm.agent.XDMDebug.XDM_DEBUG(XDMDebug.java:72)
W/System.err( 4966): 	at com.wssyncmldm.adapter.XDMInitAdapter.xdmInitAdpWaitSystemRootingCheck(XDMInitAdapter.java:441)
W/System.err( 4966): 	at com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler(XDMTask.java:220)
W/System.err( 4966): 	at com.wssyncmldm.agent.XDMTask$1.handleMessage(XDMTask.java:88)
,W/System.err( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4966): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 4966): 	at com.wssyncmldm.agent.XDMTask.run(XDMTask.java:98)
W/System.err( 4966): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 4966): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
W/System.err( 4966): 	at libcore.io.Posix.writeBytes(Native Method)
,W/System.err( 4966): 	at libcore.io.Posix.write(Posix.java:202)
,D/STATUSBAR-IconMerger( 2579): checkOverflow(384), More:false, Req:false Child:2
W/System.err( 4966): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
W/System.err( 4966): 	at libcore.io.IoBridge.write(IoBridge.java:450)
W/System.err( 4966): 	... 11 more
D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection...
,W/ApplicationsProvider( 2973): Could not fetch usage stats
W/ApplicationsProvider( 2973): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2973): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2973): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2973): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2973): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2973): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2973): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2973): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2973): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2973): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2973): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/SurfaceControl( 2418): Excessive delay in blankDisplay() while turning screen off: 226ms
I/libsuspend( 2418): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2418): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2418): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 228ms
D/PowerManagerService( 2418): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2418): [PWL] Off : 0s ago
I/PowerManagerService( 2418): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2418): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2418): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2418, ws=WorkSource{1000}) (elapsedTime=17290)
I/PowerManagerService( 2418): [PWL]       PARTIAL_WAKE_LOCK              'GpsLocationProvider' (uid=1000, pid=2418, ws=null) (elapsedTime=1061)
I/PowerManagerService( 2418): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/dalvikvm( 5757): GC_CONCURRENT freed 2996K, 30% free 9573K/13548K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 5757): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager( 2418): unregisterListener ::   
D/lights  ( 2418): led_pattern : 5 +
,D/lights  ( 2418): led_pattern : 5 -
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PackageManager( 2418): [MSG] WRITE_PACKAGE_RESTRICTIONS
,F/PackageManager( 2418): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 2418): Can't write: system_server_wtf
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2418): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2418): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2418): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2418): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2418): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2418): 	at com.android.server.pm.PackageManagerService$PackageHandler.doHandleMessage(PackageManagerService.java:1223)
E/DropBoxManagerService( 2418): 	at com.android.server.pm.PackageManagerService$PackageHandler.handleMessage(PackageManagerService.java:815)
E/DropBoxManagerService( 2418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DropBoxManagerService( 2418): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 17 more
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 370, Delta = 0
,D/QuickConnect[1.1][2] ( 5449): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 5449): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5449): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,V/QuickConnect[1.1][2] ( 5449): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42257a20
V/QuickConnect[1.1][2] ( 5449): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42257a20
D/QuickConnect[1.1][2] ( 5449): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5449): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5449): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5449): stopLeScan()
,D/QuickConnect[1.1][2] ( 5449): BleHelper.stopScan - call stopLeScan() complete
,D/PowerManagerService( 2418): [PWL] sb release: PowerManagerService.Broadcasts
,E/dalvikvm( 5757): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 5757): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 5757): VFY: replacing opcode 0x22 at 0x0000
D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@8
,W/dalvikvm( 5757): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 5757): Link of class 'Lal;' failed
E/dalvikvm( 5757): Could not find class 'al', referenced from method b.a
W/dalvikvm( 5757): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 5757): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 5757): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 5757): Link of class 'Lan;' failed
E/dalvikvm( 5757): Could not find class 'an', referenced from method b.a
W/dalvikvm( 5757): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 5757): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 5757): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 5757): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 5757): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 5757): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 5757): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 5757): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 5757): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 5757): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm( 5757): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm( 5757): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 5757): Link of class 'Lal;' failed
,D/dalvikvm( 5757): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 5757): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 5757): Link of class 'Lan;' failed
D/dalvikvm( 5757): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 5757): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 5757): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm( 5757): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 5757): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5757): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5757): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5757): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5757): VFY: unable to resolve instance field 36
,D/dalvikvm( 5757): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5757): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5757): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5757): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5757): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5757): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5757): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4230d668
D/dalvikvm( 5757): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4230d668
,D/dalvikvm( 5757): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4230d668, skipping init
,D/dalvikvm( 5757): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4230d668
D/dalvikvm( 5757): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4230d668
,V/JNIHelp ( 5757): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 2845): GC_EXPLICIT freed 867K, 19% free 11052K/13596K, paused 3ms+6ms, total 44ms
,D/dalvikvm( 5757): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4230d668
,D/dalvikvm( 5757): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4230d668
D/dalvikvm( 5757): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4230d668
,D/dalvikvm( 5757): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4230d668
,I/dalvikvm( 5757): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
,W/dalvikvm( 5757): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5757): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm( 5757): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 5757): VFY: replacing opcode 0x71 at 0x004e
,I/ProviderInstaller( 5757): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 5757): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5757): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,D/dalvikvm( 5757): GC_CONCURRENT freed 1889K, 22% free 10705K/13568K, paused 2ms+3ms, total 28ms
,I/dalvikvm( 5757): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 5757): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5757): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 5757): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5757): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 5757): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5757): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 5757): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5757): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 5757): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5757): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 5757): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5757): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 5757): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5757): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 5757): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5757): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm( 5757): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 5757): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5757): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5757): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
E/SQLiteDatabase( 5757): Failed to open database '/data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore'.
E/SQLiteDatabase( 5757): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5757): 	at ghq.a(SourceFile:1037)
E/SQLiteDatabase( 5757): 	at ghq.a(SourceFile:1060)
E/SQLiteDatabase( 5757): 	at glm.b(SourceFile:152)
E/SQLiteDatabase( 5757): 	at glp.run(SourceFile:128)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5757): 	at goz.run(SourceFile:40)
E/SQLiteDatabase( 5757): 	at java.lang.Thread.run(Thread.java:841)
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5757): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
E/SQLiteDatabase( 5757): Failed to open database '/data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore'.
E/SQLiteDatabase( 5757): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5757): 	at ghq.b(SourceFile:1110)
E/SQLiteDatabase( 5757): 	at glm.a(SourceFile:139)
E/SQLiteDatabase( 5757): 	at glo.run(SourceFile:116)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5757): 	at goz.run(SourceFile:40)
E/SQLiteDatabase( 5757): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteOpenHelper( 5757): Couldn't open com.google.android.libraries.youtube.common.task.ScheduledTaskStore for writing (will try read-only):
E/SQLiteOpenHelper( 5757): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 5757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 5757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 5757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 5757): 	at android.app.ContextImpl.openOrCreateDatabas,e(ContextImpl.java:1322)
E/SQLiteOpenHelper( 5757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5757): 	at ghq.b(SourceFile:1110)
E/SQLiteOpenHelper( 5757): 	at glm.a(SourceFile:139)
E/SQLiteOpenHelper( 5757): 	at glo.run(SourceFile:116)
E/SQLiteOpenHelper( 5757): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 5757): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5757): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteOpenHelper( 5757): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteOpenHelper( 5757): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 5757): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 5757): 	at goz.run(SourceFile:40)
E/SQLiteOpenHelper( 5757): 	at java.lang.Thread.run(Thread.java:841)
W/InstanceID/Rpc( 5757): Found 10012
W/SQLiteOpenHelper( 5757): Opened com.google.android.libraries.youtube.common.task.ScheduledTaskStore in read-only mode
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5757): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/SQLiteDatabase( 5757): Failed to open database '/data/data/com.google.android.youtube/databases/google_conversion_tracking.db'.
E/SQLiteDatabase( 5757): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5757): 	at ahe.a(SourceFile:102)
E/SQLiteDatabase( 5757): 	at aha.a(SourceFile:2161)
E/SQLiteDatabase( 5757): 	at ags.run(SourceFile:34)
E/SQLiteDatabase( 5757): 	at java.lang.Thread.run(Thread.java:841)
,W/GoogleConversionReporter( 5757): Error opening writable conversion tracking database
,E/SQLiteDatabase( 5757): Failed to open database '/data/data/com.google.android.youtube/databases/youtube_upload_service'.
E/SQLiteDatabase( 5757): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5757): 	at lax.a(SourceFile:1057)
E/SQLiteDatabase( 5757): 	at lax.call(SourceFile:41)
E/SQLiteDatabase( 5757): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5757): 	at lay.run(SourceFile:336)
E/SQLiteDatabase( 5757): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 5757): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5757): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5757): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 15 sec
,W/System.err( 4966): java.io.IOException: write failed: EBADF (Bad file number)
W/System.err( 4966): 	at libcore.io.IoBridge.write(IoBridge.java:455)
,W/System.err( 4966): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
W/System.err( 4966): 	at java.io.OutputStream.write(OutputStream.java:82)
W/System.err( 4966): 	at com.wssyncmldm.agent.XDMDebug.xdmSaveLog(XDMDebug.java:322)
W/System.err( 4966): 	at com.wssyncmldm.agent.XDMDebug.XDM_DEBUG(XDMDebug.java:72)
,W/System.err( 4966): 	at com.wssyncmldm.adapter.XDMInitAdapter.xdmInitAdpWaitSystemRootingCheck(XDMInitAdapter.java:441)
W/System.err( 4966): 	at com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler(XDMTask.java:220)
,W/System.err( 4966): 	at com.wssyncmldm.agent.XDMTask$1.handleMessage(XDMTask.java:88)
,W/System.err( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,E/SharedPreferencesImpl( 2733): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml to backup file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml.bak
W/System.err( 4966): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 4966): 	at com.wssyncmldm.agent.XDMTask.run(XDMTask.java:98)
,W/System.err( 4966): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 4966): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
,W/System.err( 4966): 	at libcore.io.Posix.writeBytes(Native Method)
,W/System.err( 4966): 	at libcore.io.Posix.write(Posix.java:202)
,W/System.err( 4966): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
,W/System.err( 4966): 	at libcore.io.IoBridge.write(IoBridge.java:450)
,W/System.err( 4966): 	... 11 more
E/SQLiteDatabase( 5757): Failed to open database '/data/data/com.google.android.youtube/databases/preload_videos_tasks.db'.
E/SQLiteDatabase( 5757): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5757): 	at jqg.a(SourceFile:65)
E/SQLiteDatabase( 5757): 	at jqj.handleMessage(SourceFile:1309)
E/SQLiteDatabase( 5757): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5757): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5757): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 5757): threadid=39: thread exiting with uncaught exception (group=0x4180ac08)
,E/SharedPreferencesImpl( 2733): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml to backup file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml.bak
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
E/AndroidRuntime( 5757): FATAL EXCEPTION: jqi
E/AndroidRuntime( 5757): Process: com.google.android.youtube, PID: 5757
E/AndroidRuntime( 5757): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 5757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 5757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 5757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 5757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 5757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 5757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5757): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5757): 	at jqg.a(SourceFile:65)
E/AndroidRuntime( 5757): 	at jqj.handleMessage(SourceFile:1309)
E/AndroidRuntime( 5757): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5757): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5757): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection...
,E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop219.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
I/Process ( 5757): Sending signal. PID: 5757 SIG: 9
,I/ActivityManager( 2418): Process com.google.android.youtube (pid 5757) (adj 5) has died.
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 304, prevStep = 4, currStep = 4
,D/dalvikvm( 3280): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 3280): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 3280): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 3280): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 3280): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3280): VFY: replacing opcode 0x62 at 0x0021
D/dalvikvm( 3280): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 3280): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 3280): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 3280): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3280): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3280): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 3280): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 3280): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 3280): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
I/dalvikvm( 3280): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 3280): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 3280): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,D/FileApkUtils( 3280): Spent 57ms computing apk sha1.
,D/FileApkUtils( 3280): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 3280): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 3280): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/GmsModuleFndr( 3280): Beginning GMS chimera module scan
,W/InstanceID/Rpc( 3280): Found 10012
,D/ChimeraCfgMgr( 3280): Beginning module configuration check
,D/ChimeraCfgMgr( 3280): Module APKs unchanged, check complete
,E/dalvikvm( 3280): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 3280): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 3280): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 3280): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 3280): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 3280): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 3280): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 3280): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 3280): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 3280): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 3280): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 3280): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 3280): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 3280): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 2733): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 2733): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 2733): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 2733): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2733): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 2733): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2733): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 2733): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 2733): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x0021
E/dalvikvm( 3280): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 3280): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/dalvikvm( 3280): VFY: replacing opcode 0x1f at 0x000e
,D/dalvikvm( 2733): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,W/dalvikvm( 2733): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2733): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 2733): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 3280): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a,
W/dalvikvm( 3280): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 3280): VFY: replacing opcode 0x1f at 0x00f6,
,W/dalvikvm( 3280): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;),
I/dalvikvm( 3280): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 3280): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,D/dalvikvm( 3280): VFY: replacing opcode 0x6e at 0x0004,
D/dalvikvm( 3280): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3280): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3280): VFY: replacing opcode 0x62 at 0x0008,
,D/GCM     ( 3280): COMPAT: Multi user not supported,
D/dalvikvm( 3280): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 3280): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a,
,D/dalvikvm( 3280): GC_CONCURRENT freed 1833K, 19% free 12472K/15272K, paused 6ms+6ms, total 51ms,
,I/CheckinService( 3280): Checkin interval check for package: unspecified last checkin: 1450135146850 min interval config: 0 actual interval: 63907630,
,I/GCoreUlr( 3280): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}],
,I/GCoreUlr( 2733): DispatchingService.onCreate(),
,I/CheckinService( 3280): Disabling old GoogleServicesFramework version
,I/dalvikvm( 2845): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 2845): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 2845): VFY: replacing opcode 0x6e at 0x0059
,W/dalvikvm( 3280): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3280): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2845): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 2845): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 2845): VFY: replacing opcode 0x6e at 0x0022
,D/ChimeraCfgMgr( 3280): Loading module com.google.android.gms.gass from APK com.google.android.gms
,F/PackageManager( 2418): Unable to backup user packages state file, current changes will be lost at reboot
,D/EnterpriseDeviceManagerService( 2418): Creating context as user 0
,D/BootCompletedReceiver( 3280): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 3280): Got an BootCompleted event.
E/DropBoxManagerService( 2418): Can't write: system_server_wtf
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop164.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2418): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2418): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2418): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2418): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2418): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2418): 	at com.android.server.pm.PackageManagerService.setEnabledSetting(PackageManagerService.java:14463)
E/DropBoxManagerService( 2418): 	at com.android.server.pm.PackageManagerService.setComponentEnabledSetting(PackageManagerService.java:14321)
E/DropBoxManagerService( 2418): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1138)
E/DropBoxManagerService( 2418): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2418): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2418): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 18 more
,D/BootCompletedReceiver( 3280): Will NOT schedule AdAttestation signal task because it's disabled.
D/dalvikvm( 2733): GC_CONCURRENT freed 1940K, 21% free 11643K/14628K, paused 6ms+9ms, total 65ms
,D/dalvikvm( 2733): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/SystemUpdateService( 3280): onCreate
,E/SharedPreferencesImpl( 2733): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LOCATION_REPORTING.xml to backup file /data/data/com.google.android.gms/shared_prefs/LOCATION_REPORTING.xml.bak
,E/SQLiteDatabase( 2845): Failed to open database '/data/data/com.google.android.gms/databases/rmq.db'.
E/SQLiteDatabase( 2845): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 2845): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 2845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2845): 	at com.google.android.gms.gcm.bx.b(SourceFile:537)
E/SQLiteDatabase( 2845): 	at com.google.android.gms.gcm.e.<init>(SourceFile:204)
E/SQLiteDatabase( 2845): 	at com.google.android.gms.gcm.GcmService.onCreate(SourceFile:232)
E/SQLiteDatabase( 2845): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2859)
E/SQLiteDatabase( 2845): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/SQLiteDatabase( 2845): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1390)
E/SQLiteDatabase( 2845): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2845): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 2845): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 2845): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 2845): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 2845): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 2845): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 2845): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 2845): Couldn't open rmq.db for writing (will try read-only):
E/SQLiteOpenHelper( 2845): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2845): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 2845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 2845): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 2845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 2845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 2845): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 2845): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 2845): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 2845): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 2845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 2845): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2845): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2845): 	at com.google.android.gms.gcm.bx.b(SourceFile:537)
E/SQLiteOpenHelper( 2845): 	at com.google.android.gms.gcm.e.<init>(SourceFile:204)
E/SQLiteOpenHelper( 2845): 	at com.google.android.gms.gcm.GcmService.onCreate(SourceFile:232)
E/SQLiteOpenHelper( 2845): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2859)
E/SQLiteOpenHelper( 2845): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/SQLiteOpenHelper( 2845): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1390)
E/SQLiteOpenHelper( 2845): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2845): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 2845): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 2845): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 2845): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 2845): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 2845): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 2845): 	at dalvik.system.NativeStart.main(Native Method)
,D/SystemUpdateService( 3280): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/SQLiteOpenHelper( 2845): Opened rmq.db in read-only mode
,E/GCoreUlr( 2733): Error opening datastore
E/GCoreUlr( 2733): com.google.android.gms.leveldb.LevelDbIoErrorException: IO error: /data/data/com.google.android.gms/app_ulr_db/LOCK: Read-only file system
E/GCoreUlr( 2733): 	at com.google.android.gms.leveldb.LevelDb.nativeOpen(Native Method)
E/GCoreUlr( 2733): 	at com.google.android.gms.leveldb.LevelDb.a(SourceFile:140)
E/GCoreUlr( 2733): 	at com.google.android.location.reporting.b.a.a(SourceFile:81)
E/GCoreUlr( 2733): 	at com.google.android.location.reporting.service.DispatchingService.onCreate(SourceFile:392)
E/GCoreUlr( 2733): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2859)
E/GCoreUlr( 2733): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/GCoreUlr( 2733): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1390)
E/GCoreUlr( 2733): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/GCoreUlr( 2733): 	at android.os.Looper.loop(Looper.java:146)
E/GCoreUlr( 2733): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/GCoreUlr( 2733): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/GCoreUlr( 2733): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/GCoreUlr( 2733): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/GCoreUlr( 2733): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/GCoreUlr( 2733): 	at dalvik.system.NativeStart.main(Native Method)
,I/GCoreUlr( 2733): DispatchingService.onDestroy()
,I/dalvikvm( 3280): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 3280): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 3280): VFY: replacing opcode 0x6e at 0x0409
I/CheckinService( 3280): Checking schedule, now: 1450199054615 next: 1450693489757
,I/CheckinService( 3280): active receiver: disabled
,V/AuthZen ( 3280): Handling intent: android.intent.action.BOOT_COMPLETED
,E/SQLiteDatabase( 3280): Failed to open database '/data/data/com.google.android.gms/databases/auth.credentials.credential_store'.
E/SQLiteDatabase( 3280): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3280): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3280): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3280): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3280): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3280): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3280): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3280): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3280): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3280): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3280): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3280): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3280): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3280): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3280): 	at com.google.android.gms.auth.api.credentials.be.persistence.e.a(SourceFile:66)
E/SQLiteDatabase( 3280): 	at com.google.android.gms.auth.api.credentials.be.persistence.af.a(SourceFile:187)
E/SQLiteDatabase( 3280): 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:137)
E/SQLiteDatabase( 3280): 	at com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService.a(SourceFile:185)
E/SQLiteDatabase( 3280): 	at com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService.onHandleIntent(SourceFile:98)
E/SQLiteDatabase( 3280): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3280): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3280): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3280): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 3280): threadid=46: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 3280): FATAL EXCEPTION: IntentService[CredentialSyncReceiverService]
E/AndroidRuntime( 3280): Process: com.google.android.gms, PID: 3280
E/AndroidRuntime( 3280): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3280): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3280): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 3280): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 3280): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 3280): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 3280): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 3280): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 3280): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 3280): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 3280): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 3280): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 3280): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3280): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3280): 	at com.google.android.gms.auth.api.credentials.be.persistence.e.a(SourceFile:66)
E/AndroidRuntime( 3280): 	at com.google.android.gms.auth.api.credentials.be.persistence.af.a(SourceFile:187)
E/AndroidRuntime( 3280): 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:137)
E/AndroidRuntime( 3280): 	at com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService.a(SourceFile:185)
E/AndroidRuntime( 3280): 	at com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService.onHandleIntent(SourceFile:98)
E/AndroidRuntime( 3280): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3280): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3280): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 3280): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/GCM     ( 2845): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,E/SharedPreferencesImpl( 2733): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/bootCount.xml to backup file /data/data/com.google.android.gms/shared_prefs/bootCount.xml.bak
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
,I/Process ( 3280): Sending signal. PID: 3280 SIG: 9
W/SocketClient( 1915): write error (Broken pipe)
,I/dalvikvm( 2845): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 2845): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 2845): VFY: replacing opcode 0x6e at 0x0053
D/ConnectivityService( 2418): handleInetConditionChange: no active default network - ignore
,W/Auth    ( 2845): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/ActivityManager( 2418): Process com.google.android.gms (pid 3280) (adj 0) has died.
D/PowerManagerService( 2418): [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'SystemUpdateService' (uid=10012, pid=3280, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=279)
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerManagerService( 2418): [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'Checkin Service' (uid=10012, pid=3280, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=247)
D/LockPatternUtils( 2579): isPcwEnable = 10
,I/SELinux ( 5864): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5864):  
,I/SELinux ( 5864): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5864):  
I/SELinux ( 5864):  
,I/SELinux ( 5864): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5864): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5864): >>>>> Normal User
,E/dalvikvm( 5864): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 5864): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5864): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5864): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5864): Added TimaKesytore provider
,D/dalvikvm( 5864): GC_CONCURRENT freed 2944K, 29% free 9623K/13544K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 5864): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/dalvikvm( 5864): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5864): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 5864): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5864): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5864): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 5864): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5864): install
,I/MultiDex( 5864): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 5864): loading existing secondary dex files
,I/MultiDex( 5864): load found 3 secondary dex files
,I/MultiDex( 5864): install done
,I/DBG_DM  ( 4966): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 16 sec
,W/System.err( 4966): java.io.IOException: write failed: EBADF (Bad file number)
W/System.err( 4966): 	at libcore.io.IoBridge.write(IoBridge.java:455)
W/System.err( 4966): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
W/System.err( 4966): 	at java.io.OutputStream.write(OutputStream.java:82)
W/System.err( 4966): 	at com.wssyncmldm.agent.XDMDebug.xdmSaveLog(XDMDebug.java:322)
W/System.err( 4966): 	at com.wssyncmldm.agent.XDMDebug.XDM_DEBUG(XDMDebug.java:72)
W/System.err( 4966): 	at com.wssyncmldm.adapter.XDMInitAdapter.xdmInitAdpWaitSystemRootingCheck(XDMInitAdapter.java:441)
W/System.err( 4966): 	at com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler(XDMTask.java:220)
,W/System.err( 4966): 	at com.wssyncmldm.agent.XDMTask$1.handleMessage(XDMTask.java:88)
,W/System.err( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 4966): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4966): 	at com.wssyncmldm.agent.XDMTask.run(XDMTask.java:98)
,W/System.err( 4966): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 4966): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
,W/System.err( 4966): 	at libcore.io.Posix.writeBytes(Native Method)
,W/System.err( 4966): 	at libcore.io.Posix.write(Posix.java:202)
W/System.err( 4966): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
W/System.err( 4966): 	at libcore.io.IoBridge.write(IoBridge.java:450)
,W/System.err( 4966): 	... 11 more
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,W/AtomicFile( 2418): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2418): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/SELinux ( 5879): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5879):  
,D/dalvikvm( 5864): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5864): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5864): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5864): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 5864): VFY: unable to resolve instance field 36
,D/dalvikvm( 5864): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5864): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5864): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5864): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5864): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5864): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5864): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4223f920
D/dalvikvm( 5864): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4223f920
,D/dalvikvm( 5864): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4223f920, skipping init
,D/dalvikvm( 5864): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4223f920
,D/dalvikvm( 5864): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4223f920
,V/JNIHelp ( 5864): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/SELinux ( 5879): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5879):  
I/SELinux ( 5879):  
,I/SELinux ( 5879): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5879): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5879): >>>>> Normal User
,E/dalvikvm( 5879): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 5879): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5879): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5879): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5879): Added TimaKesytore provider
,D/dalvikvm( 5864): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4223f920
,D/dalvikvm( 5864): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4223f920
D/dalvikvm( 5864): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4223f920
,D/dalvikvm( 5864): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4223f920,
,D/dalvikvm( 5879): GC_CONCURRENT freed 2997K, 30% free 9569K/13540K, paused 2ms+1ms, total 18ms,
,D/dalvikvm( 5879): WAIT_FOR_CONCURRENT_GC blocked 16ms,
,I/ProviderInstaller( 5864): Installed default security provider GmsCore_OpenSSL,
,W/NativeLibraryUtils( 5864): Failed to open lock file,
W/NativeLibraryUtils( 5864): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5864): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 5864): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 5864): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 5864): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 5864): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5864): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 5864): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110),
W/NativeLibraryUtils( 5864): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 5864): 	... 3 more
,E/dalvikvm( 5879): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a,
W/dalvikvm( 5879): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 5879): VFY: replacing opcode 0x22 at 0x0000,
I/dalvikvm( 5864): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 5864): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 5864): VFY: replacing opcode 0x6e at 0x0010,
,W/dalvikvm( 5879): Unable to resolve superclass of Lal; (749),
W/dalvikvm( 5879): Link of class 'Lal;' failed
E/dalvikvm( 5879): Could not find class 'al', referenced from method b.a
W/dalvikvm( 5879): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 5879): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 5879): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 5879): Link of class 'Lan;' failed
E/dalvikvm( 5879): Could not find class 'an', referenced from method b.a
W/dalvikvm( 5879): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 5879): VFY: replacing opcode 0x22 at 0x002a
,I/dalvikvm( 5879): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 5879): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 5879): Could not find method android.view.View.getTransitionName, referenced from method b.a
,W/dalvikvm( 5879): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x0006
,D/PersistentNotificationBroadcastReceiver( 2733): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
W/dalvikvm( 5879): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 5879): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 5879): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 5879): VFY: replacing opcode 0x23 at 0x0005
,D/SystemUpdateService( 5864): onCreate
,D/SystemUpdateService( 5864): onStartCommand: intent: null
,D/dalvikvm( 5879): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm( 5879): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 5879): Link of class 'Lal;' failed
,D/dalvikvm( 5879): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 5879): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 5879): Link of class 'Lan;' failed
D/dalvikvm( 5879): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 5879): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
I/dalvikvm( 5864): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 5864): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 5864): VFY: replacing opcode 0x6e at 0x0409
,I/dalvikvm( 5879): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
,W/dalvikvm( 5879): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5864): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 5864): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 5864): VFY: replacing opcode 0x6e at 0x002b
,I/SystemUpdateService( 5864): cancelUpdate (empty URL)
,I/SystemUpdateService( 5864): active receiver: disabled
,W/dalvikvm( 5864): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 5879): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5879): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5879): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5879): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5879): VFY: unable to resolve instance field 36
,D/dalvikvm( 5879): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5879): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5879): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5879): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5879): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5879): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5879): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42316838
,D/dalvikvm( 5864): Trying to load lib /data/app-lib/com.google.android.gms-5/libAppDataSearch.so 0x4223f920
D/dalvikvm( 5879): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42316838
,D/dalvikvm( 5879): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42316838, skipping init
,D/dalvikvm( 5879): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42316838
,D/dalvikvm( 5879): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42316838
,V/JNIHelp ( 5879): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 5864): Added shared lib /data/app-lib/com.google.android.gms-5/libAppDataSearch.so 0x4223f920
,D/dalvikvm( 5864): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libAppDataSearch.so 0x4223f920, skipping init
,I/dalvikvm( 5864): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 5864): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5864): VFY: replacing opcode 0x6e at 0x000d
,I/GAv4-SVC( 5864): Google Analytics 8.4.89 is starting up.
,I/dalvikvm( 5879): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 5879): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5879): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 5879): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 5879): VFY: replacing opcode 0x71 at 0x004e
D/dalvikvm( 5879): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42316838
D/dalvikvm( 5879): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42316838
D/dalvikvm( 5879): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42316838
,D/dalvikvm( 5879): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42316838
,E/SQLiteDatabase( 5864): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5864): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5864): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5864): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:870)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:798)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:628)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:262)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:272)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 5864): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5864): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5864): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5864): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5864): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.measurement.p.run(SourceFile:388)
,E/GAv4-SVC( 5864): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 5864): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 5864): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 5864): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 5864): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5864): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5864): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 5864): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5864): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5864): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5864): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5864): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5864): 	at java.lang.Thread.run(Thread.java:841)
,W/dalvikvm( 5864): threadid=15: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 5864): FATAL EXCEPTION: AsyncTask #1
E/AndroidRuntime( 5864): Process: com.google.android.gms, PID: 5864
E/AndroidRuntime( 5864): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 5864): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 5864): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 5864): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 5864): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 5864): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 5864): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 5864): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 5864): 	at java.lang.Thread.run(Thread.java:841)
E/AndroidRuntime( 5864): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5864): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 5864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 5864): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5864): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 5864): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 5864): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 5864): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 5864): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5864): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5864): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5864): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 5864): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 5864): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 5864): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 5864): 	... 4 more
E/SQLiteDatabase( 5864): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5864): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteDatabase.openD,atabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5864): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5864): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5864): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:883)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:798)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:628)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:262)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:272)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 5864): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5864): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5864): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5864): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5864): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 5864): 	at com.google.android.gms.measurement.p.run(SourceFile:388)
E/GAv4-SVC( 5864): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 5864): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ActivityManager( 2418): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager( 2418): Killing 5864:com.google.android.gms/u0a12 (adj 0): crash
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
,I/SELinux ( 5923): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5923):  
,I/ProviderInstaller( 5879): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 5923): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5923):  
I/SELinux ( 5923):  
,I/SELinux ( 5923): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5923): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5923): >>>>> Normal User
,E/dalvikvm( 5923): >>>>> com.sec.spp.push [ userId:0 | appId:10039 ]
,E/SELinux ( 5923): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 5923): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5923): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5923): Added TimaKesytore provider
,E/YouTube MDX( 5879): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/SELinux ( 5943): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5943):  
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5879): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 10% free 9502K/10524K, paused 2ms+3ms, total 30ms
,I/SELinux ( 5943): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5943):  
I/SELinux ( 5943):  
,I/SELinux ( 5943): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5943): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5943): >>>>> Normal User
,E/dalvikvm( 5943): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 5943): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9502K/10524K, paused 2ms+4ms, total 26ms
,D/TimaKeyStoreProvider( 5943): in addTimaSignatureService
D/dalvikvm( 5923): GC_CONCURRENT freed 2994K, 30% free 9576K/13544K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 5923): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/TimaKeyStoreProvider( 5943): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5943): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9502K/10524K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 5879): GC_CONCURRENT freed 1898K, 22% free 10729K/13588K, paused 5ms+7ms, total 65ms
,E/SPPClientService( 5923): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5923): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 5923): [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
,E/SPPClientService( 5923): [SystemStateMoniter] Current Time : 72552
,D/SPPClientService( 5923): PushLog.txt file is not deleted.
D/SPPClientService( 5923): PushLog.txt file is not deleted.
,D/SPPClientService( 5923): ============PushLog. stop!
,E/SharedPreferencesImpl( 5923): Couldn't rename file /data/data/com.sec.spp.push/shared_prefs/com.sec.spp.push.config.xml to backup file /data/data/com.sec.spp.push/shared_prefs/com.sec.spp.push.config.xml.bak
,E/SQLiteDatabase( 5923): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5923): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5923): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5923): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5923): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5923): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5923): 	at com.sec.spp.push.monitor.SystemStateMoniter.a(Unknown Source)
E/SQLiteDatabase( 5923): 	at com.sec.spp.push.monitor.SystemStateMoniter.onReceive(Unknown Source)
E/SQLiteDatabase( 5923): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 5923): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 5923): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 5923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5923): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5923): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5923): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5923): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5923): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5923): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5923): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5923): [d] isRegistrationTableEmpty. Exception with message =not an error (code 0): Could not open the database in read/write mode.
D/dalvikvm( 5943): GC_CONCURRENT freed 2956K, 30% free 9615K/13548K, paused 2ms+1ms, total 30ms
,D/dalvikvm( 5943): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/Volley  ( 3877): [213] DiskBasedCache.clear: Cache cleared.
W/dalvikvm( 5943): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5943): VFY: replacing opcode 0x60 at 0x000b
,D/Volley  ( 3877): [206] DiskBasedCache.clear: Cache cleared.
I/dalvikvm( 5943): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5943): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5943): VFY: replacing opcode 0x6e at 0x00cd
E/SQLiteDatabase( 5923): Failed to open database '/data/data/com.sec.spp.push/databases/log_data_db'.
E/SQLiteDatabase( 5923): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5923): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5923): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5923): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5923): 	at com.sec.spp.push.c.c.<init>(Unknown Source)
E/SQLiteDatabase( 5923): 	at com.sec.spp.push.c.c.a(Unknown Source)
E/SQLiteDatabase( 5923): 	at com.sec.spp.push.log.collector.PushClientLogCollectService.g(Unknown Source)
E/SQLiteDatabase( 5923): 	at com.sec.spp.push.log.collector.PushClientLogCollectService.b(Unknown Source)
E/SQLiteDatabase( 5923): 	at com.sec.spp.push.log.collector.PushClientLogCollectService.onHandleIntent(Unknown Source)
E/SQLiteDatabase( 5923): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5923): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5923): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SPPClientService( 5923): [[SPPLogCollecter]] null
,V/SipBroadcastReceiver( 2751): SipBroadcastReceiver onReceive
I/MultiDex( 5943): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5943): install
,I/MultiDex( 5943): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 5943): loading existing secondary dex files
,I/MultiDex( 5943): load found 3 secondary dex files
I/dalvikvm( 5879): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 5879): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5879): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 5879): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5879): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 5879): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5879): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 5879): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5879): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 5879): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5879): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 5879): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5879): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 5879): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 5879): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
I/MultiDex( 5943): install done
W/dalvikvm( 5879): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5879): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
,W/dalvikvm( 5879): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 5879): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5879): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,E/SQLiteDatabase( 5879): Failed to open database '/data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore'.
E/SQLiteDatabase( 5879): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5879): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5879): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5879): 	at ghq.a(SourceFile:1037)
E/SQLiteDatabase( 5879): 	at ghq.a(SourceFile:1060)
E/SQLiteDatabase( 5879): 	at glm.b(SourceFile:152)
E/SQLiteDatabase( 5879): 	at glp.run(SourceFile:128)
E/SQLiteDatabase( 5879): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5879): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5879): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteDatabase( 5879): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteDatabase( 5879): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5879): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5879): 	at goz.run(SourceFile:40)
E/SQLiteDatabase( 5879): 	at java.lang.Thread.run(Thread.java:841)
,W/ContextImpl( 5879): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5879): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
E/SQLiteDatabase( 5879): Failed to open database '/data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore'.
E/SQLiteDatabase( 5879): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5879): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5879): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5879): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5879): 	at ghq.b(SourceFile:1110)
E/SQLiteDatabase( 5879): 	at glm.a(SourceFile:139)
E/SQLiteDatabase( 5879): 	at glo.run(SourceFile:116)
E/SQLiteDatabase( 5879): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5879): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5879): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteDatabase( 5879): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteDatabase( 5879): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5879): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5879): 	at goz.run(SourceFile:40)
E/SQLiteDatabase( 5879): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteOpenHelper( 5879): Couldn't open com.google.android.libraries.youtube.common.task.ScheduledTaskStore for writing (will try read-only):
E/SQLiteOpenHelper( 5879): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5879): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5879): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 5879): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 5879): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5879): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5879): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5879): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 5879): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 5879): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 5879): 	at android.app.ContextImpl.openOrCreateDatabas,e(ContextImpl.java:1322)
E/SQLiteOpenHelper( 5879): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 5879): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5879): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5879): 	at ghq.b(SourceFile:1110)
E/SQLiteOpenHelper( 5879): 	at glm.a(SourceFile:139)
E/SQLiteOpenHelper( 5879): 	at glo.run(SourceFile:116)
E/SQLiteOpenHelper( 5879): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 5879): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5879): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteOpenHelper( 5879): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteOpenHelper( 5879): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 5879): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 5879): 	at goz.run(SourceFile:40)
E/SQLiteOpenHelper( 5879): 	at java.lang.Thread.run(Thread.java:841)
W/InstanceID/Rpc( 5879): Found 10012
W/SQLiteOpenHelper( 5879): Opened com.google.android.libraries.youtube.common.task.ScheduledTaskStore in read-only mode
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5879): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30

```
