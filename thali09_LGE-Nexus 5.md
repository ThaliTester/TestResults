#### Test 5253548629578ed_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 2720): GC_CONCURRENT freed 490K, 3% free 18005K/18532K, paused 3ms+2ms, total 19ms
D/dalvikvm( 2720): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4273e718
D/dalvikvm( 2720): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x4273e718
D/dalvikvm( 2720): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4273e718
D/dalvikvm( 2720): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4273e718
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1328): Module APK com.google.android.play.games already loaded
D/dalvikvm( 2720): GC_FOR_ALLOC freed 45K, 3% free 18027K/18532K, paused 14ms, total 15ms
I/dalvikvm-heap( 2720): Grow heap (frag case) to 17.668MB for 39954-byte allocation
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/dalvikvm( 1328): GC_CONCURRENT freed 454K, 3% free 18496K/18980K, paused 2ms+3ms, total 19ms
D/AsyncTaskServiceImpl( 1328): Submit a task: h
W/SQLiteConnectionPool( 1328): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 2720): GC_FOR_ALLOC freed <1K, 3% free 18066K/18572K, paused 16ms, total 16ms
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/h       ( 1328): Processing package: com.test.thalitest
D/dalvikvm( 2720): GC_FOR_ALLOC freed <1K, 3% free 18066K/18572K, paused 19ms, total 19ms
I/dalvikvm-heap( 2720): Grow heap (frag case) to 17.745MB for 79892-byte allocation
D/GassUtils( 1328): Found app info for package com.test.thalitest:18. Hash: 01e4d8ac61718f1dcdc950940ea39ae21caf015e512d4d8080feb7f016346367
D/h       ( 1328): Found info for package com.test.thalitest in db.
--------- beginning of /dev/log/system
I/ActivityManager(  755): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2779 uid=10065 gids={50065, 3003, 1028, 1015}
I/PeopleContactsSync( 1328): CP2 sync disabled
I/dalvikvm( 1328): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1328): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1328): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
,W/BaseAppContext( 1328): Using Auth Proxy for data requests.
D/dalvikvm( 2720): GC_FOR_ALLOC freed 0K, 3% free 18144K/18652K, paused 30ms, total 30ms
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
I/ProviderInstaller( 2720): Installed default security provider GmsCore_OpenSSL
W/Quickoffice( 2779): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2779): Loading recent documents list
D/Quickoffice( 2779): The number of lines present in  /proc/mount 21
D/Quickoffice( 2779): Parsing the storagedefinition.xml.
D/dalvikvm( 1328): GC_CONCURRENT freed 313K, 2% free 18739K/19084K, paused 3ms+3ms, total 24ms
D/Quickoffice( 2779): # of Storagedefinitions - 35
D/Quickoffice( 2779): The # of storage definitions available - 35
D/Quickoffice( 2779): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2779): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2779): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2779): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2779): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2779): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2779): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2779): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2779): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2779): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2779): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2779): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/dalvikvm( 2779): GC_CONCURRENT freed 171K, 2% free 16913K/17116K, paused 3ms+1ms, total 12ms
D/Quickoffice( 2779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2779): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2779): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2779): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2779): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2779): Build properties are not configured for this storage definition.
D/Quickoffice( 2779): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2779): The # of mounts identified -  1
D/com.google.android.apps.docs.quickoffice.X( 2779): Checking validity of 0 items
W/ActivityManager(  755): No permission grants found for com.quickoffice.android
D/ContentResolverUtil( 2779): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2779): 0 items were valid
D/Finsky  ( 2281): [1] PackageVerificationReceiver.checkPrerequisites: Skipping verification because own installation
D/Finsky  ( 2281): [1] PackageVerificationReceiver.onReceive: Verification requested, id = 0
D/dalvikvm( 2321): GC_CONCURRENT freed 193K, 2% free 17766K/17992K, paused 3ms+1ms, total 19ms
D/ConnectivityService(  755): Sampling interval elapsed, updating statistics ..
D/ConnectivityService(  755): Done.
D/ConnectivityService(  755): Setting timer for 720seconds
I/ActivityManager(  755): Killing 1875:com.google.android.email/u0a36 (adj 15): empty #17
D/AndroidRuntime( 2790): 
D/AndroidRuntime( 2790): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2790): CheckJNI is OFF
D/dalvikvm( 2790): Trying to load lib libjavacore.so 0x0
W/Quickoffice( 2779): Could not load clipboard.
D/dalvikvm( 2790): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2790): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2790): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2790): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/Quickoffice( 2779): Could not store clipboard.
D/dalvikvm( 2790): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1328): Module APK com.google.android.play.games already loaded
I/Icing   ( 1328): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/dalvikvm( 1328): GC_CONCURRENT freed 450K, 3% free 18880K/19360K, paused 2ms+2ms, total 19ms
D/AndroidRuntime( 2790): Calling main entry com.android.commands.am.Am
I/ActivityManager(  755): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2790
D/PermissionCache(  183): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (119 us)
D/AndroidRuntime( 2790): Shutting down VM
D/dalvikvm( 2790): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/ActivityManager(  755): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2820 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
W/ActivityManager(  755): No content provider found for permission revoke: file:///data/data/com.android.vending/cache/patches/com.android.chrome-1740066913.apk
I/PackageManager(  755): Copying native libraries to /data/app-lib/vmdl360839579
I/SearchController( 1228): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1228): mic_close
D/dalvikvm( 1228): GC_CONCURRENT freed 518K, 3% free 18506K/19056K, paused 3ms+3ms, total 25ms
I/Icing   ( 1328): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/ActivityManager(  755): Killing 2135:com.google.android.music:main/u0a58 (adj 15): empty #17
I/MicroHotwordRecognitionRunner( 1228): Hotword detection finished
F/ActivityManager(  755): Service ServiceRecord{42e2a428 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42d6e5f0 2135:com.google.android.music:main/u0a58} not same as in map: null
I/MicroHotwordRecognitionRunner( 1228): Stopping hotword detection.
,F/ActivityManager(  755): Service ServiceRecord{42e07400 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42d6e5f0 2135:com.google.android.music:main/u0a58} not same as in map: null
,V/WebViewChromiumFactoryProvider( 2820): Binding Chromium to main looper Looper (main, tid 1) {4265cb08}
,I/LibraryLoader( 2820): Expected native library version number "",actual native library version number ""
,I/chromium( 2820): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2820): Initializing chromium process, renderers=0
F/ActivityManager(  755): Service ServiceRecord{42d77f20 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42d6e5f0 2135:com.google.android.music:main/u0a58} not same as in map: null
F/ActivityManager(  755): Service ServiceRecord{42d77940 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42d6e5f0 2135:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  755): Service ServiceRecord{42cd15e8 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42d6e5f0 2135:com.google.android.music:main/u0a58} not same as in map: null
,D/BluetoothManagerService(  755): Message: 20
,D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@443b3b28:true
I/ActivityManager(  755): Killing 1812:com.google.android.gm/u0a41 (adj 15): empty #17
,I/Adreno-EGL( 2820): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,W/chromium( 2820): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 2820): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2820): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2820): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2820): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2820): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 2820): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 2820): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2820): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2820): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2820): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 2820): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 2820): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2820): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2820): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2820): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2820): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2820): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 2820): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 2820): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2820): Enabling debug mode 0
,W/AwContents( 2820): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  755): Displayed com.test.thalitest/.MainActivity: +724ms
,D/JsMessageQueue( 2820): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2820): GC_CONCURRENT freed 258K, 2% free 16922K/17212K, paused 3ms+7ms, total 26ms
,D/dalvikvm( 2820): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42660c40
,D/dalvikvm( 2820): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42660c40
,D/jxcore_app_log( 2820): JniHelper::setJavaVM(0x41544f00), pthread_self() = 1983113232
,D/JX-Cordova( 2820): jxcore cordova android initializing
,I/dalvikvm( 2820): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
,W/dalvikvm( 2820): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 2820): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 2820): GC_CONCURRENT freed 226K, 2% free 17208K/17464K, paused 0ms+1ms, total 9ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 159K, 2% free 17552K/17752K, paused 0ms+1ms, total 9ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 156K, 2% free 17894K/18092K, paused 1ms+1ms, total 12ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 153K, 2% free 18236K/18436K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 159K, 2% free 18573K/18780K, paused 2ms+2ms, total 14ms
,W/PackageParser(  755): Unknown element under <manifest>: uses-permission-sdk-m at /data/app/vmdl360839579.tmp Binary XML file line #33
,W/PackageParser(  755): Unknown element under <manifest>: uses-permission-sdk-m at /data/app/vmdl360839579.tmp Binary XML file line #34
W/ResourceType(  755): Failure getting entry for 0x7f080003 (t=7 e=3) in package 0 (error -75)
W/ResourceType(  755): Failure getting entry for 0x7f0f0038 (t=14 e=56) in package 0 (error -75)
,D/dalvikvm( 2820): GC_CONCURRENT freed 182K, 2% free 18992K/19228K, paused 2ms+1ms, total 14ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 2ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 225K, 2% free 19504K/19788K, paused 2ms+1ms, total 16ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 284K, 2% free 20123K/20472K, paused 1ms+2ms, total 19ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 331K, 2% free 20890K/21296K, paused 1ms+2ms, total 22ms
D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 409K, 3% free 21830K/22320K, paused 1ms+2ms, total 22ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm(  755): GC_CONCURRENT freed 25230K, 50% free 28509K/56332K, paused 2ms+4ms, total 104ms
,D/dalvikvm(  755): WAIT_FOR_CONCURRENT_GC blocked 94ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 1247K, 6% free 22259K/23572K, paused 1ms+2ms, total 27ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 1464K, 7% free 22531K/24144K, paused 1ms+1ms, total 24ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 2820): GC_FOR_ALLOC freed 44K, 7% free 22535K/24144K, paused 22ms, total 22ms
,I/dalvikvm-heap( 2820): Grow heap (frag case) to 22.744MB for 744140-byte allocation
,D/dalvikvm( 2820): GC_FOR_ALLOC freed 486K, 9% free 22776K/24872K, paused 23ms, total 23ms
,D/dalvikvm( 2820): GC_FOR_ALLOC freed 855K, 9% free 22763K/24872K, paused 23ms, total 23ms
,I/dalvikvm-heap( 2820): Grow heap (frag case) to 23.320MB for 1116206-byte allocation
,D/dalvikvm( 2820): GC_FOR_ALLOC freed 726K, 11% free 23126K/25964K, paused 34ms, total 34ms
,D/dalvikvm( 2820): GC_FOR_ALLOC freed 1274K, 11% free 23178K/25964K, paused 23ms, total 23ms
,I/dalvikvm-heap( 2820): Grow heap (frag case) to 24.258MB for 1674304-byte allocation
,D/dalvikvm( 2820): GC_FOR_ALLOC freed 1127K, 15% free 23685K/27600K, paused 24ms, total 24ms
,D/dalvikvm( 2820): GC_FOR_ALLOC freed 1990K, 14% free 23826K/27600K, paused 25ms, total 25ms
,I/dalvikvm-heap( 2820): Grow heap (frag case) to 25.689MB for 2511452-byte allocation
,D/dalvikvm( 2820): GC_CONCURRENT freed 158K, 14% free 26120K/30056K, paused 2ms+2ms, total 23ms
D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 4512K, 18% free 24751K/30056K, paused 2ms+4ms, total 34ms
D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2820): GC_FOR_ALLOC freed 62K, 18% free 24750K/30056K, paused 25ms, total 26ms
,I/dalvikvm-heap( 2820): Grow heap (frag case) to 27.789MB for 3767174-byte allocation
,D/dalvikvm(  755): GC_CONCURRENT freed 2835K, 50% free 28634K/56332K, paused 4ms+5ms, total 69ms
,D/dalvikvm(  755): WAIT_FOR_CONCURRENT_GC blocked 61ms
,D/dalvikvm( 2820): GC_FOR_ALLOC freed 2509K, 24% free 25920K/33736K, paused 26ms, total 26ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 290K, 24% free 25757K/33736K, paused 2ms+3ms, total 33ms
,D/dalvikvm( 2820): GC_FOR_ALLOC freed 576K, 24% free 25703K/33736K, paused 23ms, total 23ms
,W/jxcore-log( 2820): Initializing JXcore engine
,W/jxcore-log( 2820): JXcore engine is ready
,D/dalvikvm(  755): GC_CONCURRENT freed 2963K, 50% free 28662K/56332K, paused 3ms+4ms, total 68ms
,D/dalvikvm(  755): WAIT_FOR_CONCURRENT_GC blocked 51ms
,D/dalvikvm( 2820): GC_CONCURRENT freed 5365K, 31% free 23327K/33736K, paused 1ms+1ms, total 21ms
,D/dalvikvm( 2820): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/jxcore-log( 2820): Starting JXcore engine
,W/jxcore-log( 2820): Platform android
W/jxcore-log( 2820): 
,W/jxcore-log( 2820): Process ARCH arm
W/jxcore-log( 2820): 
,D/dalvikvm(  755): GC_CONCURRENT freed 2977K, 50% free 28682K/56332K, paused 3ms+7ms, total 79ms
,D/dalvikvm(  755): WAIT_FOR_CONCURRENT_GC blocked 73ms
,D/dalvikvm(  755): GC_CONCURRENT freed 2975K, 50% free 28707K/56332K, paused 2ms+4ms, total 60ms
,D/dalvikvm(  755): WAIT_FOR_CONCURRENT_GC blocked 51ms
,D/dalvikvm(  755): GC_CONCURRENT freed 2991K, 50% free 28721K/56332K, paused 5ms+4ms, total 67ms
,D/dalvikvm(  755): WAIT_FOR_CONCURRENT_GC blocked 55ms
,D/dalvikvm(  755): GC_CONCURRENT freed 2966K, 49% free 28760K/56332K, paused 3ms+3ms, total 59ms
,D/dalvikvm(  755): WAIT_FOR_CONCURRENT_GC blocked 44ms
,I/ActivityManager(  755): Force stopping com.android.chrome appid=10031 user=-1: replace sys pkg
,I/ActivityManager(  755): Killing 2412:com.android.chrome/u0a31 (adj 15): stop com.android.chrome
,W/PackageManager(  755): Trying to update system app code path from /data/app/com.android.chrome-1.apk to /data/app/com.android.chrome-2.apk
,I/jxcore-log( 2820): JXcore Cordova bridge is ready!
I/jxcore-log( 2820): 
,W/jxcore-log( 2820): JXcore engine is started
,I/Choreographer( 2820): Skipped 158 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2820): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2820): Toggling radios to true
I/jxcore-log( 2820): 
,D/BluetoothAdapter( 2820): enable(): BT is already enabled..!
,D/WifiService(  755): setWifiEnabled: true pid=2820, uid=10108
I/jxcore-log( 2820): Radios toggled
I/jxcore-log( 2820): 
I/wpa_supplicant(  923): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityService(  755): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  755): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  755): Attempting to switch to mobile
D/ConnectivityService(  755): Attempting to switch to BLUETOOTH_TETHER
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/NetUtils(  755): android_net_utils_resetConnections in env=0x778fc1f0 clazz=0x5e000001 iface=wlan0 mask=0x3
D/ConnectivityService(  755): resetConnections(wlan0, 3)
,V/NativeCrypto( 1020): Read error: ssl=0x758e8188: I/O error during system call, Connection timed out
,V/NativeCrypto( 1020): SSL shutdown failed: ssl=0x758e8188: I/O error during system call, Broken pipe
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,I/PackageManager(  755): Running dexopt on: com.android.chrome
I/wpa_supplicant(  923): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
I/wpa_supplicant(  923): wlan0: Associated with c0:ff:d4:d3:aa:48
I/wpa_supplicant(  923): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  923): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
E/WifiStateMachine(  755): scanCount==0 - aborting
,D/dalvikvm( 2895): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2820): Got Device Bluetooth address: 34:FC:EF:11:B1:66
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): my name is : LGE-Nexus 5_PT1565
I/jxcore-log( 2820): 
,D/dalvikvm( 2895): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,D/dalvikvm( 2895): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/jxcore-log( 2820): attempting to connect to test coordinator
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): check test folder
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): found test : ./testFindPeers.js
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): found test : ./testReConnect.js
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): found test : ./testSendData.js
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Test app app.js loaded
I/jxcore-log( 2820): 
,I/Choreographer( 2820): Skipped 122 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/dalvikvm( 2895): DexOpt: method is in an interface
,D/dalvikvm( 2895): DexOpt: load 232ms, verify+opt 1121ms, 5181876 bytes
,D/WifiStateMachine(  755): VerifyingLinkState enter
D/WifiStateMachine(  755): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  755): CaptivePortalCheckState enter
,D/WifiStateMachine(  755): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  755): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  755): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  755): Unexpected mtu value: android.net.wifi.WifiStateTracker@42c9e2a8
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager(  755): Force stopping com.android.chrome appid=10031 user=-1: update pkg
W/PackageManager(  755): Code path for pkg : com.android.chrome changing from /data/app/com.android.chrome-1.apk to /data/app/com.android.chrome-2.apk
,W/PackageManager(  755): Resource path for pkg : com.android.chrome changing from /data/app/com.android.chrome-1.apk to /data/app/com.android.chrome-2.apk
,W/PackageSettings(  755): Skipping PackageSetting{4274ad70 com.example.hello/10115} due to missing metadata
,W/PackageManager(  755): Unknown permission com.android.smspush.WAPPUSH_MANAGER_BIND in package com.android.phone
,W/PackageManager(  755): Unknown permission com.android.nfc.permission.NFCEE_ADMIN in package com.google.android.apps.walletnfcrel
,W/PackageManager(  755): Unknown permission com.android.vending.billing.IBillingAccountService.BIND2 in package com.google.android.gsf.login
W/PackageManager(  755): Unknown permission com.android.gallery3d.permission.GALLERY_PROVIDER in package com.android.bluetooth
,W/PackageManager(  755): Unknown permission android.permission.MMS_SEND_OUTBOX_MSG in package com.android.bluetooth
,W/PackageManager(  755): Not granting permission android.permission.BROADCAST_PACKAGE_REMOVED to package com.google.android.marvin.talkback (protectionLevel=2 flags=0x40c9be45)
W/PackageManager(  755): Not granting permission android.permission.DEVICE_POWER to package com.google.android.deskclock (protectionLevel=2 flags=0xc8be45)
,W/PackageManager(  755): Unknown permission android.permission.OBSERVE_GRANT_REVOKE_PERMISSIONS in package com.google.android.gms
,W/PackageManager(  755): Unknown permission android.permission.RECOVERY in package com.google.android.gms
W/PackageManager(  755): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gms (protectionLevel=2 flags=0x40c83ec5)
W/PackageManager(  755): Unknown permission android.permission.PROVIDE_TRUST_AGENT in package com.google.android.gms
,W/PackageManager(  755): Unknown permission com.google.android.apps.enterprise.dmagent.permission.AutoSyncPermission in package com.google.android.gms
,W/PackageManager(  755): Not granting permission android.permission.PACKAGE_USAGE_STATS to package com.google.android.gms (protectionLevel=18 flags=0x40c83ec5)
W/PackageManager(  755): Unknown permission com.google.android.googlequicksearchbox.permission.PAUSE_HOTWORD in package com.google.android.gms
W/PackageManager(  755): Unknown permission android.permission.MANAGE_VOICE_KEYPHRASES in package com.google.android.gms
W/PackageManager(  755): Unknown permission android.permission.REAL_GET_TASKS in package com.google.android.gms
W/PackageManager(  755): Unknown permission android.permission.READ_WIFI_CREDENTIAL in package com.google.android.gms
W/PackageManager(  755): Unknown permission android.permission.SCORE_NETWORKS in package com.google.android.gms
W/PackageManager(  755): Unknown permission android.permission.CONTROL_INCALL_EXPERIENCE in package com.google.android.gms
W/PackageManager(  755): Unknown permission android.permission.USER_ACTIVITY in package com.google.android.gms
W/PackageManager(  755): Unknown permission android.permission.MODIFY_AUDIO_ROUTING in package com.google.android.gms
W/PackageManager(  755): Unknown permission com.google.android.wearable.READ_SETTINGS in package com.google.android.gms
W/PackageManager(  755): Unknown permission android.permission.INTENT_FILTER_VERIFICATION_AGENT in package com.google.android.gms
W/PackageManager(  755): Unknown permission android.permission.LOCAL_MAC_ADDRESS in package com.google.android.gms
W/PackageManager(  755): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.google.android.gms
W/PackageManager(  755): Unknown permission android.permission.BODY_SENSORS in package com.google.android.gms
W/PackageManager(  755): Unknown permission com.google.android.launcher.permission.RECEIVE_LAUNCH_BROADCASTS in package com.google.android.gms
W/PackageManager(  755): Not granting permission android.permission.MANAGE_DOCUMENTS to package com.google.android.gms (protectionLevel=2 flags=0x40c83ec5)
W/PackageManager(  755): Unknown permission android.permission.NOTIFY_PENDING_SYSTEM_UPDATE in package com.google.android.gms
W/PackageManager(  755): Unknown permission com.android.voicemail.permission.READ_VOICEMAIL in package com.google.android.gms
W/PackageManager(  755): Unknown permission android.permission.READ_OWNER_DATA in package com.google.android.setupwizard
W/PackageManager(  755): Unknown permission android.permission.WRITE_OWNER_DATA in package com.google.android.setupwizard
W/PackageManager(  755): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.android.settings
W/PackageManager(  755): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.android.settings
W/PackageManager(  755): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES in package com.redbend.vdmc
W/PackageManager(  755): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES_WRITE in package com.redbend.vdmc
W/PackageManager(  755): Unknown permission com.sprint.internal.permission.CONNECTIONMANAGER in package com.redbend.vdmc
W/PackageManager(  755): Unknown permission com.sprint.internal.permission.PLATFORM in package com.redbend.vdmc
W/PackageManager(  755): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.googlequicksearchbox
W/PackageManager(  755): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.googlequicksearchbox
W/PackageManager(  755): Unknown permission com.google.android.voicesearch.SHORTCUTS_ACCESS in package com.google.android.googlequicksearchbox
W/PackageManager(  755): Unknown permission com.google.android.voicesearch.ACCESS_SETTINGS in package com.google.android.googlequicksearchbox
W/PackageManager(  755): Unknown permission com.android.browser.permission.PRELOAD in package com.google.android.googlequicksearchbox
W/PackageManager(  755): Unknown permission com.google.android.apps.googlevoice.permission.AUTO_SEND in package com.google.android.googlequicksearchbox
W/PackageManager(  755): Unknown permission com.android.chrome.PRERENDER_URL in package com.google.android.googlequicksearchbox
W/PackageManager(  755): Unknown permission com.google.android.gms.permission.CAR_SPEED in package com.google.android.apps.maps
W/PackageManager(  755): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.launcher
W/PackageManager(  755): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.launcher
W/PackageManager(  755): Unknown permission android.permission.WRITE_SYNC_STATS in package com.google.android.apps.docs
W/PackageManager(  755): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.onetimeinitializer
W/PackageManager(  755): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.onetimeinitializer
W/PackageManager(  755): Unknown permission com.android.launcher.permission.PRELOAD_WORKSPACE in package com.google.android.partnersetup
W/PackageManager(  755): Unknown permission android.permission.REGISTER_CONNECTION_MANAGER in package com.google.android.talk
W/PackageManager(  755): Not granting permission android.permission.SEND_DOWNLOAD_COMPLETED_INTENTS to package com.android.vending (protectionLevel=2 flags=0x408abe45)
W/PackageManager(  755): Unknown permission android.permission.SEND_SMS_NO_CONFIRMATION in package com.android.vending
W/PackageManager(  755): Not granting permission android.permission.BIND_WALLPAPER to package com.google.android.GoogleCamera (protectionLevel=18 flags=0xd83cc5)
W/PackageManager(  755): Not granting permission android.permission.MANAGE_DOCUMENTS to package com.google.android.youtube (protectionLevel=2 flags=0xd83ec5)
,W/PackageManager(  755): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gsf (protectionLevel=2 flags=0x40883e45)
,W/PackageManager(  755): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES in package com.lge.SprintHiddenMenu
W/PackageManager(  755): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES_WRITE in package com.lge.SprintHiddenMenu
W/PackageManager(  755): Unknown permission com.sprint.internal.permission.CONNECTIONMANAGER in package com.lge.SprintHiddenMenu
W/PackageManager(  755): Unknown permission com.sprint.internal.permission.PLATFORM in package com.lge.SprintHiddenMenu
W/PackageManager(  755): Unknown permission com.sprint.internal.permission.OMADM in package com.lge.SprintHiddenMenu
W/PackageManager(  755): Unknown permission android.permission.FACTORY in package com.lge.SprintHiddenMenu
,W/PackageManager(  755): Unknown permission com.lge.permission.LGHIDDEN in package com.lge.SprintHiddenMenu
W/PackageManager(  755): Unknown permission android.permission.MMS_PUSH in package com.lge.SprintHiddenMenu
W/PackageManager(  755): Unknown permission com.chrome.permission.DEVICE_EXTRAS in package com.android.chrome
,W/PackageManager(  755): Unknown permission com.sec.enterprise.knox.MDM_CONTENT_PROVIDER in package com.android.chrome
,D/dalvikvm(  755): GC_CONCURRENT freed 2955K, 49% free 28827K/56332K, paused 2ms+14ms, total 66ms
,D/dalvikvm(  755): WAIT_FOR_CONCURRENT_GC blocked 45ms
,W/PackageSettings(  755): Skipping PackageSetting{4274ad70 com.example.hello/10115} due to missing metadata
,I/ActivityManager(  755): Force stopping com.android.chrome appid=10031 user=0: pkg removed
,I/InputReader(  755): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "sms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1076): GC_EXPLICIT freed 1054K, 7% free 26143K/27856K, paused 2ms+3ms, total 38ms
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  755):   Scheme: "smsto"
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
,I/InputReader(  755): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  755):   Scheme: "mms"
I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mmsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/BackupManagerService(  755): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.android.chrome flg=0x4000010 (has extras) }
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "sms"
,I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/InputReader(  755): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "smsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mms"
,I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/Launcher( 1076): Deferring update until onResume
,D/dalvikvm( 1064): GC_CONCURRENT freed 464K, 3% free 16955K/17452K, paused 2ms+0ms, total 11ms
,D/BackupManagerService(  755): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.android.chrome flg=0x4000010 (has extras) }
,V/BackupManagerService(  755): removePackageParticipantsLocked: uid=10031 #1
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mmsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  755): GC_EXPLICIT freed 3233K, 53% free 26560K/56332K, paused 2ms+8ms, total 95ms
,V/BackupManagerService(  755): addPackageParticipantsLocked: #1
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "sms"
D/Tethering(  755): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  755): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Launcher( 1076): Deferring update until onResume
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "smsto"
,W/Launcher( 1076): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@4265eb70 new=com.google.android.velvet.VelvetApplication@4265eb70
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/Finsky  ( 2281): [133] 1.packageInstalled: Package install status for "com.android.chrome" is 1
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/ActivityManager(  755): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2961 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mmsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "sms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "smsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
W/ContextImpl( 2961): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mmsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/ActivityManager(  755): Killing 1697:com.google.android.calendar/u0a28 (adj 15): empty #17
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "sms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/PackageBroadcastService( 1328): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.android.chrome
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  755):   Scheme: "smsto"
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1328): Module APK com.google.android.play.games already loaded
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mmsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "sms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,E/NetworkScheduler.SchedulerReceiver( 1020): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1020): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "smsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mmsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/ActivityManager(  755): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  755): Resuming delayed broadcast
,I/ActivityManager(  755): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,D/dalvikvm(  940): GC_CONCURRENT freed 254K, 2% free 17064K/17348K, paused 2ms+2ms, total 21ms
I/ActivityManager(  755): Resuming delayed broadcast
I/ActivityManager(  755): Delay finish: com.android.musicfx/.Compatibility$Receiver
I/ActivityManager(  755): Resuming delayed broadcast
,I/RlzPingService( 2676): Setting next ping for 1449237588729
,I/Icing.InternalIcingCorporaProvider( 1228): Updating corpora: A: com.android.chrome, C: MAYBE
D/ConnectivityService(  755): NetTransition Wakelock for ConnectedState released by timeout
,D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1328): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1328): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.android.chrome
,D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1328): Module APK com.google.android.play.games already loaded
I/ActivityManager(  755): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,I/PeopleContactsSync( 1328): CP2 sync disabled
,I/Icing   ( 1328): updateResources: need to parse f{com.android.chrome}
,I/Icing.InternalIcingCorporaProvider( 1228): UpdateCorporaTask done [took 90 ms] updated apps [took 90 ms] 
,D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1328): Submit a task: h
I/ActivityManager(  755): Resuming delayed broadcast
,D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/h       ( 1328): Processing package: com.android.chrome
I/ActivityManager(  755): Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver
,D/a       ( 1328): Look up (com.android.chrome:252607600) returned no result
,D/h       ( 1328): Starting Hash for package com.android.chrome:47.0.2526.76
,D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/ActivityManager(  755): Resuming delayed broadcast
,D/GCM     ( 1020): GcmService start Intent { act=com.google.android.gms.gcm.PACKAGE_REPLACED cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gms.gcm.PACKAGE_REPLACED
I/ActivityManager(  755): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  755): Resuming delayed broadcast
,I/ActivityManager(  755): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  755): Resuming delayed broadcast
,I/ActivityManager(  755): Delay finish: com.android.musicfx/.Compatibility$Receiver
,W/Launcher( 1076): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@4265eb70 new=com.google.android.velvet.VelvetApplication@4265eb70
I/ActivityManager(  755): Resuming delayed broadcast
,I/ActivityManager(  755): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=3024 uid=10056 gids={50056, 3003, 1028, 1015}
,V/WebViewChromiumFactoryProvider( 3024): Binding Chromium to main looper Looper (main, tid 1) {4265c208}
,I/LibraryLoader( 3024): Expected native library version number "",actual native library version number ""
,I/chromium( 3024): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3024): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3024): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3024): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,W/chromium( 3024): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 3024): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 3024): GC_CONCURRENT freed 321K, 3% free 16890K/17240K, paused 6ms+1ms, total 20ms
,D/dalvikvm( 3024): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 3024): GC_CONCURRENT freed 204K, 2% free 17141K/17376K, paused 3ms+2ms, total 19ms
,I/NSApplication( 3024): Starting up...
,D/PackageBroadcastService( 1328): Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.android.chrome
,I/PeopleContactsSync( 1328): CP2 sync disabled
I/ActivityManager(  755): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/ConnectivityService(  755): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  755):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager(  755): Resuming delayed broadcast
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1328): Submit a task: h
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.vision from APK com.google.android.gms
,E/NetworkScheduler.SchedulerReceiver( 1020): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1020): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  755): Start proc com.android.chrome for service com.android.chrome/com.google.ipc.invalidation.ticl.android2.channel.GcmRegistrationTaskService: pid=3068 uid=10031 gids={50031, 3003, 1028, 1015}
I/ActivityManager(  755): Delay finish: com.google.android.gms/.gcm.nts.SchedulerReceiver
,D/dalvikvm( 1328): GC_CONCURRENT freed 563K, 4% free 18920K/19516K, paused 2ms+2ms, total 29ms
,D/h       ( 1328): Package com.android.chrome's hash: 3ee906c79bb445d7076092aff852753b0cade3c4f9200cce9d02a380d8761fbb
D/a       ( 1328): Look up (com.android.chrome:252607600) returned no result
D/dalvikvm( 3068): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3068): VFY: unable to resolve instance field 68
D/dalvikvm( 3068): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 3068): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3068): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 3068): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3068): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
I/ActivityManager(  755): Resuming delayed broadcast
D/h       ( 1328): Saved the app info in cache for package:com.android.chrome.
D/h       ( 1328): Processing package: com.android.chrome
D/GassUtils( 1328): Found app info for package com.android.chrome:252607600. Hash: 3ee906c79bb445d7076092aff852753b0cade3c4f9200cce9d02a380d8761fbb
D/h       ( 1328): Found info for package com.android.chrome in db.
I/ActivityManager(  755): Start proc com.google.android.apps.cloudprint for broadcast com.google.android.apps.cloudprint/.printdialog.receivers.UpgradeBroadcastReceiver: pid=3082 uid=10032 gids={50032, 3003, 1028}
,D/dalvikvm( 3068): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3068): VFY: unable to resolve instance field 68
D/dalvikvm( 3068): VFY: replacing opcode 0x54 at 0x0011
,I/ActivityManager(  755): Killing 965:com.google.android.keep/u0a52 (adj 15): empty #17
D/dalvikvm(  184): GC_EXPLICIT freed 41K, 1% free 16699K/16772K, paused 1ms+2ms, total 18ms
D/dalvikvm( 3068): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3068): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3068): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3068): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3068): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 3068): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/dalvikvm(  184): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+1ms, total 14ms
,D/dalvikvm(  184): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+1ms, total 14ms
,I/Icing   ( 1328): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,I/Icing   ( 1328): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/ActivityManager(  755): Killing 2482:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/MarketUpdateReceiver( 1076): market has installed: com.android.chrome
I/ActivityManager(  755): Delay finish: com.google.android.googlequicksearchbox/com.google.android.launcher.MarketUpdateReceiver
,D/SystemUpdateService( 1328): onDestroy
I/ActivityManager(  755): Resuming delayed broadcast
,I/ActivityManager(  755): Killing 1774:com.google.android.deskclock/u0a33 (adj 15): empty #17
,D/ConnectivityService(  755): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  755): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/dalvikvm(  755): Jit: resizing JitTable from 8192 to 16384
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,D/ConnectivityService(  755): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/dalvikvm( 1228): GC_CONCURRENT freed 1120K, 7% free 17914K/19064K, paused 2ms+4ms, total 25ms
,I/jxcore-log( 2820): BLE advertisement not supported: Build version is 19
I/jxcore-log( 2820): 
,I/GAV2    ( 3024): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/InputReader(  755): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "sms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "smsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/Launcher( 1076): Deferring update until onResume
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  755):   Scheme: "mmsto"
I/Launcher( 1076): Deferring update until onResume
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "sms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "smsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  755): GC_CONCURRENT freed 2330K, 53% free 26688K/56332K, paused 4ms+5ms, total 58ms
,I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  755):   Scheme: "mmsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/Icing.InternalIcingCorporaProvider( 1228): Updating corpora: A: com.google.android.gms, C: MAYBE
,W/Launcher( 1076): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@4265eb70 new=com.google.android.velvet.VelvetApplication@4265eb70
,D/PackageBroadcastService( 1328): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1328): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  755): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  755): Resuming delayed broadcast
,I/ActivityManager(  755): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/dalvikvm( 1228): GC_CONCURRENT freed 433K, 7% free 17895K/19064K, paused 3ms+3ms, total 22ms
,I/Icing   ( 1328): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  755): Resuming delayed broadcast
I/ActivityManager(  755): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  755): Resuming delayed broadcast
,V/GmsNetworkLocationProvi(  997): DISABLE
,I/GCoreNlp(  997): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/dalvikvm( 1328): GC_CONCURRENT freed 691K, 4% free 18928K/19624K, paused 1ms+1ms, total 18ms
,I/Icing.InternalIcingCorporaProvider( 1228): UpdateCorporaTask done [took 229 ms] updated apps [took 229 ms] 
,D/CaptivePortalTracker(  755): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  755): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  755): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  755): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  755): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  755): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/ActivityManager(  755): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3179 uid=10033 gids={50033, 1028}
,I/Icing   ( 1328): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,I/Icing   ( 1328): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,V/GLSActivity( 1020): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1020): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1020): GC_CONCURRENT freed 401K, 3% free 18246K/18740K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 2281): GC_CONCURRENT freed 1255K, 7% free 19779K/21084K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 2281): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/ElegantRequestDirector( 2281): I/O exception (javax.net.ssl.SSLException) caught when processing request: Write error: ssl=0x7686ce48: I/O error during system call, Broken pipe
,I/ElegantRequestDirector( 2281): Retrying request
,D/Finsky  ( 2281): [1] 5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  755): Killing 1538:com.android.providers.calendar/u0a1 (adj 15): empty #17
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/VacuumService( 1020): Vacuum at: now=1449151219875 tag=VacuumService
,D/dalvikvm( 1020): GC_CONCURRENT freed 440K, 3% free 18247K/18792K, paused 2ms+2ms, total 19ms
,D/UdcCache:FPQuery( 1328): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1020): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1020): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1020): GC_CONCURRENT freed 487K, 4% free 18219K/18808K, paused 3ms+2ms, total 17ms
,D/GetConfigurationSnapshotOperation( 1020): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm( 1328): GC_CONCURRENT freed 551K, 3% free 19124K/19704K, paused 3ms+3ms, total 31ms
,D/dalvikvm( 1328): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/PhenotypeFlagCommitter( 1020): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1020): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1020): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1020): GC_FOR_ALLOC freed 207K, 3% free 18311K/18808K, paused 13ms, total 13ms
,D/dalvikvm( 1020): GC_CONCURRENT freed 323K, 3% free 18434K/18928K, paused 9ms+3ms, total 44ms
,D/dalvikvm( 1020): GC_CONCURRENT freed 455K, 3% free 18506K/19056K, paused 3ms+3ms, total 17ms
,D/dalvikvm( 1020): GC_CONCURRENT freed 426K, 3% free 18635K/19156K, paused 1ms+2ms, total 17ms
,D/dalvikvm( 1020): GC_CONCURRENT freed 623K, 4% free 18669K/19384K, paused 2ms+5ms, total 32ms
,D/GetCommittedConfigurationOperation( 1020): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1020):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1020): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1020): GC_CONCURRENT freed 669K, 5% free 18575K/19440K, paused 2ms+3ms, total 20ms
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,D/dalvikvm( 1020): GC_CONCURRENT freed 529K, 5% free 18593K/19440K, paused 2ms+2ms, total 16ms
,D/dalvikvm( 1020): GC_CONCURRENT freed 691K, 6% free 18437K/19440K, paused 3ms+1ms, total 18ms
,D/GetCommittedConfigurationOperation( 1020): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1020): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/rmt_storage(  179): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb80be160
I/rmt_storage(  179): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  179): wakelock acquired: 1, error no: 2
,I/rmt_storage(  179): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1207181616)
,I/rmt_storage(  179): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  179): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  179): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1207181616) wakelock released: 1, error no: 0
I/rmt_storage(  179): 
,I/rmt_storage(  179): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb80be160
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/PowerManagerService(  755): Going to sleep due to screen timeout...
,I/Adreno-EGL(  755): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,D/SurfaceFlinger(  183): Screen released, type=0 flinger=0xb83b7450
,D/qdhwcomposer(  183): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  183): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  755): Excessive delay in blankDisplay() while turning screen off: 293ms
,V/KeyguardServiceDelegate(  755): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@449c54e8)
,V/KeyguardServiceDelegate(  755): **** SHOWN CALLED ****
I/WindowManager(  755): No lock screen! windowToken=null
,D/NfcService( 1064): NFC-C OFF
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/ClearcutLoggerApiImpl( 1020): disconnect managed GoogleApiClient
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Coordinator is now connected to the server!
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2820): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector command called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":17,"addressList":[{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0}]}
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Start now : testSendData.js
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 17
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): check server
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): serverPort is 42532
I/jxcore-log( 2820): 
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2820): Stoping All
I/        ( 2820): Stopping services
I/        ( 2820): Stop Bluetooth
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2820): Start-My BT: 34:FC:EF:11:B1:66
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2820):  mInstanceString : {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1565"}
,I/        ( 2820): All stuff available and enabled
I/        ( 2820): Stoping All
I/        ( 2820): Stopping services
I/        ( 2820): Stop Bluetooth
I/        ( 2820): Starting All
I/        ( 2820): Stopping services
,I/        ( 2820): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1565"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@4266e3d0
,I/        ( 2820): Stopping services
,I/        ( 2820): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1565"}
,I/        ( 2820): Add local service :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1565"}, length : 77
,I/        ( 2820): peerDiscoveryTimer timeout value:8158
,I/        ( 2820): Stop Bluetooth
I/        ( 2820): StartBluetooth listener
,I/        ( 2820): StartBluetooth listener
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2820): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1520): SOCK FLAG = 0 ***********************
,I/jxcore-log( 2820): StartBroadcasting started ok
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): do fake peer & start
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:02.917Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
I/jxcore-log( 2820): 2015-12-03T14:05:02.918Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:02.918Z SendDataConnector.js: do connect now
I/jxcore-log( 2820): 
,I/        ( 2820): Selected device address: 80:01:84:8A:B3:68, name: null
I/BTListenerThread( 2820): starting to listen
,I/BTListenerThread( 2820): waiting to accept incoming Connection
,I/        ( 2820): Connecting to null, at 80:01:84:8A:B3:68
,I/jxcore-log( 2820): 2015-12-03T14:05:02.923Z SendDataTCPServer.js: TCP/IP server is bound to port: 42532
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2820): We already were running, thus doing nothing
,I/        ( 2820): Added local service
I/        ( 2820): Cleared service requests
,I/        ( 2820): Stopped peer discovery
I/        ( 2820): Discovery state changed to Started.
,I/        ( 2820): Started peer discovery
,I/BTConnectToThread( 2820): Starting to connect
,W/BluetoothAdapter( 2820): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1520): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2820): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[250]}
,W/bt-sdp  ( 1520): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,E/bt-btif ( 1520): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 1520): invalid rfc slot id: 5
,I/BTConnectToThread( 2820): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2820): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2820): 2015-12-03T14:05:08.100Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:08.114Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:08.126Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2820): 
,I/wpa_supplicant(  923): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2820): Found 1 peers.
,I/SS      ( 2820): Peer(1): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 2820): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2820): Added service request
,I/wpa_supplicant(  923): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  923): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2820): Started service discovery
,I/wpa_supplicant(  923): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  923): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2820): 2015-12-03T14:05:13.128Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:13.129Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/        ( 2820): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5769, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5769, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 2820): 2015-12-03T14:05:18.135Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:18.136Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:18.139Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:18.140Z SendDataConnector.js: do connect now
I/jxcore-log( 2820): 
,I/        ( 2820): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 2820): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2820): Starting to connect
,W/BluetoothAdapter( 2820): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1520): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2820): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[251]}
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  755): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  755): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  755): Attempting to switch to mobile
,D/ConnectivityService(  755): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  755): android_net_utils_resetConnections in env=0x778fc1f0 clazz=0x7e600001 iface=wlan0 mask=0x3
D/ConnectivityService(  755): resetConnections(wlan0, 3)
,I/jxcore-log( 2820): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): The Coordinator has disconnected!
I/jxcore-log( 2820): 
,V/NativeCrypto( 1020): Read error: ssl=0x758e7708: I/O error during system call, Connection timed out
,V/NativeCrypto( 1020): SSL shutdown failed: ssl=0x758e7708: I/O error during system call, Broken pipe
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
D/WifiService(  755): setWifiEnabled: false pid=2820, uid=10108
,D/WifiService(  755): setWifiEnabled: true pid=2820, uid=10108
,E/WifiStateMachine(  755): scanCount==0 - aborting
,D/WifiController(  755): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 482ms
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,I/jxcore-log( 2820): Wifi toggled for connection repairment
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2820): Wifi is DISABLED !!
I/        ( 2820): Stoping All
I/        ( 2820): Stopping services
,I/        ( 2820): Stopping services
,I/        ( 2820): Stop Bluetooth
I/        ( 2820): Stop Bluetooth
I/BTListenerThread( 2820): Stopped
,E/bt-btif ( 1520): bta_jv_rfcomm_stop_server
I/BTConnectToThread( 2820): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 1520): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:6, channel:-1
,I/        ( 2820): Clearing local services failed, error code 2
,I/        ( 2820): Clearing service requests failed, error code 2
I/        ( 2820): Stopping peer discovery failed, error code 2
,I/CONNEC  ( 2820): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2820): 2015-12-03T14:05:21.768Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2820): 
I/jxcore-log( 2820): 2015-12-03T14:05:21.768Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:21.768Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2820): 
I/ActivityManager(  755): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3329 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,D/BluetoothManagerService(  755): Message: 20
,D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42c45e70:true
,I/wpa_supplicant(  923): P2P-FIND-STOPPED 
I/wpa_supplicant(  923): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  923): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  923): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/wpa_supplicant(  923): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,D/LocalBluetoothProfileManager( 3329): Adding local A2DP profile
,D/BluetoothManagerService(  755): Message: 30
,D/LocalBluetoothProfileManager( 3329): Adding local HEADSET profile
,D/BluetoothManagerService(  755): Message: 30
W/ContextImpl( 3329): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
,W/ContextImpl( 3329): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
D/BluetoothManagerService(  755): Message: 30
I/wpa_supplicant(  923): p2p0: CTRL-EVENT-TERMINATING 
,W/ContextImpl( 3329): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/LocalBluetoothProfileManager( 3329): Adding local MAP profile
,D/BluetoothMap( 3329): Create BluetoothMap proxy object
W/ContextImpl( 3329): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
W/ContextImpl( 3329): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1376 
,W/ContextImpl( 3329): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3329): LocalBluetoothProfileManager construction complete
D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,D/dalvikvm(  755): GC_EXPLICIT freed 1686K, 53% free 26673K/56332K, paused 3ms+5ms, total 65ms
,D/BluetoothManagerService(  755): Message: 30
D/BluetoothManagerService(  755): Message: 30
,D/BluetoothManagerService(  755): Message: 30
,D/dalvikvm( 3329): GC_CONCURRENT freed 328K, 3% free 16815K/17176K, paused 3ms+1ms, total 34ms
,D/BluetoothA2dp( 3329): Proxy object connected
,D/A2dpProfile( 3329): Bluetooth service connected
,I/ActivityManager(  755): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3349 uid=10052 gids={50052, 3003, 1028, 1015}
,I/ActivityManager(  755): Killing 2634:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/BluetoothHeadset( 3329): Proxy object connected
,D/HeadsetProfile( 3329): Bluetooth service connected
,D/BluetoothInputDevice( 3329): Proxy object connected
,D/HidProfile( 3329): Bluetooth service connected
,D/BluetoothPan( 3329): BluetoothPAN Proxy object connected
D/PanProfile( 3329): Bluetooth service connected
D/BluetoothMap( 3329): Proxy object connected
D/MapProfile( 3329): Bluetooth service connected
,D/BluetoothMap( 3329): getConnectedDevices()
,D/BluetoothPbap( 3329): Proxy object connected
,D/PbapServerProfile( 3329): Bluetooth service connected
,D/Tethering(  755): InitialState.processMessage what=4
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  755): sendTetherStateChangedBroadcast 0, 0, 0
,W/Settings( 1913): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  997): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 1020): GC_CONCURRENT freed 462K, 6% free 18452K/19432K, paused 1ms+2ms, total 16ms
,D/dalvikvm( 3349): GC_CONCURRENT freed 178K, 2% free 16927K/17136K, paused 3ms+1ms, total 18ms
,I/ActivityManager(  755): Killing 2961:com.android.keychain/1000 (adj 15): empty #17
,D/WifiController(  755): DEFERRED_TOGGLE handled
,D/SoftapController(  180): Softap fwReload - Ok
D/CommandListener(  180): Setting iface cfg
,D/CommandListener(  180): Trying to bring down wlan0
,I/wpa_supplicant( 3375): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3375): rfkill: Cannot open RFKILL control device
,D/WifiMonitor(  755): startMonitoring(wlan0) with mConnected = false
,D/Tethering(  755): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3375): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  755): Loading config and enabling all networks
,W/Settings( 1913): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  180): Setting iface cfg
,D/CommandListener(  180): Trying to bring up p2p0
,D/WifiMonitor(  755): startMonitoring(p2p0) with mConnected = true
I/WB      ( 2820): Wifi is now enabled !
I/        ( 2820): Stoping All
I/        ( 2820): Stopping services
I/        ( 2820): Stop Bluetooth
I/        ( 2820): Starting All
I/        ( 2820): Stopping services
I/        ( 2820): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1565"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@4266e3d0
I/        ( 2820): Stopping services
,I/        ( 2820): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1565"}
,I/        ( 2820): Add local service :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1565"}, length : 77
I/        ( 2820): peerDiscoveryTimer timeout value:9210
I/        ( 2820): Stop Bluetooth
I/        ( 2820): StartBluetooth listener
,I/        ( 2820): StartBluetooth listener
D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2820): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1520): SOCK FLAG = 0 ***********************
I/BTListenerThread( 2820): starting to listen
I/        ( 2820): Discovery state changed to Started.
,I/BTListenerThread( 2820): waiting to accept incoming Connection
,I/        ( 2820): Added local service
,I/        ( 2820): Cleared service requests
I/        ( 2820): Stopped peer discovery
,I/        ( 2820): Started peer discovery
,W/bt-sdp  ( 1520): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 1520): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 1520): invalid rfc slot id: 6
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/dalvikvm( 1245): GC_CONCURRENT freed 351K, 3% free 16741K/17124K, paused 11ms+1ms, total 22ms
,D/CaptivePortalTracker(  755): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/Babel   ( 1913): connection state changed from CONNECTED to DISCONNECTED
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1328): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2820): Found 3 peers.
,I/SS      ( 2820): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2820): Peer(2): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 2820): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2820): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2820): Added service request
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2820): 2015-12-03T14:05:26.769Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:26.769Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/        ( 2820): Started service discovery
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2820): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5597"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5597"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5597, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5597, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2820): 2015-12-03T14:05:31.801Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:31.802Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:31.804Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:31.806Z SendDataConnector.js: do connect now
I/jxcore-log( 2820): 
,I/        ( 2820): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 2820): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2820): Starting to connect
,W/BluetoothAdapter( 2820): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1520): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2820): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[252]}
,I/        ( 2820): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9133"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9133"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT9133, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT9133, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 1520): process_service_search_attr_rsp
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/BluetoothBondStateMachine( 1520): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,I/BluetoothBondStateMachine( 1520): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1520): Entering PendingCommandState State
,W/BluetoothEventManager( 3329): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,E/BluetoothEventManager( 3329): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,E/bt-btif ( 1520): services_to_search = 3fffffff
,E/bt-btif ( 1520): ****************search UUID = 1200***********
,W/bt-sdp  ( 1520): process_service_search_attr_rsp
,E/bt-btif ( 1520): services_to_search = 3ffffffe
,E/bt-btif ( 1520): ****************search UUID = 0100***********
,W/bt-btif ( 1520): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2820): Starting to Handshake
W/bt-btif ( 1520): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 1520): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2820): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2820): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2820): BTHandshakeSocketThread started
,I/BTConnectToThread( 2820): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 2820): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2820): HandshakeOk : HTC-HTC Desire 820_PT9389
,I/HS      ( 2820): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9389
,I/BTHandshakeSocketThread( 2820): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2820): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9389
,I/BtToSocketBase( 2820): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2820): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2820): mHTTPPort  set to : 36764
,I/BtConnectorHelper( 2820): Request socket is using : 36764
,I/BtToRequestSocket( 2820): Now accepting connections
,I/BtConnectorHelper( 2820): Calling ConnectionStatusUpdate with port :36764
,I/jxcore-log( 2820): 2015-12-03T14:05:36.789Z SendDataConnector.js: CLIENT connected to 36764, error: null
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:36.791Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2820): 
,I/BtToRequestSocket( 2820): incoming data from: /127.0.0.1, port: 36764
,I/BtToRequestSocket( 2820): Set local streams
,I/jxcore-log( 2820): 2015-12-03T14:05:36.827Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2820): 
,I/BtToRequestSocket( 2820): rin ended ---------------------------;
,W/bt-sdp  ( 1520): process_service_search_attr_rsp
,E/bt-btif ( 1520): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1520): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 3 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 4 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 5 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 6 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 7 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 8 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 9 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 10 uuid:00001132-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 11 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btif ( 1520): Index: 12 uuid:00006675-7475-7265-6469-616c62756d70
,I/BluetoothBondStateMachine( 1520): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 1520): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 1520): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,I/BluetoothBondStateMachine( 1520): StableState(): Entering Off State
,W/BluetoothEventManager( 3329): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,E/BluetoothEventManager( 3329): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/jxcore-log( 2820): 2015-12-03T14:05:37.483Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:37.505Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:38.129Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:38.146Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:38.358Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:38.536Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2820): 
,I/        ( 2820): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5769, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5769, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2820): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2951","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2951","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2951, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2951, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2820): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3634, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3634, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,W/bt-btif ( 1520): dm_pm_timer expires
,W/bt-btif ( 1520): dm_pm_timer expires 0
,W/bt-btif ( 1520): proc dm_pm_timer expires
,I/        ( 2820): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT411, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT411, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/        ( 2820): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9389, peerAddress: 80:01:84:8A:B3:68
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9389, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2820): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7439","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7439","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT7439, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT7439, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 2820): 2015-12-03T14:05:48.538Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:48.540Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:48.549Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:48.550Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:48.557Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2820): 
,I/BtToSocketBase( 2820): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2820): Disconnect outgoing peer: HTC-HTC Desire 820_PT9389
I/BtToSocketBase( 2820): Stop ReceivingThread
,I/BtToSocketBase( 2820): Stop SendingThread
,I/BtToSocketBase( 2820): Close local in
,I/BtToSocketBase( 2820): Close LocalOutputStream
I/BtToSocketBase( 2820): Close localHostSocket
,I/BtToSocketBase( 2820): Close bt in
,I/BtToSocketBase( 2820): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2820): Close bt out
I/BtToSocketBase( 2820): Close bt socket
,I/BtToRequestSocket( 2820): Close server socket
,W/bt-btif ( 1520): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2820): 2015-12-03T14:05:53.589Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:53.590Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothManagerService(  755): Message: 20
,D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@442781b0:true
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: HTC Desire 820
,D/dalvikvm( 1228): GC_CONCURRENT freed 465K, 6% free 17941K/19064K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 1228): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,D/dalvikvm(  997): GC_CONCURRENT freed 349K, 3% free 17956K/18432K, paused 2ms+1ms, total 17ms
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2820): Cleared service requests
,I/        ( 2820): Started peer discovery
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2820): Found 8 peers.
,I/SS      ( 2820): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2820): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 2820): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2820): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 2820): Peer(5): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 2820): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 2820): Peer(7): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2820): Peer(8): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2820): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2820): Added service request
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2820): 2015-12-03T14:05:58.621Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:58.621Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2820): 
I/jxcore-log( 2820): 2015-12-03T14:05:58.621Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:05:58.621Z SendDataConnector.js: do connect now
I/jxcore-log( 2820): 
,I/        ( 2820): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 2820): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
I/BTConnectToThread( 2820): Starting to connect
,W/BluetoothAdapter( 2820): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1520): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2820): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[283]}
,I/        ( 2820): Started service discovery
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2820): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9389, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9389, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 1520): process_service_search_attr_rsp
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,W/bt-btif ( 1520): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2820): Starting to Handshake
W/bt-btif ( 1520): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 1520): bta_dm_pm_ssr:2, lat:1200
I/BTHandshakeSocketThread( 2820): Creating BTHandshakeSocketThread
,I/BTHandshakeSocketThread( 2820): BTHandshakeSocketThread started
,I/BTConnectToThread( 2820): MESSAGE_WRITE 77 bytes.
,I/BTConnectToThread( 2820): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 2820): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2820): HandshakeOk : HTC-HTC Desire 820_PT9389
I/HS      ( 2820): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9389
I/BTHandshakeSocketThread( 2820): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2820): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9389
I/BtToSocketBase( 2820): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2820): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 2820): mHTTPPort  set to : 46533
I/BtConnectorHelper( 2820): Request socket is using : 46533
,I/BtToRequestSocket( 2820): Now accepting connections
,I/        ( 2820): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5769, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5769, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2820): Calling ConnectionStatusUpdate with port :46533
,I/jxcore-log( 2820): 2015-12-03T14:06:05.104Z SendDataConnector.js: CLIENT connected to 46533, error: null
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:05.104Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:05.107Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2820): 
,I/BtToRequestSocket( 2820): incoming data from: /127.0.0.1, port: 46533
,I/BtToRequestSocket( 2820): Set local streams
,I/BtToRequestSocket( 2820): rin ended ---------------------------;
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3375): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3375): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 1520): dm_pm_timer expires
,W/bt-btif ( 1520): dm_pm_timer expires 0
W/bt-btif ( 1520): proc dm_pm_timer expires
,I/        ( 2820): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3634, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3634, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2820): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5597"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5597"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5597, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5597, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3375): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3375): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  755): scanCount==0 - aborting
,I/wpa_supplicant( 3375): P2P-FIND-STOPPED 
,I/        ( 2820): Discovery state changed to Stopped.
,I/        ( 2820): Starting peer discovery failed, error code 2
,I/jxcore-log( 2820): 2015-12-03T14:06:15.156Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2820): 
I/jxcore-log( 2820): 2015-12-03T14:06:15.156Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2820): 
I/jxcore-log( 2820): 2015-12-03T14:06:15.156Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2820): 
I/jxcore-log( 2820): 2015-12-03T14:06:15.156Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:15.157Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2820): 
I/BtToSocketBase( 2820): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2820): Disconnect outgoing peer: HTC-HTC Desire 820_PT9389
I/BtToSocketBase( 2820): Stop ReceivingThread
I/BtToSocketBase( 2820): Stop SendingThread
I/BtToSocketBase( 2820): Close local in
I/BtToSocketBase( 2820): Close LocalOutputStream
I/BtToSocketBase( 2820): Close localHostSocket
I/BtToSocketBase( 2820): Close bt in
,I/BtToSocketBase( 2820): Close bt out
I/BtToSocketBase( 2820): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 2820): Close bt socket
,I/BtToRequestSocket( 2820): Close server socket
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 1520): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,D/WifiStateMachine(  755): VerifyingLinkState enter
,D/WifiStateMachine(  755): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  755): CaptivePortalCheckState enter
D/ConnectivityService(  755): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  755): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  755): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  755): Unexpected mtu value: android.net.wifi.WifiStateTracker@42c9e2a8
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2820): Found 10 peers.
,I/SS      ( 2820): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2820): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 2820): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 2820): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2820): Peer(5): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 2820): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 2820): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 2820): Peer(8): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 2820): Peer(9): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2820): Peer(10): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2820): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2820): Added service request
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/ConnectivityService(  755): NetTransition Wakelock for ConnectedState released by timeout
,I/jxcore-log( 2820): 2015-12-03T14:06:20.178Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:20.179Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: HTC Desire 820
,D/dalvikvm( 1520): GC_CONCURRENT freed 321K, 3% free 16899K/17252K, paused 2ms+1ms, total 11ms
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Coordinator is now connected to the server!
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,E/NetdConnector(  755): NDC Command {93 resolver setifdns wlan0  192.168.1.1} took too long (3208ms)
I/        ( 2820): Started service discovery
,D/ConnectivityService(  755): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  755):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,I/        ( 2820): Cleared service requests
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
I/        ( 2820): Started peer discovery
D/Tethering(  755): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  755): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 2820): Discovery state changed to Started.
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/SystemUpdateService( 1328): active receiver: enabled
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,I/Babel   ( 1913): connection state changed from DISCONNECTED to CONNECTED
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2820): Found 10 peers.
I/SS      ( 2820): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2820): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2820): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2820): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2820): Peer(5): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2820): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2820): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 2820): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2820): Peer(9): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2820): Peer(10): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2820): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2820): Added service request
,D/ConnectivityService(  755): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/        ( 2820): Started service discovery
,I/wpa_supplicant( 3375): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2820): 2015-12-03T14:06:25.240Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:25.241Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:25.243Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:25.245Z SendDataConnector.js: do connect now
I/jxcore-log( 2820): 
,I/        ( 2820): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 2820): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2820): Starting to connect
,W/BluetoothAdapter( 2820): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1520): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2820): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[289]}
,W/bt-sdp  ( 1520): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
,E/bt-btif ( 1520): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 1520): invalid rfc slot id: 10
,I/BTConnectToThread( 2820): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2820): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2820): 2015-12-03T14:06:30.419Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:30.421Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:30.453Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:30.454Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:30.459Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): ---- round done--------
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): do fake peer & start
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:30.470Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:30.472Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:30.474Z SendDataConnector.js: do connect now
I/jxcore-log( 2820): 
,I/        ( 2820): Selected device address: B0:C5:59:3F:75:69, name: null
,I/        ( 2820): Connecting to null, at B0:C5:59:3F:75:69
I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 2820): Starting to connect
,W/BluetoothAdapter( 2820): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1520): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2820): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[290]}
,D/CaptivePortalTracker(  755): DelayedCaptiveCheckState{ when=-4ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  755): Checking http://216.58.209.46/generate_204
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/CaptivePortalTracker(  755): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  755): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  755): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  755): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/        ( 2820): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2326"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2326"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2326, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2326, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2820): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7904","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7904","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT7904, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT7904, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 2820): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5597"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5597"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5597, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5597, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 1520): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 1520): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,I/BluetoothBondStateMachine( 1520): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1520): Entering PendingCommandState State
,W/BluetoothEventManager( 3329): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,E/BluetoothEventManager( 3329): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,E/bt-btif ( 1520): services_to_search = 3fffffff
,E/bt-btif ( 1520): ****************search UUID = 1200***********
,W/bt-sdp  ( 1520): process_service_search_attr_rsp
,E/bt-btif ( 1520): services_to_search = 3ffffffe
,E/bt-btif ( 1520): ****************search UUID = 0100***********
,W/bt-btif ( 1520): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2820): Starting to Handshake
W/bt-btif ( 1520): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 1520): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2820): Creating BTHandshakeSocketThread
I/BTConnectToThread( 2820): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2820): BTHandshakeSocketThread started
,I/BTConnectToThread( 2820): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 2820): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2820): HandshakeOk : samsung-SM-G900F_PT411
,I/HS      ( 2820): Hand Shake finished outgoing for : samsung-SM-G900F_PT411
,I/BTHandshakeSocketThread( 2820): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2820): Starting the connected thread incoming : false, samsung-SM-G900F_PT411
,I/BtToSocketBase( 2820): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2820): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2820): mHTTPPort  set to : 59838
,I/BtConnectorHelper( 2820): Request socket is using : 59838
,I/BtToRequestSocket( 2820): Now accepting connections
,I/wpa_supplicant( 3375): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/BtConnectorHelper( 2820): Calling ConnectionStatusUpdate with port :59838
,I/jxcore-log( 2820): 2015-12-03T14:06:35.398Z SendDataConnector.js: CLIENT connected to 59838, error: null
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:35.399Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2820): 
,I/BtToRequestSocket( 2820): incoming data from: /127.0.0.1, port: 59838
,I/BtToRequestSocket( 2820): Set local streams
,I/jxcore-log( 2820): 2015-12-03T14:06:35.427Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2820): 
,I/BtToRequestSocket( 2820): rin ended ---------------------------;
,W/bt-sdp  ( 1520): process_service_search_attr_rsp
,E/bt-btif ( 1520): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1520): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1520): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1520): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 1520): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 1520): Failed to remove device: B0:C5:59:3F:75:69
,W/BluetoothEventManager( 3329): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,I/BluetoothBondStateMachine( 1520): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1520): StableState(): Entering Off State
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,E/BluetoothEventManager( 3329): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/jxcore-log( 2820): 2015-12-03T14:06:36.568Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:36.603Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:36.679Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:36.889Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:37.492Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:37.730Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:37.734Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:38.231Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2820): 
,I/        ( 2820): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3634, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3634, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 2820): 2015-12-03T14:06:38.506Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2820): 
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2820): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9133"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9133"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT9133, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT9133, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3375): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,I/wpa_supplicant( 3375): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 3375): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 3375): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  755): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  755): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  755): Attempting to switch to mobile
,D/ConnectivityService(  755): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  755): android_net_utils_resetConnections in env=0x778fc1f0 clazz=0x9d200001 iface=wlan0 mask=0x3
D/ConnectivityService(  755): resetConnections(wlan0, 3)
,I/jxcore-log( 2820): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): The Coordinator has disconnected!
I/jxcore-log( 2820): 
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1020): Read error: ssl=0x7a16f348: I/O error during system call, Connection timed out
,V/NativeCrypto( 1020): SSL shutdown failed: ssl=0x7a16f348: I/O error during system call, Broken pipe
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,W/bt-btif ( 1520): dm_pm_timer expires
,W/bt-btif ( 1520): dm_pm_timer expires 0
,W/bt-btif ( 1520): proc dm_pm_timer expires
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,D/WifiService(  755): setWifiEnabled: false pid=2820, uid=10108
,D/WifiService(  755): setWifiEnabled: true pid=2820, uid=10108
,E/WifiStateMachine(  755): scanCount==0 - aborting
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/WifiController(  755): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 468ms
,I/jxcore-log( 2820): Wifi toggled for connection repairment
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2820): Wifi is DISABLED !!
,I/        ( 2820): Stoping All
I/        ( 2820): Stopping services
,I/        ( 2820): Stopping services
,I/        ( 2820): Stop Bluetooth
I/        ( 2820): Stop Bluetooth
,I/BTListenerThread( 2820): Stopped
E/bt-btif ( 1520): bta_jv_rfcomm_stop_server
I/        ( 2820): Clearing local services failed, error code 2
,I/        ( 2820): Clearing service requests failed, error code 2
,I/        ( 2820): Stopping peer discovery failed, error code 2
,I/wpa_supplicant( 3375): P2P-FIND-STOPPED 
I/wpa_supplicant( 3375): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3375): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3375): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3375): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3375): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3375): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3375): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 3375): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 3375): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering(  755): InitialState.processMessage what=4
D/Tethering(  755): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 3375): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1913): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  997): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  755): DEFERRED_TOGGLE handled
,D/SoftapController(  180): Softap fwReload - Ok
D/CommandListener(  180): Setting iface cfg
,D/CommandListener(  180): Trying to bring down wlan0
,I/wpa_supplicant( 3599): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3599): rfkill: Cannot open RFKILL control device
,D/WifiMonitor(  755): startMonitoring(wlan0) with mConnected = false
,D/Tethering(  755): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3599): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  755): Loading config and enabling all networks
,W/Settings( 1913): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  180): Setting iface cfg
,D/CommandListener(  180): Trying to bring up p2p0
,D/WifiMonitor(  755): startMonitoring(p2p0) with mConnected = true
,I/WB      ( 2820): Wifi is now enabled !
I/        ( 2820): Stoping All
I/        ( 2820): Stopping services
I/        ( 2820): Stop Bluetooth
I/        ( 2820): Starting All
I/        ( 2820): Stopping services
I/        ( 2820): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1565"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@4266e3d0
I/        ( 2820): Stopping services
,I/        ( 2820): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1565"}
I/        ( 2820): Add local service :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1565"}, length : 77
,I/        ( 2820): peerDiscoveryTimer timeout value:9717
,I/        ( 2820): Stop Bluetooth
I/        ( 2820): StartBluetooth listener
I/        ( 2820): StartBluetooth listener
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2820): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1520): SOCK FLAG = 0 ***********************
I/BTListenerThread( 2820): starting to listen
I/BTListenerThread( 2820): waiting to accept incoming Connection
,I/        ( 2820): Discovery state changed to Started.
,I/        ( 2820): Added local service
,I/        ( 2820): Cleared service requests
I/        ( 2820): Stopped peer discovery
,I/        ( 2820): Started peer discovery
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  755): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/Babel   ( 1913): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1328): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2820): Found 1 peers.
,I/SS      ( 2820): Peer(1): A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pManager( 2820): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2820): Added service request
,I/        ( 2820): Started service discovery
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2820): 2015-12-03T14:06:48.507Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:48.508Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:48.511Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:48.513Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:48.516Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2820): 
,I/BtToSocketBase( 2820): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2820): Disconnect outgoing peer: samsung-SM-G900F_PT411
,I/BtToSocketBase( 2820): Stop ReceivingThread
,I/BtToSocketBase( 2820): Stop SendingThread
,I/BtToSocketBase( 2820): Close local in
,I/BtToSocketBase( 2820): Close LocalOutputStream
,I/BtToSocketBase( 2820): Close localHostSocket
,I/BtToSocketBase( 2820): Close bt in
,I/BtToSocketBase( 2820): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2820): Close bt out
,I/BtToSocketBase( 2820): Close bt socket
,I/BtToRequestSocket( 2820): Close server socket
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 1520): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/dalvikvm(  755): GC_CONCURRENT freed 2214K, 53% free 26840K/56332K, paused 38ms+5ms, total 93ms
,I/jxcore-log( 2820): 2015-12-03T14:06:53.516Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:53.517Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,I/        ( 2820): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3634, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3634, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2820): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT411, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT411, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2820): 2015-12-03T14:06:58.539Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:58.540Z SendDataConnector.js: Connect (retry count 1) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:58.541Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:06:58.543Z SendDataConnector.js: do connect now
I/jxcore-log( 2820): 
,I/        ( 2820): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 2820): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 2820): Starting to connect
,W/BluetoothAdapter( 2820): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1520): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2820): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[294]}
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,W/bt-sdp  ( 1520): process_service_search_attr_rsp
,W/bt-btif ( 1520): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2820): Starting to Handshake
,W/bt-btif ( 1520): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 1520): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2820): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2820): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2820): BTHandshakeSocketThread started
,I/BTConnectToThread( 2820): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 2820): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2820): HandshakeOk : samsung-SM-G900F_PT411
,I/        ( 2820): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7904","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7904","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT7904, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT7904, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/HS      ( 2820): Hand Shake finished outgoing for : samsung-SM-G900F_PT411
,I/BTHandshakeSocketThread( 2820): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2820): Starting the connected thread incoming : false, samsung-SM-G900F_PT411
,I/BtToSocketBase( 2820): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2820): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2820): mHTTPPort  set to : 55982
,I/BtConnectorHelper( 2820): Request socket is using : 55982
,I/BtToRequestSocket( 2820): Now accepting connections
,I/BtConnectorHelper( 2820): Calling ConnectionStatusUpdate with port :55982
,I/jxcore-log( 2820): 2015-12-03T14:07:02.469Z SendDataConnector.js: CLIENT connected to 55982, error: null
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:02.471Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2820): 
,I/BtToRequestSocket( 2820): incoming data from: /127.0.0.1, port: 55982
,I/BtToRequestSocket( 2820): Set local streams
,I/jxcore-log( 2820): 2015-12-03T14:07:02.486Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2820): 
,I/BtToRequestSocket( 2820): rin ended ---------------------------;
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2820): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7439","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7439","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT7439, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT7439, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 1520): dm_pm_timer expires
,W/bt-btif ( 1520): dm_pm_timer expires 0
,W/bt-btif ( 1520): proc dm_pm_timer expires
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2820): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2326"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2326"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2326, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2326, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 2820): 2015-12-03T14:07:12.557Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:12.558Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:12.561Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:12.563Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:12.565Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2820): 
,I/BtToSocketBase( 2820): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2820): Disconnect outgoing peer: samsung-SM-G900F_PT411
,I/BtToSocketBase( 2820): Stop ReceivingThread
I/BtToSocketBase( 2820): Stop SendingThread
,I/BtToSocketBase( 2820): Close local in
,I/BtToSocketBase( 2820): Close LocalOutputStream
,I/BtToSocketBase( 2820): Close localHostSocket
,I/BtToSocketBase( 2820): Close bt in
,I/BtToSocketBase( 2820): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2820): Close bt out
,I/BtToSocketBase( 2820): Close bt socket
,I/BtToRequestSocket( 2820): Close server socket
,I/        ( 2820): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7616, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7616, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-btif ( 1520): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2820): 2015-12-03T14:07:17.583Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:17.584Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2820): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6183","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6183","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6183, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6183, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 2820): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5769, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5769, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 2820): 2015-12-03T14:07:22.607Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:22.608Z SendDataConnector.js: Connect (retry count 2) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:22.610Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:22.612Z SendDataConnector.js: do connect now
I/jxcore-log( 2820): 
,I/        ( 2820): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 2820): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 2820): Starting to connect
,W/BluetoothAdapter( 2820): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1520): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2820): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[296]}
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,D/dalvikvm(  997): GC_CONCURRENT freed 446K, 3% free 17901K/18444K, paused 3ms+1ms, total 20ms
,W/bt-sdp  ( 1520): process_service_search_attr_rsp
,W/bt-btif ( 1520): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2820): Starting to Handshake
,W/bt-btif ( 1520): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 1520): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2820): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2820): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2820): BTHandshakeSocketThread started
,I/BTConnectToThread( 2820): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 2820): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2820): HandshakeOk : samsung-SM-G900F_PT411
,I/HS      ( 2820): Hand Shake finished outgoing for : samsung-SM-G900F_PT411
,I/BtConnectorHelper( 2820): Starting the connected thread incoming : false, samsung-SM-G900F_PT411
,I/BtToSocketBase( 2820): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2820): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2820): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2820): mHTTPPort  set to : 53238
,I/BtConnectorHelper( 2820): Request socket is using : 53238
,I/BtToRequestSocket( 2820): Now accepting connections
,I/BtConnectorHelper( 2820): Calling ConnectionStatusUpdate with port :53238
,I/jxcore-log( 2820): 2015-12-03T14:07:26.885Z SendDataConnector.js: CLIENT connected to 53238, error: null
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:26.886Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2820): 
,I/BtToRequestSocket( 2820): incoming data from: /127.0.0.1, port: 53238
,I/BtToRequestSocket( 2820): Set local streams
,I/jxcore-log( 2820): 2015-12-03T14:07:26.901Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2820): 
,I/BtToRequestSocket( 2820): rin ended ---------------------------;
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2820): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9133"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9133"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT9133, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT9133, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 1520): dm_pm_timer expires
,W/bt-btif ( 1520): dm_pm_timer expires 0
,W/bt-btif ( 1520): proc dm_pm_timer expires
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: ALE-L21
,D/dalvikvm( 1228): GC_CONCURRENT freed 470K, 7% free 17911K/19064K, paused 2ms+1ms, total 17ms
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,E/bt-btm  ( 1520): tBTM_SEC_DEV:0x7525595c rs_disc_pending=1
,W/bt-btif ( 1520): bta_dm_check_av:0
,W/bt-btif ( 1520): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 1520): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,I/BluetoothBondStateMachine( 1520): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 12 NewState: 11
,I/BluetoothBondStateMachine( 1520): Entering PendingCommandState State
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=6
,E/bt-btif ( 1520): services_to_search = 3fffffff
,E/bt-btif ( 1520): ****************search UUID = 1200***********
,W/bt-sdp  ( 1520): process_service_search_attr_rsp
,I/        ( 2820): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 2820): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT2226, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 2820): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT2226, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,E/bt-btif ( 1520): services_to_search = 3ffffffe
,E/bt-btif ( 1520): ****************search UUID = 0100***********
,W/bt-btif ( 1520): new conn_srvc id:26, app_id:255
,W/bt-btif ( 1520): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1520): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2820): we got incoming connection
,I/BTHandshakeSocketThread( 2820): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2820): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2820): BTHandshakeSocketThread started
,I/BTListenerThread( 2820): got MESSAGE_READ 80 bytes.
,I/BTListenerThread( 2820): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7421","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2820): MESSAGE_WRITE 77 bytes.
,I/HS      ( 2820): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT7421
,I/BTHandshakeSocketThread( 2820): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2820): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7421
,I/BtToSocketBase( 2820): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2820): Creating BTConnectedThread
,I/BtConnectorHelper( 2820): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2820): --DoOneRunRound started
,I/jxcore-log( 2820): 2015-12-03T14:07:36.840Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2820): 
,I/BtToRequestSocket( 2820): LocalHost address: localhost/127.0.0.1, port: 42532
,I/BtToRequestSocket( 2820): --DoOneRunRound ended
,I/jxcore-log( 2820): 2015-12-03T14:07:36.967Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:36.967Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2820): 
I/jxcore-log( 2820): 2015-12-03T14:07:36.968Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:36.968Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2820): 
I/jxcore-log( 2820): 2015-12-03T14:07:36.968Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2820): 
,I/BtToSocketBase( 2820): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2820): Disconnect outgoing peer: samsung-SM-G900F_PT411
I/BtToSocketBase( 2820): Stop ReceivingThread
I/BtToSocketBase( 2820): Stop SendingThread
I/BtToSocketBase( 2820): Close local in
I/BtToSocketBase( 2820): Close LocalOutputStream
,I/BtToSocketBase( 2820): Close localHostSocket
I/BtToSocketBase( 2820): Close bt in
I/BtToSocketBase( 2820): Close bt out
,I/BtToSocketBase( 2820): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 2820): Close bt socket
,I/BtToRequestSocket( 2820): Close server socket
,W/bt-sdp  ( 1520): process_service_search_attr_rsp
,E/bt-btif ( 1520): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1520): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1520): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1520): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1520): Index: 4 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1520): Index: 5 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1520): Index: 6 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1520): Index: 7 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1520): Index: 8 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 1520): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 1520): Removing bonded device:58:2A:F7:ED:96:BE
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,I/BluetoothBondStateMachine( 1520): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1520): StableState(): Entering Off State
,W/BluetoothEventManager( 3329): showUnbondMessage: Not displaying any message for reason: 0
,D/BluetoothMap( 3329): getConnectedDevices()
,D/BluetoothMap( 3329): getConnectionState(58:2A:F7:ED:96:BE)
,D/MapProfile( 3329): getConnectionStatus: status is: 0
,E/bt-btm  ( 1520): tBTM_SEC_DEV:0x7525595c rs_disc_pending=0
,W/bt-btif ( 1520): bta_dm_check_av:0
,W/bt-btif ( 1520): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1520): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3599): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2820): 2015-12-03T14:07:37.586Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.590Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.628Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.634Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.686Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.692Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.740Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.774Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.785Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.797Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.824Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.890Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.919Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.956Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:37.972Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.001Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.034Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.039Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.056Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.084Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.115Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.120Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.132Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.165Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.206Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.216Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.220Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.252Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.284Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.306Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.335Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.377Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.383Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.406Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.446Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.457Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.460Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.493Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.534Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.543Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.553Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.585Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.596Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:38.670Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  755): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2820): 2015-12-03T14:07:41.988Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:41.989Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2820): 
,D/WifiService(  755): setWifiEnabled: false pid=2820, uid=10108
,D/WifiService(  755): setWifiEnabled: true pid=2820, uid=10108
,D/WifiController(  755): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 470ms
,I/jxcore-log( 2820): Wifi toggled for connection repairment
I/jxcore-log( 2820): 
,I/chromium( 2820): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiController(  755): DEFERRED_TOGGLE handled
,W/bt-btif ( 1520): dm_pm_timer expires
,W/bt-btif ( 1520): dm_pm_timer expires 0
,W/bt-btif ( 1520): proc dm_pm_timer expires
,E/WifiStateMachine(  755): scanCount==0 - aborting
,I/WB      ( 2820): Wifi is DISABLED !!
,I/        ( 2820): Stoping All
I/        ( 2820): Stopping services
,I/        ( 2820): Stopping services
,I/        ( 2820): Stop Bluetooth
,I/        ( 2820): Stop Bluetooth
I/BTListenerThread( 2820): Stopped
,E/bt-btif ( 1520): bta_jv_rfcomm_stop_server
I/        ( 2820): Clearing service requests failed, error code 2
I/        ( 2820): Starting peer discovery failed, error code 2
I/        ( 2820): Clearing local services failed, error code 2
,I/        ( 2820): Clearing service requests failed, error code 2
,I/        ( 2820): Stopping peer discovery failed, error code 2
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,I/wpa_supplicant( 3599): P2P-FIND-STOPPED 
I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant( 3599): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/jxcore-log( 2820): 2015-12-03T14:07:47.009Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:47.010Z SendDataConnector.js: Connect (retry count 3) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:47.011Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2820): 
,I/jxcore-log( 2820): 2015-12-03T14:07:47.013Z SendDataConnector.js: do connect now
I/jxcore-log( 2820): 
,D/AndroidRuntime( 2820): Shutting down VM
,W/dalvikvm( 2820): threadid=1: thread exiting with uncaught exception (group=0x4160bba8)
,I/dalvikvm( 2820): threadid=1: stack overflow on call to Ljava/lang/ThreadGroup;.uncaughtException:VLL
,I/dalvikvm( 2820):   method requires 16+20+12=48 bytes, fp is 0x6d4ab314 (20 left)
,I/dalvikvm( 2820):   expanding stack end (0x6d4ab300 to 0x6d4ab000)
,I/dalvikvm( 2820): Shrank stack (to 0x6d4ab300, curFrame is 0x6d4b0fb0)
,I/wpa_supplicant( 3599): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering(  755): InitialState.processMessage what=4
,D/Tethering(  755): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 3599): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1913): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  997): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SoftapController(  180): Softap fwReload - Ok
D/CommandListener(  180): Setting iface cfg
,D/CommandListener(  180): Trying to bring down wlan0
,D/WifiMonitor(  755): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3720): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3720): rfkill: Cannot open RFKILL control device
,W/bt-btif ( 1520): invalid rfc slot id: 12
I/BtToSocketBase( 2820): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2820): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2820): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2820): Stop ReceivingThread
I/BtToSocketBase( 2820): Stop SendingThread
I/BtToSocketBase( 2820): Close local in
I/BtToSocketBase( 2820): Close LocalOutputStream
I/BtToSocketBase( 2820): Close localHostSocket
I/BtToSocketBase( 2820): Close bt in
I/BtToSocketBase( 2820): Close bt out
,I/BtToSocketBase( 2820): Close bt socket
I/BtToSocketBase( 2820): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 2820): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,D/Tethering(  755): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3720): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  755): Loading config and enabling all networks
,W/Settings( 1913): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  180): Setting iface cfg
,D/CommandListener(  180): Trying to bring up p2p0
,D/WifiMonitor(  755): startMonitoring(p2p0) with mConnected = true
,W/wpa_supplicant( 3720): wlan0: Failed to initiate AP scan
,W/wpa_supplicant( 3720): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 3720): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,E/bt-btm  ( 1520): tBTM_SEC_DEV:0x752555e4 rs_disc_pending=0
,W/bt-btif ( 1520): bta_dm_check_av:0
,W/bt-btif ( 1520): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 1520): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 1520): RFCOMM_DisconnectInd LCID:0x47
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
E/wpa_supplicant( 3720): Retrying assoc: 1 
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 3720): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,I/wpa_supplicant( 3720): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3720): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  755): scanCount==0 - aborting
,D/WifiStateMachine(  755): VerifyingLinkState enter
,D/WifiStateMachine(  755): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  755): CaptivePortalCheckState enter
D/ConnectivityService(  755): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  755): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  755): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  755): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  755): Unexpected mtu value: android.net.wifi.WifiStateTracker@42c9e2a8
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/ConnectivityService(  755): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  755):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [58:2a:f7:ed:96:be]: 7, f, 610c
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  755): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1328): num updated entries: 0
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,I/Babel   ( 1913): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  755): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/CaptivePortalTracker(  755): DelayedCaptiveCheckState{ when=-13ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  755): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  755): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  755): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  755): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  755): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/dalvikvm(  997): GC_CONCURRENT freed 388K, 3% free 17900K/18444K, paused 2ms+1ms, total 15ms
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,D/dalvikvm( 1520): GC_CONCURRENT freed 407K, 3% free 16879K/17316K, paused 26ms+5ms, total 89ms
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityService(  755): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  755): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  755): Attempting to switch to mobile
D/ConnectivityService(  755): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  755): android_net_utils_resetConnections in env=0x778fc1f0 clazz=0xbc800001 iface=wlan0 mask=0x3
,D/ConnectivityService(  755): resetConnections(wlan0, 3)
V/NativeCrypto( 1020): Read error: ssl=0x7a16f348: I/O error during system call, Connection timed out
,V/NativeCrypto( 1020): SSL shutdown failed: ssl=0x7a16f348: I/O error during system call, Broken pipe
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3720): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
,E/wpa_supplicant( 3720): Retrying assoc: 1 
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  755): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/Babel   ( 1913): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1328): active receiver: enabled
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1328): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,D/dalvikvm( 1328): GC_CONCURRENT freed 898K, 5% free 18918K/19848K, paused 9ms+4ms, total 37ms
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,I/wpa_supplicant( 3720): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3720): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,I/wpa_supplicant( 3720): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  755): scanCount==0 - aborting
,I/wpa_supplicant( 3720): P2P-FIND-STOPPED 
,D/WifiStateMachine(  755): VerifyingLinkState enter
,D/WifiStateMachine(  755): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  755): CaptivePortalCheckState enter
D/ConnectivityService(  755): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  755): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  755): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  755): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  755): Unexpected mtu value: android.net.wifi.WifiStateTracker@42c9e2a8
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  755): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  755): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  755):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  755): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/iu.UploadsManager( 1328): num updated entries: 0
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,I/Babel   ( 1913): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm(  755): GC_CONCURRENT freed 2330K, 53% free 26925K/56332K, paused 23ms+5ms, total 115ms
,D/dalvikvm( 1020): GC_CONCURRENT freed 524K, 5% free 18423K/19364K, paused 3ms+8ms, total 32ms
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/ConnectivityService(  755): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/CaptivePortalTracker(  755): DelayedCaptiveCheckState{ when=-12ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  755): Checking http://216.58.209.46/generate_204
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/CaptivePortalTracker(  755): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  755): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  755): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  755): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/dalvikvm(  997): GC_CONCURRENT freed 387K, 3% free 17900K/18440K, paused 2ms+2ms, total 14ms
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant( 3720): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3720): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 3720): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/ConnectivityService(  755): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  755): Done.
,D/ConnectivityService(  755): Setting timer for 720seconds
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G3s-1
,D/dalvikvm( 1228): GC_CONCURRENT freed 496K, 6% free 17926K/19064K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 1228): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/dalvikvm(  997): GC_CONCURRENT freed 391K, 3% free 17900K/18436K, paused 2ms+1ms, total 15ms
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/dalvikvm( 1520): GC_CONCURRENT freed 386K, 3% free 16878K/17316K, paused 3ms+0ms, total 10ms
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1228): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1228): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/BluetoothAdapterService(1114008080)( 1520): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1520): getBondedDevices: length=5
,D/dalvikvm(  997): GC_CONCURRENT freed 388K, 3% free 17899K/18432K, paused 3ms+1ms, total 14ms
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  755): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  755): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  755): Attempting to switch to mobile
,D/ConnectivityService(  755): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  755): android_net_utils_resetConnections in env=0x778fc1f0 clazz=0xfc000001 iface=wlan0 mask=0x3
D/ConnectivityService(  755): resetConnections(wlan0, 3)
,V/NativeCrypto( 1020): Read error: ssl=0x7a16f348: I/O error during system call, Connection timed out
,V/NativeCrypto( 1020): SSL shutdown failed: ssl=0x7a16f348: I/O error during system call, Broken pipe
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3720): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3720): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3720): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  755): scanCount==0 - aborting
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  755): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/Babel   ( 1913): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.SyncManager( 1328): NEXT; no task
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1328): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,D/WifiStateMachine(  755): VerifyingLinkState enter
,D/WifiStateMachine(  755): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  755): CaptivePortalCheckState enter
,D/WifiStateMachine(  755): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  755): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  755): Unexpected mtu value: android.net.wifi.WifiStateTracker@42c9e2a8
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  755): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  755): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0,
D/ConnectivityService(  755):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  755): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  755): NoActiveNetworkState{ when=-12ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,I/Babel   ( 1913): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  755): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,D/ConnectivityService(  755): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  755): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=6 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  755): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  755): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  755): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  755): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  755): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106,
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  755): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  755): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  755): Attempting to switch to mobile
,D/ConnectivityService(  755): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  755): android_net_utils_resetConnections in env=0x778fc1f0 clazz=0x1eb00001 iface=wlan0 mask=0x3
D/ConnectivityService(  755): resetConnections(wlan0, 3)
,V/NativeCrypto( 1020): Read error: ssl=0x758e7708: I/O error during system call, Connection timed out
,V/NativeCrypto( 1020): SSL shutdown failed: ssl=0x758e7708: I/O error during system call, Broken pipe
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3720): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3720): wlan0: Associated with c0:ff:d4:d3:aa:48
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3720): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  755): scanCount==0 - aborting
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  755): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/Babel   ( 1913): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1328): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,D/dalvikvm(  755): GC_CONCURRENT freed 2321K, 52% free 27041K/56332K, paused 8ms+5ms, total 80ms
,D/WifiStateMachine(  755): VerifyingLinkState enter
D/WifiStateMachine(  755): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  755): CaptivePortalCheckState enter
,D/WifiStateMachine(  755): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  755): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  755): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  755): Unexpected mtu value: android.net.wifi.WifiStateTracker@42c9e2a8
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  755): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  755): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  755):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  755): NoActiveNetworkState{ when=-58ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
,I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
,D/dalvikvm( 1025): GC_CONCURRENT freed 388K, 3% free 17070K/17484K, paused 3ms+1ms, total 11ms
,I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,I/Babel   ( 1913): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  755): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [08:ec:a9:50:75:41]: 6, f, 4106
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/CaptivePortalTracker(  755): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=7 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  755): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  755): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  755): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  755): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  755): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [08:ec:a9:50:75:41]: 6, f, 4106
,D/dalvikvm( 1520): GC_CONCURRENT freed 385K, 3% free 16878K/17296K, paused 8ms+1ms, total 16ms
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [08:ec:a9:50:75:41]: 6, f, 4106
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1520): tBTM_SEC_DEV:0x75255cd4 rs_disc_pending=1
,W/bt-btif ( 1520): bta_dm_check_av:0
,W/bt-btif ( 1520): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1520): tBTM_SEC_DEV:0x75255e90 rs_disc_pending=0
,W/bt-btif ( 1520): bta_dm_check_av:0
,W/bt-btif ( 1520): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1520): l2cu_get_conn_role 0
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [08:ec:a9:50:75:41]: 6, f, 4106
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1520): tBTM_SEC_DEV:0x75255cd4 rs_disc_pending=1
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1520): bta_dm_check_av:0
,W/bt-btif ( 1520): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1520): tBTM_SEC_DEV:0x75255e90 rs_disc_pending=0
,W/bt-btif ( 1520): bta_dm_check_av:0
,W/bt-btif ( 1520): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [34:fc:ef:11:ae:67]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1520): GC_CONCURRENT freed 392K, 3% free 16878K/17304K, paused 7ms+0ms, total 51ms
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  755): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  755): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  755): Attempting to switch to mobile
,D/ConnectivityService(  755): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  755): android_net_utils_resetConnections in env=0x778fc1f0 clazz=0x3cd00001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1020): Read error: ssl=0x758e7708: I/O error during system call, Connection timed out
D/ConnectivityService(  755): resetConnections(wlan0, 3)
,V/NativeCrypto( 1020): SSL shutdown failed: ssl=0x758e7708: I/O error during system call, Broken pipe
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3720): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,D/ConnectivityService(  755): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3720): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3720): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3720): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  755): scanCount==0 - aborting
,W/bt-l2cap( 1520): l2cu_get_conn_role 1
,W/bt-btif ( 1520): info:x10
,D/        ( 1520): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  755): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/Babel   ( 1913): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/dalvikvm( 1020): GC_CONCURRENT freed 499K, 5% free 18399K/19364K, paused 1ms+1ms, total 28ms
,D/dalvikvm( 3068): GC_CONCURRENT freed 282K, 2% free 16802K/17116K, paused 2ms+1ms, total 14ms
,D/SystemUpdateService( 1328): onDestroy
,D/WifiStateMachine(  755): VerifyingLinkState enter
D/WifiStateMachine(  755): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  755): CaptivePortalCheckState enter
,D/WifiStateMachine(  755): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  755): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  755): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  755): Unexpected mtu value: android.net.wifi.WifiStateTracker@42c9e2a8
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  755): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  755): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  755):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  755): requiresClat: netType=1, hasIPv4Address=true
,D/btif_config_util( 1520): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/ConnectivityService(  755): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  755): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,D/dalvikvm( 2321): GC_CONCURRENT freed 424K, 3% free 17734K/18188K, paused 4ms+4ms, total 24ms
,D/dalvikvm( 1328): GC_CONCURRENT freed 634K, 5% free 18929K/19848K, paused 3ms+6ms, total 40ms
,D/dalvikvm( 1913): GC_CONCURRENT freed 1791K, 8% free 22689K/24516K, paused 1ms+2ms, total 33ms
,D/dalvikvm( 1913): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/Babel   ( 1913): connection state changed from DISCONNECTED to CONNECTED
,E/bt-btm  ( 1520): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1520): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  755): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,D/ConnectivityService(  755): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  755): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  755): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  755): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  755): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  755): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  755): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  755): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  755): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/ConnectivityService(  755): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  755): Done.
,D/ConnectivityService(  755): Setting timer for 720seconds
,I/ProcessStatsService(  755): Prepared write state in 42ms
,I/ProcessStatsService(  755): Prepared write state in 6ms
,I/ProcessStatsService(  755): Pruning old procstats: /data/system/procstats/state-2015-12-02-15-59-20.bin
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager(  755): Killing 940:android.process.acore/u0a3 (adj 15): empty for 1800s
I/ActivityManager(  755): Killing 3082:com.google.android.apps.cloudprint/u0a32 (adj 15): empty for 1810s
I/ActivityManager(  755): Killing 3024:com.google.android.apps.magazines/u0a56 (adj 15): empty for 1810s
I/ActivityManager(  755): Killing 2703:com.android.musicfx/u0a13 (adj 15): empty for 1810s
I/ActivityManager(  755): Killing 2779:com.quickoffice.android/u0a65 (adj 15): empty for 1810s
I/ActivityManager(  755): Killing 2720:com.google.android.apps.docs/u0a35 (adj 15): empty for 1811s
I/ActivityManager(  755): Killing 2676:com.google.android.partnersetup/u0a11 (adj 15): empty for 1811s
D/AndroidRuntime( 4377): 
D/AndroidRuntime( 4377): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4377): CheckJNI is OFF
D/dalvikvm( 4377): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4377): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4377): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4377): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4377): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4377): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 4377): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  755): Force stopping com.test.thalitest appid=10108 user=-1: uninstall pkg
I/ActivityManager(  755): Killing 2820:com.test.thalitest/u0a108 (adj 0): stop com.test.thalitest
I/ActivityManager(  755):   Force finishing activity ActivityRecord{449bde30 u0 com.test.thalitest/.MainActivity t2}
I/WindowState(  755): WIN DEATH: Window{44989390 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  755): Skipping PackageSetting{4274ad70 com.example.hello/10115} due to missing metadata
I/ActivityManager(  755): Force stopping com.test.thalitest appid=10108 user=0: pkg removed
I/InputReader(  755): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  755): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4396 uid=10003 gids={50003, 3003, 1028, 1015}
D/dalvikvm(  981): GC_CONCURRENT freed 308K, 2% free 17014K/17348K, paused 2ms+10ms, total 35ms
D/dalvikvm( 1076): GC_EXPLICIT freed 551K, 7% free 26310K/28112K, paused 1ms+2ms, total 53ms
I/LatinIME:LogUtils(  981): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
I/Launcher( 1076): Deferring update until onResume
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  755):   Scheme: "sms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
W/GeofencerStateMachine(  997): Ignoring removeGeofence because network location is disabled.
D/dalvikvm(  755): GC_EXPLICIT freed 2609K, 53% free 26841K/56332K, paused 2ms+5ms, total 100ms
I/Launcher( 1076): Deferring update until onResume
D/dalvikvm( 1228): GC_EXPLICIT freed 186K, 7% free 17825K/19064K, paused 1ms+2ms, total 116ms
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  755):   Scheme: "smsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  755):   Scheme: "mms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
W/Binder  (  981): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  981): java.lang.NullPointerException
W/Binder  (  981): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  981): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  981): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  981): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  755): Got RemoteException sending setActive(false) notification to pid 2820 uid 10108
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  755):   Scheme: "mmsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm(  755): GC_EXPLICIT freed 420K, 53% free 26715K/56332K, paused 3ms+5ms, total 89ms
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  755):   Scheme: "sms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/BackupManagerService(  755): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  755): removePackageParticipantsLocked: uid=10108 #1
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  755):   Scheme: "smsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  755):   Scheme: "mms"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/AndroidRuntime( 4377): Shutting down VM
D/dalvikvm( 4377): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 1ms+1ms, total 3ms
D/dalvikvm( 4396): GC_CONCURRENT freed 257K, 2% free 16954K/17240K, paused 3ms+1ms, total 15ms
D/dalvikvm( 4396): WAIT_FOR_CONCURRENT_GC blocked 4ms
I/PackageManager(  755):   Action: "android.intent.action.SENDTO"
I/PackageManager(  755):   Category: "android.intent.category.DEFAULT"
D/dalvikvm( 4396): WAIT_FOR_CONCURRENT_GC blocked 5ms
I/PackageManager(  755):   Scheme: "mmsto"
I/PackageManager(  755): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/VoicemailCleanupService( 4396): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  755): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4425 uid=10013 gids={50013, 3003, 3002}
I/Icing.InternalIcingCorporaProvider( 1228): Updating corpora: A: com.test.thalitest, C: MAYBE
W/Launcher( 1076): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@4265eb70 new=com.google.android.velvet.VelvetApplication@4265eb70
I/ActivityManager(  755): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4441 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
W/ContextImpl( 4441): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
I/ActivityManager(  755): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4455 uid=10035 gids={50035, 1028, 3003, 1015}
I/ContactLocale( 4396): AddressBook Labels [en_US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Icing.InternalIcingCorporaProvider( 1228): UpdateCorporaTask done [took 62 ms] updated apps [took 62 ms] 
I/dalvikvm( 4455): Could not find method android.app.Activity.finishAfterTransition, referenced from method bx.onBackPressed
W/dalvikvm( 4455): VFY: unable to resolve virtual method 1145: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 4455): VFY: replacing opcode 0x6e at 0x0012
D/dalvikvm( 4455): GC_CONCURRENT freed 287K, 2% free 16869K/17184K, paused 2ms+1ms, total 13ms
D/dalvikvm( 4455): GC_CONCURRENT freed 314K, 3% free 17049K/17400K, paused 1ms+2ms, total 11ms
I/dalvikvm( 4455): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gwe.a
W/dalvikvm( 4455): VFY: unable to resolve virtual method 1697: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4455): VFY: replacing opcode 0x6e at 0x000f
I/GAv4    ( 4455): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4455):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4455):   adb logcat -s GAv4
W/GAv4    ( 4455): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/dalvikvm( 4455): Could not find method android.content.Context.checkSelfPermission, referenced from method arg.a
W/dalvikvm( 4455): VFY: unable to resolve virtual method 1515: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 4455): VFY: replacing opcode 0x6e at 0x001b
D/dalvikvm( 4455): GC_CONCURRENT freed 338K, 3% free 17224K/17592K, paused 2ms+1ms, total 12ms
D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 3ms
D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 3ms
W/GAv4    ( 4455): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4455): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 4455): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.453.15.35, sample rate 1.0
I/dalvikvm( 4455): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method efh.a
W/dalvikvm( 4455): VFY: unable to resolve static method 2872: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
D/dalvikvm( 4455): VFY: replacing opcode 0x71 at 0x0075
D/dalvikvm( 4455): GC_CONCURRENT freed 217K, 2% free 17508K/17756K, paused 2ms+2ms, total 14ms
D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/dalvikvm( 4455): GC_CONCURRENT freed 463K, 3% free 17560K/18052K, paused 1ms+1ms, total 14ms
D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 4455): GC_FOR_ALLOC freed 42K, 3% free 17604K/18052K, paused 11ms, total 11ms
E/DatabaseHelper( 4455): Unable to reenable write ahead logging in onOpen.
W/dalvikvm( 4455): threadid=14: thread exiting with uncaught exception (group=0x4160bba8)
W/FileUtils( 4455): Failed to chmod(/data/data/com.google.android.apps.docs/databases/DocList.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
W/FileUtils( 4455): Failed to chmod(/data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/AbstractDatabaseInstance( 4455): Failed to query Account150 object, columns: [accountHolderName], selection: null, args: null, groupBy: null, having: null, orderBy: null, limit: null
E/AbstractDatabaseInstance( 4455): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnectionPool.tryAcquirePrimaryConnectionLocked(SQLiteConnectionPool.java:860)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnectionPool.waitForConnection(SQLiteConnectionPool.java:613)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnectionPool.acquireConnection(SQLiteConnectionPool.java:348)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteSession.acquireConnection(SQLiteSession.java:894)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteSession.prepare(SQLiteSession.java:586)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteProgram.<init>(SQLiteProgram.java:58)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteStatement.<init>(SQLiteStatement.java:31)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1672)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1603)
E/AbstractDatabaseInstance( 4455): 	at aug.a(PG:1553)
E/AbstractDatabaseInstance( 4455): 	at jnh$a.a(PG:131)
E/AbstractDatabaseInstance( 4455): 	at aue.c(PG:148)
E/AbstractDatabaseInstance( 4455): 	at aue.a(PG:379)
E/AbstractDatabaseInstance( 4455): 	at aue.a(PG:366)
E/AbstractDatabaseInstance( 4455): 	at awe.e(PG:843)
E/AbstractDatabaseInstance( 4455): 	at efh.a(PG:1117)
E/AbstractDatabaseInstance( 4455): 	at amf.run(PG:39)
E/AbstractDatabaseInstance( 4455): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4455): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4455): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4455): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4455): 	at java.lang.Thread.run(Thread.java:841)
D/PackageBroadcastService( 1328): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1328): Clearing selected account for com.test.thalitest
I/ActivityManager(  755): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/dalvikvm( 4455): GC_CONCURRENT freed 300K, 2% free 17819K/18148K, paused 1ms+2ms, total 17ms
D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 10ms
E/AbstractDatabaseInstance( 4455): Failed to query Account150 object, columns: [accountHolderName], selection: null, args: null, groupBy: null, having: null, orderBy: null, limit: null
E/AbstractDatabaseInstance( 4455): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnectionPool.tryAcquirePrimaryConnectionLocked(SQLiteConnectionPool.java:860)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnectionPool.waitForConnection(SQLiteConnectionPool.java:613)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteConnectionPool.acquireConnection(SQLiteConnectionPool.java:348)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteSession.acquireConnection(SQLiteSession.java:894)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteSession.prepare(SQLiteSession.java:586)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteProgram.<init>(SQLiteProgram.java:58)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteStatement.<init>(SQLiteStatement.java:31)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1672)
E/AbstractDatabaseInstance( 4455): 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1603)
E/AbstractDatabaseInstance( 4455): 	at aug.a(PG:1553)
E/AbstractDatabaseInstance( 4455): 	at jnh$a.a(PG:131)
E/AbstractDatabaseInstance( 4455): 	at aue.c(PG:148)
E/AbstractDatabaseInstance( 4455): 	at aue.a(PG:379)
E/AbstractDatabaseInstance( 4455): 	at aue.a(PG:366)
E/AbstractDatabaseInstance( 4455): 	at awe.e(PG:843)
E/AbstractDatabaseInstance( 4455): 	at ayp.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 4455): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AbstractDatabaseInstance( 4455): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4455): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 4455): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4455): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4455): 	at java.lang.Thread.run(Thread.java:841)
W/dalvikvm( 4455): threadid=16: thread exiting with uncaught exception (group=0x4160bba8)
D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 10ms
E/SharedPreferencesImpl( 4455): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
E/SQLiteLog( 4455): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4    ( 4455): Local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 4455): Couldn't create directory for SharedPreferences file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml
I/LocationSettingsChecker( 1328): Removing dialog suppression flag for package com.test.thalitest
E/SharedPreferencesImpl( 4455): Couldn't create directory for SharedPreferences file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml
E/SQLiteDatabase( 1328): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1328): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1328): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteDatabase( 1328): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1328): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1328): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1328): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1328): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1328): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4455): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4    ( 4455): Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 4455): Couldn't create directory for SharedPreferences file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml
E/SQLiteOpenHelper( 1328): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1328): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1328): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1328): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1328): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1328): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1328): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1328): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1328): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1328): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1328): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1328): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteOpenHelper( 1328): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1328): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1328): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1328): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1328): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 1328): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1328): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1328): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1328): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
