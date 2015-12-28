#### Test 503880191ec81a5_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
W/ApplicationsProvider( 2958): Could not fetch usage stats
W/ApplicationsProvider( 2958): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2958): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2958): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2958): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2958): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2958): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2958): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/TimaKeyStoreProvider( 4967): in addTimaSignatureService
D/TimaKeyStoreProvider( 4967): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4967): Added TimaKesytore provider
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/Auth    ( 2850): [BroadcastManager] Broadcasting account services changed.
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2421): onPackageAdded : com.example.hello
D/dalvikvm( 4967): GC_CONCURRENT freed 3004K, 32% free 9566K/13936K, paused 4ms+2ms, total 51ms
D/dalvikvm( 4967): WAIT_FOR_CONCURRENT_GC blocked 43ms
--------- beginning of /dev/log/system
I/ActivityManager( 2421): Killing 3863:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty #43
W/ContextImpl( 4967): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:61 android.app.ActivityThread.handleReceiver:2698 
V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SELinux ( 4985): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4985):  
I/SELinux ( 4985): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4985):  
I/SELinux ( 4985):  
I/SELinux ( 4985): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4985): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4985): >>>>> Normal User
E/dalvikvm( 4985): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
E/SELinux ( 4985): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 3311): GC_CONCURRENT freed 1644K, 21% free 12012K/15024K, paused 5ms+42ms, total 126ms
D/TimaKeyStoreProvider( 4985): in addTimaSignatureService
D/TimaKeyStoreProvider( 4985): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4985): Added TimaKesytore provider
D/dalvikvm( 2850): GC_CONCURRENT freed 1619K, 23% free 10774K/13932K, paused 6ms+3ms, total 49ms
D/dalvikvm( 4985): GC_CONCURRENT freed 3003K, 32% free 9569K/13940K, paused 3ms+2ms, total 29ms
D/dalvikvm( 4985): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/BluetoothBDAdrressReceiver( 4985): onReceive(), action: android.intent.action.BOOT_COMPLETED
W/ContextImpl( 4985): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
W/ContextImpl( 4985): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
D/BluetoothBDTestService( 2754): onCreate()
E/BluetoothBDTestService( 2754): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
E/BluetoothBDTestService( 2754): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 2754): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/SELinux ( 4997): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4997):  
I/SELinux ( 4997): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4997):  
I/SELinux ( 4997):  
I/SELinux ( 4997): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4997): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4997): >>>>> Normal User
E/dalvikvm( 4997): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
E/SELinux ( 4997): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 4997): in addTimaSignatureService
D/TimaKeyStoreProvider( 4997): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4997): Added TimaKesytore provider
I/ActivityManager( 2421): Killing 3932:com.android.documentsui/u0a93 (adj 15): empty #43
I/ActivityManager( 2421): Killing 3216:com.sec.android.app.mt/1000 (adj 15): empty #43
D/dalvikvm( 4997): GC_CONCURRENT freed 2987K, 32% free 9572K/13932K, paused 4ms+2ms, total 31ms
D/dalvikvm( 4997): WAIT_FOR_CONCURRENT_GC blocked 27ms
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 3611): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
I/SELinux ( 5011): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5011):  
I/ActivityManager( 2421): Killing 3947:com.android.externalstorage/u0a9 (adj 15): empty #43
I/SELinux ( 5011): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5011):  
I/SELinux ( 5011):  
I/SELinux ( 5011): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5011): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5011): >>>>> Normal User
E/dalvikvm( 5011): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
E/SELinux ( 5011): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5011): in addTimaSignatureService
I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 3 sec
D/TimaKeyStoreProvider( 5011): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5011): Added TimaKesytore provider
I/Icing   ( 3311): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4967): Resource data:2131165197
I/AMMetaDataParserService( 4967): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
I/AMMetaDataParserService( 4967): Resource data:2131165194
I/AMMetaDataParserService( 4967): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
D/dalvikvm( 5011): GC_CONCURRENT freed 3003K, 32% free 9565K/13940K, paused 2ms+2ms, total 20ms
D/dalvikvm( 5011): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/        ( 4967): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4967): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
E/PersonaManagerService( 2421): returning null in  getPersonasForUser
I/SELinux ( 5023): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5023):  
I/ActivityManager( 2421): Killing 3971:com.sec.phone/1001 (adj 15): empty #43
D/        ( 4967): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4967): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
I/SELinux ( 5023): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5023):  
I/SELinux ( 5023):  
I/SELinux ( 5023): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5023): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5023): >>>>> Normal User
E/dalvikvm( 5023): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
D/dalvikvm( 4967): GC_CONCURRENT freed 438K, 14% free 12087K/13936K, paused 3ms+1ms, total 30ms
D/dalvikvm( 4967): WAIT_FOR_CONCURRENT_GC blocked 12ms
E/SELinux ( 5023): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5023): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5023): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5023): Added TimaKesytore provider
D/        ( 4967): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4967): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
D/dalvikvm( 5023): GC_CONCURRENT freed 3002K, 32% free 9568K/13936K, paused 2ms+1ms, total 19ms
D/dalvikvm( 5023): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/        ( 4967): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4967): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
I/AMMetaDataParserService( 4967): Resource data:2131165194
I/AMMetaDataParserService( 4967): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
D/        ( 4967): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4967): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
D/        ( 4967): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4967): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
D/        ( 4967): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4967): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
W/BackupManagerService( 2421): dataChanged but no participant pkg='com.android.providers.settings' uid=10088
D/        ( 4967): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4967): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 4967): Resource data:2131165195
I/AMMetaDataParserService( 4967): getResourceName:com.sec.android.gallery3d:xml/device_filter
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4967): Resource data:2131165204
I/AMMetaDataParserService( 4967): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4967): Resource data:2131165204
I/AMMetaDataParserService( 4967): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4967): Resource data:2131165204
I/AMMetaDataParserService( 4967): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
D/AndroidRuntime( 5035): 
D/AndroidRuntime( 5035): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5035): CheckJNI is OFF
D/AndroidRuntime( 5035): setted country_code = Poland
D/AndroidRuntime( 5035): setted countryiso_code = PL
D/AndroidRuntime( 5035): setted sales_code = PLS
D/AndroidRuntime( 5035): readGMSProperty: start
D/AndroidRuntime( 5035): readGMSProperty: already setted!!
D/AndroidRuntime( 5035): readGMSProperty: end
D/AndroidRuntime( 5035): addProductProperty: start
I/SELinux ( 5038): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5038):  
I/ActivityManager( 2421): Killing 4056:com.gameloft.android.GloftPSHU/u0a181 (adj 15): empty #43
D/dalvikvm( 5035): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5035): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5035): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5035): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5035): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 5038): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5038):  
I/SELinux ( 5038):  
I/SELinux ( 5038): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5038): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5038): >>>>> Normal User
E/dalvikvm( 5038): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
E/SELinux ( 5038): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 4967): Resource data:2131099676
I/AMMetaDataParserService( 4967): getResourceName:com.android.mms:xml/spellscroll
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/AMMetaDataParserService( 4967): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
I/AMMetaDataParserService( 4967): Resource data:2131099648
I/AMMetaDataParserService( 4967): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
D/TimaKeyStoreProvider( 5038): in addTimaSignatureService
D/TimaKeyStoreProvider( 5038): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5038): Added TimaKesytore provider
D/        ( 4967): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4967): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
D/dalvikvm( 5038): GC_CONCURRENT freed 3012K, 32% free 9559K/13940K, paused 3ms+2ms, total 24ms
D/dalvikvm( 5038): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/        ( 4967): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4967): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
I/SELinux ( 5057): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5057):  
I/ActivityManager( 2421): Killing 4113:com.n7mobile.muzodajnia:main/u0a184 (adj 15): empty #43
E/memtrack( 5035): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5035): failed to load memtrack module: -2
I/SELinux ( 5057): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5057):  
I/SELinux ( 5057):  
I/SELinux ( 5057): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5057): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5057): >>>>> Normal User
E/dalvikvm( 5057): >>>>> com.dropbox.android [ userId:0 | appId:10095 ]
E/SELinux ( 5057): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/        ( 4967): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4967): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
D/TimaKeyStoreProvider( 5057): in addTimaSignatureService
D/TimaKeyStoreProvider( 5057): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5057): Added TimaKesytore provider
D/dalvikvm( 5035): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/        ( 4967): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4967): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
D/dalvikvm( 5057): GC_CONCURRENT freed 2986K, 32% free 9583K/13936K, paused 3ms+1ms, total 21ms
D/dalvikvm( 5057): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/        ( 4967): PNG_doEncode true 106, 106
D/AndroidRuntime( 5035): Calling main entry com.android.commands.am.Am
I/AMMetaDataParserService( 4967): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
D/        ( 4967): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4967): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
I/AMMetaDataParserService( 4967): Resource data:2131099648
I/AMMetaDataParserService( 4967): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
V/ApplicationPolicy( 2421): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1921): id=14 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1921): id=15 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2421): mDVFSHelper.acquire()
D/        ( 4967): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4967): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): tr p:2421,o:f
D/Launcher.HomeView( 2764): onPause
I/SurfaceFlinger( 1921): id=16 createSurf (1x1),1 flag=404, iello
D/AndroidRuntime( 5035): Shutting down VM
D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): tr p:2764,o:f
D/dalvikvm( 5035): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 4ms
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
D/        ( 4967): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4967): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
I/SELinux ( 5073): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5073):  
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 4 sec
I/SELinux ( 5073): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5073):  
I/SELinux ( 5073):  
I/SELinux ( 5073): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5073): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5073): >>>>> Normal User
E/dalvikvm( 5073): >>>>> com.example.hello [ userId:0 | appId:10579 ]
E/SELinux ( 5073): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/com.dropbox.android.service.DropboxNetworkReceiver( 5057): Setting receiver enabled: false
D/TimaKeyStoreProvider( 5073): in addTimaSignatureService
D/TimaKeyStoreProvider( 5073): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5073): Added TimaKesytore provider
D/        ( 4967): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4967): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
V/WindowOrientationListener( 2421): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 2421): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 2764): onStop
V/WindowManager( 2421): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/com.dropbox.sync.android.a( 5057): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
D/Launcher( 2764): onTrimMemory. Level: 20
,D/dalvikvm( 5073): GC_CONCURRENT freed 2989K, 32% free 9576K/13936K, paused 5ms+2ms, total 32ms
,D/dalvikvm( 5073): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(40)
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/com.dropbox.sync.android.aa( 5057): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800F armeabi-v7a; en_US))
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,V/WebViewChromium( 5073): Binding Chromium to the background looper Looper (main, tid 1) {42929320}
,I/chromium( 5073): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5073): Initializing chromium process, renderers=0
,W/chromium( 5073): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,D/libEGL  ( 5073): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 5073): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 5073): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 5073): Mali API Version : 401
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
,I/Mali    ( 5073): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4967): Resource data:2131099648
,I/SELinux ( 5109): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5109):  
,I/AMMetaDataParserService( 4967): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/ActivityManager( 2421): Killing 3983:com.google.android.apps.docs/u0a94 (adj 15): empty #43
,I/dalvikvm( 5073): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 5073): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5073): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5073): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5073): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5073): VFY: replacing opcode 0x6e at 0x0008
I/SELinux ( 5109): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5109):  
I/SELinux ( 5109):  
,I/SELinux ( 5109): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5109): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5109): >>>>> Normal User
,E/dalvikvm( 5109): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 5109): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4967): PNG_doEncode true 106, 106
D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
I/AMMetaDataParserService( 4967): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
D/StatusBarManagerService( 2421): tr p:5073,o:f
W/dalvikvm( 5073): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5073): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5073): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5073): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5073): VFY: replacing opcode 0x6f at 0x001a
,D/TimaKeyStoreProvider( 5109): in addTimaSignatureService
W/dalvikvm( 5073): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,I/dalvikvm( 5073): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5073): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 5073): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5073): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5073): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5073): VFY: replacing opcode 0x6e at 0x0000
,D/TimaKeyStoreProvider( 5109): Cannot add TimaSignature Service, License check Failed
,D/SystemWebViewEngine( 5073): CordovaWebView is running on device made by: samsung
,D/ActivityThread( 5109): Added TimaKesytore provider
,I/SurfaceFlinger( 1921): id=9 Removed Mauncher (7/10)
,I/SurfaceFlinger( 1921): id=9 Removed Mauncher (-2/10)
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/dalvikvm( 5109): GC_CONCURRENT freed 2993K, 32% free 9575K/13940K, paused 3ms+3ms, total 28ms
,D/dalvikvm( 5109): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/elm:14132( 5109): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 5109): ELMEngine.ELMEngine( context ).
,D/elm:14132( 5109): MDMBridge.setEnterpriseBridge()
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/elm:14132( 5109): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/StatusBarManagerService( 2421): semi p:5073,o:f
,D/elm:14132( 5109): ElmAgentService : onCreate()
,I/SELinux ( 5129): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5129):  
,D/elm:14132( 5109): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,I/SurfaceFlinger( 1921): id=17 createSurf (1x1),1 flag=404, NainActivit
,D/elm:14132( 5109): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:14132( 5109): BootCompletedState : startBootCompleted() call
,D/elm:14132( 5109): ModuleBase.resetCalllogAPIAlarm()
,D/elm:14132( 5109): MDMBridge.getAllLicenseInfoFromSDK()
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
I/SELinux ( 5129): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5129):  
I/SELinux ( 5129):  
,I/SELinux ( 5129): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5129): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5129): >>>>> Normal User
,E/dalvikvm( 5129): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,E/SELinux ( 5129): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/elm:14132( 5109): Get License : 0
,I/HWUI    ( 5073): EGLImpl-HWUI Protected EGL context created
,D/SensorService( 2421):   0.3 0.0 9.9
,D/OpenGLRenderer( 5073): Enabling debug mode 0
,W/AwContents( 5073): nativeOnDraw failed; clearing to background color.
,D/TimaKeyStoreProvider( 5129): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5129): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5129): Added TimaKesytore provider
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/elm:14132( 5109): ElmAgentService : onDestroy().
,I/ActivityManager( 2421): Killing 4129:com.google.android.configupdater/u0a3 (adj 15): empty #43
,W/AwContents( 5073): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2421): mDVFSHelper.release()
,D/        ( 4967): PNG_doEncode true 106, 106
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,I/AMMetaDataParserService( 4967): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/dalvikvm( 5129): GC_CONCURRENT freed 3003K, 32% free 9565K/13936K, paused 5ms+1ms, total 25ms
,D/dalvikvm( 5129): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SELinux ( 5150): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5150):  
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 2421): Killing 4199:com.sec.dsm.system/1000 (adj 15): empty #43
,I/SELinux ( 5150): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5150):  
I/SELinux ( 5150):  
,I/SELinux ( 5150): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5150): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5150): >>>>> Normal User
,E/dalvikvm( 5150): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,E/SELinux ( 5150): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/TimaKeyStoreProvider( 5150): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5150): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5150): Added TimaKesytore provider
,I/SurfaceFlinger( 1921): id=16 Removed iello (9/10)
,I/SurfaceFlinger( 1921): id=16 Removed iello (-2/10)
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4967): Resource data:2131099648
,I/System.out( 5057): Thread-369(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/AMMetaDataParserService( 4967): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/System.out( 5057): Thread-369(ApacheHTTPLog):isShipBuild true
,I/System.out( 5057): Thread-369(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/chromium( 5073): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,E/AndroidProtocolHandler( 5073): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 5 sec
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
D/dalvikvm( 5150): GC_CONCURRENT freed 3000K, 32% free 9572K/13940K, paused 3ms+4ms, total 24ms
,D/dalvikvm( 5150): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 370, Delta = 10
,D/JsMessageQueue( 5073): Set native->JS mode to OnlineEventsBridgeMode
,I/CameraApp( 5150): CameraApp.onCreate()... mFeature : null
,I/testFeature( 5150): Feature.Feature(context)
I/testFeature( 5150): Feature.readInternalDefaultXml()
,I/testFeature( 5150): ResetFeatureValue
I/CameraFirmware_broadcast( 5150): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 5150): CameraApp.getAppFeature()...
,I/SELinux ( 5168): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5168):  
,I/ActivityManager( 2421): Killing 4211:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 13% free 9502K/10916K, paused 3ms+5ms, total 33ms
I/SELinux ( 5168): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5168):  
I/SELinux ( 5168):  
,I/SELinux ( 5168): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5168): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5168): >>>>> Normal User
,E/dalvikvm( 5168): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
,E/SELinux ( 5168): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10916K, paused 2ms+3ms, total 26ms
,I/HarmonyEASService( 2421): Updating for all 1
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10916K, paused 2ms+2ms, total 24ms
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/TimaKeyStoreProvider( 5168): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5168): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5168): Added TimaKesytore provider
,I/chromium( 5073): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/dalvikvm( 5073): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x4292a0c8
,I/chromium( 5073): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/dalvikvm( 5073): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x4292a0c8
D/jxcore_app_log( 5073): JniHelper::setJavaVM(0x41e77220), pthread_self() = 2026219856
,D/JX-Cordova( 5073): jxcore cordova android initializing
E/libGLESv2( 5073): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 5073): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/dalvikvm( 5168): GC_CONCURRENT freed 3006K, 32% free 9559K/13936K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 5168): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/PackageManager( 2421): [MSG] MCS_UNBIND
I/PackageManager( 2421): calling disconnectService()
,D/PackageIntentReceiver( 5168): ACTION_BOOT_COMPLETED
D/PackageManager( 2421): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2421): Killing 4224:com.sec.factory/1000 (adj 15): empty #43
,D/PackageIntentReceiver( 5168): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,I/ActivityManager( 2421): Killing 3146:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #43
D/        ( 4967): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4967): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4967): Resource data:2131099648
I/AMMetaDataParserService( 4967): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
,I/SELinux ( 5182): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5182):  
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 5182): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5182):  
I/SELinux ( 5182):  
,I/SELinux ( 5182): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5182): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5182): >>>>> Normal User
,E/dalvikvm( 5182): >>>>> com.google.android.gm [ userId:0 | appId:10106 ]
,E/SELinux ( 5182): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5182): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5182): Cannot add TimaSignature Service, License check Failed
,D/        ( 4967): PNG_doEncode true 106, 106
D/ActivityThread( 5182): Added TimaKesytore provider
,I/AMMetaDataParserService( 4967): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,W/jxcore-log( 5073): Initializing JXcore engine
,W/jxcore-log( 5073): JXcore engine is ready
D/dalvikvm( 5182): GC_CONCURRENT freed 2990K, 32% free 9580K/13940K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 5182): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,W/jxcore-log( 5073): Starting JXcore engine
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4967): Resource data:2131099648
I/AMMetaDataParserService( 4967): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
D/        ( 4967): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4967): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,W/GAV2    ( 5182): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/GAV2    ( 3611): Thread[GAThread,5,main]: No campaign data found.
,I/SELinux ( 5208): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5208):  
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
W/jxcore-log( 5073): Platform android
W/jxcore-log( 5073): 
W/jxcore-log( 5073): Process ARCH arm
W/jxcore-log( 5073): 
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 5208): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5208):  
I/SELinux ( 5208):  
,I/SELinux ( 5208): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5208): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5208): >>>>> Normal User
,E/dalvikvm( 5208): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 5208): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
,I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 6 sec
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4967): Resource data:2131099671
,D/TimaKeyStoreProvider( 5208): in addTimaSignatureService
I/AMMetaDataParserService( 4967): getResourceName:com.android.mms:xml/searchable
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
D/TimaKeyStoreProvider( 5208): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
,I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
,D/ActivityThread( 5208): Added TimaKesytore provider
I/AMMetaDataParserService( 4967): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
,I/jxcore-log( 5073): JXcore Cordova bridge is ready!
I/jxcore-log( 5073): 
,W/jxcore-log( 5073): JXcore engine is started
,I/Choreographer( 5073): Skipped 45 frames!  The application may be doing too much work on its main thread.
E/libGLESv2( 5073): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 5073): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/dalvikvm( 5057): GC_CONCURRENT freed 2014K, 25% free 10518K/13936K, paused 3ms+2ms, total 89ms
,D/dalvikvm( 5057): WAIT_FOR_CONCURRENT_GC blocked 83ms
,I/System.out( 5057): pool-4-thread-1 calls detatch()
,D/dalvikvm( 5208): GC_CONCURRENT freed 2999K, 32% free 9569K/13936K, paused 3ms+1ms, total 65ms
,D/dalvikvm( 5208): WAIT_FOR_CONCURRENT_GC blocked 55ms
,D/dalvikvm( 4967): GC_CONCURRENT freed 1826K, 21% free 12309K/15500K, paused 11ms+6ms, total 105ms
,D/dalvikvm( 4967): WAIT_FOR_CONCURRENT_GC blocked 44ms
,I/SELinux ( 5224): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5224):  
,I/ActivityManager( 2421): Killing 4278:com.sec.android.diagmonagent/1000 (adj 15): empty #43
E/jxcore-log( 5073): >> samsung-SM-G800F
E/jxcore-log( 5073): 
,I/jxcore-log( 5073): Total memory 1319530496
I/jxcore-log( 5073): 
I/jxcore-log( 5073): Free memory 31649792
I/jxcore-log( 5073): 
,I/jxcore-log( 5073): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5073): 
,I/jxcore-log( 5073): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5073): 
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4967): Resource data:2131165216
,I/jxcore-log( 5073): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5073): 
I/jxcore-log( 5073): Size 720 1280
I/jxcore-log( 5073): 
I/SELinux ( 5224): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5224):  
I/SELinux ( 5224):  
,I/SELinux ( 5224): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5224): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5224): >>>>> Normal User
E/dalvikvm( 5224): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/jxcore-log( 5073): Screen Brightness 134
I/jxcore-log( 5073): 
,E/SELinux ( 5224): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/jxcore-log( 5073): Dummy Error Log.
E/jxcore-log( 5073): 
,D/        ( 4967): PNG_doEncode true 80, 80
,I/AMMetaDataParserService( 4967): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,D/TimaKeyStoreProvider( 5224): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5224): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5224): Added TimaKesytore provider
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429086
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131296695
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429086
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429071
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429071
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wifi_settings
,I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429071
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131297114
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ApnSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429073
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429073
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429095
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/mirror_link_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429086
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131296695
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429086
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131296695
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429071
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131297114
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429086
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131296695
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429086
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131296695
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
,I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429086
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131296695
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429086
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131296695
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429086
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131296695
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429146
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429118
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429118
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429118
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429118
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429118
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429118
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131298419
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429118
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131298419
,I/Gmail   ( 5182): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 292, prevStep = 4, currStep = 4
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/language_keyboard_settings_title
,I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429118
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131298419
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429103
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429103
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429100
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429100
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429099
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429099
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429109
I/Gmail   ( 5182): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429100
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429113
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429113
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429100
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131297804
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/display_settings
,I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429100
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429155
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.users.UserOptions
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429055
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429055
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429055
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.LaunchApplication
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429054
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429054
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/home_settings
,I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429055
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429055
I/Gmail   ( 5182): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
,I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429055
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429080
I/Gmail   ( 5182): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429151
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429151
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131296750
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/security_settings_title
,I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429151
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429050
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/privacy_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429151
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131296750
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429151
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131296750
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429114
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429114
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131298587
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
,D/dalvikvm( 2421): GC_EXPLICIT freed 4037K, 19% free 24454K/29976K, paused 9ms+16ms, total 195ms
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429114
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131298587
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429118
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429107
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/driving_mode
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429150
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429152
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429086
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4967): Resource data:2131296695
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429092
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429152
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429150
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131297938
,I/ActivityManager( 2421): Waited long enough for: ServiceRecord{437ae730 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429150
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131297938
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429088
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429090
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 4967): Resourc,e data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429094
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131296695
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429148
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429148
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429046
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429144
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429151
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429151
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429151
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429086
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429100
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429135
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429213
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429151
D/dalvikvm( 5224): GC_CONCURRENT freed 2997K, 32% free 9572K/13940K, paused 2ms+2ms, total 23ms
D/dalvikvm( 5224): WAIT_FOR_CONCURRENT_GC blocked 17ms
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429128
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429112
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429112
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131299843
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/power_saving_mode_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429112
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429112
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/power_saving_mode
,I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429149
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/power_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429113
W/ContextImpl( 5224): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4967): Resource data:1
W/ResourceType( 4967): No package identifier when getting name for resource number 0x00000001
W/System.err( 4967): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 4967): 	at android.content.res.Resources.getResourceName(Resources.java:2988)
W/System.err( 4967): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 4967): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 4967): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 4967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4967): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429126
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131301070
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429100
I/knox    ( 5224): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131297804
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429130
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/header_display_notification_panel
,W/ContextImpl( 5224): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429120
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429121
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/knox    ( 5224): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/AMMetaDataParserService( 4967): Resource data:2131429133
D/knox    ( 5224): KNOXAgentService : onCreate()
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131300118
D/knox    ( 5224): KNOXAgentService : set alarms for deniallog and usage data upload
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429123
D/knox    ( 5224): KNOXAgentService. startJobThread() start
D/knox    ( 5224): KNOXAgentService. JobThread()
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 4967): Resourc,e data:Inside bundle  check
D/knox    ( 5224): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 5224): KNOXAgentService. startJobThread() wait
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429187
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429124
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429218
I/SELinux ( 5243): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5243):  
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429155
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429126
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429126
D/knox    ( 5224): mKnoxAgentEngine.ELMEngine( context , reStart:true).
D/knox    ( 5224): KNOXAgentService : onDestroy().
D/knox    ( 5224): ModuleBase.cancelAllAlarmManageModule()
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429126
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429126
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$OneHandEditMenuActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429100
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429100
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429100
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429212
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429099
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131301505
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429130
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429130
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131302906
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429106
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2130838226
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 4967): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429143
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429136
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
,I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429136
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429104
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429139
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429140
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429080
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131302078
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429080
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131302078
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429080
I/SELinux ( 5243): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5243):  
I/SELinux ( 5243):  
,I/SELinux ( 5243): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131302107
E/SELinux ( 5243): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5243): >>>>> Normal User
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/place_settings_title
E/dalvikvm( 5243): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429086
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429086
E/SELinux ( 5243): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429044
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429049
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429122
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131297804
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429078
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429131
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429131
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 4967): getResourceTypeNameid
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429122
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2130838278
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:drawable/ic_settings_torchlight
,I/AMMetaDataParserService( 4967): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2130838278
D/TimaKeyStoreProvider( 5243): in addTimaSignatureService
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 4967): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429129
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429129
D/TimaKeyStoreProvider( 5243): Cannot add TimaSignature Service, License check Failed
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.SearchActivity
D/ActivityThread( 5243): Added TimaKesytore provider
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4967): Resource data:2131165371
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:xml/searchable
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429051
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429114
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4967): Resource data:2131298587
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 4967): getResourceTypeNamestring
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
,I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429125
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429185
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
,I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429147
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/safetycare_settings
,I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429147
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4967): Resource data:2131429203
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429203
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429075
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429169
,I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429138
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2130838226
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 4967): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4967): Resource data:2131429119
I/AMMetaDataParserService( 4967): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 4967): getResourceTypeNameid
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4967): Resource data:2131034120
,I/AMMetaDataParserService( 4967): getResourceName:com.android.contacts:xml/searchable
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4967): Resource data:2131034113
I/AMMetaDataParserService( 4967): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
,I/jxcore-log( 5073): getBuffer is called!!!!
I/jxcore-log( 5073): 
D/dalvikvm( 5243): GC_CONCURRENT freed 3001K, 32% free 9566K/13936K, paused 4ms+2ms, total 32ms
,D/dalvikvm( 5243): WAIT_FOR_CONCURRENT_GC blocked 24ms
,E/KnoxSetupWizardClient( 5243): isShipMode : 1
,I/KnoxSetupWizardClient( 5243): onReceive : android.intent.action.BOOT_COMPLETED
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,W/System.err( 5243): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 5243): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 5243): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 5243): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
D/ShortcutReceiver2( 5243):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,W/System.err( 5243): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 5243): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
W/System.err( 5243): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/yash    ( 5243): setDisableWidget>size:0
W/System.err( 5243): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
,W/System.err( 5243): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 5243): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 5243): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 5243): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
,W/System.err( 5243): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
W/System.err( 5243): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
,W/System.err( 5243): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/SELinux ( 5256): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5256):  
,I/ActivityManager( 2421): Killing 4311:com.fmm.dm/1000 (adj 15): empty #43
D/        ( 4967): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4967): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/        ( 4967): PNG_doEncode true 106, 106
I/SELinux ( 5256): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5256):  
I/SELinux ( 5256):  
,I/SELinux ( 5256): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5256): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 4967): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,E/dalvikvm( 5256): >>>>> Normal User
,E/dalvikvm( 5256): >>>>> com.LocalFota [ userId:0 | appId:10113 ]
,E/SELinux ( 5256): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5256): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 5256): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 5256): Added TimaKesytore provider
,D/        ( 4967): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4967): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530,
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity,
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check,
I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 7 sec
,I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4967): Resource data:2131034113
,I/AMMetaDataParserService( 4967): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,D/dalvikvm( 5256): GC_CONCURRENT freed 3006K, 32% free 9565K/13940K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 5256): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/DBG_WSS_LF( 5256): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
,I/DBG_WSS_LF( 5256): [20.0040.140326][Line:27][<init>] First call
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/DBG_WSS_LF( 5256): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_WSS_LF( 5256): [20.0040.140326][Line:31][onReceive] *** boot complete ***
,I/DBG_WSS_LF( 5256): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
,I/DBG_WSS_LF( 5256): [20.0040.140326][Line:41][onReceive] nStatus : -1
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/SELinux ( 5271): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5271):  
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4967): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 4967): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 4967): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4967): Resource data:2131034112
I/ActivityManager( 2421): Killing 4292:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
,D/dalvikvm( 5073): GC_CONCURRENT freed 2391K, 27% free 10214K/13972K, paused 2ms+3ms, total 32ms
I/SELinux ( 5271): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5271):  
I/SELinux ( 5271):  
,I/SELinux ( 5271): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/AMMetaDataParserService( 4967): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
,E/SELinux ( 5271): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5271): >>>>> Normal User
,E/dalvikvm( 5271): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
,E/SELinux ( 5271): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
,D/TimaKeyStoreProvider( 5271): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5271): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5271): Added TimaKesytore provider
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
,D/dalvikvm( 5271): GC_CONCURRENT freed 2998K, 32% free 9570K/13940K, paused 14ms+1ms, total 30ms
,D/dalvikvm( 5271): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
,D/StatusChecker( 5271): onReceive : android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 4967): GC_CONCURRENT freed 2003K, 22% free 12276K/15644K, paused 3ms+3ms, total 47ms
,I/SELinux ( 5285): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5285):  
I/ActivityManager( 2421): Killing 3171:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sams,ung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
I/AMMetaDataParserService( 4967): Resource data:2131034113
I/SELinux ( 5285): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5285):  
I/SELinux ( 5285):  
I/SELinux ( 5285): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 4967): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4967): getResourceTypeNamexml
E/SELinux ( 5285): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5285): >>>>> Normal User
E/dalvikvm( 5285): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10135 ]
,E/SELinux ( 5285): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/AlarmManager( 2421): waitForAlarm result :4
V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,D/TimaKeyStoreProvider( 5285): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5285): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5285): Added TimaKesytore provider
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/dalvikvm( 5285): GC_CONCURRENT freed 3014K, 32% free 9559K/13940K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 5285): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,D/dalvikvm( 2722): GC_EXPLICIT freed 396K, 34% free 9924K/14832K, paused 4ms+6ms, total 40ms
,D/QuickConnect( 5285): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,I/iu.UploadsManager( 3311): End new media; added: 0, uploading: 0, time: 141 ms
,W/BackupManagerService( 2421): dataChanged but no participant pkg='com.android.providers.settings' uid=10135
D/QuickConnect( 5285): Utils.setQCRunningSetting - set : 0
I/QuickConnect( 5285): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
D/        ( 4967): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4967): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
V/QuickConnect( 5285): SconnectManager.getInstance - () return existing instance null
W/ContextImpl( 5285): Implicit intents with startService are not safe: Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } android.content.ContextWrapper.startServiceAsUser:517 android.content.ContextWrapper.startServiceAsUser:517 com.samsung.android.sconnect.periph.PeriphStartReceiver.onReceive:30 
,I/QuickConnect( 5285): PeriphService.onCreate - [START]
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4967): Resource data:2131034116
I/AMMetaDataParserService( 4967): getResourceName:com.android.contacts:xml/findo_searchable
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
,I/SELinux ( 5299): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5299):  
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4967): Resource data:2131099668
I/QuickConnect( 5285): PeriphService.onCreate - [START] USER_OWNER
,D/QuickConnect( 5285): PeriphService.setProcessForeground - Build.VERSION.SDK_INT = 19
,I/QuickConnect( 5285): PeriphService.setProcessForeground - true of JB_MR2 complete 
I/QuickConnect( 5285): PeriphService.setState - 0 >> 1
,V/QuickConnect( 5285): PeriphService.runService - ,
I/AMMetaDataParserService( 4967): getResourceName:com.sec.android.app.sbrowser:xml/searchable
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml,
I/AMMetaDataParserService( 4967): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 4967): Resource data:2131099650,
I/QuickConnect[1.1][2] ( 5285): SconnectManager.SconnectManager - initiate from com.samsung.android.sconnect.periph.PeriphService@42933918
I/QuickConnect[1.1][2] ( 5285): SconnectManager.SconnectManager - set getApplicationContext android.app.Application@429210b0
D/QuickConnect[1.1][2] ( 5285): SconnectManager.registerBroadcast - --,
I/AMMetaDataParserService( 4967): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist,
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml,
,D/QuickConnect[1.1][2] ( 5285): SconnectManager.SconnectManager - REQUEST_ID :  1,
,D/QuickConnect[1.1][2] ( 5285): ScanThread.ScanThread - created!,
,V/QuickConnect[1.1][2] ( 5285): BluetoothHelper.BluetoothHelper - ,
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,I/SELinux ( 5299): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5299):  
I/SELinux ( 5299):  
,I/SELinux ( 5299): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5299): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5299): >>>>> Normal User
,E/dalvikvm( 5299): >>>>> com.sec.android.service.bezel [ userId:0 | appId:1000 ]
,E/SELinux ( 5299): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/QuickConnect[1.1][2] ( 5285): BluetoothHelper.registerBluetoothAdapterReceiver - mIsBluetoothAdapterReceiver = false
,D/TimaKeyStoreProvider( 5299): in addTimaSignatureService
,V/QuickConnect[1.1][2] ( 5285): BleHelper.BleHelper - Constructor
,D/TimaKeyStoreProvider( 5299): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5299): Added TimaKesytore provider
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
,E/QuickConnect[1.1][2] ( 5285): BleHelper.startScan - not isGattServiceReady. Try to BLE On calling addLeRadioReference()
,D/BluetoothRadioManager( 5285): addLeRadioReference: Add CB  com.samsung.android.sconnect.common.net.BleHelper$GattServiceStateChangeCallback@42947a68
D/BluetoothRadioManager( 5285):  addRadioReference enabled = false
,D/BluetoothRadioManager( 5285):  BLE Radio count is : 1
,D/BluetoothRadioManager( 5285): addRadioReference()  registerRadioClient mUUID = e1a41dc5-dbce-4f92-99e1-d9b36332eb4a
,D/BluetoothManagerService( 2421): foregroundUser: 0
,D/dalvikvm( 4967): GC_FOR_ALLOC freed 820K, 24% free 12017K/15688K, paused 32ms, total 32ms
,E/BluetoothManagerService( 2421): Package is exist.
,D/BluetoothRadioManager( 5285): addLeRadioReference: isRadioEnabled() =  false
,V/QuickConnect[1.1][2] ( 5285): BleHelper.mSearchWearable - true
,I/bluedroid( 4003): update_radio_count
D/BluetoothAdapterState( 4003): CURRENT_STATE=ON, MSG = USER_TURN_ON_RADIO
,I/BluetoothAdapterState( 4003): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=false
D/BluetoothAdapterState( 4003): CURRENT_STATE=PENDING, MSG = BEGIN_ENABLE_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
,I/bluedroid( 4003): enable
,E/bt-btif ( 4003): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
,E/bt-btif ( 4003): btif_sock_init, radio_req:1, rfc_init:1, vhci_init:1
,D/BluetoothAdapterState( 4003): CURRENT_STATE=PENDING, MSG = ENABLED_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
I/BluetoothAdapterState( 4003): Bluetooth adapter radio state changed: 14
,D/BluetoothAdapterService( 4003): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 4003): updateAdapterState state is 14
,D/BluetoothAdapterService( 4003): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 4003): Autoconnection is available 
,D/BluetoothManagerService( 2421): Broadcasting Radio() to 1 Radio Mgr receivers.
D/BluetoothAdapterService( 4003): updateAdapterState prevState = 12newState = 14
V/QuickConnect[1.1][2] ( 5285): UpnpHelper.UpnpHelper - 
,D/BluetoothRadioManager( 5285): onBTRadioStateChange:  up = true
,I/BluetoothAdapterState( 4003): Entering On State from state = 12
,V/QuickConnect[1.1][2] ( 5285): JmdnsHelper.JmdnsHelper - Constructor
,V/QuickConnect[1.1][2] ( 5285): P2pHelper.P2pHelper - EXEC
D/QuickConnect[1.1][2] ( 5285): p2pHelperWorkThread.p2pHelperWorkThread - created!
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
,E/QuickConnect[1.1][2] ( 5285): BleHelper.onGattServiceStateChange - up = true, BluetoothGatt is android.bluetooth.IBluetoothGatt$Stub$Proxy@4299bd68
,E/QuickConnect[1.1][2] ( 5285): BleHelper.onGattServiceStateChange - Radio turned on
,D/QuickConnect[1.1][2] ( 5285): WifiHelper.WifiHelper -  -- 
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
D/dalvikvm( 5299): GC_CONCURRENT freed 3000K, 32% free 9565K/13932K, paused 3ms+1ms, total 36ms
D/dalvikvm( 5299): WAIT_FOR_CONCURRENT_GC blocked 24ms
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 4967): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
,D/WifiDisplayAdapter( 2421): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/QuickConnect[1.1][2] ( 5285): CentralActionManager.CentralActionManager - EXEC
V/QuickConnect[1.1][2] ( 5285): BluetoothOppActionHelper.BluetoothOppActionHelper - 
V/QuickConnect[1.1][2] ( 5285): GroupVoiceTalkActionHelper.GroupVoiceTalkActionHelper -  --
V/QuickConnect[1.1][2] ( 5285): SmartHomeActionHelper.SmartHomeActionHelper - --
V/QuickConnect[1.1][2] ( 5285): ScreenMirrorActionHelper.ScreenMirrorActionHelper - 
D/BezelQuickConnect( 5299): BezelBroadcastReceiver - onReceive : android.intent.action.BOOT_COMPLETED
D/BezelQuickConnect( 5299): BezelBroadcastReceiver - StartBezelInteractionService
V/QuickConnect[1.1][2] ( 5285): BluetoothActionHelper.BluetoothActionHelper - 
D/BezelQuickConnect( 5299): BezelManagerService - setProcessForeground, Build.VERSION.SDK_INT = 19
I/BezelQuickConnect( 5299): BezelManagerService - setProcessForeground, true of JB_MR2 complete 
D/BezelQuickConnect( 5299): BezelBroadcastReceiver - onReceive : Send to quickpanel - service.ENABLED
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setu,p.AccountSetupAutoDiscover
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4967): Resource data:2131099667
,W/ContextImpl( 5299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.android.service.bezel.BezelBroadcastReceiver.onReceive:40 android.app.ActivityThread.handleReceiver:2698 
V/PhoneStatusBar( 2581): onReceive: Intent { act=com.sec.android.sconnect.service.ENABLED flg=0x10 }mQconnectEnable = true
I/AMMetaDataParserService( 4967): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
,E/NetworkSettingsReceiver( 3230): onReceive: android.intent.action.BOOT_COMPLETED
D/STATUSBAR-PhoneStatusBar( 2581): showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
,E/BluetoothHeadset( 5285): BTStateChangeCB is registed
,E/BluetoothHeadset( 5285): BluetoothHeadset service is binded
,I/QuickConnect[1.1][2] ( 5285): SconnectManager.getInstance - make new instance com.samsung.android.sconnect.SconnectManager@42936488
,V/QuickConnect[1.1][2] ( 5285): SconnectManager.getInstance - return existing instance com.samsung.android.sconnect.SconnectManager@42936488
D/        ( 4967): PNG_doEncode true 106, 106
V/QuickConnect[1.1][2] ( 5285): PreDiscoveryHelper.PreDiscoveryHelper -  -- 
,D/QuickConnect[1.1][2] ( 5285): PreDiscoveryHelper.setVisibilityFromSystemDb - --
,W/BroadcastQueue( 2421): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.android.calendar/.magazine.CalendarUpdateRelatedDataReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
I/AMMetaDataParserService( 4967): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559
D/QuickConnect[1.1][2] ( 5285): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 5285): Utils.getFromDb -  Key[quick_connect_contact_only], isEnabled [1] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 5285): PreDiscoveryHelper.setVisibilityFromSystemDb - isAllowToConnect : false, isContactOnly : true, visibilitySetting : 2
D/QuickConnect[1.1][2] ( 5285): PreDiscoveryHelper.changeResponseSetting - changed: 2
V/QuickConnect[1.1][2] ( 5285): PreDiscoveryHelper.updateAdvData - 
V/QuickConnect[1.1][2] ( 5285): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42936488
,D/QuickConnect[1.1][2] ( 5285): WifiHelper.isEnableMobileAP - HOTSPOT Disabled
,I/SELinux ( 5316): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5316):  
,V/QuickConnect[1.1][2] ( 5285): PreDiscoveryHelper.updateRespTarget - 
,D/QuickConnect[1.1][2] ( 5285): PreDiscoveryHelper.initializeAdvData - 
V/QuickConnect[1.1][2] ( 5285): PreDiscoveryHelper.initializeAdvData - name: S5mini-1(8)
D/QuickConnect[1.1][2] ( 5285): PreDiscoveryHelper.initializeAdvData - name selected: S5mini-1(8)
,V/QuickConnect[1.1][2] ( 5285): CONTACT_Info.getMyMobileNumber - 
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558
,I/SELinux ( 5316): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5316):  
I/SELinux ( 5316):  
,I/SELinux ( 5316): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5316): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5316): >>>>> Normal User
,E/dalvikvm( 5316): >>>>> com.sec.android.app.camera [ userId:0 | appId:10149 ]
D/QuickConnect[1.1][2] ( 5285): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 5285): CONTACT_Info.getMyMobileNumber - null 
,E/SELinux ( 5316): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/QuickConnect[1.1][2] ( 5285): NetUtil.getP2pMacFromWifiMac - ($)
,V/QuickConnect[1.1][2] ( 5285): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42936488
,W/QuickConnect[1.1][2] ( 5285): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.emeeting.b2c.hancom
,D/QuickConnect[1.1][2] ( 5285): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.emeeting
,D/QuickConnect[1.1][2] ( 5285): AppPackageUtil.isStubApk - but Stub version[2.7.025] of com.samsung.groupcast
W/QuickConnect[1.1][2] ( 5285): AppPackageUtil.isAppInstalled - this is Stub - com.samsung.groupcast
D/QuickConnect[1.1][2] ( 5285): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.samsung.groupcast
,D/        ( 4967): PNG_doEncode true 106, 106
W/QuickConnect[1.1][2] ( 5285): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.sidesync30
I/AMMetaDataParserService( 4967): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
,D/QuickConnect[1.1][2] ( 5285): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.sidesync30
,D/TimaKeyStoreProvider( 5316): in addTimaSignatureService
,D/QuickConnect[1.1][2] ( 5285): PeriphService.registerUserReceiver - mIsUserReceiver == false
,I/QuickConnect[1.1][2] ( 5285): PeriphService.onStartCommand - USER_OWNER
I/QuickConnect[1.1][2] ( 5285): PeriphService.onStartCommand - Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } flags[0] startId[1]
,I/QuickConnect[1.1][2] ( 5285): PeriphService.onStartCommand - Action: com.samsung.android.sconnect.periph.START_SERVICE
D/QuickConnect[1.1][2] ( 5285): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,D/QuickConnect[1.1][2] ( 5285): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/TimaKeyStoreProvider( 5316): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5316): Added TimaKesytore provider
D/QuickConnect[1.1][2] ( 5285): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/BluetoothA2dp( 5285): Proxy object connected
,D/SensorService( 2421):   0.3 0.0 9.8
,D/QuickConnect[1.1][2] ( 5285): A2dpProfile.onServiceConnected - Bluetooth service connected
D/WifiP2pService( 2421): InactiveState{ what=139287 }
D/WifiP2pService( 2421): P2pEnabledState{ what=139287 }
,D/WifiP2pService( 2421): DefaultState{ what=139287 }
D/QuickConnect[1.1][2] ( 5285): HeadsetProfile.onServiceConnected - Bluetooth service connected
D/BluetoothInputDevice( 5285): Proxy object connected
D/QuickConnect[1.1][2] ( 5285): HidProfile.onServiceConnected - Bluetooth service connected
D/QuickConnect[1.1][2] ( 5285): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
,D/dalvikvm( 5316): GC_CONCURRENT freed 3008K, 32% free 9556K/13936K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 5316): WAIT_FOR_CONCURRENT_GC blocked 17ms
,W/dalvikvm( 5316): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2421): Killing 4351:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
,I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 8 sec
,I/SELinux ( 5330): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5330):  
,I/QuickConnect[1.1][2] ( 5285): BleAdvertiser.BleAdvertiser - Constructor
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 4967): Resource data:2131099689
I/AMMetaDataParserService( 4967): getResourceName:com.android.email:xml/spellscroll
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4967): Resource data:2131099685
I/AMMetaDataParserService( 4967): getResourceName:com.android.email:xml/searchable
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
I/AMMetaDataParserService( 4967): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 4967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4967): getResourcePackageName:com.android.keyguard.layout
,I/AMMetaDataParserService( 4967): Resource data:2130903052
I/AMMetaDataParserService( 4967): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
I/AMMetaDataParserService( 4967): getResourceTypeNamelayout
I/AMMetaDataParserService( 4967): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4967): Resource data:2131034112
I/AMMetaDataParserService( 4967): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 4967): getResourceTypeNamexml
,D/BluetoothGattServer( 5285): registerCallback()
,D/BluetoothGattServer( 5285): registerCallback() - UUID=b916a159-640e-4839-8d37-86badf5cf621
I/SELinux ( 5330): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5330):  
I/SELinux ( 5330):  
,I/SELinux ( 5330): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5330): >>>>> Normal User
,E/dalvikvm( 5330): >>>>> com.android.email [ userId:0 | appId:10157 ]
D/BtGatt.GattService( 4003): registerServer() - UUID=b916a159-640e-4839-8d37-86badf5cf621
E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BtGatt.btif( 4003): btif_gatts_register_app
D/BtGatt.btif( 4003): btgatts_handle_event: Event 2000
E/bt-btif ( 4003): register application first_unuse rcb_idx = 0
D/BtGatt.btif( 4003): btapp_gatts_handle_cback: Event 0
,D/BtGatt.GattService( 4003): onServerRegistered() - UUID=b916a159-640e-4839-8d37-86badf5cf621, serverIf=5
,D/BluetoothGattServer( 5285): onServerRegistered() - status=0 serverIf=5
V/QuickConnect[1.1][2] ( 5285): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5285): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,V/QuickConnect[1.1][2] ( 5285): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42936488
,V/QuickConnect[1.1][2] ( 5285): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42936488
V/QuickConnect[1.1][2] ( 5285): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5285): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42936488
V/QuickConnect[1.1][2] ( 5285): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42936488
,V/QuickConnect[1.1][2] ( 5285): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42936488
D/QuickConnect[1.1][2] ( 5285): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5285): BleHelper.startScan - bluetoothActionState = 0
,D/QuickConnect[1.1][2] ( 5285): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5285): BleHelper.startScan - shouldScanBleFg = false
,D/TimaKeyStoreProvider( 5330): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5330): Cannot add TimaSignature Service, License check Failed
D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,D/ActivityThread( 5330): Added TimaKesytore provider
,D/        ( 4967): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4967): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
,D/dalvikvm( 5330): GC_CONCURRENT freed 2984K, 32% free 9585K/13936K, paused 1ms+2ms, total 20ms
,D/dalvikvm( 5330): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 4967): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
I/ActivityManager( 2421): Killing 3378:com.sec.android.app.mss/u0a21 (adj 15): empty #43
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/BadgeProvider( 4737): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2764): reloadBadges entered.
D/BadgeProvider( 4737): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4737): sendNotify, [notify] : null
D/BadgeProvider( 4737): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4737): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4737): update, [UpdateCount] : 1
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,W/ActivityManager( 2421): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5354): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5354):  
,I/ActivityManager( 2421): Killing 4368:com.sec.android.app.msa/u0a23 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 13% free 9502K/10916K, paused 4ms+5ms, total 49ms
I/SELinux ( 5354): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5354):  
I/SELinux ( 5354):  
,I/SELinux ( 5354): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5354): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5354): >>>>> Normal User
,E/dalvikvm( 5354): >>>>> com.android.exchange [ userId:0 | appId:10158 ]
,E/SELinux ( 5354): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/ActivityManager( 2421): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10916K, paused 3ms+3ms, total 31ms
,D/TimaKeyStoreProvider( 5354): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5354): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5354): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10916K, paused 3ms+4ms, total 31ms
,I/Process ( 5330): Sending signal. PID: 5330 SIG: 9
,I/ActivityManager( 2421): Process com.android.email (pid 5330) (adj 9) has died.,
,D/dalvikvm( 5354): GC_CONCURRENT freed 3006K, 32% free 9568K/13940K, paused 2ms+2ms, total 21ms,
,D/dalvikvm( 5354): WAIT_FOR_CONCURRENT_GC blocked 18ms,
,I/SELinux ( 5368): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 5368):  
,D/PowerManagerService( 2421): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2421): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2421): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2421): lcd : 2 +,
D/RampAnimator( 2421): Light Animator Finished currentValue=2,
,I/SELinux ( 5373): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 5373):  
,I/SELinux ( 5368): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 5368):  
I/SELinux ( 5368):  
D/lights  ( 2421): lcd : 2 -
,I/SELinux ( 5368): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5368): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5368): >>>>> Normal User
D/LightsService( 2421): Excessive delay setting light: 51ms
,E/dalvikvm( 5368): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 5368): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5368): in addTimaSignatureService
I/SELinux ( 5373): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5373):  
I/SELinux ( 5373):  
,I/SELinux ( 5373): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5373): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5373): >>>>> Normal User
E/dalvikvm( 5373): >>>>> com.android.email [ userId:0 | appId:10157 ]
,D/TimaKeyStoreProvider( 5368): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5368): Added TimaKesytore provider
,E/SELinux ( 5373): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5373): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5373): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5373): Added TimaKesytore provider
,I/ActivityManager( 2421): Killing 4382:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5368): GC_CONCURRENT freed 2997K, 32% free 9572K/13940K, paused 7ms+2ms, total 33ms
,D/dalvikvm( 5368): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 9 sec
,D/dalvikvm( 5373): GC_CONCURRENT freed 2994K, 32% free 9572K/13936K, paused 3ms+3ms, total 28ms
,D/dalvikvm( 5373): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/SELinux ( 5396): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5396):  
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
I/ActivityManager( 2421): Killing 4395:com.android.onetimeinitializer/u0a28 (adj 15): empty #43
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,I/SELinux ( 5396): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5396):  
I/SELinux ( 5396):  
,I/SELinux ( 5396): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5396): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5396): >>>>> Normal User
,E/dalvikvm( 5396): >>>>> com.sec.modem.settings [ userId:0 | appId:1000 ]
,E/SELinux ( 5396): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5396): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5396): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5396): Added TimaKesytore provider
,D/BadgeProvider( 4737): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2764): reloadBadges entered.
D/BadgeProvider( 4737): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4737): sendNotify, [notify] : null
D/BadgeProvider( 4737): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4737): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4737): update, [UpdateCount] : 1
,I/Process ( 5354): Sending signal. PID: 5354 SIG: 9
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,I/ActivityManager( 2421): Process com.android.exchange (pid 5354) (adj 9) has died.
D/dalvikvm( 5396): GC_CONCURRENT freed 3004K, 32% free 9565K/13936K, paused 4ms+2ms, total 23ms
D/dalvikvm( 5396): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/SELinux ( 5417): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5417):  
W/ActivityManager( 2421): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5417): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5417):  
I/SELinux ( 5417):  
,I/SELinux ( 5417): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5417): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5417): >>>>> Normal User
,E/dalvikvm( 5417): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 5417): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5417): in addTimaSignatureService
D/TimaKeyStoreProvider( 5417): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5417): Added TimaKesytore provider
,D/dalvikvm( 5417): GC_CONCURRENT freed 3002K, 32% free 9566K/13940K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 5417): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 2421): GC_EXPLICIT freed 1372K, 20% free 24278K/29976K, paused 6ms+17ms, total 194ms
,D/NotiRemoteService( 5417): action com.peel.widget.notification.SETUP_SERVICE_CONNECTION
,D/NotiRemoteService( 5417): connectToPeelService 0
I/SELinux ( 5437): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5437):  
,W/ContextImpl( 5417): Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:529 tv.peel.samsung.widget.a.c.<init>:68 tv.peel.samsung.widget.NotiRemoteService.a:554 
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/NotiRemoteService( 5417): onServiceOn() mServiceState = 1
,D/NotiRemoteService( 5417): Send action to self com.peel.widget.notification.SERVICE_BINDED
,D/NotiRemoteService( 5417): action com.peel.widget.notification.SERVICE_BINDED
,D/NotiRemoteService( 5417): feature is Off. Stop service
,D/NotiRemoteService( 5417): Send action to self com.peel.widget.notification.STOP_PROCESS
,D/NotiRemoteService( 5417): action com.peel.widget.notification.STOP_PROCESS
,D/NotiRemoteService( 5417): onDestroy()
,D/NotiRemoteService( 5417): mOrientationChangeReceier was not registered
,I/SELinux ( 5437): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5437):  
I/SELinux ( 5437):  
,I/SELinux ( 5437): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5437): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5437): >>>>> Normal User
,E/dalvikvm( 5437): >>>>> org.simalliance.openmobileapi.service [ userId:0 | appId:1101 ]
,E/SELinux ( 5437): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5437): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5437): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5437): Added TimaKesytore provider
,D/dalvikvm( 5437): GC_CONCURRENT freed 3000K, 32% free 9573K/13940K, paused 4ms+1ms, total 21ms
,D/dalvikvm( 5437): WAIT_FOR_CONCURRENT_GC blocked 14ms
,V/SmartcardService( 5437): main Received broadcast
,V/SmartcardService( 5437): Starting smartcard service after boot completed
I/ActivityManager( 2421): Killing 4409:com.sec.pcw.device/1000 (adj 15): empty #43
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
I/SELinux ( 5450): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5450):  
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 5450): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5450):  
I/SELinux ( 5450):  
,I/SELinux ( 5450): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5450): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5450): >>>>> Normal User
,E/dalvikvm( 5450): >>>>> com.sec.android.app.sysscope [ userId:0 | appId:1000 ]
,E/SELinux ( 5450): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 10 sec
,D/TimaKeyStoreProvider( 5450): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5450): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5450): Added TimaKesytore provider
,D/dalvikvm( 5450): GC_CONCURRENT freed 3009K, 32% free 9565K/13940K, paused 5ms+1ms, total 23ms
,D/dalvikvm( 5450): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/ContextImpl( 5450): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 5463): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5463):  
,I/SELinux ( 5463): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5463):  
I/SELinux ( 5463):  
,I/SELinux ( 5463): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5463): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5463): >>>>> Normal User
,E/dalvikvm( 5463): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 5463): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5463): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5463): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5463): Added TimaKesytore provider
,D/dalvikvm( 5463): GC_CONCURRENT freed 3007K, 32% free 9566K/13940K, paused 4ms+2ms, total 27ms
,D/dalvikvm( 5463): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/SELinux ( 5475): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5475):  
I/ActivityManager( 2421): Killing 4324:com.android.chrome/u0a85 (adj 15): empty #43
,I/SELinux ( 5475): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5475):  
I/SELinux ( 5475):  
,I/SELinux ( 5475): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5475): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5475): >>>>> Normal User
,E/dalvikvm( 5475): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 5475): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5475): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5475): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5475): Added TimaKesytore provider
,D/dalvikvm( 5475): GC_CONCURRENT freed 2994K, 32% free 9566K/13932K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 5475): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/Intent to TravelDirActivity( 5475): inside TravelBroadcastReceiver
,I/SELinux ( 5487): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5487):  
,I/ActivityManager( 2421): Killing 4440:com.vlingo.midas/u0a34 (adj 15): empty #43
,I/SELinux ( 5487): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5487):  
I/SELinux ( 5487):  
,I/SELinux ( 5487): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5487): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5487): >>>>> Normal User
,E/dalvikvm( 5487): >>>>> com.sec.android.daemonapp [ userId:0 | appId:10173 ]
,E/SELinux ( 5487): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5487): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5487): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5487): Added TimaKesytore provider
,D/dalvikvm( 5487): GC_CONCURRENT freed 2997K, 32% free 9571K/13936K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 5487): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/GAV2    ( 5182): Thread[GAThread,5,main]: No campaign data found.
,D/comsamsungapp( 5487): [MSC_Daemon]>>> KWCP:218 [0:0] KWeather Provider Created
,D/comsamsungapp( 5487): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5487): [MSC_Daemon]>>> WCP:1080 [0:0] Provider Created
,D/comsamsungapp( 5487): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5487): [MSC_Daemon]>>> CCP:223 [0:0] CmaWeather Provider Created
,D/comsamsungapp( 5487): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5487): [MSC_Daemon]>>> WNCP:204 [0:0] WeatherNewsJP Provider Created
,D/comsamsungapp( 5487): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5487): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/comsamsungapp( 5487): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/comsamsungapp( 5487): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 5487): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,D/comsamsungapp( 5487): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionBOOT_COMPLETED, run:false
D/comsamsunglog( 5487): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5487): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5487): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5487): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5487): [MSC_Daemon]>>> WDSM:48 [0:0] WeatherClockService start : 
,D/daemonapp( 5487): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5487): [MSC_Daemon]>>> WDSM:87 [0:0] ABOOTCOPLD
,D/daemonapp( 5487): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
W/BackupManagerService( 2421): dataChanged but no participant pkg='com.android.providers.settings' uid=10173
,D/daemonapp( 5487): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5487): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5487): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5487): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5487): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5487): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5487): [MSC_Daemon]>>> WU:1761 [0:0] [boot]now           :1451341486447
,D/daemonapp( 5487): [MSC_Daemon]>>> WU:1762 [0:0] [boot]NUT :1451362440000
D/daemonapp( 5487): [MSC_Daemon]>>> WU:1763 [0:0] [boot]interval       :3 (21600000 ms)
I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 11 sec
,D/daemonapp( 5487): [MSC_Daemon]>>> WU:1764 [0:0] [boot]NUT - now :true
,D/daemonapp( 5487): [MSC_Daemon]>>> WDBH:2157 [0:0] ud NT1451362440000
,D/daemonapp( 5487): [MSC_Daemon]>>> WCP:1212 [0:0] cp update : count : 1, pt : 18
,D/daemonapp( 5487): [MSC_Daemon]>>> WU:1774 [0:0] Boot set AR_nexttime :1451362440000
,D/daemonapp( 5487): [MSC_Daemon]>>> WCS:40 [0:0] onStartcommand()
,D/daemonapp( 5487): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5487): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5487): [MSC_Daemon]>>> WCS:63 [0:0] CP Name cp_eng
,D/daemonapp( 5487): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5487): [MSC_Daemon]>>> WCS:82 [0:0] td null
,D/comdaemonstockapp( 5487): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 5487): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/SELinux ( 5502): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5502):  
,I/SELinux ( 5502): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5502):  
I/SELinux ( 5502):  
,I/SELinux ( 5502): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5502): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5502): >>>>> Normal User
,E/dalvikvm( 5502): >>>>> com.gameloft.android.GloftGF2H [ userId:0 | appId:10179 ]
,D/SensorService( 2421):   0.3 -0.0 9.9
,E/SELinux ( 5502): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5502): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5502): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5502): Added TimaKesytore provider
,D/dalvikvm( 5502): GC_CONCURRENT freed 3001K, 32% free 9566K/13940K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 5502): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/BluetoothAdapterService(1117159424)( 4003): unRegister RemoteMessageListener
,D/HeadsetService( 4003): registerMessageListener
D/BluetoothAdapterState( 4003): CURRENT_STATE=ON, MSG = USER_TURN_OFF
I/BluetoothAdapterState( 4003): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 4003): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 4003): updateAdapterState state is 13
,D/HeadsetStateMachine( 4003): Disconnected process message: 80
,D/HeadsetStateMachine( 4003): processUnRegisterMessageListener : 2
,I/WifiManager( 5073): packageName : com.example.hello
D/BluetoothAdapterService( 4003): Broadcasting updateAdapterState() to 1 receivers.
,I/BluetoothPbapService( 4003): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,I/WifiManager( 5073): setWifiEnabled : false
D/BluetoothAdapterService( 4003): Autoconnection is available 
D/BluetoothAdapterService( 4003): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 4003): terminating service from this receiver
I/WifiService( 2421): setWifiEnabled: false pid=5073, uid=10579
,E/bt-btif ( 4003): bta_jv_rfcomm_stop_server
,W/ContextImpl( 4003): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
W/InputMethodManagerService( 2421): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2421): [BT Setting State] State =13
,D/PhoneApp( 2754): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,I/QuickConnect[1.1][2] ( 5285): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
,I/jxcore-log( 5073): ****TEST TOOK:  5139  ms ****
I/jxcore-log( 5073): 
,I/SamsungIME( 2976): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/jxcore-log( 5073): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5073): 
D/GKI_LINUX( 4003): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BluetoothAdapterState( 4003): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterState( 4003): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 4003): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 4003): bta_jv_rfcomm_stop_server
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:2
E/bt-btif ( 4003): cmd socket is not created
I/wpa_supplicant( 3968): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3968): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3968): Scan requested (ret=0) - scan timeout 30 seconds
D/btif_config_util( 4003): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
W/Settings( 2421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2421): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2421): InactiveState{ what=143375 }
D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/IOP_DB_BT( 4003): db_close: nbr users 0
,D/IOP_DB_BT( 4003): db_close: free database
,I/SELinux ( 5518): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5518):  
,I/ActivityManager( 2421): Killing 4480:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
D/ConnectivityService( 2421): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2421): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2421): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2421): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2421): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2421): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/ConnectivityService( 2421): Attempting to switch to mobile
,D/ConnectivityService( 2421): Attempting to switch to BLUETOOTH_TETHER
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 13% free 9502K/10916K, paused 3ms+4ms, total 48ms
I/SELinux ( 5518): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5518):  
I/SELinux ( 5518):  
,I/SELinux ( 5518): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5518): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5518): >>>>> Normal User
,E/dalvikvm( 5518): >>>>> com.gameloft.android.GloftKLMF [ userId:0 | appId:10180 ]
,E/SELinux ( 5518): [DEBUG] seapp_context_lookup: seinfoCategory = default
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/WifiP2pService( 2421): InactiveState{ what=131204 }
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10916K, paused 3ms+3ms, total 29ms
D/WifiP2pService( 2421): P2pEnabledState{ what=131204 }
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,E/WifiStateMachine( 2421): Error! unhandled message{ when=-31ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2421): Error! unhandled message{ when=-30ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10916K, paused 3ms+3ms, total 26ms
D/WifiP2pService( 2421): sending p2p connection changed broadcast: FAILED
W/WifiP2pStateTracker( 2421): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/QuickConnect[1.1][2] ( 5285): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/TimaKeyStoreProvider( 5518): in addTimaSignatureService
,D/QuickConnect[1.1][2] ( 5285): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/WifiDisplayController( 2421): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2421): onP2pDisconnected
D/IpRemoteDisplayController( 2421): disconnectWfdBridgeServer
,D/IpRemoteDisplayController( 2421): WfdBridgeServer is already null
W/NetworkManagementService( 2421): route cmd failed: 
W/NetworkManagementService( 2421): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '33 route del src v6 2' failed with '400 33 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2421): '
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2421): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2421): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/TimaKeyStoreProvider( 5518): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5518): Added TimaKesytore provider
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,D/WifiP2pService( 2421): sending p2p connection changed broadcast: DISCONNECTED
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,E/WifiStateMachine( 2421): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/QuickConnect[1.1][2] ( 5285): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
D/QuickConnect[1.1][2] ( 5285): P2pHelper.cancelConnectPeer -  mTargetList clear all 
,D/QuickConnect[1.1][2] ( 5285): P2pHelper.removeP2pConfirm - skip: false
D/WifiDisplayController( 2421): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 2421): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2421): disconnect
D/WifiDisplayController( 2421): updateConnection
D/WifiDisplayController( 2421): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 2421): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/QuickConnect[1.1][2] ( 5285): CentralActionManager.removeHoldingIntentAll - all request done.
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/QuickConnect[1.1][2] ( 5285): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService( 2421): P2pDisablingState
D/WifiP2pService( 2421): P2pDisablingState{ what=139287 }
D/WifiP2pService( 2421): DefaultState{ what=139287 }
W/WifiP2pStateTracker( 2421): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2421): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2421): onP2pDisconnected
D/IpRemoteDisplayController( 2421): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 2421): WfdBridgeServer is already null
,D/NetUtils( 2421): android_net_utils_resetConnections in env=0x77d5d430 clazz=0x4e100001 iface=wlan0 mask=0x3
D/BluetoothAdapterState( 4003): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 4003): isSecureModeOn:false
W/BluetoothAdapterService( 4003): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 4003): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 4003): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/QuickConnect[1.1][2] ( 5285): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/ConnectivityService( 2421): resetConnections(wlan0, 3)
,W/BluetoothAdapterService( 4003): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/QuickConnect[1.1][2] ( 5285): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/QuickConnect[1.1][2] ( 5285): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiDisplayAdapter( 2421): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService( 2421): P2pDisablingState{ what=147458 }
,W/BluetoothAdapterService( 4003): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/HeadsetService( 4003): Received stop request...Stopping profile...
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/WifiP2pService( 2421): p2p socket connection lost
,W/BluetoothAdapterService( 4003): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/QuickConnect[1.1][2] ( 5285): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
D/WifiP2pService( 2421): P2pDisabledState
D/WifiP2pService( 2421): P2pDisabledState{ what=139376 }
,D/WifiP2pService( 2421): DefaultState{ what=139376 }
W/BluetoothAdapterService( 4003): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 4003): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 4003): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 4003): Not skipping com.android.bluetooth.hdp.HealthService
,D/QuickConnect[1.1][2] ( 5285): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
E/WifiP2pService( 2421): Unhandled message { what=139376 }
D/WifiP2pService( 2421): P2pDisabledState{ what=139287 }
,D/WifiP2pService( 2421): DefaultState{ what=139287 }
W/BluetoothAdapterService( 4003): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 4003): Not skipping com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 4003): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 4003): Not skipping com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 4003): check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 4003): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 4003): Stopping profile services that were post enabled
,D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4003): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHeadsetServiceJni( 4003): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 4003): Cleaning up Bluetooth Handsfree callback object
D/A2dpService( 4003): Received stop request...Stopping profile...
,D/A2dpStateMachine( 4003): Exit Disconnected: -1
,D/MediaFocusControl( 2421): <<< unregisterRemoteControlDisplay
,D/Avrcp   ( 4003): Unregistering previous receiver
,D/BluetoothA2dp( 2421): Proxy object disconnected
D/BluetoothA2dp( 5285): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 5285): A2dpProfile.onServiceConnected - Bluetooth service disconnected
,D/BluetoothA2dp( 4173): Proxy object disconnected
D/HidService( 4003): Received stop request...Stopping profile...
,D/HidService( 4003): Stopping Bluetooth HidService
,D/BluetoothInputDevice( 5285): Proxy object disconnected
D/HealthService( 4003): Received stop request...Stopping profile...
,D/QuickConnect[1.1][2] ( 5285): HidProfile.onServiceDisconnected - Bluetooth service disconnected
,D/PanService( 4003): Received stop request...Stopping profile...
,D/BluetoothPan( 2421): BluetoothPAN Proxy object disconnected
,D/BluetoothMapService( 4003): Received stop request...Stopping profile...
D/SapService( 4003): Received stop request...Stopping profile...
,D/SapService( 4003): Stopping Bluetooth SapService
D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4003): Profile still running: com.broadcom.bt.service.sap.SapService
,I/GKI_LINUX( 4003): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 4003): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 4003): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4003): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHidServiceJni( 4003): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 4003): Cleaning up Bluetooth GID callback object
,D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 4003): Profile still running: com.broadcom.bt.service.sap.SapService
,W/BluetoothHealthServiceJni( 4003): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 4003): Cleaning up Bluetooth Health object
D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4003): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 4003): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 4003): Cleaning up Bluetooth PAN callback object
,D/BtSettings.ProfileConfig( 4003): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4003): Profile still running: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4003): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
W/BluetoothSAPServiceJni( 4003): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,W/BluetoothSAPServiceJni( 4003): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterState( 4003): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,I/BluetoothAdapterState( 4003): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 4003): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 4003): updateAdapterState state is 10
,D/BluetoothAdapterService( 4003): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService( 4003): Autoconnection is available 
D/BluetoothAdapterService( 4003): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 4003): Entering OffState
,D/GKI_LINUX( 4003): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothA2dp( 5285): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 4173): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 5285): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2421): onBluetoothStateChange: up=false
,W/InputMethodManagerService( 2421): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2421): [BT Setting State] State =10
,I/InputMethodManagerService( 2421): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/PhoneApp( 2754): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
,I/SamsungIME( 2976): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/QuickConnect[1.1][2] ( 5285): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
,D/dalvikvm( 5518): GC_CONCURRENT freed 2999K, 32% free 9575K/13940K, paused 7ms+2ms, total 44ms
,D/dalvikvm( 5518): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/WifiNative( 2421): callSECApiBoolean - ID [13]
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
,I/wpa_supplicant( 3968): USE_NETWORK : USE_NETWORK OFF
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,E/WifiStateMachine( 2421): Error! unhandled message{ when=-15ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2421): Error! unhandled message{ when=-14ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2421): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2421): Error! unhandled message{ when=-3ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,I/SELinux ( 5544): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5544):  
D/AndroidRuntime( 5522): 
D/AndroidRuntime( 5522): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/ActivityManager( 2421): Killing 4645:com.policydm/1000 (adj 15): empty #43
D/AndroidRuntime( 5522): CheckJNI is OFF
D/AndroidRuntime( 5522): setted country_code = Poland
D/AndroidRuntime( 5522): setted countryiso_code = PL
D/AndroidRuntime( 5522): setted sales_code = PLS
D/AndroidRuntime( 5522): readGMSProperty: start
D/AndroidRuntime( 5522): readGMSProperty: already setted!!
D/AndroidRuntime( 5522): readGMSProperty: end
D/AndroidRuntime( 5522): addProductProperty: start
,D/dalvikvm( 5522): Trying to load lib libjavacore.so 0x0
,I/wpa_supplicant( 3968): p2p0: CTRL-EVENT-TERMINATING 
,V/NetworkStats( 2421): updateIfacesLocked()
D/dalvikvm( 5522): Added shared lib libjavacore.so 0x0
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/Tethering( 2421): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2421): interfaceStatusChanged p2p0, true
,V/NetworkStats( 2421): performPollLocked(flags=0x1)
D/dalvikvm( 5522): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5522): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5522): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,V/NetworkStats( 2421): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/Tethering( 2421): interfaceLinkStateChanged p2p0, false
D/Tethering( 2421): interfaceStatusChanged p2p0, false
D/BluetoothTethering( 2421): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 2421): attempted to stop reverse tether with nothing tethered
I/wpa_supplicant( 3968): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
I/SELinux ( 5544): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5544):  
I/SELinux ( 5544):  
D/Tethering( 2421): interfaceStatusChanged wlan0, true
,I/SELinux ( 5544): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,V/NetworkStats( 2421): performPollLocked() took 26ms
E/SELinux ( 5544): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5544): >>>>> Normal User
E/dalvikvm( 5544): >>>>> com.gameloft.android.GloftPSHU [ userId:0 | appId:10181 ]
E/SELinux ( 5544): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5544): in addTimaSignatureService
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 5544): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5544): Added TimaKesytore provider
,D/Tethering( 2421): interfaceLinkStateChanged wlan0, true,
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
,D/dalvikvm( 5544): GC_CONCURRENT freed 2990K, 32% free 9579K/13936K, paused 4ms+1ms, total 31ms
,D/dalvikvm( 5544): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,I/SELinux ( 5566): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5566):  
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/ActivityManager( 2421): Killing 4662:com.osp.app.signin/u0a44 (adj 15): empty #43
,E/memtrack( 5522): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5522): failed to load memtrack module: -2
,I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 12 sec
,I/SELinux ( 5566): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5566):  
I/SELinux ( 5566):  
,I/SELinux ( 5566): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5566): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5566): >>>>> Normal User
,E/dalvikvm( 5566): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 5566): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 5522): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,I/wpa_supplicant( 3968): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 2421): interfaceLinkStateChanged wlan0, false
D/Tethering( 2421): interfaceStatusChanged wlan0, false
,D/TimaKeyStoreProvider( 5566): in addTimaSignatureService
,D/Tethering( 2421): InitialState.processMessage what=4
,E/Tethering( 2421): No numeric data
,D/TimaKeyStoreProvider( 5566): Cannot add TimaSignature Service, License check Failed
,I/ConnectivityService( 2421): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering( 2421): sendTetherStateChangedBroadcast 0, 0, 0
D/ActivityThread( 5566): Added TimaKesytore provider
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,V/NetworkStats( 2421): performPollLocked() took 14ms
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/dalvikvm( 5566): GC_CONCURRENT freed 2994K, 32% free 9576K/13936K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 5566): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/AndroidRuntime( 5522): Calling main entry com.android.commands.pm.Pm
,D/WifiStateMachine( 2421): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ApplicationPolicy( 2421): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2421): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2421): deletePackageX- pkg:com.example.hello, userId:0
D/PackageManager( 2421): START PACKAGE DELETE: observer{1117954472}
D/PackageManager( 2421): pkg{<packageName>}
D/PackageManager( 2421): user{0}
D/PackageManager( 2421): deletePackageAsUser : uid = 2000 userId = 0
,D/PackageManager( 2421): [MSG] DELETE_PACKAGE_AS_USER
W/Settings( 2738): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/PackageManager( 2421): !@killApplicatoin: 10579, uninstall pkg
,I/ActivityManager( 2421): Killing 5073:com.example.hello/u0a579 (adj 0): stop com.example.hello
,W/ActivityManager( 2421): Force removing ActivityRecord{43af1750 u0 com.example.hello/.MainActivity t3}: app died, no saved state
I/SurfaceFlinger( 1921): id=15 Removed EimLayer (5/9)
I/SurfaceFlinger( 1921): id=15 Removed EimLayer (-2/9)
I/SurfaceFlinger( 1921): id=14 Removed EimLayer (4/8)
I/SurfaceFlinger( 1921): id=14 Removed EimLayer (-2/8)
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,I/SQLiteSecureOpenHelper( 4173): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4173): getDatabaseLocked(b,b,pwd)...
,I/SurfaceFlinger( 1921): id=17 Removed NainActivit (6/7)
,I/SurfaceFlinger( 1921): id=17 Removed NainActivit (-2/7)
,I/WindowState( 2421): WIN DEATH: Window{43a9d0b8 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger( 1921): id=17 Removed NainActivit (-2/7)
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.acquire()
,W/PackageSettings( 2421): Skipping PackageSetting{42a52b78 com.test.thalitest/10578} due to missing metadata
,D/PackageManager( 2421): getApplicationInfo - Execution time: 118 ms
,D/PackageManager( 2421): setPackageStoppedState - Execution time: 114 ms
D/PackageManager( 2421): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10579, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/dalvikvm( 5566): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 5566): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 5566): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 5566): VFY: replacing opcode 0x22 at 0x0000
,V/WindowOrientationListener( 2421): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 2421): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/WifiStateMachine( 2421): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
V/WindowManager( 2421): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2764): onRestart, Launcher: 1120874648
,D/Launcher( 2764): onStart, Launcher: 1120874648
,D/Launcher.HomeView( 2764): onStart
,D/Launcher( 2764): onResume, Launcher: 1120874648
E/dalvikvm( 5566): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
W/dalvikvm( 5566): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 5566): VFY: replacing opcode 0x22 at 0x0037
,D/Launcher.HomeView( 2764): onResume
D/StatusBarManagerService( 2421): semi p:2764,o:f
D/StatusBarManagerService( 2421): tr p:2764,o:f
D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): semi p:2764,o:f
,D/MenuAppsGridFragment( 2764): onResume
D/PackageManager( 2421): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10579, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Tethering( 2421): Tethering got CONNECTIVITY_ACTION
,I/ApplicationPolicy( 2421): updateDataUsageMap
,D/Tethering( 2421): MasterInitialState.processMessage what=3
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/dalvikvm( 2958): GC_EXPLICIT freed 1311K, 29% free 10017K/13936K, paused 3ms+4ms, total 44ms
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/CaptivePortalTracker( 2421): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2421): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/dalvikvm( 5566): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5566): Link of class 'Ldqp;' failed
I/DBG_DM  ( 4786): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 5566): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5566): Link of class 'Ldqp;' failed
I/dalvikvm( 5566): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x0000
,I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.PACKAGE_REMOVED
,E/SamsungIME( 2976): mOCRHelper is null
,D/QuickConnect[1.1][2] ( 5285): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.example.hello
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "sms"
I/InputReader( 2421): Reconfiguring input devices.  changes=0x00000010
,I/SurfaceFlinger( 1921): id=18 createSurf (720x1280),1 flag=4, Mauncher
,W/GeofencerStateMachine( 2738): Ignoring removeGeofence because network location is disabled.
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/RCPManagerService( 2421): PackageReceiver onReceive()
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "smsto"
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/HarmonyEASService( 2421): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,D/StatusBarManagerService( 2421): tr p:2764,o:f
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): semi p:2764,o:f
,D/RegisteredServicesCache( 2759): empty dynamic service
,E/dalvikvm( 5566): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 5566): VFY: replacing opcode 0x22 at 0x0000
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/dalvikvm( 5566): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5566): Link of class 'Ldqp;' failed
,W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 5566): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5566): Link of class 'Ldqp;' failed
I/dalvikvm( 5566): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 5566): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 5566): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 5566): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5566): Link of class 'Ldqp;' failed
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 5566): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5566): Link of class 'Ldqp;' failed
I/dalvikvm( 5566): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 5566): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 5566): Link of class 'Lax;' failed
,E/dalvikvm( 5566): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
D/dalvikvm( 5566): VFY: replacing opcode 0x22 at 0x0006
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mmsto"
W/dalvikvm( 5566): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 5566): Link of class 'Laz;' failed
E/dalvikvm( 5566): Could not find class 'az', referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 5566): VFY: replacing opcode 0x22 at 0x002c
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/dalvikvm( 5566): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 5566): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 5566): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 5566): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 5566): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
,D/dalvikvm( 5566): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 5566): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 5566): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 5566): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 5566): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 5566): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 5566): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 5566): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 5566): VFY: replacing opcode 0x23 at 0x0005
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "sms"
I/dalvikvm( 5566): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 5566): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x0009
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "smsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 2759): GC_CONCURRENT freed 1185K, 29% free 10636K/14828K, paused 3ms+3ms, total 49ms
,D/dalvikvm( 2759): WAIT_FOR_CONCURRENT_GC blocked 35ms
,W/dalvikvm( 5566): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 5566): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 5566): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 5566): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 5566): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 5566): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 5566): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 5566): VFY: replacing opcode 0x1f at 0x000c
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "mmsto"
D/dalvikvm( 5566): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5566): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5566): VFY: replacing opcode 0x62 at 0x0006
D/dalvikvm( 5566): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 5566): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 5566): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 5566): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 5566): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 5566): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 5566): Link of class 'Lax;' failed
,D/dalvikvm( 5566): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 5566): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 5566): Link of class 'Laz;' failed
,D/dalvikvm( 5566): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 5566): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 5566): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 2421): GC_EXPLICIT freed 2389K, 18% free 24618K/29976K, paused 20ms+19ms, total 383ms
D/PackageManager( 2421): delete sourFile : 
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2421): Got RemoteException sending setActive(false) notification to pid 5073 uid 10579
,D/dalvikvm( 5566): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42927a68
,D/dalvikvm( 5566): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42927a68
D/PackageManager( 2421): delete native library directory: 
D/PackageManager( 2421): return delete result to caller: 1117954472
,D/PackageManager( 2421): returnCode: 1
D/AndroidRuntime( 5522): Shutting down VM
D/dalvikvm( 5522): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+0ms, total 3ms
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "sms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/EnterpriseDeviceManagerService( 2421): Package has changed for user 0
,D/BackupManagerService( 2421): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 2421): removePackageParticipantsLocked: uid=10579 #1
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "smsto"
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(4)
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 13 sec
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "mms"
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mmsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/dalvikvm( 5566): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
,W/dalvikvm( 5566): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x0076
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,I/Babel_SMS( 5566): MmsConfig: mnc/mcc: 0/0,
,I/Babel_SMS( 5566): MmsConfig.loadMmsSettings,
I/Babel_SMS( 5566): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
I/Babel_SMS( 5566): MmsConfig.loadFromDatabase
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Babel_SMS( 5566): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5566): MmsConfig.loadFromResources
,E/Babel_SMS( 5566): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5566): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,D/dalvikvm( 5566): GC_CONCURRENT freed 1598K, 22% free 11053K/14016K, paused 5ms+2ms, total 48ms
,D/dalvikvm( 5566): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 5566): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 5566): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(38)
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/dalvikvm( 5566): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 5566): Link of class 'Lfzc;' failed
E/dalvikvm( 5566): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 5566): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
D/dalvikvm( 5566): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 5566): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 5566): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
D/dalvikvm( 5566): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 5566): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 5566): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 5566): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 5566): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 5566): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 5566): Link of class 'Lfzc;' failed
D/dalvikvm( 5566): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
W/ServiceManager( 2421): Permission failure: com.samsung.permission.SSENSOR from uid=10109 pid=5566
D/PermissionCache( 2421): checking com.samsung.permission.SSENSOR for uid=10109 => denied (380 us)
E/SensorService( 2421): Permission Denial : SEC Private Sensor 
E/SensorService( 2421): Permission Denial : SEC Private Sensor 
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
W/Settings( 5566): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5566): startup - clean
I/dalvikvm( 5566): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 5566): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x000d
I/Babel   ( 5566): deleted: false for 0
D/WallpaperManager( 2764): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
D/WallpaperManager( 2764): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
D/WallpaperManager( 2764): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 5566): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 5566): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/dalvikvm( 5566): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 5566): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
D/dalvikvm( 5566): VFY: replacing opcode 0x22 at 0x0071
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 5566): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 5566): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
D/dalvikvm( 5566): VFY: replacing opcode 0x1f at 0x0021
W/dalvikvm( 5566): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 5566): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/UsbSettingsManager( 2421): clearDefaults: com.example.hello
I/CrashAnrDetector( 2421): onPackageRemoved : com.example.hello
D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection...
I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
D/dalvikvm( 5566): GC_CONCURRENT freed 1115K, 18% free 11921K/14416K, paused 2ms+2ms, total 34ms
D/dalvikvm( 5566): WAIT_FOR_CONCURRENT_GC blocked 31ms
I/dalvikvm( 5566): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 5566): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
D/dalvikvm( 5566): VFY: replacing opcode 0x6e at 0x0074
D/dalvikvm( 5566): GC_FOR_ALLOC freed 500K, 20% free 12391K/15312K, paused 24ms, total 24ms
W/ApplicationsProvider( 2958): Could not fetch usage stats
W/ApplicationsProvider( 2958): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2958): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2958): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2958): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2958): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2958): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2958): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/dalvikvm( 5566): GC_FOR_ALLOC freed 1671K, 25% free 12635K/16648K, paused 23ms, total 23ms
E/dalvikvm( 5566): Could not find class 'android.content.pm.LauncherApps', referenced from method cbk.a
W/dalvikvm( 5566): VFY: unable to resolve check-cast 469 (Landroid/content/pm/LauncherApps;) in Lcbk;
D/dalvikvm( 5566): VFY: replacing opcode 0x1f at 0x0014
I/vclib   ( 5566): onServiceConnected
W/Babel   ( 5566): Attempted to change video mute state without an active call.
I/SELinux ( 5596): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5596):  
I/ActivityManager( 2421): Killing 4679:com.android.providers.calendar/u0a45 (adj 15): empty #43
E/SQLiteDatabase( 2738): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2738): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2738): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 2738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 2738): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2738): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 2738): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 2738): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 2738): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 2738): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 2738): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 2738): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2738): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2738): 	at com.google.android.gms.playlog.store.r.b(SourceFile:421)
E/SQLiteDatabase( 2738): 	at com.google.android.gms.playlog.store.r.a(SourceFile:303)
E/SQLiteDatabase( 2738): 	at com.google.android.gms.playlog.service.d.a(SourceFile:123)
E/SQLiteDatabase( 2738): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/SQLiteDatabase( 2738): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2738): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2738): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 2738): 	at java.lang.Thread.run(Thread.java:841)
E/PlayLogIntentService( 2738): not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 2738): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 2738): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PlayLogIntentService( 2738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PlayLogIntentService( 2738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PlayLogIntentService( 2738): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PlayLogIntentService( 2738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PlayLogIntentService( 2738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PlayLogIntentService( 2738): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PlayLogIntentService( 2738): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PlayLogIntentService( 2738): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PlayLogIntentService( 2738): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PlayLogIntentService( 2738): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 2738): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 2738): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PlayLogIntentService( 2738): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PlayLogIntentService( 2738): 	at com.google.android.gms.playlog.store.r.b(SourceFile:421)
E/PlayLogIntentService( 2738): 	at com.google.android.gms.playlog.store.r.a(SourceFile:303)
E/PlayLogIntentService( 2738): 	at com.google.android.gms.playlog.service.d.a(SourceFile:123)
E/PlayLogIntentService( 2738): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/PlayLogIntentService( 2738): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/PlayLogIntentService( 2738): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/PlayLogIntentService( 2738): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/PlayLogIntentService( 2738): 	at java.lang.Thread.run(Thread.java:841)
I/SELinux ( 5596): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5596):  
I/SELinux ( 5596):  
I/SELinux ( 5596): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5596): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5596): >>>>> Normal User
E/dalvikvm( 5596): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
E/SELinux ( 5596): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5596): in addTimaSignatureService
D/TimaKeyStoreProvider( 5596): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5596): Added TimaKesytore provider
E/SQLiteLog( 3311): (3850) statement aborts at 168: [DELETE FROM FileContent163 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
E/DocListDatabase( 3311): Failed to delete from FileContent163 table
E/DocListDatabase( 3311): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 3311): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 3311): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/DocListDatabase( 3311): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 3311): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 3311): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/DocListDatabase( 3311): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 3311): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/DocListDatabase( 3311): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/DocListDatabase( 3311): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/DocListDatabase( 3311): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 3311): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 3311): 	at java.lang.Thread.run(Thread.java:841)
W/dalvikvm( 3311): threadid=34: thread exiting with uncaught exception (group=0x41e8ac08)
E/AndroidRuntime( 3311): FATAL EXCEPTION: pool-9-thread-1
E/AndroidRuntime( 3311): Process: com.google.android.gms, PID: 3311
E/AndroidRuntime( 3311): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3311): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3311): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 3311): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3311): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3311): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 3311): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 3311): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/AndroidRuntime( 3311): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/AndroidRuntime( 3311): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/AndroidRuntime( 3311): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3311): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3311): 	at java.lang.Thread.run(Thread.java:841)
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop215.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
D/dalvikvm( 5596): GC_CONCURRENT freed 2998K, 32% free 9570K/13940K, paused 3ms+1ms, total 23ms
D/dalvikvm( 5596): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=4, hms
F/PackageManager( 2421): Unable to backup user packages state file, current changes will be lost at reboot
D/PackageManager( 2421): [MSG] WRITE_PACKAGE_RESTRICTIONS
E/dalvikvm( 5596): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 5596): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
D/dalvikvm( 5596): VFY: replacing opcode 0x22 at 0x0000
E/DropBoxManagerService( 2421): Can't write: system_server_wtf
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2421): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2421): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2421): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2421): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2421): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2421): 	at com.android.server.pm.PackageManagerService$PackageHandler.doHandleMessage(PackageManagerService.java:1223)
E/DropBoxManagerService( 2421): 	at com.android.server.pm.PackageManagerService$PackageHandler.handleMessage(PackageManagerService.java:815)
E/DropBoxManagerService( 2421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DropBoxManagerService( 2421): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 17 more
W/dalvikvm( 5596): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 5596): Link of class 'Lal;' failed
E/dalvikvm( 5596): Could not find class 'al', referenced from method b.a
W/dalvikvm( 5596): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
D/dalvikvm( 5596): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 5596): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 5596): Link of class 'Lan;' failed
E/dalvikvm( 5596): Could not find class 'an', referenced from method b.a
W/dalvikvm( 5596): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(56)
I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 14 sec
D/dalvikvm( 5596): VFY: replacing opcode 0x22 at 0x002a
W/System.err( 4786): java.io.IOException: write failed: EBADF (Bad file number)
W/System.err( 4786): 	at libcore.io.IoBridge.write(IoBridge.java:455)
W/System.err( 4786): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
W/System.err( 4786): 	at java.io.OutputStream.write(OutputStream.java:82)
W/System.err( 4786): 	at com.wssyncmldm.agent.XDMDebug.xdmSaveLog(XDMDebug.java:322)
W/System.err( 4786): 	at com.wssyncmldm.agent.XDMDebug.XDM_DEBUG(XDMDebug.java:72)
W/System.err( 4786): 	at com.wssyncmldm.adapter.XDMInitAdapter.xdmInitAdpWaitSystemRootingCheck(XDMInitAdapter.java:441)
W/System.err( 4786): 	at com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler(XDMTask.java:220)
W/System.err( 4786): 	at com.wssyncmldm.agent.XDMTask$1.handleMessage(XDMTask.java:88)
W/System.err( 4786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4786): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4786): 	at com.wssyncmldm.agent.XDMTask.run(XDMTask.java:98)
W/System.err( 4786): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 4786): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
W/System.err( 4786): 	at libcore.io.Posix.writeBytes(Native Method)
W/System.err( 4786): 	at libcore.io.Posix.write(Posix.java:202)
W/System.err( 4786): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
W/System.err( 4786): 	at libcore.io.IoBridge.write(IoBridge.java:450)
W/System.err( 4786): 	... 11 more
I/dalvikvm( 5596): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 5596): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 5596): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 5596): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x0006
W/dalvikvm( 5596): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 5596): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 5596): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
D/dalvikvm( 5596): VFY: replacing opcode 0x23 at 0x0005
D/dalvikvm( 5596): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm( 5596): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 5596): Link of class 'Lal;' failed
D/dalvikvm( 5596): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 5596): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 5596): Link of class 'Lan;' failed
D/dalvikvm( 5596): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
D/dalvikvm( 5596): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
I/dalvikvm( 5596): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm( 5596): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x000d
D/dalvikvm( 5596): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5596): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5596): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5596): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5596): VFY: unable to resolve instance field 36
D/dalvikvm( 5596): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5596): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5596): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5596): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5596): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 5596): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 5596): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x429e6708
D/dalvikvm( 5596): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x429e6708
D/dalvikvm( 5596): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x429e6708, skipping init
D/dalvikvm( 5596): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x429e6708
D/dalvikvm( 5596): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x429e6708
V/JNIHelp ( 5596): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/dalvikvm( 5596): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 5596): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x000d
D/dalvikvm( 5596): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x429e6708
D/dalvikvm( 5596): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x429e6708
D/dalvikvm( 5596): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x429e6708
D/dalvikvm( 5596): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x429e6708
I/dalvikvm( 5596): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 5596): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 5596): VFY: replacing opcode 0x71 at 0x004e
,I/ProviderInstaller( 5596): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 5596): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5596): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/dalvikvm( 5596): GC_CONCURRENT freed 1852K, 24% free 10725K/13940K, paused 4ms+4ms, total 39ms
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection...
,I/dalvikvm( 5596): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 5596): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5596): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 5596): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5596): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 5596): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5596): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 5596): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5596): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 5596): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5596): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 5596): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5596): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 5596): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5596): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 5596): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5596): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm( 5596): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 5596): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5596): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/android.os.Debug( 2421): !@Dumpstate > dumpstate -k -t -z -d -o /data/log/dumpstate_app_error
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
D/SensorService( 2421):   0.3 0.0 9.9
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5596): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
E/SQLiteDatabase( 5596): Failed to open database '/data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore'.
E/SQLiteDatabase( 5596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5596): 	at ghq.a(SourceFile:1037)
E/SQLiteDatabase( 5596): 	at ghq.a(SourceFile:1060)
E/SQLiteDatabase( 5596): 	at glm.b(SourceFile:152)
E/SQLiteDatabase( 5596): 	at glp.run(SourceFile:128)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5596): 	at goz.run(SourceFile:40)
E/SQLiteDatabase( 5596): 	at java.lang.Thread.run(Thread.java:841)
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5596): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
E/SQLiteDatabase( 5596): Failed to open database '/data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore'.
E/SQLiteDatabase( 5596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5596): 	at ghq.b(SourceFile:1110)
E/SQLiteDatabase( 5596): 	at glm.a(SourceFile:139)
E/SQLiteDatabase( 5596): 	at glo.run(SourceFile:116)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5596): 	at goz.run(SourceFile:40)
E/SQLiteDatabase( 5596): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteOpenHelper( 5596): Couldn't open com.google.android.libraries.youtube.common.task.ScheduledTaskStore for writing (will try read-only):
E/SQLiteOpenHelper( 5596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 5596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 5596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 5596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 5596): 	at android.app.ContextImpl.openOrCreateDatabas,e(ContextImpl.java:1322)
E/SQLiteOpenHelper( 5596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5596): 	at ghq.b(SourceFile:1110)
E/SQLiteOpenHelper( 5596): 	at glm.a(SourceFile:139)
E/SQLiteOpenHelper( 5596): 	at glo.run(SourceFile:116)
E/SQLiteOpenHelper( 5596): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 5596): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5596): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteOpenHelper( 5596): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteOpenHelper( 5596): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 5596): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 5596): 	at goz.run(SourceFile:40)
E/SQLiteOpenHelper( 5596): 	at java.lang.Thread.run(Thread.java:841)
W/SQLiteOpenHelper( 5596): Opened com.google.android.libraries.youtube.common.task.ScheduledTaskStore in read-only mode
W/InstanceID/Rpc( 5596): Found 10012
I/dumpstate( 5650): begin
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5596): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/SQLiteDatabase( 5596): Failed to open database '/data/data/com.google.android.youtube/databases/google_conversion_tracking.db'.
E/SQLiteDatabase( 5596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5596): 	at ahe.a(SourceFile:102)
E/SQLiteDatabase( 5596): 	at aha.a(SourceFile:2161)
E/SQLiteDatabase( 5596): 	at ags.run(SourceFile:34)
E/SQLiteDatabase( 5596): 	at java.lang.Thread.run(Thread.java:841)
,W/GoogleConversionReporter( 5596): Error opening writable conversion tracking database
,E/SQLiteDatabase( 5596): Failed to open database '/data/data/com.google.android.youtube/databases/youtube_upload_service'.
E/SQLiteDatabase( 5596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5596): 	at lax.a(SourceFile:1057)
E/SQLiteDatabase( 5596): 	at lax.call(SourceFile:41)
E/SQLiteDatabase( 5596): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5596): 	at lay.run(SourceFile:336)
E/SQLiteDatabase( 5596): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 5596): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5596): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5596): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SharedPreferencesImpl( 2738): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml to backup file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml.bak
,E/SQLiteDatabase( 5596): Failed to open database '/data/data/com.google.android.youtube/databases/preload_videos_tasks.db'.
E/SQLiteDatabase( 5596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5596): 	at jqg.a(SourceFile:65)
E/SQLiteDatabase( 5596): 	at jqj.handleMessage(SourceFile:1309)
E/SQLiteDatabase( 5596): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5596): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5596): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 5596): threadid=40: thread exiting with uncaught exception (group=0x41e8ac08)
,E/SharedPreferencesImpl( 2738): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml to backup file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml.bak
E/AndroidRuntime( 5596): FATAL EXCEPTION: jqi
E/AndroidRuntime( 5596): Process: com.google.android.youtube, PID: 5596
E/AndroidRuntime( 5596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 5596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 5596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 5596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 5596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 5596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 5596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5596): 	at jqg.a(SourceFile:65)
E/AndroidRuntime( 5596): 	at jqj.handleMessage(SourceFile:1309)
E/AndroidRuntime( 5596): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5596): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5596): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop218.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, zoutube
,D/PowerManagerService( 2421): [s] UserActivityState : 2 -> 0
,I/PowerManagerService( 2421): Nap time...
D/PowerManagerService( 2421): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2421): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2421): Going to sleep due to screen timeout...
,D/PowerManagerService( 2421): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2421): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2421): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
,D/SensorManager( 2421): unregisterListener ::   
D/DisplayPowerController( 2421): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/SurfaceFlinger( 1921): id=21 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/Sensors ( 2421): HAL:resetDataRates mEnabled=4
I/DisplayPowerController( 2421): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SensorManager( 2421): unregisterListener ::   
D/DisplayPowerController( 2421): !@ElectronBeam entry
,D/dalvikvm( 3311): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,W/dalvikvm( 3311): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 3311): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 3311): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 3311): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3311): VFY: replacing opcode 0x62 at 0x0021
,D/dalvikvm( 3311): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 3311): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 3311): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 3311): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 3311): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3311): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 3311): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 3311): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 3311): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
,I/dalvikvm( 3311): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 3311): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 3311): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,D/FileApkUtils( 3311): Spent 43ms computing apk sha1.
,D/FileApkUtils( 3311): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 3311): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 3311): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/GmsModuleFndr( 3311): Beginning GMS chimera module scan
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,W/InstanceID/Rpc( 3311): Found 10012
,D/ChimeraCfgMgr( 3311): Beginning module configuration check
,D/ChimeraCfgMgr( 3311): Module APKs unchanged, check complete
,D/lights  ( 2421): lcd : 0 +
,D/lights  ( 2421): lcd : 0 -
,I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 15 sec
V/WindowOrientationListener( 2421): WindowOrientationListener disabled
D/SensorService( 2421): AutoRotationSensor::activate (ident=0x79b18d10, enabled=0)
,I/Sensors ( 2421): HAL: batch Dry Run is complete
W/System.err( 4786): java.io.IOException: write failed: EBADF (Bad file number)
D/MISC PowerHAL( 2421): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2421): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2421): blankAllDisplays() is called.
D/PowerManagerService( 2421): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2421): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2421): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2421): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2421): miscpower_set_interactive: /sys/class/input/input0/enabled
W/System.err( 4786): 	at libcore.io.IoBridge.write(IoBridge.java:455)
D/MISC PowerHAL( 2421): sysfs_write +: /sys/class/input/input0/enabled: 0
W/System.err( 4786): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
D/KeyguardViewMediator( 2581): onScreenTurnedOff(3)
D/MISC PowerHAL( 2421): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2421): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2421): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2421): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2421): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2421): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2421): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2421): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SensorManager( 2421): unregisterListener ::   
D/SEC PowerHAL( 2421): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2421): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SEC PowerHAL( 2421): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/InputDispatcher( 2421): setInputDispatchMode: enabled=0, frozen=0
,D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x40a00550
W/System.err( 4786): 	at java.io.OutputStream.write(OutputStream.java:82)
W/System.err( 4786): 	at com.wssyncmldm.agent.XDMDebug.xdmSaveLog(XDMDebug.java:322),
W/System.err( 4786): ,	at com.wssyncmldm.agent.XDMDebug.XDM_DEBUG(XDMDebug.java:72)
,D/PowerManagerService( 2421): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage,
W/System.err( 4786): 	at com.wssyncmldm.adapter.XDMInitAdapter.xdmInitAdpWaitSystemRootingCheck(XDMInitAdapter.java:441)
W/System.err( 4786): 	,at com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler(XDMTask.java:220)
W/System.err( 4786): 	at com.wssyncmldm.agent.XDMTask$1.handleMessage(XDMTask.java:88)
W/System.err( 4786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4786): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4786): ,	at com.wssyncmldm.agent.XDMTask.run(XDMTask.java:98)
W/System.err( 4786): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 4786): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
D/Launcher.HomeView( 2764): onPause
,W/System.err( 4786): 	at libcore.io.Posix.writeBytes(Native Method)
W/System.err( 4786): 	at libcore.io.Posix.write(Posix.java:202)
W/System.err( 4786): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
W/System.err( 4786): 	at libcore.io.IoBridge.write(IoBridge.java:450)
,W/System.err( 4786): 	... 11 more
,D/LockPatternUtils( 2581): isPcwEnable = 10,
D/LockPatternUtils( 2581): isPcwEnable = 10
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false,
,D/KeyguardViewMediator( 2581): setting alarm to turn off keyguard, seq = 1,
D/StatusBarManagerService( 2421): tr p:2764,o:f
D/SSRMv2:SIOP( 2421): SIOP:: AP = 370, Delta = 0
,D/LightsService( 2421): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2421) ,
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0,
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On,
,D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  ,
D/BatteryService( 2421): turn on LED for fully charged
,D/VibratorService( 2421): JNI vibratorOff(),
D/Launcher.HomeView( 2764): onStop
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling,
D/STATUSBAR-NotificationService( 2421): ACTION_SCREEN_OFF
D/LightsService( 2421): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2421) 
,E/dalvikvm( 3311): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate,
W/dalvikvm( 3311): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 3311): VFY: replacing opcode 0x22 at 0x00af
I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=off)
,D/LightsService( 2421): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
W/dalvikvm( 3311): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 3311): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 3311): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 3311): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 3311): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 3311): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
D/dalvikvm( 3311): VFY: replacing opcode 0x6e at 0x0021
I/SecExternalDisplayIntents_Java( 2421): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/dalvikvm( 3311): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 3311): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 3311): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
D/dalvikvm( 3311): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,D/IpRemoteDisplayController( 2421): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2421): Bridge Server is not available
,D/PersonaManagerService( 2421): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2421): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2581): makeExpandedInvisible
D/PhoneStatusBarView( 2581): marqueeStatusBar:121, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is finished!!!! 
,E/dalvikvm( 2738): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 2738): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 2738): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 2738): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2738): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 2738): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2738): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 2738): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 2738): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 2738): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 2738): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 2738): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2738): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,E/dalvikvm( 3311): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 3311): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/dalvikvm( 3311): VFY: replacing opcode 0x1f at 0x000e
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
I/NfcService( 2759): applyRouting return - 2 
E/NfcService( 2759): callback == null
,D/dalvikvm( 2738): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,D/SurfaceControl( 2421): Excessive delay in blankDisplay() while turning screen off: 208ms
,I/libsuspend( 2421): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2421): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2421): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 208ms
I/PowerManagerService( 2421): [PWL] Off : 0s ago
D/PowerManagerService( 2421): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2421): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2421): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2421): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2421, ws=WorkSource{1000}) (elapsedTime=18810)
I/PowerManagerService( 2421): [PWL]       PARTIAL_WAKE_LOCK              'GpsLocationProvider' (uid=1000, pid=2421, ws=null) (elapsedTime=2670)
I/PowerManagerService( 2421): [PWL]       PARTIAL_WAKE_LOCK              'Checkin Handoff' (uid=10012, pid=3311, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=42)
I/PowerManagerService( 2421): [PWL]   PowerManagerService.Broadcasts: ref count=1
,E/dalvikvm( 3311): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 3311): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 3311): VFY: replacing opcode 0x1f at 0x00f6
,D/dalvikvm( 2738): GC_CONCURRENT freed 1591K, 23% free 11472K/14876K, paused 13ms+4ms, total 70ms
,W/dalvikvm( 3311): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,I/dalvikvm( 3311): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 3311): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,D/dalvikvm( 3311): VFY: replacing opcode 0x6e at 0x0004
,D/dalvikvm( 3311): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3311): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3311): VFY: replacing opcode 0x62 at 0x0008
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtils( 2581): isPcwEnable = 10
D/dalvikvm( 3311): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 3311): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 370, Delta = 0
D/GCM     ( 3311): COMPAT: Multi user not supported
,D/QuickConnect[1.1][2] ( 5285): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 5285): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5285): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5285): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42936488
V/QuickConnect[1.1][2] ( 5285): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42936488
,D/QuickConnect[1.1][2] ( 5285): BleHelper.stopScan - force = true
,D/QuickConnect[1.1][2] ( 5285): BleHelper.stopScan - shouldScanBleBg = false
,D/Sensors ( 2421): LightSensor enable = 0
I/QuickConnect[1.1][2] ( 5285): BleHelper.stopScan - call stopLeScan()
,D/BluetoothAdapter( 5285): stopLeScan()
D/QuickConnect[1.1][2] ( 5285): BleHelper.stopScan - call stopLeScan() complete
,D/Sensors ( 2421): LightSensor enableSensor = 0
,D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 5
D/SensorManager( 2421): unregisterListener ::   
D/lights  ( 2421): led_pattern : 5 +
,D/lights  ( 2421): led_pattern : 5 -
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PowerManagerService( 2421): [PWL] sb release: PowerManagerService.Broadcasts
,I/CheckinService( 3311): Checkin interval check for package: unspecified last checkin: 1451252271153 min interval config: 0 actual interval: 89219627
,I/GCoreUlr( 3311): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/CheckinService( 3311): Disabling old GoogleServicesFramework version
,I/GCoreUlr( 2738): DispatchingService.onCreate()
,W/dalvikvm( 3311): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3311): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,E/SharedPreferencesImpl( 2738): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LOCATION_REPORTING.xml to backup file /data/data/com.google.android.gms/shared_prefs/LOCATION_REPORTING.xml.bak
,D/ChimeraCfgMgr( 3311): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 3311): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 3311): Got an BootCompleted event.
,D/BootCompletedReceiver( 3311): Will NOT schedule AdAttestation signal task because it's disabled.
I/dalvikvm( 2850): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 2850): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 2850): VFY: replacing opcode 0x6e at 0x0059
,D/SystemUpdateService( 3311): onCreate
,F/PackageManager( 2421): Unable to backup user packages state file, current changes will be lost at reboot
,E/GCoreUlr( 2738): Error opening datastore
E/GCoreUlr( 2738): com.google.android.gms.leveldb.LevelDbIoErrorException: IO error: /data/data/com.google.android.gms/app_ulr_db/LOCK: Read-only file system
E/GCoreUlr( 2738): 	at com.google.android.gms.leveldb.LevelDb.nativeOpen(Native Method)
E/GCoreUlr( 2738): 	at com.google.android.gms.leveldb.LevelDb.a(SourceFile:140)
E/GCoreUlr( 2738): 	at com.google.android.location.reporting.b.a.a(SourceFile:81)
E/GCoreUlr( 2738): 	at com.google.android.location.reporting.service.DispatchingService.onCreate(SourceFile:392)
E/GCoreUlr( 2738): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2859)
E/GCoreUlr( 2738): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/GCoreUlr( 2738): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1390)
E/GCoreUlr( 2738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/GCoreUlr( 2738): 	at android.os.Looper.loop(Looper.java:146)
E/GCoreUlr( 2738): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/GCoreUlr( 2738): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/GCoreUlr( 2738): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/GCoreUlr( 2738): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/GCoreUlr( 2738): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/GCoreUlr( 2738): 	at dalvik.system.NativeStart.main(Native Method)
,D/EnterpriseDeviceManagerService( 2421): Creating context as user 0
E/DropBoxManagerService( 2421): Can't write: system_server_wtf
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop169.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2421): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2421): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2421): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2421): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2421): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2421): 	at com.android.server.pm.PackageManagerService.setEnabledSetting(PackageManagerService.java:14463)
E/DropBoxManagerService( 2421): 	at com.android.server.pm.PackageManagerService.setComponentEnabledSetting(PackageManagerService.java:14321)
E/DropBoxManagerService( 2421): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1138)
E/DropBoxManagerService( 2421): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2421): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2421): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 18 more
,I/GCoreUlr( 2738): DispatchingService.onDestroy()
,W/BroadcastQueue( 2421): Skipping deliver [background] BroadcastRecord{4381a618 u-1 android.intent.action.BATTERY_CHANGED} to ReceiverList{4381a408 3311 com.google.android.gms/10012/u0 remote:439faf40}: process crashing
,D/SystemUpdateService( 3311): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/CheckinService( 3311): Checking schedule, now: 1451341490866 next: 1451810614047
,I/CheckinService( 3311): active receiver: disabled
W/BroadcastQueue( 2421): Skipping deliver [background] BroadcastRecord{4381a7e8 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{4381a408 3311 com.google.android.gms/10012/u0 remote:439faf40}: process crashing
,I/dalvikvm( 3311): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 3311): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 3311): VFY: replacing opcode 0x6e at 0x0409
I/dalvikvm( 2850): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 2850): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 2850): VFY: replacing opcode 0x6e at 0x0022
,V/AuthZen ( 3311): Handling intent: android.intent.action.BOOT_COMPLETED
,E/SQLiteDatabase( 2850): Failed to open database '/data/data/com.google.android.gms/databases/rmq.db'.
E/SQLiteDatabase( 2850): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 2850): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 2850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2850): 	at com.google.android.gms.gcm.bx.b(SourceFile:537)
E/SQLiteDatabase( 2850): 	at com.google.android.gms.gcm.e.<init>(SourceFile:204)
E/SQLiteDatabase( 2850): 	at com.google.android.gms.gcm.GcmService.onCreate(SourceFile:232)
E/SQLiteDatabase( 2850): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2859)
E/SQLiteDatabase( 2850): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/SQLiteDatabase( 2850): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1390)
E/SQLiteDatabase( 2850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2850): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 2850): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 2850): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 2850): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 2850): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 2850): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 2850): 	at dalvik.system.NativeStart.main(Native Method)
,E/android.os.Debug( 2421): !@Dumpstate > dumpstate -k -t -z -d -o /data/log/dumpstate_app_error
,W/BroadcastQueue( 2421): Skipping deliver [background] BroadcastRecord{43b924c0 u0 com.google.android.checkin.CHECKIN_COMPLETE} to ReceiverList{4381a408 3311 com.google.android.gms/10012/u0 remote:439faf40}: process crashing
,E/SQLiteOpenHelper( 2850): Couldn't open rmq.db for writing (will try read-only):
E/SQLiteOpenHelper( 2850): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 2850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 2850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 2850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 2850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 2850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 2850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 2850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 2850): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 2850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 2850): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2850): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2850): 	at com.google.android.gms.gcm.bx.b(SourceFile:537)
E/SQLiteOpenHelper( 2850): 	at com.google.android.gms.gcm.e.<init>(SourceFile:204)
E/SQLiteOpenHelper( 2850): 	at com.google.android.gms.gcm.GcmService.onCreate(SourceFile:232)
E/SQLiteOpenHelper( 2850): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2859)
E/SQLiteOpenHelper( 2850): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/SQLiteOpenHelper( 2850): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1390)
E/SQLiteOpenHelper( 2850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2850): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 2850): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 2850): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 2850): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 2850): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 2850): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 2850): 	at dalvik.system.NativeStart.main(Native Method)
,E/SharedPreferencesImpl( 2738): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/bootCount.xml to backup file /data/data/com.google.android.gms/shared_prefs/bootCount.xml.bak
,W/SQLiteOpenHelper( 2850): Opened rmq.db in read-only mode
,I/dumpstate( 5697): begin
I/SystemUpdateService( 3311): cancelUpdate (empty URL)
,I/SystemUpdateService( 3311): active receiver: disabled
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,W/AtomicFile( 2421): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2421): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,W/dalvikvm( 3311): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,F/PackageManager( 2421): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 2421): Can't write: system_server_wtf
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop163.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2421): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2421): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2421): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2421): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2421): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2421): 	at com.android.server.pm.PackageManagerService.setEnabledSetting(PackageManagerService.java:14463)
E/DropBoxManagerService( 2421): 	at com.android.server.pm.PackageManagerService.setComponentEnabledSetting(PackageManagerService.java:14321)
E/DropBoxManagerService( 2421): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1138)
E/DropBoxManagerService( 2421): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2421): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2421): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 18 more
,D/EnterpriseDeviceManagerService( 2421): Creating context as user 0
,D/ConnectivityService( 2421): handleInetConditionChange: no active default network - ignore
I/dalvikvm( 2850): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 2850): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 2850): VFY: replacing opcode 0x6e at 0x0053
D/GCM     ( 2850): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,W/Auth    ( 2850): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/SystemUpdateService( 3311): onDestroy
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/AuthZenEventHandler( 3311): Handling event: android.intent.action.BOOT_COMPLETED
,E/SQLiteDatabase( 3311): Failed to open database '/data/data/com.google.android.gms/databases/auth.credentials.credential_store'.
E/SQLiteDatabase( 3311): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3311): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3311): 	at com.google.android.gms.auth.api.credentials.be.persistence.e.a(SourceFile:66)
E/SQLiteDatabase( 3311): 	at com.google.android.gms.auth.api.credentials.be.persistence.af.a(SourceFile:187)
E/SQLiteDatabase( 3311): 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:137)
E/SQLiteDatabase( 3311): 	at com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService.a(SourceFile:185)
E/SQLiteDatabase( 3311): 	at com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService.onHandleIntent(SourceFile:98)
E/SQLiteDatabase( 3311): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3311): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3311): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3311): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 3311): threadid=47: thread exiting with uncaught exception (group=0x41e8ac08)
,I/Process ( 3311): Sending signal. PID: 3311 SIG: 9
,D/PersistentNotificationBroadcastReceiver( 2738): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,E/JavaBinder( 2421): !!! FAILED BINDER TRANSACTION !!!
,I/SurfaceFlinger( 1921): id=19 Removed hms (6/10)
,I/SurfaceFlinger( 1921): id=19 Removed hms (-2/10)
W/BroadcastQueue( 2421): Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncBroadcastReceiver}
W/BroadcastQueue( 2421): android.os.TransactionTooLargeException
W/BroadcastQueue( 2421): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue( 2421): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:856)
W/BroadcastQueue( 2421): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:267)
W/BroadcastQueue( 2421): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1041)
W/BroadcastQueue( 2421): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16628)
W/BroadcastQueue( 2421): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:409)
W/BroadcastQueue( 2421): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2758)
W/BroadcastQueue( 2421): 	at android.os.Binder.execTransact(Binder.java:404)
W/BroadcastQueue( 2421): 	at dalvik.system.NativeStart.run(Native Method)
,I/SELinux ( 5708): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5708):  
,I/SELinux ( 5708): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5708):  
I/SELinux ( 5708):  
,I/SELinux ( 5708): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5708): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5708): >>>>> Normal User
,E/dalvikvm( 5708): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 5708): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5708): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5708): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5708): Added TimaKesytore provider
,D/dalvikvm( 5708): GC_CONCURRENT freed 2952K, 32% free 9615K/13936K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 5708): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/dalvikvm( 5708): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5708): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 5708): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 5708): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5708): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 5708): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5708): install
,I/MultiDex( 5708): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 5708): loading existing secondary dex files
,I/MultiDex( 5708): load found 3 secondary dex files
,I/MultiDex( 5708): install done
,D/dalvikvm( 5708): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5708): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5708): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5708): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5708): VFY: unable to resolve instance field 36
,D/dalvikvm( 5708): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5708): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5708): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5708): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5708): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5708): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5708): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4291eff8
D/dalvikvm( 5708): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4291eff8
,D/dalvikvm( 5708): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4291eff8, skipping init
,D/dalvikvm( 5708): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4291eff8
D/dalvikvm( 5708): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4291eff8
,V/JNIHelp ( 5708): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 5708): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4291eff8
D/dalvikvm( 5708): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4291eff8
D/dalvikvm( 5708): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4291eff8
,D/dalvikvm( 5708): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4291eff8
,I/DBG_DM  ( 4786): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 16 sec
,W/System.err( 4786): java.io.IOException: write failed: EBADF (Bad file number)
W/System.err( 4786): 	at libcore.io.IoBridge.write(IoBridge.java:455)
W/System.err( 4786): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
W/System.err( 4786): 	at java.io.OutputStream.write(OutputStream.java:82)
W/System.err( 4786): 	at com.wssyncmldm.agent.XDMDebug.xdmSaveLog(XDMDebug.java:322)
W/System.err( 4786): 	at com.wssyncmldm.agent.XDMDebug.XDM_DEBUG(XDMDebug.java:72)
W/System.err( 4786): 	at com.wssyncmldm.adapter.XDMInitAdapter.xdmInitAdpWaitSystemRootingCheck(XDMInitAdapter.java:441)
W/System.err( 4786): 	at com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler(XDMTask.java:220)
W/System.err( 4786): 	at com.wssyncmldm.agent.XDMTask$1.handleMessage(XDMTask.java:88)
,W/System.err( 4786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4786): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4786): 	at com.wssyncmldm.agent.XDMTask.run(XDMTask.java:98)
W/System.err( 4786): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 4786): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
,W/System.err( 4786): 	at libcore.io.Posix.writeBytes(Native Method)
W/System.err( 4786): 	at libcore.io.Posix.write(Posix.java:202)
W/System.err( 4786): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
W/System.err( 4786): 	at libcore.io.IoBridge.write(IoBridge.java:450)
,W/System.err( 4786): 	... 11 more
,I/ProviderInstaller( 5708): Installed default security provider GmsCore_OpenSSL
,W/NativeLibraryUtils( 5708): Failed to open lock file
W/NativeLibraryUtils( 5708): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5708): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 5708): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 5708): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 5708): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 5708): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5708): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 5708): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 5708): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 5708): 	... 3 more
,I/dalvikvm( 5708): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 5708): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5708): VFY: replacing opcode 0x6e at 0x000d
,I/GAv4-SVC( 5708): Google Analytics 8.4.89 is starting up.
,E/SQLiteDatabase( 5708): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:870)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:798)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:628)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:262)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:272)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5708): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.measurement.p.run(SourceFile:388)
,E/GAv4-SVC( 5708): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 5708): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 5708): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 5708): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:883)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:798)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:628)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:262)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:272)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5708): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.measurement.p.run(SourceFile:388)
,E/GAv4-SVC( 5708): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 5708): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 5708): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 5708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 5708): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5708): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5708): 	at java.lang.Thread.run(Thread.java:841)
,I/SELinux ( 5736): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5736):  
,W/GAv4-SVC( 5708): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5708): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4-SVC( 5708): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/dalvikvm( 5708): threadid=13: thread exiting with uncaught exception (group=0x41e8ac08)
,E/SharedPreferencesImpl( 5708): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 5708): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 5708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5708): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:422)
E/SQLiteDatabase( 5708): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase( 5708): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase( 5708): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase( 5708): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.reminders.a.a.a(SourceFile:66)
E/SQLiteDatabase( 5708): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
E/SQLiteDatabase( 5708): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5708): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5708): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5708): 	at java.lang.Thread.run(Thread.java:841)
,E/AndroidRuntime( 5708): FATAL EXCEPTION: AsyncTask #1
E/AndroidRuntime( 5708): Process: com.google.android.gms, PID: 5708
E/AndroidRuntime( 5708): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 5708): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 5708): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 5708): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 5708): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 5708): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 5708): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 5708): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 5708): 	at java.lang.Thread.run(Thread.java:841)
E/AndroidRuntime( 5708): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 5708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 5708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 5708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 5708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 5708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 5708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5708): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5708): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 5708): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 5708): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 5708): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 5708): 	... 4 more
E/SQLiteOpenHelper( 5708): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 5708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 5708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 5708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 5708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 5708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQL,iteDatabase.java:696)
E/SQLiteOpenHelper( 5708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 5708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 5708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5708): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5708): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:422)
E/SQLiteOpenHelper( 5708): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteOpenHelper( 5708): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteOpenHelper( 5708): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteOpenHelper( 5708): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteOpenHelper( 5708): 	at com.google.android.gms.reminders.a.a.a(SourceFile:66)
E/SQLiteOpenHelper( 5708): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
E/SQLiteOpenHelper( 5708): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteOpenHelper( 5708): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5708): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 5708): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 5708): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 5708): 	at java.lang.Thread.run(Thread.java:841)
,W/ActivityManager( 2421): Process com.google.android.gms has crashed too many times: killing!
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/ActivityManager( 2421): Killing 5708:com.google.android.gms/u0a12 (adj 0): crash
,I/SELinux ( 5736): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5736):  
I/SELinux ( 5736):  
,I/SELinux ( 5736): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5736): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5736): >>>>> Normal User
,E/dalvikvm( 5736): >>>>> com.sec.spp.push [ userId:0 | appId:10039 ]
,E/SELinux ( 5736): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 5736): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5736): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5736): Added TimaKesytore provider
,D/dalvikvm( 5736): GC_CONCURRENT freed 3005K, 32% free 9563K/13936K, paused 1ms+1ms, total 17ms
,D/dalvikvm( 5736): WAIT_FOR_CONCURRENT_GC blocked 15ms
,E/SPPClientService( 5736): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5736): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 5736): [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
,E/SPPClientService( 5736): [SystemStateMoniter] Current Time : 70349
,D/SPPClientService( 5736): PushLog.txt file is not deleted.
E/SharedPreferencesImpl( 5736): Couldn't rename file /data/data/com.sec.spp.push/shared_prefs/com.sec.spp.push.config.xml to backup file /data/data/com.sec.spp.push/shared_prefs/com.sec.spp.push.config.xml.bak
D/SPPClientService( 5736): PushLog.txt file is not deleted.
,D/SPPClientService( 5736): ============PushLog. stop!
,E/SQLiteDatabase( 5736): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5736): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5736): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5736): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5736): 	at com.sec.spp.push.monitor.SystemStateMoniter.a(Unknown Source)
E/SQLiteDatabase( 5736): 	at com.sec.spp.push.monitor.SystemStateMoniter.onReceive(Unknown Source)
E/SQLiteDatabase( 5736): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 5736): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 5736): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 5736): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5736): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5736): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5736): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5736): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5736): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5736): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5736): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5736): [d] isRegistrationTableEmpty. Exception with message =not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 5736): Failed to open database '/data/data/com.sec.spp.push/databases/log_data_db'.
E/SQLiteDatabase( 5736): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5736): 	at com.sec.spp.push.c.c.<init>(Unknown Source)
E/SQLiteDatabase( 5736): 	at com.sec.spp.push.c.c.a(Unknown Source)
E/SQLiteDatabase( 5736): 	at com.sec.spp.push.log.collector.PushClientLogCollectService.g(Unknown Source)
E/SQLiteDatabase( 5736): 	at com.sec.spp.push.log.collector.PushClientLogCollectService.b(Unknown Source)
E/SQLiteDatabase( 5736): 	at com.sec.spp.push.log.collector.PushClientLogCollectService.onHandleIntent(Unknown Source)
E/SQLiteDatabase( 5736): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5736): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5736): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5736): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SPPClientService( 5736): [[SPPLogCollecter]] null
,D/Volley  ( 3878): [213] DiskBasedCache.clear: Cache cleared.
,V/SipBroadcastReceiver( 2754): SipBroadcastReceiver onReceive
,D/Volley  ( 3878): [206] DiskBasedCache.clear: Cache cleared.
,W/BroadcastQueue( 2421): Unable to launch app com.google.android.gms/10012 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
,W/BroadcastQueue( 2421): Unable to launch app com.google.android.gms/10012 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
,D/WearableService( 2738): callingUid 10012, callindPid: 2738
D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 294, prevStep = 4, currStep = 4
W/BroadcastQueue( 2421): Unable to launch app com.google.android.gms/10012 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
D/AuthorizationBluetoothService( 2850): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2850): Proximity feature is not enabled.
,E/MDM     ( 2738): [99] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SharedPreferencesImpl( 3281): Couldn't rename file /data/data/com.android.contacts/shared_prefs/com.android.contacts_preferences.xml to backup file /data/data/com.android.contacts/shared_prefs/com.android.contacts_preferences.xml.bak

```
