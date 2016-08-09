#### Test 80598264be6cebf_thali08_samsung-SM-G900F Logs


```
--------- beginning of main
08-09 13:02:06.858  1986  1986 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-09 13:02:06.908  5678  5678 W Finsky  : [1] com.google.android.finsky.autoupdate.t.a(252): Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-09 13:02:06.918  5678  5678 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(741): Logging device features
--------- beginning of system
08-09 13:02:06.948   745   810 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cddb97a u0 com.google.android.vending.verifier.intent.action.VERIFY_INSTALLED_PACKAGES qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{20d5941 5678:com.android.vending/u0a29}
08-09 13:02:06.948  5678  5678 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(59): Cancelling accelerated self-Update check
08-09 13:02:06.958  5678  5678 W InstanceID/Rpc: Found 10011
08-09 13:02:06.968  5678  5678 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(946): Scheduling new run in 857 minutes (failures=5)
08-09 13:02:06.998  5678  5678 I Finsky  : [1] com.google.android.vending.verifier.VerifyInstalledPackagesReceiver.onReceive(2100): Skipping verification because network inactive
08-09 13:02:07.018  1986  1986 D WearableService: callingUid 10011, callindPid: 1986
08-09 13:02:07.018   745  1683 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2a8fa34 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{65ae6fe 1986:com.google.android.gms.persistent/u0a11}
08-09 13:02:07.038   745  2422 V AlarmManager:  remove PendingIntent] PendingIntent{666905d: PendingIntentRecord{f35bc35 com.google.android.gms broadcastIntent}}
08-09 13:02:07.038   745  1237 V AlarmManager: Expired Alarm result :4
08-09 13:02:07.038  1986  4840 D DeviceConnectionService: client connected with version: 8487000
08-09 13:02:07.048  5678  5678 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
08-09 13:02:07.048  5678  5678 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=hygiene due to Gms not connected
08-09 13:02:07.048   745   810 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b9f3ea3 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{20d5941 5678:com.android.vending/u0a29}
08-09 13:02:07.088  5678  6229 I Finsky  : [816] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
08-09 13:02:07.088  5678  5709 I PlayCommon: [789] com.google.android.play.a.al.e(730): Preparing logs for uploading
08-09 13:02:07.118  5678  6232 I PlayCommon: [818] com.google.android.play.a.w.a(27553): Starting to flush logs
08-09 13:02:07.118  5678  6232 I PlayCommon: [818] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
08-09 13:02:07.128  1986  1986 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-09 13:02:07.158  5678  5709 I PlayCommon: [789] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
08-09 13:02:07.158  5678  5709 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-09 13:02:07.158  5678  5709 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-09 13:02:07.168   305  1192 D EnterpriseController: netId is 0
08-09 13:02:07.168   305  1192 D Netd    : getNetworkForDns: using netid 0 for uid 10029
08-09 13:02:07.168  5678  5709 E PlayCommon: [789] com.google.android.play.a.al.a(881): Failed to connect to server: java.net.UnknownHostException: Unable to resolve host "play.googleapis.com": No address associated with hostname
08-09 13:02:07.178   745  2414 I ActivityManager: Killing 4975:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
08-09 13:02:07.208   745   765 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
08-09 13:02:08.198  2335  2335 E audit   : type=1400 msg=audit(1470740528.188:278): avc:  denied  { execmod } for  pid=6222 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-09 13:02:08.198  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-09 13:02:08.198  2335  2335 E audit   : type=1300 msg=audit(1470740528.188:278): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe0000 a1=51000 a2=5 a3=4 items=0 ppid=3395 ppcomm=adbd pid=6222 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-09 13:02:08.198  2335  2335 E audit   : type=1327 msg=audit(1470740528.188:278): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-09 13:02:08.198  2335  2335 E audit   : type=1320 msg=audit(1470740528.188:278): 
08-09 13:02:08.268  2335  2335 E audit   : type=1400 msg=audit(1470740528.268:279): avc:  denied  { execmod } for  pid=6222 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-09 13:02:08.268  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-09 13:02:08.268  2335  2335 E audit   : type=1300 msg=audit(1470740528.268:279): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fa0000 a1=51000 a2=5 a3=4 items=0 ppid=3395 ppcomm=adbd pid=6222 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-09 13:02:08.268  2335  2335 E audit   : type=1327 msg=audit(1470740528.268:279): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-09 13:02:08.268  2335  2335 E audit   : type=1320 msg=audit(1470740528.268:279): 
08-09 13:02:08.328  2335  2335 E audit   : type=1400 msg=audit(1470740528.328:280): avc:  denied  { execmod } for  pid=6222 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-09 13:02:08.328  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-09 13:02:08.328  2335  2335 E audit   : type=1300 msg=audit(1470740528.328:280): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fa0000 a1=51000 a2=5 a3=4 items=0 ppid=3395 ppcomm=adbd pid=6222 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-09 13:02:08.328  2335  2335 E audit   : type=1327 msg=audit(1470740528.328:280): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-09 13:02:08.328  2335  2335 E audit   : type=1320 msg=audit(1470740528.328:280): 
08-09 13:02:08.328  6222  6222 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-09 13:02:08.338  6222  6222 D AndroidRuntime: CheckJNI is OFF
08-09 13:02:08.338  6222  6222 D AndroidRuntime: readGMSProperty: start
08-09 13:02:08.338  6222  6222 D AndroidRuntime: readGMSProperty: already setted!!
08-09 13:02:08.338  6222  6222 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-09 13:02:08.338  6222  6222 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-09 13:02:08.338  6222  6222 D AndroidRuntime: readGMSProperty: end
08-09 13:02:08.338  6222  6222 D AndroidRuntime: addProductProperty: start
08-09 13:02:08.348  6222  6222 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-09 13:02:08.348  6222  6222 W art     : af14e000-b2074000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-09 13:02:08.348  6222  6222 W art     : b2074000-b42e3000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-09 13:02:08.348  6222  6222 W art     : b42e3000-b42e4000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-09 13:02:08.348  6222  6222 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-09 13:02:08.348  6222  6222 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
08-09 13:02:08.348  6222  6222 W art     : b4733000-b473d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-09 13:02:08.348  6222  6222 W art     : b473d000-b473e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-09 13:02:08.348  6222  6222 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
08-09 13:02:08.348  6222  6222 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-09 13:02:08.348  6222  6222 W art     : b4846000-b486f000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-09 13:02:08.348  6222  6222 W art     : b486f000-b4872000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-09 13:02:08.348  6222  6222 W art     : b4872000-b4873000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-09 13:02:08.348  6222  6222 W art     : b4873000-b4874000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-09 13:02:08.348  6222  6222 W art     : b4874000-b4875000 r--p 00000000 00:00 0 
08-09 13:02:08.348  6222  6222 W art     : b4875000-b4895000 r--s 00000000 00:0b 7179       /dev/__properties__
08-09 13:02:08.348  6222  6222 W art     : b4895000-b52a6000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-09 13:02:08.348  6222  6222 W art     : b52a6000-b52a7000 ---p 00000000 00:00 0 
08-09 13:02:08.348  6222  6222 W art     : b52a7000-b52f0000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-09 13:02:08.348  6222  6222 W art     : b52f0000-b52f1000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-09 13:02:08.358  6222  6222 W art     : b52f1000-b52f9000 rw-p 00000000 00:00 0 
08-09 13:02:08.358  6222  6222 W art     : b52f9000-b52fa000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.358  6222  6222 W art     : b52fa000-b532f000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-09 13:02:08.358  6222  6222 W art     : b532f000-b5330000 ---p 00000000 00:00 0 
08-09 13:02:08.358  6222  6222 W art     : b5330000-b5331000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-09 13:02:08.358  6222  6222 W art     : b5331000-b5332000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-09 13:02:08.358  6222  6222 W art     : b5332000-b538a000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-09 13:02:08.358  6222  6222 W art     : b538a000-b538b000 ---p 00000000 00:00 0 
08-09 13:02:08.358  6222  6222 W art     : b538b000-b538c000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-09 13:02:08.358  6222  6222 W art     : b538c000-b538d000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-09 13:02:08.358  6222  6222 W art     : b538e000-b5394000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-09 13:02:08.358  6222  6222 W art     : b5394000-b5395000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-09 13:02:08.358  6222  6222 W art     : b5395000-b5396000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-09 13:02:08.358  6222  6222 W art     : b5396000-b5398000 rw-p 00000000 00:00 0 
08-09 13:02:08.358  6222  6222 W art     : b5399000-b53a3000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-09 13:02:08.358  6222  6222 W art     : b53a3000-b53a6000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-09 13:02:08.358  6222  6222 W art     : b53a6000-b53a7000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-09 13:02:08.358  6222  6222 W art     : b53a8000-b53bf000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-09 13:02:08.358  6222  6222 W art     : b53bf000-b53c0000 ---p 00000000 00:00 0 
08-09 13:02:08.358  6222  6222 W art     : b53c0000-b53c1000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-09 13:02:08.358  6222  6222 W art     : b53c1000-b53c2000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-09 13:02:08.358  6222  6222 W art     : b53c3000-b53cd000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-09 13:02:08.358  6222  6222 W art     : b53cd000-b53ce000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-09 13:02:08.358  6222  6222 W art     : b53ce000-b53cf000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-09 13:02:08.358  6222  6222 W art     : b53cf000-b53d3000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-09 13:02:08.358  6222  6222 W art     : b53d3000-b53d4000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-09 13:02:08.358  6222  6222 W art     : b53d4000-b53d5000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-09 13:02:08.358  6222  6222 W art     : b53d5000-b53eb000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-09 13:02:08.358  6222  6222 W art     : b53eb000-b53ec000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-09 13:02:08.358  6222  6222 W art     : b53ec000-b53ed000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-09 13:02:08.358  6222  6222 W art     : b53ed000-b53fa000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-09 13:02:08.358  6222  6222 W art     : b53fa000-b53fb000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-09 13:02:08.358  6222  6222 W art     : b53fb000-b53fc000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-09 13:02:08.358  6222  6222 W art     : b53fc000-b545c000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-09 13:02:08.358  6222  6222 W art     : b545c000-b545f000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-09 13:02:08.358  6222  6222 W art     : b545f000-b5463000 rw-p 00000000 00:00 0 
08-09 13:02:08.358  6222  6222 W art     : b5463000-b54c4000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-09 13:02:08.358  6222  6222 W art     : b54c4000-b54c5000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-09 13:02:08.358  6222  6222 W art     : b54c5000-b5514000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-09 13:02:08.358  6222  6222 W art     : b5514000-b5516000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-09 13:02:08.358  6222  6222 W art     : b5516000-b5517000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-09 13:02:08.358  6222  6222 W art     : b5517000-b5518000 rw-p 00000000 00:00 0 
08-09 13:02:08.358  6222  6222 W art     : b5518000-b551f000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-09 13:02:08.358  6222  6222 W art     : b551f000-b5520000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-09 13:02:08.358  6222  6222 W art     : b5520000-b5521000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-09 13:02:08.358  6222  6222 W art     : b5522000-b5525000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-09 13:02:08.358  6222  6222 W art     : b5525000-b5526000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-09 13:02:08.358  6222  6222 W art     : b5526000-b5527000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-09 13:02:08.358  6222  6222 W art     : b5528000-b552c000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-09 13:02:08.358  6222  6222 W art     : b552c000-b552d000 ---p 00000000 00:00 0 
08-09 13:02:08.358  6222  6222 W art     : b552d000-b552e000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-09 13:02:08.358  6222  6222 W art     : b552e000-b552f000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-09 13:02:08.368  6222  6222 W art     : b5530000-b554d000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-09 13:02:08.368  6222  6222 W art     : b554d000-b554e000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-09 13:02:08.368  6222  6222 W art     : b554e000-b554f000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-09 13:02:08.368  6222  6222 W art     : b5550000-b5555000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-09 13:02:08.368  6222  6222 W art     : b5555000-b5556000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-09 13:02:08.368  6222  6222 W art     : b5556000-b5557000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-09 13:02:08.368  6222  6222 W art     : b5558000-b5589000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-09 13:02:08.368  6222  6222 W art     : b5589000-b558c000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-09 13:02:08.368  6222  6222 W art     : b558c000-b558d000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-09 13:02:08.368  6222  6222 W art     : b558e000-b55c9000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-09 13:02:08.368  6222  6222 W art     : b55c9000-b55ca000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-09 13:02:08.368  6222  6222 W art     : b55ca000-b55cb000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-09 13:02:08.368  6222  6222 W art     : b55cc000-b55d3000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-09 13:02:08.368  6222  6222 W art     : b55d3000-b55d4000 ---p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b55d4000-b55d5000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-09 13:02:08.368  6222  6222 W art     : b55d5000-b55d6000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-09 13:02:08.368  6222  6222 W art     : b55d6000-b55d7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.368  6222  6222 W art     : b55d7000-b55ee000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-09 13:02:08.368  6222  6222 W art     : b55ee000-b55ef000 ---p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b55ef000-b55f2000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-09 13:02:08.368  6222  6222 W art     : b55f2000-b55f3000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-09 13:02:08.368  6222  6222 W art     : b55f3000-b5612000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-09 13:02:08.368  6222  6222 W art     : b5612000-b5613000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-09 13:02:08.368  6222  6222 W art     : b5613000-b5614000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-09 13:02:08.368  6222  6222 W art     : b5614000-b5652000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-09 13:02:08.368  6222  6222 W art     : b5652000-b5653000 ---p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b5653000-b5655000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-09 13:02:08.368  6222  6222 W art     : b5655000-b5656000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-09 13:02:08.368  6222  6222 W art     : b5657000-b565e000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-09 13:02:08.368  6222  6222 W art     : b565e000-b565f000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-09 13:02:08.368  6222  6222 W art     : b565f000-b5660000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-09 13:02:08.368  6222  6222 W art     : b5661000-b5664000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-09 13:02:08.368  6222  6222 W art     : b5664000-b5665000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-09 13:02:08.368  6222  6222 W art     : b5665000-b5666000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-09 13:02:08.368  6222  6222 W art     : b5666000-b566c000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-09 13:02:08.368  6222  6222 W art     : b566c000-b566d000 ---p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b566d000-b566e000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-09 13:02:08.368  6222  6222 W art     : b566e000-b566f000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-09 13:02:08.368  6222  6222 W art     : b566f000-b5678000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-09 13:02:08.368  6222  6222 W art     : b5678000-b5679000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-09 13:02:08.368  6222  6222 W art     : b5679000-b567a000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-09 13:02:08.368  6222  6222 W art     : b567a000-b570b000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-09 13:02:08.368  6222  6222 W art     : b570b000-b570c000 ---p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b570c000-b5717000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-09 13:02:08.368  6222  6222 W art     : b5717000-b5718000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-09 13:02:08.368  6222  6222 W art     : b5719000-b572b000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-09 13:02:08.368  6222  6222 W art     : b572b000-b572c000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-09 13:02:08.368  6222  6222 W art     : b572c000-b572d000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-09 13:02:08.368  6222  6222 W art     : b572e000-b5733000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-09 13:02:08.368  6222  6222 W art     : b5733000-b5734000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-09 13:02:08.368  6222  6222 W art     : b5734000-b5735000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-09 13:02:08.368  6222  6222 W art     : b5736000-b57a3000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-09 13:02:08.368  6222  6222 W art     : b57a3000-b57a4000 ---p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b57a4000-b57a6000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-09 13:02:08.368  6222  6222 W art     : b57a6000-b57a7000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-09 13:02:08.368  6222  6222 W art     : b57a7000-b57a8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.368  6222  6222 W art     : b57a8000-b57af000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-09 13:02:08.368  6222  6222 W art     : b57af000-b57b0000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-09 13:02:08.368  6222  6222 W art     : b57b0000-b57b1000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-09 13:02:08.368  6222  6222 W art     : b57b2000-b5832000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-09 13:02:08.368  6222  6222 W art     : b5832000-b5833000 ---p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b5833000-b5834000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-09 13:02:08.368  6222  6222 W art     : b5834000-b5835000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-09 13:02:08.368  6222  6222 W art     : b5835000-b584c000 rw-p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b584c000-b5883000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-09 13:02:08.368  6222  6222 W art     : ib/libqc-opt.so
08-09 13:02:08.368  6222  6222 W art     : b5883000-b5884000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-09 13:02:08.368  6222  6222 W art     : b5884000-b5885000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-09 13:02:08.368  6222  6222 W art     : b5885000-b58a1000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-09 13:02:08.368  6222  6222 W art     : b58a1000-b58a2000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-09 13:02:08.368  6222  6222 W art     : b58a2000-b58a3000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-09 13:02:08.368  6222  6222 W art     : b58a4000-b5905000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-09 13:02:08.368  6222  6222 W art     : b5905000-b5907000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-09 13:02:08.368  6222  6222 W art     : b5907000-b5908000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-09 13:02:08.368  6222  6222 W art     : b5909000-b5930000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-09 13:02:08.368  6222  6222 W art     : b5930000-b5931000 ---p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b5931000-b5932000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-09 13:02:08.368  6222  6222 W art     : b5932000-b5933000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-09 13:02:08.368  6222  6222 W art     : b5934000-b593c000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-09 13:02:08.368  6222  6222 W art     : b593c000-b593e000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-09 13:02:08.368  6222  6222 W art     : b593e000-b593f000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-09 13:02:08.368  6222  6222 W art     : b5940000-b5943000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-09 13:02:08.368  6222  6222 W art     : b5943000-b5944000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-09 13:02:08.368  6222  6222 W art     : b5944000-b5945000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-09 13:02:08.368  6222  6222 W art     : b5945000-b5949000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-09 13:02:08.368  6222  6222 W art     : b5949000-b594a000 ---p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b594a000-b594b000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-09 13:02:08.368  6222  6222 W art     : b594b000-b594c000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-09 13:02:08.368  6222  6222 W art     : b594c000-b595c000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-09 13:02:08.368  6222  6222 W art     : b595c000-b595d000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-09 13:02:08.368  6222  6222 W art     : b595d000-b595e000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-09 13:02:08.368  6222  6222 W art     : b595e000-b59a4000 rw-p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b59a4000-b59ad000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-09 13:02:08.368  6222  6222 W art     : b59ad000-b59ae000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-09 13:02:08.368  6222  6222 W art     : b59ae000-b59af000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-09 13:02:08.368  6222  6222 W art     : b59b0000-b59b5000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-09 13:02:08.368  6222  6222 W art     : b59b5000-b59b6000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-09 13:02:08.368  6222  6222 W art     : b59b6000-b59b7000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-09 13:02:08.368  6222  6222 W art     : b59b7000-b59ba000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-09 13:02:08.368  6222  6222 W art     : b59ba000-b59bb000 ---p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b59bb000-b59bc000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-09 13:02:08.368  6222  6222 W art     : b59bc000-b59bd000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-09 13:02:08.368  6222  6222 W art     : b59be000-b59d6000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-09 13:02:08.368  6222  6222 W art     : b59d6000-b59d7000 ---p 00000000 00:00 0 
08-09 13:02:08.368  6222  6222 W art     : b59d7000-b59d8000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-09 13:02:08.378  6222  6222 W art     : b59d8000-b59d9000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-09 13:02:08.378  6222  6222 W art     : b59d9000-b59da000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-09 13:02:08.378  6222  6222 W art     : b59da000-b5b74000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-09 13:02:08.378  6222  6222 W art     : b5b74000-b5b75000 ---p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b5b75000-b5b82000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-09 13:02:08.378  6222  6222 W art     : b5b82000-b5b83000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-09 13:02:08.378  6222  6222 W art     : b5b83000-b5b87000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-09 13:02:08.378  6222  6222 W art     : b5b87000-b5b88000 ---p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b5b88000-b5b89000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-09 13:02:08.378  6222  6222 W art     : b5b89000-b5b8a000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-09 13:02:08.378  6222  6222 W art     : b5b8a000-b5b9d000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-09 13:02:08.378  6222  6222 W art     : b5b9d000-b5b9e000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-09 13:02:08.378  6222  6222 W art     : b5b9e000-b5b9f000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-09 13:02:08.378  6222  6222 W art     : b5ba0000-b5beb000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-09 13:02:08.378  6222  6222 W art     : b5beb000-b5bec000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-09 13:02:08.378  6222  6222 W art     : b5bec000-b5bed000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-09 13:02:08.378  6222  6222 W art     : b5bed000-b5bef000 rw-p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b5bf0000-b5c01000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-09 13:02:08.378  6222  6222 W art     : b5c01000-b5c02000 ---p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b5c02000-b5c03000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-09 13:02:08.378  6222  6222 W art     : b5c03000-b5c04000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-09 13:02:08.378  6222  6222 W art     : b5c04000-b5c05000 r--p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b5c05000-b5c0f000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-09 13:02:08.378  6222  6222 W art     : b5c0f000-b5c11000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-09 13:02:08.378  6222  6222 W art     : b5c11000-b5c12000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-09 13:02:08.378  6222  6222 W art     : b5c12000-b5c2b000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-09 13:02:08.378  6222  6222 W art     : b5c2b000-b5c2c000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-09 13:02:08.378  6222  6222 W art     : b5c2c000-b5c2f000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-09 13:02:08.378  6222  6222 W art     : b5c2f000-b5c33000 rw-p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b5c33000-b5ca7000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-09 13:02:08.378  6222  6222 W art     : b5ca7000-b5ca8000 ---p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b5ca8000-b5cab000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-09 13:02:08.378  6222  6222 W art     : b5cab000-b5cac000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-09 13:02:08.378  6222  6222 W art     : b5cac000-b5cad000 r--p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b5cad000-b5cb0000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-09 13:02:08.378  6222  6222 W art     : b5cb0000-b5cb1000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-09 13:02:08.378  6222  6222 W art     : b5cb1000-b5cb2000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-09 13:02:08.378  6222  6222 W art     : b5cb2000-b5cb3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.378  6222  6222 W art     : b5cb3000-b5cb8000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-09 13:02:08.378  6222  6222 W art     : b5cb8000-b5cb9000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-09 13:02:08.378  6222  6222 W art     : b5cb9000-b5cba000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-09 13:02:08.378  6222  6222 W art     : b5cba000-b5cbb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.378  6222  6222 W art     : b5cbb000-b5cbe000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-09 13:02:08.378  6222  6222 W art     : b5cbe000-b5cbf000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-09 13:02:08.378  6222  6222 W art     : b5cbf000-b5cc0000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-09 13:02:08.378  6222  6222 W art     : b5cc0000-b5cc1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.378  6222  6222 W art     : b5cc1000-b5cc5000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-09 13:02:08.378  6222  6222 W art     : b5cc5000-b5cc6000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-09 13:02:08.378  6222  6222 W art     : b5cc6000-b5cc7000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-09 13:02:08.378  6222  6222 W art     : b5cc7000-b5cc8000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-09 13:02:08.378  6222  6222 W art     : b5cc8000-b5ccc000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-09 13:02:08.378  6222  6222 W art     : b5ccc000-b5ccd000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-09 13:02:08.378  6222  6222 W art     : b5ccd000-b5cce000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-09 13:02:08.378  6222  6222 W art     : b5cce000-b5ccf000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.378  6222  6222 W art     : b5ccf000-b5cdd000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-09 13:02:08.378  6222  6222 W art     : b5cdd000-b5cde000 ---p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b5cde000-b5cdf000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-09 13:02:08.378  6222  6222 W art     : b5cdf000-b5ce0000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-09 13:02:08.378  6222  6222 W art     : b5ce0000-b5cea000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-09 13:02:08.378  6222  6222 W art     : b5cea000-b5ced000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-09 13:02:08.378  6222  6222 W art     : b5ced000-b5cee000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-09 13:02:08.378  6222  6222 W art     : b5cee000-b5cef000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.378  6222  6222 W art     : b5cef000-b5cf9000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-09 13:02:08.378  6222  6222 W art     : b5cf9000-b5cfc000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-09 13:02:08.378  6222  6222 W art     : b5cfc000-b5cfd000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-09 13:02:08.378  6222  6222 W art     : b5cfd000-b5d01000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-09 13:02:08.378  6222  6222 W art     : b5d01000-b5d02000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-09 13:02:08.378  6222  6222 W art     : b5d02000-b5d03000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-09 13:02:08.378  6222  6222 W art     : b5d03000-b5d04000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.378  6222  6222 W art     : b5d04000-b5d11000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-09 13:02:08.378  6222  6222 W art     : b5d11000-b5d13000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-09 13:02:08.378  6222  6222 W art     : b5d13000-b5d14000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-09 13:02:08.378  6222  6222 W art     : b5d14000-b6126000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-09 13:02:08.378  6222  6222 W art     : b6126000-b6127000 ---p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b6127000-b6130000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-09 13:02:08.378  6222  6222 W art     : b6130000-b6134000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-09 13:02:08.378  6222  6222 W art     : b6134000-b6135000 rw-p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b6135000-b613c000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-09 13:02:08.378  6222  6222 W art     : b613c000-b613d000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-09 13:02:08.378  6222  6222 W art     : b613d000-b613e000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-09 13:02:08.378  6222  6222 W art     : b613e000-b613f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.378  6222  6222 W art     : b613f000-b615a000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-09 13:02:08.378  6222  6222 W art     : b615a000-b615b000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-09 13:02:08.378  6222  6222 W art     : b615b000-b615c000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-09 13:02:08.378  6222  6222 W art     : b615c000-b615d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.378  6222  6222 W art     : b615d000-b61a9000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-09 13:02:08.378  6222  6222 W art     : b61a9000-b61aa000 ---p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b61aa000-b61ab000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-09 13:02:08.378  6222  6222 W art     : b61ab000-b61ac000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-09 13:02:08.378  6222  6222 W art     : b61ac000-b61ad000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.378  6222  6222 W art     : b61ad000-b61b1000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-09 13:02:08.378  6222  6222 W art     : b61b1000-b61b2000 ---p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b61b2000-b61b3000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-09 13:02:08.378  6222  6222 W art     : b61b3000-b61b4000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-09 13:02:08.378  6222  6222 W art     : b61b4000-b61ec000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-09 13:02:08.378  6222  6222 W art     : b61ec000-b61ed000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-09 13:02:08.378  6222  6222 W art     : b61ed000-b61ee000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-09 13:02:08.378  6222  6222 W art     : b61ee000-b61ef000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.378  6222  6222 W art     : b61ef000-b628d000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-09 13:02:08.378  6222  6222 W art     : b628d000-b628e000 ---p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b628e000-b62ac000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-09 13:02:08.378  6222  6222 W art     : b62ac000-b62ad000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-09 13:02:08.378  6222  6222 W art     : b62ad000-b6420000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-09 13:02:08.378  6222  6222 W art     : b6420000-b642b000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-09 13:02:08.378  6222  6222 W art     : b642b000-b642c000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-09 13:02:08.378  6222  6222 W art     : b642c000-b6543000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-09 13:02:08.378  6222  6222 W art     : b6543000-b654e000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-09 13:02:08.378  6222  6222 W art     : b654e000-b654f000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-09 13:02:08.378  6222  6222 W art     : b654f000-b6553000 rw-p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b6553000-b6577000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-09 13:02:08.378  6222  6222 W art     : b6577000-b6579000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-09 13:02:08.378  6222  6222 W art     : b6579000-b657a000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-09 13:02:08.378  6222  6222 W art     : b657a000-b6620000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-09 13:02:08.378  6222  6222 W art     : b6620000-b662d000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-09 13:02:08.378  6222  6222 W art     : b662d000-b662e000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-09 13:02:08.378  6222  6222 W art     : b662e000-b662f000 rw-p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b662f000-b6682000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-09 13:02:08.378  6222  6222 W art     : b6682000-b6683000 ---p 00000000 00:00 0 
08-09 13:02:08.378  6222  6222 W art     : b6683000-b6684000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-09 13:02:08.388  6222  6222 W art     : b6684000-b6685000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-09 13:02:08.388  6222  6222 W art     : b6685000-b668a000 rw-p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b668a000-b669c000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-09 13:02:08.388  6222  6222 W art     : b669c000-b669d000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b669d000-b669e000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-09 13:02:08.388  6222  6222 W art     : b669e000-b669f000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-09 13:02:08.388  6222  6222 W art     : b669f000-b66a6000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-09 13:02:08.388  6222  6222 W art     : b66a6000-b66a7000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-09 13:02:08.388  6222  6222 W art     : b66a7000-b66a8000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-09 13:02:08.388  6222  6222 W art     : b66a8000-b66a9000 rw-p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b66a9000-b66ac000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-09 13:02:08.388  6222  6222 W art     : b66ac000-b66ad000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-09 13:02:08.388  6222  6222 W art     : b66ad000-b66ae000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-09 13:02:08.388  6222  6222 W art     : b66ae000-b66b2000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-09 13:02:08.388  6222  6222 W art     : b66b2000-b66b3000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-09 13:02:08.388  6222  6222 W art     : b66b3000-b66b4000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-09 13:02:08.388  6222  6222 W art     : b66b4000-b66c2000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-09 13:02:08.388  6222  6222 W art     : b66c2000-b66c3000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b66c3000-b66c4000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-09 13:02:08.388  6222  6222 W art     : b66c4000-b66c5000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-09 13:02:08.388  6222  6222 W art     : b66c5000-b66ce000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-09 13:02:08.388  6222  6222 W art     : b66ce000-b66cf000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-09 13:02:08.388  6222  6222 W art     : b66cf000-b66d0000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-09 13:02:08.388  6222  6222 W art     : b66d0000-b6736000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-09 13:02:08.388  6222  6222 W art     : b6736000-b6737000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6737000-b6739000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-09 13:02:08.388  6222  6222 W art     : b6739000-b6742000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
,08-09 13:02:08.388  6222  6222 W art     : b6742000-b6745000 rw-p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6745000-b67dc000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-09 13:02:08.388  6222  6222 W art     : b67dc000-b67de000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-09 13:02:08.388  6222  6222 W art     : b67de000-b67df000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-09 13:02:08.388  6222  6222 W art     : b67df000-b67e0000 rw-p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b67e0000-b6b01000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-09 13:02:08.388  6222  6222 W art     : b6b01000-b6b02000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6b02000-b6b1d000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-09 13:02:08.388  6222  6222 W art     : b6b1d000-b6b21000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-09 13:02:08.388  6222  6222 W art     : b6b21000-b6b26000 rw-p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6b26000-b6b2e000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-09 13:02:08.388  6222  6222 W art     : b6b2e000-b6b2f000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-09 13:02:08.388  6222  6222 W art     : b6b2f000-b6b30000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-09 13:02:08.388  6222  6222 W art     : b6b30000-b6b5e000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-09 13:02:08.388  6222  6222 W art     : b6b5e000-b6b5f000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6b5f000-b6b66000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-09 13:02:08.388  6222  6222 W art     : b6b66000-b6b67000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-09 13:02:08.388  6222  6222 W art     : b6b67000-b6bad000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-09 13:02:08.388  6222  6222 W art     : b6bad000-b6bae000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6bae000-b6bb1000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-09 13:02:08.388  6222  6222 W art     : b6bb1000-b6bb2000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-09 13:02:08.388  6222  6222 W art     : b6bb2000-b6bcd000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-09 13:02:08.388  6222  6222 W art     : b6bcd000-b6bd1000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-09 13:02:08.388  6222  6222 W art     : b6bd1000-b6bd2000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-09 13:02:08.388  6222  6222 W art     : b6bd2000-b6c1f000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-09 13:02:08.388  6222  6222 W art     : b6c1f000-b6c20000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6c20000-b6c2c000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-09 13:02:08.388  6222  6222 W art     : b6c2c000-b6c2d000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-09 13:02:08.388  6222  6222 W art     : b6c2d000-b6c3a000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-09 13:02:08.388  6222  6222 W art     : b6c3a000-b6c3b000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6c3b000-b6c3c000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-09 13:02:08.388  6222  6222 W art     : b6c3c000-b6c3d000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-09 13:02:08.388  6222  6222 W art     : b6c3d000-b6c45000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-09 13:02:08.388  6222  6222 W art     : b6c45000-b6c46000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6c46000-b6c47000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-09 13:02:08.388  6222  6222 W art     : b6c47000-b6c48000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-09 13:02:08.388  6222  6222 W art     : b6c48000-b6c4f000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-09 13:02:08.388  6222  6222 W art     : b6c4f000-b6c50000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-09 13:02:08.388  6222  6222 W art     : b6c50000-b6c51000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-09 13:02:08.388  6222  6222 W art     : b6c51000-b6c65000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-09 13:02:08.388  6222  6222 W art     : b6c65000-b6c67000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-09 13:02:08.388  6222  6222 W art     : b6c67000-b6c68000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-09 13:02:08.388  6222  6222 W art     : b6c68000-b6c90000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-09 13:02:08.388  6222  6222 W art     : b6c90000-b6c92000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-09 13:02:08.388  6222  6222 W art     : b6c92000-b6c93000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-09 13:02:08.388  6222  6222 W art     : b6c93000-b6c96000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-09 13:02:08.388  6222  6222 W art     : b6c96000-b6c97000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-09 13:02:08.388  6222  6222 W art     : b6c97000-b6c98000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-09 13:02:08.388  6222  6222 W art     : b6c98000-b6ca1000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-09 13:02:08.388  6222  6222 W art     : b6ca1000-b6ca2000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-09 13:02:08.388  6222  6222 W art     : b6ca2000-b6ca3000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-09 13:02:08.388  6222  6222 W art     : b6ca3000-b6cc3000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-09 13:02:08.388  6222  6222 W art     : b6cc3000-b6cc4000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-09 13:02:08.388  6222  6222 W art     : b6cc4000-b6cc5000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-09 13:02:08.388  6222  6222 W art     : b6cc5000-b6d38000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-09 13:02:08.388  6222  6222 W art     : b6d38000-b6d3c000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-09 13:02:08.388  6222  6222 W art     : b6d3c000-b6d3f000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-09 13:02:08.388  6222  6222 W art     : b6d3f000-b6d49000 rw-p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6d49000-b6dd1000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-09 13:02:08.388  6222  6222 W art     : b6dd1000-b6dd2000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6dd2000-b6dd6000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-09 13:02:08.388  6222  6222 W art     : b6dd6000-b6dd7000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-09 13:02:08.388  6222  6222 W art     : b6dd7000-b6dd8000 rw-p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6dd8000-b6e01000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-09 13:02:08.388  6222  6222 W art     : b6e01000-b6e02000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6e02000-b6e05000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-09 13:02:08.388  6222  6222 W art     : b6e05000-b6e06000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-09 13:02:08.388  6222  6222 W art     : b6e06000-b6ee0000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-09 13:02:08.388  6222  6222 W art     : b6ee0000-b6ee7000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-09 13:02:08.388  6222  6222 W art     : b6ee7000-b6eef000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-09 13:02:08.388  6222  6222 W art     : b6eef000-b6ef0000 rw-p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6ef0000-b6ef1000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-09 13:02:08.388  6222  6222 W art     : b6ef1000-b6ef2000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-09 13:02:08.388  6222  6222 W art     : b6ef2000-b6ef3000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.388  6222  6222 W art     : b6ef3000-b6ef6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.388  6222  6222 W art     : b6ef6000-b6f1b000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-09 13:02:08.388  6222  6222 W art     : b6f1b000-b6f1c000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6f1c000-b6f23000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-09 13:02:08.388  6222  6222 W art     : b6f23000-b6f24000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-09 13:02:08.388  6222  6222 W art     : b6f24000-b6f2b000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-09 13:02:08.388  6222  6222 W art     : b6f2b000-b6f2c000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-09 13:02:08.388  6222  6222 W art     : b6f2c000-b6f2d000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-09 13:02:08.388  6222  6222 W art     : b6f2d000-b6f2e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.388  6222  6222 W art     : b6f2e000-b6f46000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-09 13:02:08.388  6222  6222 W art     : b6f46000-b6f47000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6f47000-b6f48000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-09 13:02:08.388  6222  6222 W art     : b6f48000-b6f49000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-09 13:02:08.388  6222  6222 W art     : b6f49000-b6f57000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-09 13:02:08.388  6222  6222 W art     : b6f57000-b6f58000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6f58000-b6f59000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-09 13:02:08.388  6222  6222 W art     : b6f59000-b6f5a000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-09 13:02:08.388  6222  6222 W art     : b6f5a000-b6f5b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-09 13:02:08.388  6222  6222 W art     : b6f5b000-b6f5d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.388  6222  6222 W art     : b6f5d000-b6f5e000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.388  6222  6222 W art     : b6f5e000-b6f5f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-09 13:02:08.388  6222  6222 W art     : b6f5f000-b6f60000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-09 13:02:08.388  6222  6222 W art     : b6f60000-b6f61000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:08.388  6222  6222 W art     : b6f61000-b6f81000 r--s 00000000 00:0b 7179       /dev/__properties__
08-09 13:02:08.388  6222  6222 W art     : b6f81000-b6f82000 r--p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6f82000-b6f83000 ---p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6f83000-b6f85000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-09 13:02:08.388  6222  6222 W art     : b6f85000-b6f86000 r-xp 00000000 00:00 0          [sigpage]
08-09 13:02:08.388  6222  6222 W art     : b6f86000-b6fa1000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-09 13:02:08.388  6222  6222 W art     : b6fa1000-b6fa2000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-09 13:02:08.388  6222  6222 W art     : b6fa2000-b6fa4000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-09 13:02:08.388  6222  6222 W art     : b6fa4000-b6fa6000 rw-p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : b6fa6000-b6fab000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-09 13:02:08.388  6222  6222 W art     : b6fab000-b6fac000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-09 13:02:08.388  6222  6222 W art     : b6fac000-b6fad000 rw-p 00000000 00:00 0 
08-09 13:02:08.388  6222  6222 W art     : beb24000-beb45000 rw-p 00000000 00:00 0          [stack]
08-09 13:02:08.388  6222  6222 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-09 13:02:08.548  6222  6222 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-09 13:02:08.608  1986  2308 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
08-09 13:02:08.608  1986  2308 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
08-09 13:02:08.618  6222  6222 I Radio-JNI: register_android_hardware_Radio DONE
08-09 13:02:08.628  6222  6222 E AffinityControl: AffinityControl: registerfunction enter
08-09 13:02:08.658  6222  6222 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-09 13:02:08.668   745  1680 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-09 13:02:08.678   745  1680 D ActivityManager: mDVFSHelper.acquire()
08-09 13:02:08.678   745  1680 D FocusedStackFrame: Set to : 0
08-09 13:02:08.688   745  1680 V WindowManager: addAppToken: AppWindowToken{4cfb9f6 token=Token{8e6d691 ActivityRecord{34a68b8 u0 com.test.thalitest/.MainActivity t128}}} to stack=1 task=128 at 0
08-09 13:02:08.688   745   884 D SecWifiDisplayUtil: Metadata value : none
08-09 13:02:08.688   745   884 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{24011ce V.E...... R.....ID 0,0-0,0}
08-09 13:02:08.698   745   884 D ISSUE_DEBUG: InputChannelName : b354ffc Starting com.test.thalitest
08-09 13:02:08.708   293   293 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
08-09 13:02:08.708   745  1680 I ActivityManager: Start proc 6262:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-09 13:02:08.718  6262  6262 E Zygote  : v2
08-09 13:02:08.718  6262  6262 I libpersona: KNOX_SDCARD checking this for 10004
08-09 13:02:08.718  6262  6262 I libpersona: KNOX_SDCARD not a persona
08-09 13:02:08.718  6262  6262 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-09 13:02:08.718  6262  6262 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-09 13:02:08.718  6262  6262 E Zygote  : accessInfo : 0
08-09 13:02:08.718  6262  6262 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-09 13:02:08.738   745  1680 D InputDispatcher: Focused application set to: xxxx
08-09 13:02:08.738   745   884 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-09 13:02:08.738   745  1680 D InputDispatcher: Focus left window: 1674
08-09 13:02:08.738   745  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-09 13:02:08.738  6222  6222 D AndroidRuntime: Shutting down VM
08-09 13:02:08.748  6262  6262 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 13:02:08.748  6262  6262 D ActivityThread: Added TimaKeyStore provider
08-09 13:02:08.758   745  1624 V WindowOrientationListener: setCurrentAppOrientation :-1
08-09 13:02:08.758   745  1624 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-09 13:02:08.758   745   820 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{b354ffc u0 d0 Starting com.test.thalitest}
08-09 13:02:08.758  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-09 13:02:08.758   745  1624 D ActivityManager:  Launching com.test.thalitest, updated priority
08-09 13:02:08.778   745   884 V WindowStateAnimator: Finishing drawing window Window{b354ffc u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-09 13:02:08.778   745   884 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:745 uid:1000
08-09 13:02:08.778   745   884 D PointerIcon: setMouseCustomIcon IconType is same.101
08-09 13:02:08.778   745   884 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:745 uid:1000
08-09 13:02:08.778   745   884 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-09 13:02:08.778  1674  1839 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-09 13:02:08.778  1674  1674 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-09 13:02:08.778   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbee42364
08-09 13:02:08.808   293   828 D libEGL  : eglTerminate EGLDisplay = 0xb2b2864c
08-09 13:02:08.808   293   828 D libEGL  : eglTerminate EGLDisplay = 0xb2b2864c
08-09 13:02:08.818   293  4616 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-09 13:02:08.818   293   360 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-09 13:02:08.828   745   810 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-09 13:02:08.828   745  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-09 13:02:08.828   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee423a4
08-09 13:02:08.828   745  3288 D M       : limitCPUFreq:: freq = -1
08-09 13:02:08.828   745  3288 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 745  tag : SIOP_ARM_MAX@25
08-09 13:02:08.828   745  3288 D M       : limitGPUFreq:: freq = -1
08-09 13:02:08.848  6262  6262 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-09 13:02:08.848  2140  2153 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-09 13:02:08.848   745  3288 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-09 13:02:08.848  1674  1674 V ActivityThread: updateVisibility : ActivityRecord{d227ec1 token=android.os.BinderProxy@45b37b4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-09 13:02:08.848  1674  1674 D Launcher: onTrimMemory. Level: 20
08-09 13:02:08.878  6262  6262 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-09 13:02:08.888  6262  6262 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-09 13:02:08.908  6262  6262 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
08-09 13:02:08.938  6262  6262 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
08-09 13:02:08.948   745   757 I art     : Background partial concurrent mark sweep GC freed 16304(928KB) AllocSpace objects, 6(120KB) LOS objects, 27% free, 41MB/57MB, paused 2.505ms total 137.927ms
08-09 13:02:08.948  6262  6262 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-09 13:02:08.958  6262  6262 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 7854-7858)
08-09 13:02:08.958  6262  6262 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-09 13:02:08.988  6262  6262 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f7344}
08-09 13:02:08.988  6262  6262 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-09 13:02:08.988  6262  6262 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
08-09 13:02:08.988  6262  6283 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
08-09 13:02:08.998  6262  6262 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
08-09 13:02:09.018  6262  6284 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
08-09 13:02:09.038  6262  6262 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-09 13:02:09.038  6262  6262 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-09 13:02:09.038  6262  6262 I Adreno-EGL: Build Date: 01/28/16 Thu
08-09 13:02:09.038  6262  6262 I Adreno-EGL: Local Branch: ss
08-09 13:02:09.038  6262  6262 I Adreno-EGL: Remote Branch: 
08-09 13:02:09.038  6262  6262 I Adreno-EGL: Local Patches: 
08-09 13:02:09.038  6262  6262 I Adreno-EGL: Reconstruct Branch: 
08-09 13:02:09.038  6262  6262 D libEGL  : eglInitialize EGLDisplay = 0xbe893dac
08-09 13:02:09.088   745  3534 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
08-09 13:02:09.088   745  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
08-09 13:02:09.198  6262  6262 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
08-09 13:02:09.218  6262  6262 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
08-09 13:02:09.218  6262  6262 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
08-09 13:02:09.218  6262  6262 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
08-09 13:02:09.218  6262  6262 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
08-09 13:02:09.238  6262  6262 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
08-09 13:02:09.248  6262  6262 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-09 13:02:09.318   745   810 W ActivityManager: Activity pause timeout for ActivityRecord{34a68b8 u0 com.test.thalitest/.MainActivity t128}
08-09 13:02:09.348  6262  6262 D SecWifiDisplayUtil: Metadata value : none
08-09 13:02:09.358  6262  6262 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e171cc2 I.E...... R.....ID 0,0-0,0}
08-09 13:02:09.358  6262  6310 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-09 13:02:09.368   745  1946 D ISSUE_DEBUG: InputChannelName : b295da9 com.test.thalitest/com.test.thalitest.MainActivity
08-09 13:02:09.368   745  1690 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-09 13:02:09.368   745  1690 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-09 13:02:09.368   745   745 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-09 13:02:09.368   745   745 I KnoxTimeoutHandler: Shared devices show user statefalse
08-09 13:02:09.388  6262  6262 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6262
08-09 13:02:09.398   745  3534 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6262 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 13:02:09.408  6262  6262 V ActivityThread: updateVisibility : ActivityRecord{5be430e token=android.os.BinderProxy@72e150d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-09 13:02:09.418  6262  6283 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
08-09 13:02:09.428  6262  6262 D SecWifiDisplayUtil: Metadata value : none
08-09 13:02:09.438   293   293 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
08-09 13:02:09.448   745   763 D InputDispatcher: Focus entered window: 6262
08-09 13:02:09.448   745   884 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:745 uid:1000
08-09 13:02:09.448   745   884 D PointerIcon: setMouseCustomIcon IconType is same.101
08-09 13:02:09.448   745   884 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:745 uid:1000
08-09 13:02:09.448   745   884 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-09 13:02:09.448  6262  6310 D libEGL  : eglInitialize EGLDisplay = 0x9d67f7c4
08-09 13:02:09.448  6262  6310 I OpenGLRenderer: Initialized EGL, version 1.4
08-09 13:02:09.508  6262  6262 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-09 13:02:09.508  6262  6262 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-09 13:02:09.508   745  2414 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-09 13:02:09.528  6262  6262 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
08-09 13:02:09.558   745   765 V WindowStateAnimator: Finishing drawing window Window{b295da9 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
08-09 13:02:09.558  6262  6262 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-09 13:02:09.558   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbee42364
08-09 13:02:09.558  6262  6262 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@72e150d time:98458
08-09 13:02:09.568   745   884 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-09 13:02:09.568   745   745 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-09 13:02:09.568   745   884 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +750ms (total +878ms)
08-09 13:02:09.568   745   745 I KnoxTimeoutHandler: SD activityfalse
08-09 13:02:09.578   745   884 D ActivityManager: mDVFSHelper.release()
08-09 13:02:09.578   745   884 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34a68b8 u0 com.test.thalitest/.MainActivity t128} time:98470
08-09 13:02:09.578   745   884 D ViewRootImpl: #3 mView = null
08-09 13:02:09.578   293  4616 I SurfaceFlinger: id=18 Removed uhalitest (7/9)
08-09 13:02:09.578   293   360 I SurfaceFlinger: id=18 Removed uhalitest (-2/9)
08-09 13:02:09.588  6262  6318 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-09 13:02:09.588  6262  6318 D libEGL  : eglInitialize EGLDisplay = 0x9ad1a3ec
08-09 13:02:09.588   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee423a4
08-09 13:02:09.648  6262  6262 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6262
08-09 13:02:09.828   745  3289 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-09 13:02:09.928  6262  6262 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-09 13:02:10.038   745  3308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-09 13:02:10.118  6262  6324 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1723729616
,08-09 13:02:10.128  6262  6324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-09 13:02:10.128  6262  6324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-09 13:02:10.128  6262  6324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-09 13:02:10.128  6262  6324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-09 13:02:10.128  6262  6324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-09 13:02:10.128  6262  6324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5b5b7d added. We now have 1 listener(s)
,08-09 13:02:10.138  6262  6324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-09 13:02:10.138  6262  6324 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-09 13:02:10.138  6262  6324 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-09 13:02:10.138  6262  6324 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-09 13:02:10.148  6262  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d4a340 added. We now have 1 listener(s)
,08-09 13:02:10.148  6262  6324 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 13:02:10.148  6262  6324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 13:02:10.148  6262  6324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-09 13:02:10.148  6262  6324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-09 13:02:10.148  6262  6324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-09 13:02:10.148  6262  6324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-09 13:02:10.158  6262  6324 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 13:02:10.158  6262  6324 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-09 13:02:10.158  6262  6324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 13:02:10.158  6262  6324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 13:02:10.158  6262  6324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 13:02:10.158  6262  6324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 13:02:10.158  6262  6324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 13:02:10.158  6262  6324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 13:02:10.158  6262  6324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 13:02:10.158  6262  6324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 13:02:10.158  6262  6324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 13:02:10.158  6262  6324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-09 13:02:10.158  6262  6324 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 13:02:10.158  6262  6324 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-09 13:02:10.188  6262  6262 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-09 13:02:10.328  1448  1448 D Recents : onTaskStackChanged
,08-09 13:02:10.338  1448  1448 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-09 13:02:10.388  6262  6272 I art     : Background sticky concurrent mark sweep GC freed 47400(3MB) AllocSpace objects, 8(160KB) LOS objects, 33% free, 17MB/25MB, paused 1.126ms total 125.202ms
,08-09 13:02:11.138  6262  6328 E filemap : mmap(19017728,0) failed: Invalid argument
08-09 13:02:11.138  6262  6328 W asset   : create map from entry failed
,08-09 13:02:11.138  6262  6328 W jxcore-FileManager: aproxFileSize failed
08-09 13:02:11.138  6262  6328 W System.err: java.io.FileNotFoundException: www/jxcore/node_modules/write-stream/Makefile
,08-09 13:02:11.148  6262  6328 W System.err: 	at android.content.res.AssetManager.openAsset(Native Method)
,08-09 13:02:11.148  6262  6328 W System.err: 	at android.content.res.AssetManager.open(AssetManager.java:363)
08-09 13:02:11.148  6262  6328 W System.err: 	at io.jxcore.node.FileManager.aproxFileSize(FileManager.java:48)
08-09 13:02:11.148  6262  6328 W System.err: 	at io.jxcore.node.jxcore.Initialize(jxcore.java:281)
08-09 13:02:11.148  6262  6328 W System.err: 	at io.jxcore.node.jxcore.access$200(jxcore.java:25)
,08-09 13:02:11.148  6262  6328 W System.err: 	at io.jxcore.node.jxcore$6.run(jxcore.java:343)
08-09 13:02:11.148  6262  6328 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 13:02:11.148  6262  6328 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 13:02:11.148  6262  6328 W System.err: 	at android.os.Looper.loop(Looper.java:158)
,08-09 13:02:11.148  6262  6328 W System.err: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,08-09 13:02:11.168  6262  6328 W jxcore-log: Initializing JXcore engine
08-09 13:02:11.168  6262  6328 W jxcore-log: JXcore engine is ready
,08-09 13:02:11.238  2335  2335 E audit   : type=1400 msg=audit(1470740531.238:281): avc:  denied  { ioctl } for  pid=6328 comm="Thread-895" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-09 13:02:11.238  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-09 13:02:11.238  2335  2335 E audit   : type=1300 msg=audit(1470740531.238:281): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9881f3c8 items=0 ppid=350 ppcomm=main pid=6328 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-895" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-09 13:02:11.238  2335  2335 E audit   : type=1327 msg=audit(1470740531.238:281): proctitle="com.test.thalitest"
08-09 13:02:11.238  2335  2335 E audit   : type=1320 msg=audit(1470740531.238:281): 
,08-09 13:02:11.238  2335  2335 E audit   : type=1400 msg=audit(1470740531.238:282): avc:  denied  { ioctl } for  pid=6328 comm="Thread-895" path="socket:[37656]" dev="sockfs" ino=37656 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-09 13:02:11.238  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-09 13:02:11.238  2335  2335 E audit   : type=1300 msg=audit(1470740531.238:282): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9881f3c8 items=0 ppid=350 ppcomm=main pid=6328 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-895" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-09 13:02:11.238  2335  2335 E audit   : type=1327 msg=audit(1470740531.238:282): proctitle="com.test.thalitest"
08-09 13:02:11.238  2335  2335 E audit   : type=1320 msg=audit(1470740531.238:282): 
,08-09 13:02:11.258  6262  6328 W jxcore-log: Starting JXcore engine
,08-09 13:02:11.348  6262  6328 W jxcore-log: Platform android
08-09 13:02:11.348  6262  6328 W jxcore-log: 
08-09 13:02:11.348  6262  6328 W jxcore-log: Process ARCH arm
08-09 13:02:11.348  6262  6328 W jxcore-log: 
,08-09 13:02:11.508  6188  6188 D CAR.SERVICE: onUnbind
,08-09 13:02:11.508  6188  6188 D CAR.SERVICE: CSB onClientsDisconnected
08-09 13:02:11.508  6188  6188 D CAR.SERVICE: tearDown
08-09 13:02:11.508  6188  6188 D CAR.SERVICE: tearDownCarState
,08-09 13:02:11.518  6188  6188 D CAR.SERVICE: Skip, car not connected.
,08-09 13:02:11.518  6262  6328 I jxcore-log: JXcore Cordova bridge is ready!
08-09 13:02:11.518  6262  6328 I jxcore-log: 
,08-09 13:02:11.518  6262  6328 W jxcore-log: JXcore engine is started
,08-09 13:02:11.518  6188  6188 D CAR.SERVICE: tearDownClientState
08-09 13:02:11.528  6188  6188 D CAR.SERVICE: requestStop
08-09 13:02:11.528  6188  6188 D CAR.SERVICE: onDestroy
08-09 13:02:11.528  6188  6188 D CAR.SERVICE: tearDown
08-09 13:02:11.528  6262  6324 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-09 13:02:11.528  6188  6188 D CAR.SERVICE: tearDownCarState
08-09 13:02:11.528  6188  6188 D CAR.SERVICE: Skip, car not connected.
08-09 13:02:11.528  6188  6188 D CAR.SERVICE: tearDownClientState
08-09 13:02:11.528  6188  6188 D CAR.SERVICE: requestStop
08-09 13:02:11.528  6262  6262 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-09 13:02:11.548  6188  6188 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@9ee5bb9 that was originally bound here
08-09 13:02:11.548  6188  6188 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@9ee5bb9 that was originally bound here
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1204)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1098)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1412)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1395)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:165)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3834)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.app.ActivityThread.access$2200(ActivityThread.java:221)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1887)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.os.Looper.loop(Looper.java:158)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-09 13:02:11.548  6188  6188 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-09 13:02:11.548   745  1683 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@785c663
,08-09 13:02:11.728   745  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/128_task.xml.bak
,08-09 13:02:14.848   745  3288 D M       : limitCPUFreq:: freq = 1728000
,08-09 13:02:14.858   745  3288 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 745  pkgName : SIOP_ARM_MAX@25
,08-09 13:02:14.858   745  3288 D M       : limitGPUFreq:: freq = 389000000
,08-09 13:02:14.878   745  3288 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-09 13:02:15.048   745  3308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-09 13:02:15.088   745   763 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-09 13:02:15.098   745   763 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4377, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-09 13:02:15.098   745   763 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-09 13:02:15.098   745   763 D BatteryService: stay LED for charging
,08-09 13:02:15.098   745   745 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-09 13:02:15.098   745   745 I MotionRecognitionService: Plugged
,08-09 13:02:15.098   745   745 D MotionRecognitionService:   cableConnection= 1
,08-09 13:02:15.098   745   745 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-09 13:02:15.098   745   745 D MotionRecognitionService: skip setTransmitPower. 
,08-09 13:02:15.108  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-09 13:02:15.108  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-09 13:02:15.108  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-09 13:02:15.128  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-09 13:02:15.128  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-09 13:02:15.128  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-09 13:02:15.958   745  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-09 13:02:15.958   745  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-09 13:02:16.248   745  3288 D SSRM:n  : SIOP:: AP = 410, PST = 457, CUR = 450, LCD = 0
,08-09 13:02:16.248   745  3288 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-09 13:02:16.748  3519  3519 D FactoryTest: User mode
,08-09 13:02:16.758  3519  3519 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-09 13:02:16.758  3519  3519 D MTPRx   : still no open session command from host, so toast
,08-09 13:02:16.758   745  2422 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-09 13:02:16.768   745  2422 D ActivityManager: mDVFSHelper.acquire()
,08-09 13:02:16.768   745  2422 V WindowManager: addAppToken: AppWindowToken{4a11fde token=Token{3b80319 ActivityRecord{9f9d260 u0 com.samsung.android.MtpApplication/.USBConnection t129}}} to stack=1 task=129 at 0
,08-09 13:02:16.768   745  2422 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-09 13:02:16.778   745   810 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-09 13:02:16.798   745  2422 D InputDispatcher: Focused application set to: xxxx
,08-09 13:02:16.798   745  2422 D InputDispatcher: Focus left window: 6262
,08-09 13:02:16.808   745   884 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:745 uid:1000
,08-09 13:02:16.808   745   884 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-09 13:02:16.808   745   884 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:745 uid:1000
08-09 13:02:16.808   745   884 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-09 13:02:16.818  3519  3519 E MTPRx   : started activity for popup
,08-09 13:02:16.818  3519  3519 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-09 13:02:16.818   745  3288 D M       : limitCPUFreq:: freq = -1
,08-09 13:02:16.818   745  3288 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 745  tag : SIOP_ARM_MAX@25
08-09 13:02:16.818  3519  3519 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-09 13:02:16.818   745  3288 D M       : limitGPUFreq:: freq = -1
,08-09 13:02:16.828   745  3288 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-09 13:02:16.838  3519  3519 D MTPUSBConnection: onCreate in USBConnection
08-09 13:02:16.838  3519  3519 V MTPUSBConnection: Registering broadcast receiver.
,08-09 13:02:16.838  3519  3519 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-09 13:02:16.838   745  2414 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-09 13:02:16.878  3519  3519 D TAG     : dev.kiessupport is : TRUE
,08-09 13:02:16.908  3519  3519 D SecWifiDisplayUtil: Metadata value : none
,08-09 13:02:16.908  3519  3519 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b174d3d V.E...... R.....I. 0,0-0,0}
,08-09 13:02:16.918  3519  6350 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-09 13:02:16.918   745  1320 D ISSUE_DEBUG: InputChannelName : 54b4cb6 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-09 13:02:16.918   745  1320 D InputDispatcher: Focus entered window: 3519
,08-09 13:02:16.918   745   820 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{54b4cb6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-09 13:02:16.928   745   884 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:745 uid:1000
08-09 13:02:16.928   745   884 D PointerIcon: setMouseCustomIcon IconType is same.101
08-09 13:02:16.928   745   884 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:745 uid:1000
08-09 13:02:16.928   745   884 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-09 13:02:16.928  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-09 13:02:16.928  3519  3519 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{80fe6f5 I.E...... R.....I. 0,0-0,0}
,08-09 13:02:16.928   745  1683 D ISSUE_DEBUG: InputChannelName : 3100924 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-09 13:02:16.938   745  3534 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-09 13:02:16.938   745  3534 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-09 13:02:16.938   745   745 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-09 13:02:16.938   745   745 I KnoxTimeoutHandler: Shared devices show user statefalse
08-09 13:02:16.938   745   745 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-09 13:02:16.978   293   293 I SurfaceFlinger: id=20 createSurf (145x145),1 flag=4, VSBConnecti
,08-09 13:02:16.998  3519  6350 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-09 13:02:16.998  3519  6350 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-09 13:02:16.998  3519  6350 I Adreno-EGL: Build Date: 01/28/16 Thu
08-09 13:02:16.998  3519  6350 I Adreno-EGL: Local Branch: ss
08-09 13:02:16.998  3519  6350 I Adreno-EGL: Remote Branch: 
08-09 13:02:16.998  3519  6350 I Adreno-EGL: Local Patches: 
08-09 13:02:16.998  3519  6350 I Adreno-EGL: Reconstruct Branch: 
,08-09 13:02:16.998  3519  6350 D libEGL  : eglInitialize EGLDisplay = 0x9ef0d7c4
08-09 13:02:16.998  3519  6350 I OpenGLRenderer: Initialized EGL, version 1.4
,08-09 13:02:17.038   293   293 I SurfaceFlinger: id=21 createSurf (193x193),1 flag=4, VSBConnecti
,08-09 13:02:17.048  3519  3519 V ActivityThread: updateVisibility : ActivityRecord{d7f5f18 token=android.os.BinderProxy@ca2a932 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-09 13:02:17.058  3519  3519 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-09 13:02:17.148   745  1690 V WindowStateAnimator: Finishing drawing window Window{54b4cb6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-09 13:02:17.148  3519  3519 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-09 13:02:17.148   745  2422 V WindowStateAnimator: Finishing drawing window Window{3100924 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-09 13:02:17.148  3519  3519 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-09 13:02:17.148  3519  3519 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-09 13:02:17.158   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbee42364
,08-09 13:02:17.158   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbee42364
08-09 13:02:17.158   745   884 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-09 13:02:17.158   745   745 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-09 13:02:17.158   745   884 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +360ms (total +384ms)
08-09 13:02:17.158   745   884 D ActivityManager: mDVFSHelper.release()
08-09 13:02:17.158   745   884 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9f9d260 u0 com.samsung.android.MtpApplication/.USBConnection t129} time:106054
,08-09 13:02:17.158   745   745 I KnoxTimeoutHandler: SD activityfalse
,08-09 13:02:17.158   745  1277 V WindowStateAnimator: Finishing drawing window Window{54b4cb6 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-09 13:02:17.158   745  1680 V WindowStateAnimator: Finishing drawing window Window{3100924 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-09 13:02:17.158  3519  3519 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ca2a932 time:106059
,08-09 13:02:17.168   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbee42364
,08-09 13:02:17.808   745  3289 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-09 13:02:17.938  1448  1448 D Recents : onTaskStackChanged
,08-09 13:02:17.958  1448  1448 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-09 13:02:18.738   745   909 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-09 13:02:18.748   745   909 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-09 13:02:20.048   745  3308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-09 13:02:22.188  6262  6328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-09 13:02:22.188  6262  6328 I jxcore-log: 
,08-09 13:02:22.188  6262  6328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-09 13:02:22.188  6262  6328 I jxcore-log: 
,08-09 13:02:22.188  6262  6328 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 13:02:22.188  6262  6328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 13:02:22.188  6262  6328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 13:02:22.188  6262  6328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 13:02:22.188  6262  6328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 13:02:22.188  6262  6328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 13:02:22.188  6262  6328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 13:02:22.188  6262  6328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 13:02:22.188  6262  6328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 13:02:22.188  6262  6328 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 13:02:22.188  6262  6328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 13:02:22.188  6262  6328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-09 13:02:22.188  6262  6328 I jxcore-log: 
,08-09 13:02:22.198  6262  6328 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-09 13:02:22.198  6262  6328 I jxcore-log: 
,08-09 13:02:22.538  6262  6328 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
,08-09 13:02:22.538  6262  6328 I jxcore-log: Failed to execute UT.
08-09 13:02:22.538  6262  6328 I jxcore-log: 
08-09 13:02:22.538  6262  6328 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-09 13:02:22.538  6262  6328 I jxcore-log: 
,08-09 13:02:22.538  6262  6328 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 13:02:22.538  6262  6328 I jxcore-log: 
08-09 13:02:22.538  6262  6262 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-09 13:02:22.828   745  3288 D M       : limitCPUFreq:: freq = 1728000
,08-09 13:02:22.838   745  3288 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 745  pkgName : SIOP_ARM_MAX@25
,08-09 13:02:22.838   745  3288 D M       : limitGPUFreq:: freq = 389000000
,08-09 13:02:22.858   745  3288 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-09 13:02:23.628  2335  2335 E audit   : type=1400 msg=audit(1470740543.628:283): avc:  denied  { execmod } for  pid=6367 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-09 13:02:23.628  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-09 13:02:23.628  2335  2335 E audit   : type=1300 msg=audit(1470740543.628:283): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4030000 a1=51000 a2=5 a3=4 items=0 ppid=3395 ppcomm=adbd pid=6367 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-09 13:02:23.628  2335  2335 E audit   : type=1327 msg=audit(1470740543.628:283): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-09 13:02:23.628  2335  2335 E audit   : type=1320 msg=audit(1470740543.628:283): 
,08-09 13:02:23.698  2335  2335 E audit   : type=1400 msg=audit(1470740543.698:284): avc:  denied  { execmod } for  pid=6367 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-09 13:02:23.698  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-09 13:02:23.708  2335  2335 E audit   : type=1300 msg=audit(1470740543.698:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fef000 a1=51000 a2=5 a3=4 items=0 ppid=3395 ppcomm=adbd pid=6367 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-09 13:02:23.708  2335  2335 E audit   : type=1327 msg=audit(1470740543.698:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-09 13:02:23.708  2335  2335 E audit   : type=1320 msg=audit(1470740543.698:284): 
,08-09 13:02:23.758  2335  2335 E audit   : type=1400 msg=audit(1470740543.758:285): avc:  denied  { execmod } for  pid=6367 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-09 13:02:23.758  2335  2335 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-09 13:02:23.758  2335  2335 E audit   : type=1300 msg=audit(1470740543.758:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ff0000 a1=51000 a2=5 a3=4 items=0 ppid=3395 ppcomm=adbd pid=6367 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-09 13:02:23.758  2335  2335 E audit   : type=1327 msg=audit(1470740543.758:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-09 13:02:23.758  2335  2335 E audit   : type=1320 msg=audit(1470740543.758:285): 
,08-09 13:02:23.768  6367  6367 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-09 13:02:23.778  6367  6367 D AndroidRuntime: CheckJNI is OFF
,08-09 13:02:23.778  6367  6367 D AndroidRuntime: readGMSProperty: start
08-09 13:02:23.778  6367  6367 D AndroidRuntime: readGMSProperty: already setted!!
08-09 13:02:23.778  6367  6367 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,08-09 13:02:23.778  6367  6367 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-09 13:02:23.778  6367  6367 D AndroidRuntime: readGMSProperty: end
08-09 13:02:23.778  6367  6367 D AndroidRuntime: addProductProperty: start
,08-09 13:02:23.788  6367  6367 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-09 13:02:23.788  6367  6367 W art     : af19f000-b20c5000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
,08-09 13:02:23.788  6367  6367 W art     : b20c5000-b4334000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-09 13:02:23.788  6367  6367 W art     : b4334000-b4335000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-09 13:02:23.788  6367  6367 W art     : b4335000-b435e000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-09 13:02:23.788  6367  6367 W art     : b435e000-b4361000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-09 13:02:23.788  6367  6367 W art     : b4361000-b4362000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-09 13:02:23.788  6367  6367 W art     : b4362000-b4363000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-09 13:02:23.788  6367  6367 W art     : b4363000-b47b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-09 13:02:23.788  6367  6367 W art     : b47b1000-b47b2000 ---p 00000000 00:00 0 
,08-09 13:02:23.788  6367  6367 W art     : b47b2000-b47bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-09 13:02:23.788  6367  6367 W art     : b47bc000-b47bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-09 13:02:23.788  6367  6367 W art     : b47bd000-b47bf000 rw-p 00000000 00:00 0 
08-09 13:02:23.788  6367  6367 W art     : b47bf000-b47c0000 r--p 00000000 00:00 0 
08-09 13:02:23.788  6367  6367 W art     : b47c0000-b48c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-09 13:02:23.788  6367  6367 W art     : b48c2000-b48c3000 r--p 00000000 00:00 0 
08-09 13:02:23.788  6367  6367 W art     : b48c3000-b48e3000 r--s 00000000 00:0b 7179       /dev/__properties__
08-09 13:02:23.788  6367  6367 W art     : b48e3000-b52f4000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
,08-09 13:02:23.788  6367  6367 W art     : b52f4000-b52f5000 ---p 00000000 00:00 0 
08-09 13:02:23.788  6367  6367 W art     : b52f5000-b533e000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-09 13:02:23.788  6367  6367 W art     : b533e000-b533f000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-09 13:02:23.788  6367  6367 W art     : b533f000-b5347000 rw-p 00000000 00:00 0 
08-09 13:02:23.788  6367  6367 W art     : b5347000-b5348000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.788  6367  6367 W art     : b5348000-b537d000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-09 13:02:23.788  6367  6367 W art     : b537d000-b537e000 ---p 00000000 00:00 0 
08-09 13:02:23.788  6367  6367 W art     : b537e000-b537f000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
,08-09 13:02:23.788  6367  6367 W art     : b537f000-b5380000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-09 13:02:23.788  6367  6367 W art     : b5380000-b53d8000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-09 13:02:23.788  6367  6367 W art     : b53d8000-b53d9000 ---p 00000000 00:00 0 
08-09 13:02:23.788  6367  6367 W art     : b53d9000-b53da000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-09 13:02:23.788  6367  6367 W art     : b53da000-b53db000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-09 13:02:23.788  6367  6367 W art     : b53dc000-b53e2000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-09 13:02:23.788  6367  6367 W art     : b53e2000-b53e3000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-09 13:02:23.788  6367  6367 W art     : b53e3000-b53e4000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-09 13:02:23.788  6367  6367 W art     : b53e4000-b53e6000 rw-p 00000000 00:00 0 
08-09 13:02:23.788  6367  6367 W art     : b53e7000-b53f1000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-09 13:02:23.788  6367  6367 W art     : b53f1000-b53f4000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-09 13:02:23.788  6367  6367 W art     : b53f4000-b53f5000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-09 13:02:23.788  6367  6367 W art     : b53f6000-b540d000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-09 13:02:23.788  6367  6367 W art     : b540d000-b540e000 ---p 00000000 00:00 0 
,08-09 13:02:23.788  6367  6367 W art     : b540e000-b540f000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-09 13:02:23.788  6367  6367 W art     : b540f000-b5410000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-09 13:02:23.788  6367  6367 W art     : b5411000-b541b000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-09 13:02:23.798  6367  6367 W art     : b541b000-b541c000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-09 13:02:23.798  6367  6367 W art     : b541c000-b541d000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-09 13:02:23.798  6367  6367 W art     : b541d000-b5421000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-09 13:02:23.798  6367  6367 W art     : b5421000-b5422000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-09 13:02:23.798  6367  6367 W art     : b5422000-b5423000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-09 13:02:23.798  6367  6367 W art     : b5423000-b5439000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
,08-09 13:02:23.798  6367  6367 W art     : b5439000-b543a000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-09 13:02:23.798  6367  6367 W art     : b543a000-b543b000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
,08-09 13:02:23.798  6367  6367 W art     : b543b000-b5448000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-09 13:02:23.798  6367  6367 W art     : b5448000-b5449000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-09 13:02:23.798  6367  6367 W art     : b5449000-b544a000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-09 13:02:23.798  6367  6367 W art     : b544a000-b54aa000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-09 13:02:23.798  6367  6367 W art     : b54aa000-b54ad000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-09 13:02:23.798  6367  6367 W art     : b54ad000-b54b1000 rw-p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b54b1000-b5512000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-09 13:02:23.798  6367  6367 W art     : b5512000-b5513000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-09 13:02:23.798  6367  6367 W art     : b5513000-b5562000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-09 13:02:23.798  6367  6367 W art     : b5562000-b5564000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
,08-09 13:02:23.798  6367  6367 W art     : b5564000-b5565000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-09 13:02:23.798  6367  6367 W art     : b5565000-b5566000 rw-p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b5566000-b556d000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-09 13:02:23.798  6367  6367 W art     : b556d000-b556e000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-09 13:02:23.798  6367  6367 W art     : b556e000-b556f000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-09 13:02:23.798  6367  6367 W art     : avc_common.so
08-09 13:02:23.798  6367  6367 W art     : b5570000-b5573000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-09 13:02:23.798  6367  6367 W art     : b5573000-b5574000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-09 13:02:23.798  6367  6367 W art     : b5574000-b5575000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-09 13:02:23.798  6367  6367 W art     : enc_common.so
,08-09 13:02:23.798  6367  6367 W art     : b5576000-b557a000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-09 13:02:23.798  6367  6367 W art     : b557a000-b557b000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b557b000-b557c000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-09 13:02:23.798  6367  6367 W art     : b557c000-b557d000 rw-p 00005000 b3:17 2510       /syste
08-09 13:02:23.798  6367  6367 W art     : m/lib/libpowermanager.so
08-09 13:02:23.798  6367  6367 W art     : b557e000-b559b000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-09 13:02:23.798  6367  6367 W art     : b559b000-b559c000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-09 13:02:23.798  6367  6367 W art     : b559c000-b559d000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-09 13:02:23.798  6367  6367 W art     : b559e000-b55a3000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-09 13:02:23.798  6367  6367 W art     : b55a3000-b55a4000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-09 13:02:23.798  6367  6367 W art     : b55a4000-b55a5000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-09 13:02:23.798  6367  6367 W art     : b55a6000-b55d7000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-09 13:02:23.798  6367  6367 W art     : b55d7000-b55da000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-09 13:02:23.798  6367  6367 W art     : b55da000-b55db000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-09 13:02:23.798  6367  6367 W art     : b55dc000-b5617000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-09 13:02:23.798  6367  6367 W art     : b5617000-b5618000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-09 13:02:23.798  6367  6367 W art     : b5618000-b5619000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-09 13:02:23.798  6367  6367 W art     : b561a000-b5621000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-09 13:02:23.798  6367  6367 W art     : b5621000-b5622000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b5622000-b5623000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-09 13:02:23.798  6367  6367 W art     : b5623000-b5624000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
,08-09 13:02:23.798  6367  6367 W art     : b5624000-b5625000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.798  6367  6367 W art     : b5625000-b563c000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-09 13:02:23.798  6367  6367 W art     : b563c000-b563d000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b563d000-b5640000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-09 13:02:23.798  6367  6367 W art     : b5640000-b5641000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-09 13:02:23.798  6367  6367 W art     : b5641000-b5660000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-09 13:02:23.798  6367  6367 W art     : b5660000-b5661000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-09 13:02:23.798  6367  6367 W art     : b5661000-b5662000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-09 13:02:23.798  6367  6367 W art     : b5662000-b56a0000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-09 13:02:23.798  6367  6367 W art     : b56a0000-b56a1000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b56a1000-b56a3000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
,08-09 13:02:23.798  6367  6367 W art     : b56a3000-b56a4000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-09 13:02:23.798  6367  6367 W art     : b56a5000-b56ac000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-09 13:02:23.798  6367  6367 W art     : b56ac000-b56ad000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-09 13:02:23.798  6367  6367 W art     : b56ad000-b56ae000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-09 13:02:23.798  6367  6367 W art     : b56af000-b56b2000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-09 13:02:23.798  6367  6367 W art     : b56b2000-b56b3000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-09 13:02:23.798  6367  6367 W art     : b56b3000-b56b4000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-09 13:02:23.798  6367  6367 W art     : b56b4000-b56ba000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-09 13:02:23.798  6367  6367 W art     : b56ba000-b56bb000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b56bb000-b56bc000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-09 13:02:23.798  6367  6367 W art     : b56bc000-b56bd000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-09 13:02:23.798  6367  6367 W art     : b56bd000-b56c6000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-09 13:02:23.798  6367  6367 W art     : b56c6000-b56c7000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-09 13:02:23.798  6367  6367 W art     : b56c7000-b56c8000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-09 13:02:23.798  6367  6367 W art     : b56c8000-b5759000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-09 13:02:23.798  6367  6367 W art     : b5759000-b575a000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b575a000-b5765000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-09 13:02:23.798  6367  6367 W art     : b5765000-b5766000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-09 13:02:23.798  6367  6367 W art     : b5767000-b5779000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-09 13:02:23.798  6367  6367 W art     : b5779000-b577a000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
,08-09 13:02:23.798  6367  6367 W art     : b577a000-b577b000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-09 13:02:23.798  6367  6367 W art     : b577c000-b5781000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-09 13:02:23.798  6367  6367 W art     : b5781000-b5782000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-09 13:02:23.798  6367  6367 W art     : b5782000-b5783000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-09 13:02:23.798  6367  6367 W art     : b5784000-b57f1000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-09 13:02:23.798  6367  6367 W art     : b57f1000-b57f2000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b57f2000-b57f4000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-09 13:02:23.798  6367  6367 W art     : b57f4000-b57f5000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-09 13:02:23.798  6367  6367 W art     : b57f5000-b57f6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.798  6367  6367 W art     : b57f6000-b57fd000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-09 13:02:23.798  6367  6367 W art     : b57fd000-b57fe000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-09 13:02:23.798  6367  6367 W art     : b57fe000-b57ff000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-09 13:02:23.798  6367  6367 W art     : b5800000-b5880000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-09 13:02:23.798  6367  6367 W art     : b5880000-b5881000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b5881000-b5882000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-09 13:02:23.798  6367  6367 W art     : b5882000-b5883000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-09 13:02:23.798  6367  6367 W art     : b5883000-b589a000 rw-p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b589a000-b58d1000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-09 13:02:23.798  6367  6367 W art     : ib/libqc-opt.so
08-09 13:02:23.798  6367  6367 W art     : b58d1000-b58d2000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-09 13:02:23.798  6367  6367 W art     : b58d2000-b58d3000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
,08-09 13:02:23.798  6367  6367 W art     : b58d3000-b58ef000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-09 13:02:23.798  6367  6367 W art     : b58ef000-b58f0000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-09 13:02:23.798  6367  6367 W art     : b58f0000-b58f1000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-09 13:02:23.798  6367  6367 W art     : b58f2000-b5953000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-09 13:02:23.798  6367  6367 W art     : b5953000-b5955000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-09 13:02:23.798  6367  6367 W art     : b5955000-b5956000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-09 13:02:23.798  6367  6367 W art     : b5957000-b597e000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-09 13:02:23.798  6367  6367 W art     : b597e000-b597f000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b597f000-b5980000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-09 13:02:23.798  6367  6367 W art     : b5980000-b5981000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
,08-09 13:02:23.798  6367  6367 W art     : b5982000-b598a000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-09 13:02:23.798  6367  6367 W art     : b598a000-b598c000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-09 13:02:23.798  6367  6367 W art     : b598c000-b598d000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-09 13:02:23.798  6367  6367 W art     : b598e000-b5991000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-09 13:02:23.798  6367  6367 W art     : b5991000-b5992000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-09 13:02:23.798  6367  6367 W art     : b5992000-b5993000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-09 13:02:23.798  6367  6367 W art     : b5993000-b5997000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-09 13:02:23.798  6367  6367 W art     : b5997000-b5998000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b5998000-b5999000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-09 13:02:23.798  6367  6367 W art     : b5999000-b599a000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
,08-09 13:02:23.798  6367  6367 W art     : b599a000-b59aa000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-09 13:02:23.798  6367  6367 W art     : b59aa000-b59ab000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-09 13:02:23.798  6367  6367 W art     : b59ab000-b59ac000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-09 13:02:23.798  6367  6367 W art     : b59ac000-b59f2000 rw-p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b59f2000-b59fb000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-09 13:02:23.798  6367  6367 W art     : b59fb000-b59fc000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-09 13:02:23.798  6367  6367 W art     : b59fc000-b59fd000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-09 13:02:23.798  6367  6367 W art     : b59fe000-b5a03000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-09 13:02:23.798  6367  6367 W art     : b5a03000-b5a04000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-09 13:02:23.798  6367  6367 W art     : b5a04000-b5a05000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
,08-09 13:02:23.798  6367  6367 W art     : b5a05000-b5a08000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-09 13:02:23.798  6367  6367 W art     : b5a08000-b5a09000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b5a09000-b5a0a000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-09 13:02:23.798  6367  6367 W art     : b5a0a000-b5a0b000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-09 13:02:23.798  6367  6367 W art     : b5a0c000-b5a24000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-09 13:02:23.798  6367  6367 W art     : b5a24000-b5a25000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b5a25000-b5a26000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-09 13:02:23.798  6367  6367 W art     : b5a26000-b5a27000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-09 13:02:23.798  6367  6367 W art     : b5a28000-b5bc2000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-09 13:02:23.798  6367  6367 W art     : b5bc2000-b5bc3000 ---p 00000000 00:00 0 
,08-09 13:02:23.798  6367  6367 W art     : b5bc3000-b5bd0000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-09 13:02:23.798  6367  6367 W art     : b5bd0000-b5bd1000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-09 13:02:23.798  6367  6367 W art     : b5bd1000-b5bd5000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-09 13:02:23.798  6367  6367 W art     : b5bd5000-b5bd6000 ---p 00000000 00:00 0 
08-09 13:02:23.798  6367  6367 W art     : b5bd6000-b5bd7000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-09 13:02:23.798  6367  6367 W art     : b5bd7000-b5bd8000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-09 13:02:23.798  6367  6367 W art     : b5bd8000-b5beb000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-09 13:02:23.798  6367  6367 W art     : b5beb000-b5bec000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-09 13:02:23.798  6367  6367 W art     : b5bec000-b5bed000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-09 13:02:23.798  6367  6367 W art     : b5bed000-b5bee000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-09 13:02:23.798  6367  6367 W art     : b5bee000-b5c39000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-09 13:02:23.808  6367  6367 W art     : b5c39000-b5c3a000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-09 13:02:23.808  6367  6367 W art     : b5c3a000-b5c3b000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-09 13:02:23.808  6367  6367 W art     : b5c3b000-b5c3d000 rw-p 00000000 00:00 0 
08-09 13:02:23.808  6367  6367 W art     : b5c3e000-b5c4f000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-09 13:02:23.808  6367  6367 W art     : b5c4f000-b5c50000 ---p 00000000 00:00 0 
08-09 13:02:23.808  6367  6367 W art     : b5c50000-b5c51000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-09 13:02:23.808  6367  6367 W art     : b5c51000-b5c52000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-09 13:02:23.808  6367  6367 W art     : b5c53000-b5c5d000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-09 13:02:23.808  6367  6367 W art     : b5c5d000-b5c5f000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-09 13:02:23.808  6367  6367 W art     : b5c5f000-b5c60000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-09 13:02:23.808  6367  6367 W art     : b5c60000-b5c79000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-09 13:02:23.808  6367  6367 W art     : b5c79000-b5c7a000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-09 13:02:23.808  6367  6367 W art     : b5c7a000-b5c7d000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-09 13:02:23.808  6367  6367 W art     : b5c7d000-b5c81000 rw-p 00000000 00:00 0 
08-09 13:02:23.808  6367  6367 W art     : b5c81000-b5cf5000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-09 13:02:23.808  6367  6367 W art     : b5cf5000-b5cf6000 ---p 00000000 00:00 0 
08-09 13:02:23.808  6367  6367 W art     : b5cf6000-b5cf9000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-09 13:02:23.808  6367  6367 W art     : b5cf9000-b5cfa000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-09 13:02:23.808  6367  6367 W art     : b5cfa000-b5cfb000 r--p 00000000 00:00 0 
08-09 13:02:23.808  6367  6367 W art     : b5cfb000-b5cfe000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-09 13:02:23.808  6367  6367 W art     : b5cfe000-b5cff000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-09 13:02:23.808  6367  6367 W art     : b5cff000-b5d00000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-09 13:02:23.808  6367  6367 W art     : b5d00000-b5d01000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.808  6367  6367 W art     : b5d01000-b5d06000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-09 13:02:23.808  6367  6367 W art     : b5d06000-b5d07000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-09 13:02:23.808  6367  6367 W art     : b5d07000-b5d08000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-09 13:02:23.808  6367  6367 W art     : b5d08000-b5d09000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.808  6367  6367 W art     : b5d09000-b5d0c000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-09 13:02:23.808  6367  6367 W art     : b5d0c000-b5d0d000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-09 13:02:23.818  6367  6367 W art     : b5d0d000-b5d0e000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-09 13:02:23.818  6367  6367 W art     : b5d0e000-b5d0f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.818  6367  6367 W art     : b5d0f000-b5d13000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-09 13:02:23.818  6367  6367 W art     : b5d13000-b5d14000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-09 13:02:23.818  6367  6367 W art     : b5d14000-b5d15000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-09 13:02:23.818  6367  6367 W art     : b5d15000-b5d16000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-09 13:02:23.818  6367  6367 W art     : b5d16000-b5d1a000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-09 13:02:23.818  6367  6367 W art     : b5d1a000-b5d1b000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-09 13:02:23.818  6367  6367 W art     : b5d1b000-b5d1c000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-09 13:02:23.818  6367  6367 W art     : b5d1c000-b5d1d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.818  6367  6367 W art     : b5d1d000-b5d2b000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-09 13:02:23.818  6367  6367 W art     : b5d2b000-b5d2c000 ---p 00000000 00:00 0 
08-09 13:02:23.818  6367  6367 W art     : b5d2c000-b5d2d000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-09 13:02:23.818  6367  6367 W art     : b5d2d000-b5d2e000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
,08-09 13:02:23.818  6367  6367 W art     : b5d2e000-b5d38000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-09 13:02:23.818  6367  6367 W art     : b5d38000-b5d3b000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-09 13:02:23.818  6367  6367 W art     : b5d3b000-b5d3c000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-09 13:02:23.818  6367  6367 W art     : b5d3c000-b5d3d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.818  6367  6367 W art     : b5d3d000-b5d47000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-09 13:02:23.818  6367  6367 W art     : b5d47000-b5d4a000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-09 13:02:23.818  6367  6367 W art     : b5d4a000-b5d4b000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-09 13:02:23.818  6367  6367 W art     : b5d4b000-b5d4f000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-09 13:02:23.818  6367  6367 W art     : b5d4f000-b5d50000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
,08-09 13:02:23.818  6367  6367 W art     : b5d50000-b5d51000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-09 13:02:23.818  6367  6367 W art     : b5d51000-b5d52000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.818  6367  6367 W art     : b5d52000-b5d5f000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-09 13:02:23.818  6367  6367 W art     : b5d5f000-b5d61000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-09 13:02:23.818  6367  6367 W art     : b5d61000-b5d62000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-09 13:02:23.818  6367  6367 W art     : b5d62000-b6174000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-09 13:02:23.818  6367  6367 W art     : b6174000-b6175000 ---p 00000000 00:00 0 
08-09 13:02:23.818  6367  6367 W art     : b6175000-b617e000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-09 13:02:23.818  6367  6367 W art     : b617e000-b6182000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-09 13:02:23.818  6367  6367 W art     : b6182000-b6183000 rw-p 00000000 00:00 0 
08-09 13:02:23.818  6367  6367 W art     : b6183000-b618a000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-09 13:02:23.818  6367  6367 W art     : b618a000-b618b000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
,08-09 13:02:23.828  6367  6367 W art     : b618b000-b618c000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-09 13:02:23.828  6367  6367 W art     : b618c000-b618d000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-09 13:02:23.828  6367  6367 W art     : b618d000-b61a8000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-09 13:02:23.828  6367  6367 W art     : b61a8000-b61a9000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-09 13:02:23.828  6367  6367 W art     : b61a9000-b61aa000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
,08-09 13:02:23.828  6367  6367 W art     : b61aa000-b61ab000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.828  6367  6367 W art     : b61ab000-b61f7000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-09 13:02:23.828  6367  6367 W art     : b61f7000-b61f8000 ---p 00000000 00:00 0 
08-09 13:02:23.828  6367  6367 W art     : b61f8000-b61f9000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
,08-09 13:02:23.828  6367  6367 W art     : b61f9000-b61fa000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-09 13:02:23.828  6367  6367 W art     : b61fa000-b61fb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.828  6367  6367 W art     : b61fb000-b61ff000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-09 13:02:23.828  6367  6367 W art     : b61ff000-b6200000 ---p 00000000 00:00 0 
,08-09 13:02:23.828  6367  6367 W art     : b6200000-b6201000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-09 13:02:23.828  6367  6367 W art     : b6201000-b6202000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-09 13:02:23.828  6367  6367 W art     : b6202000-b623a000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
,08-09 13:02:23.828  6367  6367 W art     : b623a000-b623b000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-09 13:02:23.828  6367  6367 W art     : b623b000-b623c000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-09 13:02:23.828  6367  6367 W art     : b623c000-b623d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.828  6367  6367 W art     : b623d000-b62db000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
,08-09 13:02:23.828  6367  6367 W art     : b62db000-b62dc000 ---p 00000000 00:00 0 
08-09 13:02:23.828  6367  6367 W art     : b62dc000-b62fa000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
,08-09 13:02:23.828  6367  6367 W art     : b62fa000-b62fb000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-09 13:02:23.828  6367  6367 W art     : b62fb000-b646e000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-09 13:02:23.828  6367  6367 W art     : b646e000-b6479000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-09 13:02:23.828  6367  6367 W art     : b6479000-b647a000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-09 13:02:23.828  6367  6367 W art     : b647a000-b6591000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-09 13:02:23.828  6367  6367 W art     : b6591000-b659c000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-09 13:02:23.828  6367  6367 W art     : b659c000-b659d000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-09 13:02:23.828  6367  6367 W art     : b659d000-b65a1000 rw-p 00000000 00:00 0 
08-09 13:02:23.828  6367  6367 W art     : b65a1000-b65c5000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-09 13:02:23.828  6367  6367 W art     : b65c5000-b65c7000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-09 13:02:23.828  6367  6367 W art     : b65c7000-b65c8000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
,08-09 13:02:23.838  6367  6367 W art     : b65c8000-b666e000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-09 13:02:23.838  6367  6367 W art     : b666e000-b667b000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-09 13:02:23.838  6367  6367 W art     : b667b000-b667c000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-09 13:02:23.838  6367  6367 W art     : b667c000-b667d000 rw-p 00000000 00:00 0 
,08-09 13:02:23.838  6367  6367 W art     : b667d000-b66d0000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-09 13:02:23.838  6367  6367 W art     : b66d0000-b66d1000 ---p 00000000 00:00 0 
08-09 13:02:23.838  6367  6367 W art     : b66d1000-b66d2000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-09 13:02:23.838  6367  6367 W art     : b66d2000-b66d3000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-09 13:02:23.838  6367  6367 W art     : b66d3000-b66d8000 rw-p 00000000 00:00 0 
08-09 13:02:23.838  6367  6367 W art     : b66d8000-b66ea000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-09 13:02:23.838  6367  6367 W art     : b66ea000-b66eb000 ---p 00000000 00:00 0 
08-09 13:02:23.838  6367  6367 W art     : b66eb000-b66ec000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-09 13:02:23.838  6367  6367 W art     : b66ec000-b66ed000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-09 13:02:23.838  6367  6367 W art     : b66ed000-b66f4000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-09 13:02:23.838  6367  6367 W art     : b66f4000-b66f5000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-09 13:02:23.838  6367  6367 W art     : b66f5000-b66f6000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-09 13:02:23.838  6367  6367 W art     : b66f6000-b66f7000 rw-p 00000000 00:00 0 
08-09 13:02:23.838  6367  6367 W art     : b66f7000-b66fa000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-09 13:02:23.838  6367  6367 W art     : b66fa000-b66fb000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-09 13:02:23.838  6367  6367 W art     : b66fb000-b66fc000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-09 13:02:23.838  6367  6367 W art     : b66fc000-b6700000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-09 13:02:23.838  6367  6367 W art     : b6700000-b6701000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-09 13:02:23.838  6367  6367 W art     : b6701000-b6702000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-09 13:02:23.838  6367  6367 W art     : b6702000-b6710000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-09 13:02:23.838  6367  6367 W art     : b6710000-b6711000 ---p 00000000 00:00 0 
08-09 13:02:23.838  6367  6367 W art     : b6711000-b6712000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-09 13:02:23.838  6367  6367 W art     : b6712000-b6713000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-09 13:02:23.838  6367  6367 W art     : b6713000-b671c000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-09 13:02:23.838  6367  6367 W art     : b671c000-b671d000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-09 13:02:23.838  6367  6367 W art     : b671d000-b671e000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-09 13:02:23.838  6367  6367 W art     : b671e000-b6784000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-09 13:02:23.838  6367  6367 W art     : b6784000-b6785000 ---p 00000000 00:00 0 
08-09 13:02:23.838  6367  6367 W art     : b6785000-b6787000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-09 13:02:23.838  6367  6367 W art     : b6787000-b6790000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-09 13:02:23.838  6367  6367 W art     : b6790000-b6793000 rw-p 00000000 00:00 0 
08-09 13:02:23.838  6367  6367 W art     : b6793000-b682a000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-09 13:02:23.838  6367  6367 W art     : b682a000-b682c000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-09 13:02:23.838  6367  6367 W art     : b682c000-b682d000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-09 13:02:23.838  6367  6367 W art     : b682d000-b682e000 rw-p 00000000 00:00 0 
08-09 13:02:23.838  6367  6367 W art     : b682e000-b6b4f000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-09 13:02:23.848  6367  6367 W art     : b6b4f000-b6b50000 ---p 00000000 00:00 0 
08-09 13:02:23.848  6367  6367 W art     : b6b50000-b6b6b000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-09 13:02:23.848  6367  6367 W art     : b6b6b000-b6b6f000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-09 13:02:23.848  6367  6367 W art     : b6b6f000-b6b74000 rw-p 00000000 00:00 0 
08-09 13:02:23.848  6367  6367 W art     : b6b74000-b6b7c000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-09 13:02:23.848  6367  6367 W art     : b6b7c000-b6b7d000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-09 13:02:23.848  6367  6367 W art     : b6b7d000-b6b7e000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-09 13:02:23.848  6367  6367 W art     : b6b7e000-b6bac000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-09 13:02:23.848  6367  6367 W art     : b6bac000-b6bad000 ---p 00000000 00:00 0 
08-09 13:02:23.848  6367  6367 W art     : b6bad000-b6bb4000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-09 13:02:23.848  6367  6367 W art     : b6bb4000-b6bb5000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-09 13:02:23.848  6367  6367 W art     : b6bb5000-b6bfb000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-09 13:02:23.848  6367  6367 W art     : b6bfb000-b6bfc000 ---p 00000000 00:00 0 
08-09 13:02:23.848  6367  6367 W art     : b6bfc000-b6bff000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-09 13:02:23.848  6367  6367 W art     : b6bff000-b6c00000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-09 13:02:23.848  6367  6367 W art     : b6c00000-b6c1b000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-09 13:02:23.848  6367  6367 W art     : b6c1b000-b6c1f000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-09 13:02:23.848  6367  6367 W art     : b6c1f000-b6c20000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-09 13:02:23.848  6367  6367 W art     : b6c20000-b6c6d000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-09 13:02:23.848  6367  6367 W art     : b6c6d000-b6c6e000 ---p 00000000 00:00 0 
08-09 13:02:23.848  6367  6367 W art     : b6c6e000-b6c7a000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-09 13:02:23.848  6367  6367 W art     : b6c7a000-b6c7b000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-09 13:02:23.848  6367  6367 W art     : b6c7b000-b6c88000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-09 13:02:23.848  6367  6367 W art     : b6c88000-b6c89000 ---p 00000000 00:00 0 
08-09 13:02:23.848  6367  6367 W art     : b6c89000-b6c8a000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-09 13:02:23.848  6367  6367 W art     : b6c8a000-b6c8b000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-09 13:02:23.848  6367  6367 W art     : b6c8b000-b6c93000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-09 13:02:23.848  6367  6367 W art     : b6c93000-b6c94000 ---p 00000000 00:00 0 
08-09 13:02:23.848  6367  6367 W art     : b6c94000-b6c95000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-09 13:02:23.848  6367  6367 W art     : b6c95000-b6c96000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-09 13:02:23.848  6367  6367 W art     : b6c96000-b6c9d000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-09 13:02:23.848  6367  6367 W art     : b6c9d000-b6c9e000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-09 13:02:23.848  6367  6367 W art     : b6c9e000-b6c9f000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-09 13:02:23.848  6367  6367 W art     : b6c9f000-b6cb3000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-09 13:02:23.848  6367  6367 W art     : b6cb3000-b6cb5000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-09 13:02:23.848  6367  6367 W art     : b6cb5000-b6cb6000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-09 13:02:23.848  6367  6367 W art     : b6cb6000-b6cde000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-09 13:02:23.848  6367  6367 W art     : b6cde000-b6ce0000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-09 13:02:23.848  6367  6367 W art     : b6ce0000-b6ce1000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-09 13:02:23.858  6367  6367 W art     : b6ce1000-b6ce4000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-09 13:02:23.858  6367  6367 W art     : b6ce4000-b6ce5000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-09 13:02:23.858  6367  6367 W art     : b6ce5000-b6ce6000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-09 13:02:23.858  6367  6367 W art     : b6ce6000-b6cef000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-09 13:02:23.858  6367  6367 W art     : b6cef000-b6cf0000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-09 13:02:23.858  6367  6367 W art     : b6cf0000-b6cf1000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-09 13:02:23.858  6367  6367 W art     : b6cf1000-b6d11000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-09 13:02:23.858  6367  6367 W art     : b6d11000-b6d12000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-09 13:02:23.858  6367  6367 W art     : b6d12000-b6d13000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-09 13:02:23.858  6367  6367 W art     : b6d13000-b6d86000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-09 13:02:23.858  6367  6367 W art     : b6d86000-b6d8a000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-09 13:02:23.858  6367  6367 W art     : b6d8a000-b6d8d000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-09 13:02:23.858  6367  6367 W art     : b6d8d000-b6d97000 rw-p 00000000 00:00 0 
08-09 13:02:23.858  6367  6367 W art     : b6d97000-b6e1f000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-09 13:02:23.858  6367  6367 W art     : b6e1f000-b6e20000 ---p 00000000 00:00 0 
08-09 13:02:23.858  6367  6367 W art     : b6e20000-b6e24000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-09 13:02:23.858  6367  6367 W art     : b6e24000-b6e25000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-09 13:02:23.858  6367  6367 W art     : b6e25000-b6e26000 rw-p 00000000 00:00 0 
08-09 13:02:23.858  6367  6367 W art     : b6e26000-b6e4f000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-09 13:02:23.858  6367  6367 W art     : b6e4f000-b6e50000 ---p 00000000 00:00 0 
08-09 13:02:23.858  6367  6367 W art     : b6e50000-b6e53000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-09 13:02:23.858  6367  6367 W art     : b6e53000-b6e54000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-09 13:02:23.858  6367  6367 W art     : b6e54000-b6f2e000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-09 13:02:23.858  6367  6367 W art     : b6f2e000-b6f35000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-09 13:02:23.858  6367  6367 W art     : b6f35000-b6f3d000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-09 13:02:23.858  6367  6367 W art     : b6f3d000-b6f3e000 rw-p 00000000 00:00 0 
08-09 13:02:23.858  6367  6367 W art     : b6f3e000-b6f3f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-09 13:02:23.858  6367  6367 W art     : b6f3f000-b6f40000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-09 13:02:23.858  6367  6367 W art     : b6f40000-b6f41000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.858  6367  6367 W art     : b6f41000-b6f44000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.858  6367  6367 W art     : b6f44000-b6f69000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-09 13:02:23.858  6367  6367 W art     : b6f69000-b6f6a000 ---p 00000000 00:00 0 
08-09 13:02:23.858  6367  6367 W art     : b6f6a000-b6f71000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-09 13:02:23.858  6367  6367 W art     : b6f71000-b6f72000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-09 13:02:23.858  6367  6367 W art     : b6f72000-b6f79000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-09 13:02:23.858  6367  6367 W art     : b6f79000-b6f7a000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-09 13:02:23.858  6367  6367 W art     : b6f7a000-b6f7b000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-09 13:02:23.858  6367  6367 W art     : b6f7b000-b6f7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.858  6367  6367 W art     : b6f7c000-b6f94000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-09 13:02:23.868  6367  6367 W art     : b6f94000-b6f95000 ---p 00000000 00:00 0 
08-09 13:02:23.868  6367  6367 W art     : b6f95000-b6f96000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-09 13:02:23.868  6367  6367 W art     : b6f96000-b6f97000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-09 13:02:23.868  6367  6367 W art     : b6f97000-b6fa5000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-09 13:02:23.868  6367  6367 W art     : b6fa5000-b6fa6000 ---p 00000000 00:00 0 
08-09 13:02:23.868  6367  6367 W art     : b6fa6000-b6fa7000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-09 13:02:23.868  6367  6367 W art     : b6fa7000-b6fa8000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-09 13:02:23.868  6367  6367 W art     : b6fa8000-b6fa9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-09 13:02:23.868  6367  6367 W art     : b6fa9000-b6fab000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.868  6367  6367 W art     : b6fab000-b6fac000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.868  6367  6367 W art     : b6fac000-b6fad000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-09 13:02:23.868  6367  6367 W art     : b6fad000-b6fae000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-09 13:02:23.868  6367  6367 W art     : b6fae000-b6faf000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-09 13:02:23.868  6367  6367 W art     : b6faf000-b6fcf000 r--s 00000000 00:0b 7179       /dev/__properties__
08-09 13:02:23.868  6367  6367 W art     : b6fcf000-b6fd0000 r--p 00000000 00:00 0 
08-09 13:02:23.868  6367  6367 W art     : b6fd0000-b6fd1000 ---p 00000000 00:00 0 
08-09 13:02:23.868  6367  6367 W art     : b6fd1000-b6fd3000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-09 13:02:23.868  6367  6367 W art     : b6fd3000-b6fd4000 r-xp 00000000 00:00 0          [sigpage]
08-09 13:02:23.868  6367  6367 W art     : b6fd4000-b6fef000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-09 13:02:23.868  6367  6367 W art     : b6fef000-b6ff0000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-09 13:02:23.868  6367  6367 W art     : b6ff0000-b6ff2000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-09 13:02:23.868  6367  6367 W art     : b6ff2000-b6ff4000 rw-p 00000000 00:00 0 
08-09 13:02:23.868  6367  6367 W art     : b6ff4000-b6ff9000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-09 13:02:23.868  6367  6367 W art     : b6ff9000-b6ffa000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-09 13:02:23.868  6367  6367 W art     : b6ffa000-b6ffb000 rw-p 00000000 00:00 0 
08-09 13:02:23.868  6367  6367 W art     : bee65000-bee86000 rw-p 00000000 00:00 0          [stack]
08-09 13:02:23.868  6367  6367 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-09 13:02:23.938  6367  6367 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-09 13:02:24.018  6367  6367 I Radio-JNI: register_android_hardware_Radio DONE
,08-09 13:02:24.028  6367  6367 E AffinityControl: AffinityControl: registerfunction enter
,08-09 13:02:24.048  6367  6367 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-09 13:02:24.068   745  2414 D PackageManager: START PACKAGE DELETE: observer{108334221}
08-09 13:02:24.068   745  2414 D PackageManager: pkg{<packageName>}
08-09 13:02:24.068   745  2414 D PackageManager: user{0}
08-09 13:02:24.068   745  2414 D PackageManager: caller{2000}
08-09 13:02:24.068   745  2414 D PackageManager: flags{2}
08-09 13:02:24.068   745  2414 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-09 13:02:24.068   745  2414 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-09 13:02:24.068   745  2414 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-09 13:02:24.068   745  2414 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-09 13:02:24.068   745  2414 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-09 13:02:24.068   745   909 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-09 13:02:24.068   745   909 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-09 13:02:24.068   745   909 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-09 13:02:24.068   745   909 D ApplicationPolicy: getApplicationUninstallationEnabled
08-09 13:02:24.068   745   909 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-09 13:02:24.068   745   909 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-09 13:02:24.068   745   909 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-09 13:02:24.068   745   909 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-09 13:02:24.068   745   810 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-09 13:02:24.068   745   909 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-09 13:02:24.068   745   909 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-09 13:02:24.068   745   810 I ActivityManager: Killing 6262:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,08-09 13:02:24.078   745   810 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-09 13:02:24.078   745   810 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-09 13:02:24.098  6376  6376 E Zygote  : v2
08-09 13:02:24.098  6376  6376 I libpersona: KNOX_SDCARD checking this for 10004
08-09 13:02:24.098  6376  6376 I libpersona: KNOX_SDCARD not a persona
08-09 13:02:24.098  6376  6376 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-09 13:02:24.098  6376  6376 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-09 13:02:24.098  6376  6376 E Zygote  : accessInfo : 0
08-09 13:02:24.098  6376  6376 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-09 13:02:24.108   745   810 I ActivityManager: Start proc 6376:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
,08-09 13:02:24.108   745   810 I ActivityManager:   Force finishing activity ActivityRecord{34a68b8 u0 com.test.thalitest/.MainActivity t128}
,08-09 13:02:24.118   293   828 I SurfaceFlinger: id=19 Removed NainActivit (4/10)
,08-09 13:02:24.118   293   360 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,08-09 13:02:24.128   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee4238c
,08-09 13:02:24.138  6376  6376 D TimaKeyStoreProvider: TimaSignature is unavailable
08-09 13:02:24.138  6376  6376 D ActivityThread: Added TimaKeyStore provider
,08-09 13:02:24.138   745   909 D AASAinstall: there is not AASApackages.xml file
,08-09 13:02:24.168   745  1683 D GraphicsStats: Buffer count: 4
,08-09 13:02:24.168   745  3532 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@bb77e42)
,08-09 13:02:24.168   745  1332 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-09 13:02:24.168   745  1332 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-09 13:02:24.168   745  1332 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-09 13:02:24.478   745   909 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-09 13:02:24.508   745   909 W PackageSettings: Skipping PackageSetting{80d5fd8 com.example.hello/10192} due to missing metadata
,08-09 13:02:24.598   745   909 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-09 13:02:24.598   745  1624 I ActivityManager: Killing 4992:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-09 13:02:24.618  6376  6376 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-09 13:02:24.628  6376  6376 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,08-09 13:02:24.628   324   324 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-09 13:02:24.628   745   909 I art     : Starting a blocking GC Explicit
08-09 13:02:24.628  6376  6376 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-09 13:02:24.628  6376  6376 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-09 13:02:24.628  6376  6376 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-09 13:02:24.638   745  1690 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-09 13:02:24.648  6376  6376 D AndroidRuntime: Shutting down VM
,08-09 13:02:24.648  6376  6376 E AndroidRuntime: FATAL EXCEPTION: main
08-09 13:02:24.648  6376  6376 E AndroidRuntime: Process: com.test.thalitest, PID: 6376
08-09 13:02:24.648  6376  6376 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-09 13:02:24.648  6376  6376 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-09 13:02:24.648  6376  6376 E AndroidRuntime: 	... 9 more
,08-09 13:02:24.668  6376  6376 I Process : Sending signal. PID: 6376 SIG: 9
,08-09 13:02:24.688   745   810 I ActivityManager: Start proc 6394:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,08-09 13:02:24.688  6394  6394 E Zygote  : v2
08-09 13:02:24.688  6394  6394 I libpersona: KNOX_SDCARD checking this for 1000
08-09 13:02:24.688  6394  6394 I libpersona: KNOX_SDCARD not a persona
,08-09 13:02:24.688  6394  6394 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-09 13:02:24.688  6394  6394 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-09 13:02:24.688  6394  6394 E Zygote  : accessInfo : 0
,08-09 13:02:24.688   745  2414 I ActivityManager: Process com.test.thalitest (pid 6376)(adj 9) has died(143,742)
,08-09 13:02:24.688   745  2414 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-09 13:02:24.688   745  2414 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-09 13:02:24.698   745  2414 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26661 com.android.server.am.ActivityManagerService.appDiedLocked:7558 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,08-09 13:02:24.708   745   810 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
08-09 13:02:24.708   745   810 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,08-09 13:02:24.718  6394  6394 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-09 13:02:24.718  6394  6394 D ActivityThread: Added TimaKeyStore provider
,08-09 13:02:24.728   745   763 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ea50e53 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dd69390 6394:com.samsung.android.sm/1000}
,08-09 13:02:24.738  6394  6394 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-09 13:02:24.778  6394  6394 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-09 13:02:24.788   745  1680 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ea50e53 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b3925a 2569:com.google.android.gms/u0a11}
,08-09 13:02:24.838   745   909 I art     : Explicit concurrent mark sweep GC freed 89440(4MB) AllocSpace objects, 17(340KB) LOS objects, 27% free, 41MB/57MB, paused 4.431ms total 204.131ms
,08-09 13:02:24.878   745   909 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-09 13:02:24.878   745   909 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-09 13:02:24.878   745   909 D AASAinstall: there is not AASApackages.xml file
,08-09 13:02:24.888   745   909 D PackageManager: result of delete: 1{108334221}
,08-09 13:02:24.888  6367  6367 I art     : System.exit called, status: 0
08-09 13:02:24.888  6367  6367 I AndroidRuntime: VM exiting with result code 0.
,08-09 13:02:24.898   745   909 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-09 13:02:24.898   745   909 D PackageManager: userId{-1}
08-09 13:02:24.898   745   909 D PackageManager: andCode{true}
,08-09 13:02:24.908   745   909 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-09 13:02:24.928  5432  6410 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-09 13:02:24.928  5432  6410 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-09 13:02:24.928  5432  6410 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-09 13:02:24.968   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.978   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.978   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.978  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-09 13:02:24.978  1378  1378 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-09 13:02:24.978   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.978   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.988   745   884 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.988   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.988   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.988   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-09 13:02:24.988   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.988   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.988   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.988   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-09 13:02:24.988   745   745 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.988   745   884 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.998   745  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-09 13:02:24.998   745   745 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-09 13:02:24.998  1953  1953 E SamsungIME: mOCRHelper is null
,08-09 13:02:24.998   745   745 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:24.998  1986  2237 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-09 13:02:25.008   745   745 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.008   745   745 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.008   745   745 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.008   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.008   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.018   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.018   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.018   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.018   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.018   745   745 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.018   745   745 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.018  1659  1659 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-09 13:02:25.028   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.028   745   810 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a77d56d u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98b0a2f 4087:com.samsung.klmsagent/u0a18}
,08-09 13:02:25.038   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.038   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.038  4087  4087 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Tue Aug 09 13:02:25 GMT+02:00 2016
,08-09 13:02:25.038   745   805 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.038   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.038   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.038   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.038   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.038  3066  3094 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-09 13:02:25.048  3066  3094 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-09 13:02:25.048  3066  3094 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-09 13:02:25.048  3066  3094 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-09 13:02:25.048   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.048   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.048   745  1690 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-09 13:02:25.048   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.048   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.058   745  1365 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/128_task.xml
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.058   745  1365 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/128_task_thumbnail.png
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.058   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.058  4087  4087 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-09 13:02:25.068   745   805 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.068   745   805 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.068   745   745 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.068   745   745 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.068  4087  4087 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-09 13:02:25.068  4087  4087 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-09 13:02:25.068  4087  4087 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-09 13:02:25.078   745   745 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.078   745   745 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.078  4087  6422 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-09 13:02:25.078  4087  6422 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-09 13:02:25.078   745  1323 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-09 13:02:25.078   745  1323 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-09 13:02:25.078  4087  6422 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2d7b314 in tid 6422 (IntentService[K)
,08-09 13:02:25.078  2335  2335 E audit_log: File locking failed. error= Bad file descriptor
08-09 13:02:25.078   745   745 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.078   745   745 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.088   745  1624 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a77d56d u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3e56c94 745:system/1000}
,08-09 13:02:25.088  2335  2335 E audit_log: File locking failed. error= Bad file descriptor
,08-09 13:02:25.088   745   745 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.088   745   745 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.088   745   745 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.088   745   745 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.098   745  1298 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-09 13:02:25.098   745   745 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.098   745   745 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.098   745   745 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.098   745   745 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.098   745   745 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.098   745   745 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.098   745   745 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.098   745   745 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.108   745   745 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.108   745   745 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.118   745   745 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.118   291   291 E lowmemorykiller: Error writing /proc/4087/oom_score_adj; errno=22
08-09 13:02:25.128   745   745 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.128   745   745 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.138   745   745 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.138  1650  6424 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-09 13:02:25.138  1650  6424 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-09 13:02:25.138  1650  6424 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-09 13:02:25.138  1650  6424 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-09 13:02:25.138  1650  6424 D RegisteredComponentCache: Collect Tech packages for Knox
,08-09 13:02:25.148   745   745 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.148   745   745 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.148   745   745 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.148   745   745 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.148   745   745 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.148   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.148   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.148   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.148   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.148   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.148   745  2422 I ActivityManager: Process com.samsung.klmsagent (pid 4087)(adj 5) has died(162,736)
,08-09 13:02:25.148   745  2422 D ActivityManager: isAutoRunBlockedApp:: com.samsung.klmsagent, Auto Run ON
08-09 13:02:25.148   745  2422 I ActivityManager: isWidgetUsingPkg : com.samsung.klmsagent no widget is using.
,08-09 13:02:25.158   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.158   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.158   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.158   745   805 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.158   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.158   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.158   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.158   745   745 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.158   745   745 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.158   745   805 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.158   745   805 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.158   745   805 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.158   745   805 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.168   745  1298 I EventHub: Removing device '/dev/input/event5' due to inotify event
,08-09 13:02:25.178  2569  6408 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ad3af33 in tid 6408 (IntentService[D)
08-09 13:02:25.178  2569  6408 F libc    : Unable to open connection to debuggerd: Connection refused
,08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.188   350   350 I Zygote  : Process 4087 exited due to signal (7)
,08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.188   745   805 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.188   745   805 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.188   745   805 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.188   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.198   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.208   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.208   745  1298 I EventHub: Removing device '/dev/input/event6' due to inotify event
08-09 13:02:25.208   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.208   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-09 13:02:25.208   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.208   745   745 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-09 13:02:25.208  2335  2335 E audit_log: File locking failed. error= Bad file descriptor
,08-09 13:02:25.208   745   745 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,08-09 13:02:25.208   745   745 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-09 13:02:25.208   745   805 D EnterpriseDeviceManagerService: Package has changed for user 0
08-09 13:02:25.208   745   805 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-09 13:02:25.208   745   805 W TextServicesManagerService: no available spell checker services found
,08-09 13:02:25.208   745   745 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
08-09 13:02:25.208   745   745 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
08-09 13:02:25.208   745   745 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-09 13:02:25.218   745   745 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e6215d6 in tid 745 (system_server)
,08-09 13:02:25.218   745   745 F libc    : Unable to open connection to debuggerd: Connection refused
08-09 13:02:25.218  2335  2335 E audit_log: File locking failed. error= Bad file descriptor
,08-09 13:02:25.288   350   350 I Zygote  : Process 2569 exited due to signal (7)
,08-09 13:02:25.308   322   322 E installd: eof
08-09 13:02:25.308   322   322 E installd: failed to read size
08-09 13:02:25.308   322   322 I installd: closing connection
,08-09 13:02:25.318   293   360 D libEGL  : eglTerminate EGLDisplay = 0xb66ff6fc
,08-09 13:02:25.318  1986  4840 W Sensors : sensorservice died [0xa907fe80]
,08-09 13:02:25.318  1909  1921 W Sensors : sensorservice died [0xad93fa80]
08-09 13:02:25.318  2380  2396 W Sensors : sensorservice died [0xa913fb40]
,08-09 13:02:25.318  1378  1860 W Sensors : sensorservice died [0xad3c8c80]
,08-09 13:02:25.318   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6aa4000
,08-09 13:02:25.318   293   358 I SurfaceFlinger: restart the boot-animation @ binderDied
,08-09 13:02:25.318  1986  2234 E WifiManager: Channel connection lost
,08-09 13:02:25.328  1659  2126 E WifiManager: Channel connection lost
08-09 13:02:25.328   318   958 W AudioFlinger: power manager service died !!!
08-09 13:02:25.328   318   958 W AudioFlinger: power manager service died !!!
,08-09 13:02:25.328  1659  1659 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
,08-09 13:02:25.328   292   292 I ServiceManager: service 'edmnativehelper' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'SEAMService' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'media.camera.proxy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'account' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'content' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'DirEncryptService' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'LSManager' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'ReactiveService' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'DeviceRootKeyService' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'EngineeringModeService' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'SatsService' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'sedenial' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'vibrator' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'tw_toolbox' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'tima' died
08-09 13:02:25.328  1378  1588 E WifiManager: Channel connection lost
08-09 13:02:25.328   292   292 I ServiceManager: service 'iccc' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'cepproxyks' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'emailksproxy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'consumer_ir' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'alarm' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'user' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'procstats' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'meminfo' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'gfxinfo' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'dbinfo' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'cpuinfo' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'permission' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'processinfo' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'sensorservice' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'mdm.remotedesktop' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'battery' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'usagestats' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'webviewupdate' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'scheduling_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'telephony.registry' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'persona' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'enterprise_license_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'application_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'wifi_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'remoteinjection' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'knox_ucsm_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'edm_proxy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'mum_container_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'otp_service' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'enterpr,ise_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'statusbar' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'clipboard' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'clipboardEx' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'persona_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'activity' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'midi' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'mount' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'lock_settings' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'deviceidle' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'device_policy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'harmony_eas_service' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'sdp' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'sdp_log' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'dlp' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'log_manager_service' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'context_aware' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'scontext' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'barbeam' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'multiwindow_facade' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'window' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'input' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'bluetooth_manager' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'rcp' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'input_method' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'accessibility' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'cover' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'telecom' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'notification' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'devicestoragemonitor' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'location' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'country_detector' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'sec_location' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'search' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'execute' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'dropbox' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'wallpaper' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'audio' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'DockObserver' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'usb' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'serial' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'kiesusb' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'jobscheduler' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'backup' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'appwidget' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'voiceinteraction' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'SecExternalDisplayService' died
,08-09 13:02:25.328   292   292 I ServiceManager: service 'diskstats' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'mDNIe' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'AAS' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'MSCS' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'spengestureservice' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'quickconnect' died
,08-09 13:02:25.328   292   292 I ServiceManager: service 'samplingprofiler' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'commontime_management' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'dreams' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'graphicsstats' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'print' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'restrictions' died
,08-09 13:02:25.328   292   292 I ServiceManager: service 'media_session' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'media_router' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'trust' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'fingerprint' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'launcherapps' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'voip' died
,08-09 13:02:25.328   292   292 I ServiceManager: service 'media_projection' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'lpnet' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'imms' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'network_management' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'textservices' died
,08-09 13:02:25.328   292   292 I ServiceManager: service 'network_score' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'netstats' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'netpolicy' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'wifip2p' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'wifi' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'wifihs20' died
,08-09 13:02:25.328   292   292 I ServiceManager: service 'wifiscanner' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'rttmanager' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'ethernet' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'connectivity' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'sb_service' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'servicediscovery' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'updatelock' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'sec_analytics' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'batterystats' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'appops' died
,08-09 13:02:25.328   292   292 I ServiceManager: service 'power' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'display' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'uimode' died
08-09 13:02:25.328   292   292 I ServiceManager: service 'package' died
08-09 13:02:25.328   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-09 13:02:25.338  1783  1894 E WifiManager: Channel connection lost
,08-09 13:02:25.338   293  4616 I SurfaceFlinger: id=17 Removed DolorFade (9/9)
08-09 13:02:25.338   293  4616 I SurfaceFlinger: id=5 Removed TtatusBar (8/8)
08-09 13:02:25.338   293  4616 I SurfaceFlinger: id=17 Removed DolorFade (-2/8)
08-09 13:02:25.338   293   360 I SurfaceFlinger: id=20 Removed VSBConnecti (7/7)
08-09 13:02:25.338   293   360 I SurfaceFlinger: id=21 Removed VSBConnecti (5/6)
08-09 13:02:25.338   293  4616 I SurfaceFlinger: id=5 Removed TtatusBar (-2/6)
08-09 13:02:25.338   293  4616 I SurfaceFlinger: id=7 Removed JmageWallpa (3/5)
,08-09 13:02:25.338   293  4616 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/5)
08-09 13:02:25.338   293  4616 I SurfaceFlinger: id=13 Removed EimLayer(Di (4/4)
08-09 13:02:25.338   293  4616 I SurfaceFlinger: id=14 Removed EimLayer(An (2/3)
08-09 13:02:25.338   293  4616 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/3)
08-09 13:02:25.338   293  4616 I SurfaceFlinger: id=21 Removed VSBConnecti (-2/3)
08-09 13:02:25.338  1674  1686 W Sensors : sensorservice died [0xad3ce200]
08-09 13:02:25.338   293   828 I SurfaceFlinger: id=14 Removed EimLayer(An (-2/3)
,08-09 13:02:25.338   293   828 I SurfaceFlinger: id=2 Removed GocusedStac (2/2)
08-09 13:02:25.338   293   828 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/1)
08-09 13:02:25.338   293   828 I SurfaceFlinger: id=4 Removed EimLayer(An (0/0)
08-09 13:02:25.338   293   828 I SurfaceFlinger: id=13 Removed EimLayer(Di (-2/0)
08-09 13:02:25.338   293   828 I SurfaceFlinger: id=2 Removed GocusedStac (-2/0)
08-09 13:02:25.338   293   828 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/0)
,08-09 13:02:25.338   293   828 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/0)
,08-09 13:02:25.578   291   291 I lowmemorykiller: ActivityManager disconnected
08-09 13:02:25.578   291   291 I lowmemorykiller: Closing Activity Manager data connection
08-09 13:02:25.578   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
08-09 13:02:25.578   293   550 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-09 13:02:25.578   293   696 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
08-09 13:02:25.578   293   696 E SurfaceFlinger: eventControl(0, 1) failed Operation not permitted
,08-09 13:02:25.808   293   550 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-09 13:02:25.828   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-09 13:02:25.828   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee423a4
,08-09 13:02:25.828   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee4238c
,08-09 13:02:25.828   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee4238c
,08-09 13:02:25.838   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee4238c
,08-09 13:02:25.838   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee4238c
,08-09 13:02:25.838   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee4238c
,08-09 13:02:25.838   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee4238c
,08-09 13:02:25.848   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee423a4
,08-09 13:02:25.848   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee423a4

```
