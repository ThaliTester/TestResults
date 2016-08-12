#### Test 797638306af5278_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
08-12 18:22:17.369   756  2454 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,08-12 18:22:17.379   756  2454 V MARsPolicyManager: updateSMDBValues
08-12 18:22:17.379   756   889 E MARsDBManager: updateDBAll : begin --size 0
08-12 18:22:17.379   756   889 E MARsDBManager: updateDBAll : end
--------- beginning of main
08-12 18:22:18.239  5551  5551 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-12 18:22:18.239  5551  5551 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-12 18:22:18.239  5551  5551 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-12 18:22:18.239  5551  5551 I art     : System.exit called, status: 0
08-12 18:22:18.239  5551  5551 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-12 18:22:18.279   756  1415 I ActivityManager: Process com.samsung.aasaservice (pid 5551)(adj 0) has died(114,745)
08-12 18:22:18.279   756  1415 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-12 18:22:18.279   756  1415 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-12 18:22:18.279   756  1415 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-12 18:22:18.289  2380  2380 E audit   : type=1400 msg=audit(1471018938.269:285): avc:  denied  { execmod } for  pid=6501 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 18:22:18.289  2380  2380 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:18.289  2380  2380 E audit   : type=1300 msg=audit(1471018938.269:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f53000 a1=51000 a2=5 a3=4 items=0 ppid=3760 ppcomm=adbd pid=6501 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 18:22:18.289  2380  2380 E audit   : type=1327 msg=audit(1471018938.269:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 18:22:18.289  2380  2380 E audit   : type=1320 msg=audit(1471018938.269:285): 
08-12 18:22:18.299  5518  5518 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-12 18:22:18.299   756   842 I ActivityManager: Start proc 6515:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-12 18:22:18.299   756  1321 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 18:22:18.309  6515  6515 E Zygote  : v2
08-12 18:22:18.309  6515  6515 I libpersona: KNOX_SDCARD checking this for 10014
08-12 18:22:18.309  6515  6515 I libpersona: KNOX_SDCARD not a persona
08-12 18:22:18.309  6515  6515 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:18.309  6515  6515 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:18.309  6515  6515 E Zygote  : accessInfo : 0
08-12 18:22:18.309  6515  6515 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-12 18:22:18.329  2380  2380 E audit   : type=1400 msg=audit(1471018938.329:286): avc:  denied  { execmod } for  pid=6501 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 18:22:18.329  2380  2380 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:18.329  2380  2380 E audit   : type=1300 msg=audit(1471018938.329:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f13000 a1=51000 a2=5 a3=4 items=0 ppid=3760 ppcomm=adbd pid=6501 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 18:22:18.329  2380  2380 E audit   : type=1327 msg=audit(1471018938.329:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 18:22:18.329  2380  2380 E audit   : type=1320 msg=audit(1471018938.329:286): 
08-12 18:22:18.339  6515  6515 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:18.339  6515  6515 D ActivityThread: Added TimaKeyStore provider
08-12 18:22:18.349   756  3876 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3cc1584 6515:com.google.android.partnersetup/u0a14}
08-12 18:22:18.349   756  1321 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-12 18:22:18.359  6515  6515 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-12 18:22:18.369  6515  6515 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-12 18:22:18.369  2380  2380 E audit   : type=1400 msg=audit(1471018938.369:287): avc:  denied  { execmod } for  pid=6501 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 18:22:18.369  2380  2380 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:18.369  2380  2380 E audit   : type=1300 msg=audit(1471018938.369:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f13000 a1=51000 a2=5 a3=4 items=0 ppid=3760 ppcomm=adbd pid=6501 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 18:22:18.369  2380  2380 E audit   : type=1327 msg=audit(1471018938.369:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 18:22:18.369  2380  2380 E audit   : type=1320 msg=audit(1471018938.369:287): 
08-12 18:22:18.369  6501  6501 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 18:22:18.379  6501  6501 D AndroidRuntime: CheckJNI is OFF
08-12 18:22:18.379  6501  6501 D AndroidRuntime: readGMSProperty: start
08-12 18:22:18.379  6501  6501 D AndroidRuntime: readGMSProperty: already setted!!
08-12 18:22:18.379  6501  6501 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 18:22:18.379  6501  6501 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 18:22:18.379  6501  6501 D AndroidRuntime: readGMSProperty: end
08-12 18:22:18.379  6501  6501 D AndroidRuntime: addProductProperty: start
08-12 18:22:18.379  6501  6501 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 18:22:18.379  6501  6501 W art     : af0a5000-b1fcb000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-12 18:22:18.379  6501  6501 W art     : b1fcb000-b423a000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 18:22:18.379  6501  6501 W art     : b423a000-b423b000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-12 18:22:18.379  6501  6501 W art     : b423b000-b4264000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 18:22:18.379  6501  6501 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-12 18:22:18.379  6501  6501 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-12 18:22:18.379  6501  6501 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-12 18:22:18.379  6501  6501 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-12 18:22:18.379  6501  6501 W art     : b47e2000-b47e5000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 18:22:18.379  6501  6501 W art     : b47e5000-b47e6000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-12 18:22:18.379  6501  6501 W art     : b47e6000-b47e7000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-12 18:22:18.379  6501  6501 W art     : b47e7000-b47e8000 r--p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b47e8000-b4808000 r--s 00000000 00:0b 6702       /dev/__properties__
08-12 18:22:18.379  6501  6501 W art     : b4808000-b5219000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 18:22:18.379  6501  6501 W art     : b5219000-b521a000 ---p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b521a000-b5263000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-12 18:22:18.379  6501  6501 W art     : b5263000-b5264000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 18:22:18.379  6501  6501 W art     : b5264000-b526c000 rw-p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b526c000-b526d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.379  6501  6501 W art     : b526d000-b52a2000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 18:22:18.379  6501  6501 W art     : b52a2000-b52a3000 ---p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b52a3000-b52a4000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 18:22:18.379  6501  6501 W art     : b52a4000-b52a5000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 18:22:18.379  6501  6501 W art     : b52a5000-b52fd000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-12 18:22:18.379  6501  6501 W art     : b52fd000-b52fe000 ---p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b52fe000-b52ff000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 18:22:18.379  6501  6501 W art     : b52ff000-b5300000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 18:22:18.379  6501  6501 W art     : b5301000-b5307000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 18:22:18.379  6501  6501 W art     : b5307000-b5308000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 18:22:18.379  6501  6501 W art     : b5308000-b5309000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 18:22:18.379  6501  6501 W art     : b5309000-b530b000 rw-p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b530c000-b5316000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 18:22:18.379  6501  6501 W art     : b5316000-b5319000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 18:22:18.379  6501  6501 W art     : b5319000-b531a000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 18:22:18.379  6501  6501 W art     : b531b000-b5332000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 18:22:18.379  6501  6501 W art     : b5332000-b5333000 ---p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b5333000-b5334000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 18:22:18.379  6501  6501 W art     : b5334000-b5335000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 18:22:18.379  6501  6501 W art     : b5336000-b5340000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 18:22:18.379  6501  6501 W art     : b5340000-b5341000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 18:22:18.379  6501  6501 W art     : b5341000-b5342000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-12 18:22:18.379  6501  6501 W art     : b5342000-b5346000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 18:22:18.379  6501  6501 W art     : b5346000-b5347000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 18:22:18.379  6501  6501 W art     : b5347000-b5348000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 18:22:18.379  6501  6501 W art     : b5348000-b535e000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-12 18:22:18.379  6501  6501 W art     : b535e000-b535f000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 18:22:18.379  6501  6501 W art     : b535f000-b5360000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 18:22:18.379  6501  6501 W art     : b5360000-b536d000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 18:22:18.379  6501  6501 W art     : b536d000-b536e000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 18:22:18.379  6501  6501 W art     : b536e000-b536f000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 18:22:18.379  6501  6501 W art     : b536f000-b53cf000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-12 18:22:18.379  6501  6501 W art     : b53cf000-b53d2000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-12 18:22:18.379  6501  6501 W art     : b53d2000-b53d6000 rw-p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b53d6000-b5437000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 18:22:18.379  6501  6501 W art     : b5437000-b5438000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 18:22:18.379  6501  6501 W art     : b5438000-b5487000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-12 18:22:18.379  6501  6501 W art     : b5487000-b5489000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-12 18:22:18.379  6501  6501 W art     : b5489000-b548a000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 18:22:18.379  6501  6501 W art     : b548a000-b548b000 rw-p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b548b000-b5492000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 18:22:18.379  6501  6501 W art     : b5492000-b5493000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 18:22:18.379  6501  6501 W art     : b5493000-b5494000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 18:22:18.379  6501  6501 W art     : b5495000-b5498000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 18:22:18.379  6501  6501 W art     : b5498000-b5499000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 18:22:18.379  6501  6501 W art     : b5499000-b549a000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 18:22:18.379  6501  6501 W art     : b549b000-b549f000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 18:22:18.379  6501  6501 W art     : b549f000-b54a0000 ---p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b54a0000-b54a1000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-12 18:22:18.379  6501  6501 W art     : b54a1000-b54a2000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-12 18:22:18.379  6501  6501 W art     : b54a3000-b54c0000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 18:22:18.379  6501  6501 W art     : b54c0000-b54c1000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 18:22:18.379  6501  6501 W art     : b54c1000-b54c2000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 18:22:18.379  6501  6501 W art     : b54c3000-b54c8000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 18:22:18.379  6501  6501 W art     : b54c8000-b54c9000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 18:22:18.379  6501  6501 W art     : b54c9000-b54ca000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 18:22:18.379  6501  6501 W art     : b54cb000-b54fc000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 18:22:18.379  6501  6501 W art     : b54fc000-b54ff000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 18:22:18.379  6501  6501 W art     : b54ff000-b5500000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 18:22:18.379  6501  6501 W art     : b5501000-b553c000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 18:22:18.379  6501  6501 W art     : b553c000-b553d000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-12 18:22:18.379  6501  6501 W art     : b553d000-b553e000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 18:22:18.379  6501  6501 W art     : b553f000-b5546000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-12 18:22:18.379  6501  6501 W art     : b5546000-b5547000 ---p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b5547000-b5548000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-12 18:22:18.379  6501  6501 W art     : b5548000-b5549000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 18:22:18.379  6501  6501 W art     : b5549000-b554a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.379  6501  6501 W art     : b554a000-b5561000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 18:22:18.379  6501  6501 W art     : b5561000-b5562000 ---p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b5562000-b5565000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-12 18:22:18.379  6501  6501 W art     : b5565000-b5566000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-12 18:22:18.379  6501  6501 W art     : b5566000-b5585000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-12 18:22:18.379  6501  6501 W art     : b5585000-b5586000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 18:22:18.379  6501  6501 W art     : b5586000-b5587000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-12 18:22:18.379  6501  6501 W art     : b5587000-b55c5000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 18:22:18.379  6501  6501 W art     : b55c5000-b55c6000 ---p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b55c6000-b55c8000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 18:22:18.379  6501  6501 W art     : b55c8000-b55c9000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 18:22:18.379  6501  6501 W art     : b55ca000-b55d1000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 18:22:18.379  6501  6501 W art     : b55d1000-b55d2000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 18:22:18.379  6501  6501 W art     : b55d2000-b55d3000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 18:22:18.379  6501  6501 W art     : b55d4000-b55d7000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 18:22:18.379  6501  6501 W art     : b55d7000-b55d8000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 18:22:18.379  6501  6501 W art     : b55d8000-b55d9000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 18:22:18.379  6501  6501 W art     : b55d9000-b55df000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 18:22:18.379  6501  6501 W art     : b55df000-b55e0000 ---p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b55e0000-b55e1000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 18:22:18.379  6501  6501 W art     : b55e1000-b55e2000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 18:22:18.379  6501  6501 W art     : b55e2000-b55eb000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 18:22:18.379  6501  6501 W art     : b55eb000-b55ec000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 18:22:18.379  6501  6501 W art     : b55ec000-b55ed000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 18:22:18.379  6501  6501 W art     : b55ed000-b567e000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 18:22:18.379  6501  6501 W art     : b567e000-b567f000 ---p 00000000 00:00 0 
08-12 18:22:18.379  6501  6501 W art     : b567f000-b568a000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 18:22:18.379  6501  6501 W art     : b568a000-b568b000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 18:22:18.389  6501  6501 W art     : b568c000-b569e000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 18:22:18.389  6501  6501 W art     : b569e000-b569f000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 18:22:18.389  6501  6501 W art     : b569f000-b56a0000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-12 18:22:18.389  6501  6501 W art     : b56a1000-b56a6000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-12 18:22:18.389  6501  6501 W art     : b56a6000-b56a7000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 18:22:18.389  6501  6501 W art     : b56a7000-b56a8000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 18:22:18.389  6501  6501 W art     : b56a9000-b5716000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-12 18:22:18.389  6501  6501 W art     : b5716000-b5717000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b5717000-b5719000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 18:22:18.389  6501  6501 W art     : b5719000-b571a000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 18:22:18.389  6501  6501 W art     : b571a000-b571b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b571b000-b5722000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 18:22:18.389  6501  6501 W art     : b5722000-b5723000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 18:22:18.389  6501  6501 W art     : b5723000-b5724000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 18:22:18.389  6501  6501 W art     : b5725000-b57a5000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 18:22:18.389  6501  6501 W art     : b57a5000-b57a6000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b57a6000-b57a7000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 18:22:18.389  6501  6501 W art     : b57a7000-b57a8000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 18:22:18.389  6501  6501 W art     : b57a8000-b57bf000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b57bf000-b57f6000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 18:22:18.389  6501  6501 W art     : ib/libqc-opt.so
08-12 18:22:18.389  6501  6501 W art     : b57f6000-b57f7000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 18:22:18.389  6501  6501 W art     : b57f7000-b57f8000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 18:22:18.389  6501  6501 W art     : b57f8000-b5814000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 18:22:18.389  6501  6501 W art     : b5814000-b5815000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 18:22:18.389  6501  6501 W art     : b5815000-b5816000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 18:22:18.389  6501  6501 W art     : b5817000-b5878000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 18:22:18.389  6501  6501 W art     : b5878000-b587a000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 18:22:18.389  6501  6501 W art     : b587a000-b587b000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 18:22:18.389  6501  6501 W art     : b587c000-b58a3000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 18:22:18.389  6501  6501 W art     : b58a3000-b58a4000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b58a4000-b58a5000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-12 18:22:18.389  6501  6501 W art     : b58a5000-b58a6000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 18:22:18.389  6501  6501 W art     : b58a7000-b58af000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 18:22:18.389  6501  6501 W art     : b58af000-b58b1000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 18:22:18.389  6501  6501 W art     : b58b1000-b58b2000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 18:22:18.389  6501  6501 W art     : b58b3000-b58b6000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 18:22:18.389  6501  6501 W art     : b58b6000-b58b7000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 18:22:18.389  6501  6501 W art     : b58b7000-b58b8000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 18:22:18.389  6501  6501 W art     : b58b8000-b58bc000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 18:22:18.389  6501  6501 W art     : b58bc000-b58bd000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b58bd000-b58be000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 18:22:18.389  6501  6501 W art     : b58be000-b58bf000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 18:22:18.389  6501  6501 W art     : b58bf000-b58cf000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-12 18:22:18.389  6501  6501 W art     : b58cf000-b58d0000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 18:22:18.389  6501  6501 W art     : b58d0000-b58d1000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 18:22:18.389  6501  6501 W art     : b58d1000-b5917000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b5917000-b5920000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 18:22:18.389  6501  6501 W art     : b5920000-b5921000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 18:22:18.389  6501  6501 W art     : b5921000-b5922000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-12 18:22:18.389  6501  6501 W art     : b5923000-b5928000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 18:22:18.389  6501  6501 W art     : b5928000-b5929000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 18:22:18.389  6501  6501 W art     : b5929000-b592a000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 18:22:18.389  6501  6501 W art     : b592a000-b592d000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 18:22:18.389  6501  6501 W art     : b592d000-b592e000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b592e000-b592f000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 18:22:18.389  6501  6501 W art     : b592f000-b5930000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 18:22:18.389  6501  6501 W art     : b5931000-b5949000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 18:22:18.389  6501  6501 W art     : b5949000-b594a000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b594a000-b594b000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 18:22:18.389  6501  6501 W art     : b594b000-b594c000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 18:22:18.389  6501  6501 W art     : b594c000-b594d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:22:18.389  6501  6501 W art     : b594d000-b5ae7000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 18:22:18.389  6501  6501 W art     : b5ae7000-b5ae8000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b5ae8000-b5af5000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 18:22:18.389  6501  6501 W art     : b5af5000-b5af6000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 18:22:18.389  6501  6501 W art     : b5af6000-b5afa000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 18:22:18.389  6501  6501 W art     : b5afa000-b5afb000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b5afb000-b5afc000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 18:22:18.389  6501  6501 W art     : b5afc000-b5afd000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-12 18:22:18.389  6501  6501 W art     : b5afd000-b5b10000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 18:22:18.389  6501  6501 W art     : b5b10000-b5b11000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 18:22:18.389  6501  6501 W art     : b5b11000-b5b12000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 18:22:18.389  6501  6501 W art     : b5b13000-b5b5e000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 18:22:18.389  6501  6501 W art     : b5b5e000-b5b5f000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 18:22:18.389  6501  6501 W art     : b5b5f000-b5b60000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 18:22:18.389  6501  6501 W art     : b5b60000-b5b62000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b5b63000-b5b74000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 18:22:18.389  6501  6501 W art     : b5b74000-b5b75000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b5b75000-b5b76000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 18:22:18.389  6501  6501 W art     : b5b76000-b5b77000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 18:22:18.389  6501  6501 W art     : b5b77000-b5b78000 r--p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b5b78000-b5b82000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 18:22:18.389  6501  6501 W art     : b5b82000-b5b84000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 18:22:18.389  6501  6501 W art     : b5b84000-b5b85000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 18:22:18.389  6501  6501 W art     : b5b85000-b5b9e000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 18:22:18.389  6501  6501 W art     : b5b9e000-b5b9f000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 18:22:18.389  6501  6501 W art     : b5b9f000-b5ba2000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 18:22:18.389  6501  6501 W art     : b5ba2000-b5ba6000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b5ba6000-b5c1a000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 18:22:18.389  6501  6501 W art     : b5c1a000-b5c1b000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b5c1b000-b5c1e000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 18:22:18.389  6501  6501 W art     : b5c1e000-b5c1f000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 18:22:18.389  6501  6501 W art     : b5c1f000-b5c20000 r--p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b5c20000-b5c23000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-12 18:22:18.389  6501  6501 W art     : b5c23000-b5c24000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 18:22:18.389  6501  6501 W art     : b5c24000-b5c25000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 18:22:18.389  6501  6501 W art     : b5c25000-b5c26000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b5c26000-b5c2b000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 18:22:18.389  6501  6501 W art     : b5c2b000-b5c2c000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 18:22:18.389  6501  6501 W art     : b5c2c000-b5c2d000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 18:22:18.389  6501  6501 W art     : b5c2d000-b5c2e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b5c2e000-b5c31000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 18:22:18.389  6501  6501 W art     : b5c31000-b5c32000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 18:22:18.389  6501  6501 W art     : b5c32000-b5c33000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 18:22:18.389  6501  6501 W art     : b5c33000-b5c34000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b5c34000-b5c38000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 18:22:18.389  6501  6501 W art     : b5c38000-b5c39000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 18:22:18.389  6501  6501 W art     : b5c39000-b5c3a000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 18:22:18.389  6501  6501 W art     : b5c3a000-b5c3b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:22:18.389  6501  6501 W art     : b5c3b000-b5c3f000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 18:22:18.389  6501  6501 W art     : b5c3f000-b5c40000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 18:22:18.389  6501  6501 W art     : b5c40000-b5c41000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 18:22:18.389  6501  6501 W art     : b5c41000-b5c42000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b5c42000-b5c50000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 18:22:18.389  6501  6501 W art     : b5c50000-b5c51000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b5c51000-b5c52000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 18:22:18.389  6501  6501 W art     : b5c52000-b5c53000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 18:22:18.389  6501  6501 W art     : b5c53000-b5c5d000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 18:22:18.389  6501  6501 W art     : b5c5d000-b5c60000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 18:22:18.389  6501  6501 W art     : b5c60000-b5c61000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 18:22:18.389  6501  6501 W art     : b5c61000-b5c62000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b5c62000-b5c6c000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 18:22:18.389  6501  6501 W art     : b5c6c000-b5c6f000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 18:22:18.389  6501  6501 W art     : b5c6f000-b5c70000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-12 18:22:18.389  6501  6501 W art     : b5c70000-b5c74000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 18:22:18.389  6501  6501 W art     : b5c74000-b5c75000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 18:22:18.389  6501  6501 W art     : b5c75000-b5c76000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 18:22:18.389  6501  6501 W art     : b5c76000-b5c77000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b5c77000-b5c84000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 18:22:18.389  6501  6501 W art     : b5c84000-b5c86000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 18:22:18.389  6501  6501 W art     : b5c86000-b5c87000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 18:22:18.389  6501  6501 W art     : b5c87000-b6099000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 18:22:18.389  6501  6501 W art     : b6099000-b609a000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b609a000-b60a3000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 18:22:18.389  6501  6501 W art     : b60a3000-b60a7000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 18:22:18.409   756  1415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3cc1584 6515:com.google.android.partnersetup/u0a14}
08-12 18:22:18.389  6501  6501 W art     : b60a7000-b60a8000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b60a8000-b60af000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-12 18:22:18.389  6501  6501 W art     : b60af000-b60b0000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 18:22:18.389  6501  6501 W art     : b60b0000-b60b1000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 18:22:18.389  6501  6501 W art     : b60b1000-b60b2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b60b2000-b60cd000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-12 18:22:18.389  6501  6501 W art     : b60cd000-b60ce000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 18:22:18.389  6501  6501 W art     : b60ce000-b60cf000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 18:22:18.389  6501  6501 W art     : b60cf000-b60d0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b60d0000-b611c000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 18:22:18.389  6501  6501 W art     : b611c000-b611d000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b611d000-b611e000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 18:22:18.389  6501  6501 W art     : b611e000-b611f000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 18:22:18.389  6501  6501 W art     : b611f000-b6120000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b6120000-b6124000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 18:22:18.389  6501  6501 W art     : b6124000-b6125000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6125000-b6126000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-12 18:22:18.389  6501  6501 W art     : b6126000-b6127000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-12 18:22:18.389  6501  6501 W art     : b6127000-b615f000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 18:22:18.389  6501  6501 W art     : b615f000-b6160000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 18:22:18.389  6501  6501 W art     : b6160000-b6161000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 18:22:18.389  6501  6501 W art     : b6161000-b6162000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b6162000-b6200000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 18:22:18.389  6501  6501 W art     : b6200000-b6201000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6201000-b621f000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 18:22:18.389  6501  6501 W art     : b621f000-b6220000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-12 18:22:18.389  6501  6501 W art     : b6220000-b6393000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 18:22:18.389  6501  6501 W art     : b6393000-b639e000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 18:22:18.389  6501  6501 W art     : b639e000-b639f000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 18:22:18.389  6501  6501 W art     : b639f000-b64b6000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-12 18:22:18.389  6501  6501 W art     : b64b6000-b64c1000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 18:22:18.389  6501  6501 W art     : b64c1000-b64c2000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 18:22:18.389  6501  6501 W art     : b64c2000-b64c6000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b64c6000-b64ea000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-12 18:22:18.389  6501  6501 W art     : b64ea000-b64ec000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 18:22:18.389  6501  6501 W art     : b64ec000-b64ed000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 18:22:18.389  6501  6501 W art     : b64ed000-b6593000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 18:22:18.389  6501  6501 W art     : b6593000-b65a0000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-12 18:22:18.389  6501  6501 W art     : b65a0000-b65a1000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-12 18:22:18.389  6501  6501 W art     : b65a1000-b65a2000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b65a2000-b65f5000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 18:22:18.389  6501  6501 W art     : b65f5000-b65f6000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b65f6000-b65f7000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 18:22:18.389  6501  6501 W art     : b65f7000-b65f8000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 18:22:18.389  6501  6501 W art     : b65f8000-b65fd000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b65fd000-b660f000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-12 18:22:18.389  6501  6501 W art     : b660f000-b6610000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6610000-b6611000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-12 18:22:18.389  6501  6501 W art     : b6611000-b6612000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 18:22:18.389  6501  6501 W art     : b6612000-b6619000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 18:22:18.389  6501  6501 W art     : b6619000-b661a000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 18:22:18.389  6501  6501 W art     : b661a000-b661b000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 18:22:18.389  6501  6501 W art     : b661b000-b661c000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b661c000-b661f000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 18:22:18.389  6501  6501 W art     : b661f000-b6620000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 18:22:18.389  6501  6501 W art     : b6620000-b6621000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-12 18:22:18.389  6501  6501 W art     : b6621000-b6625000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 18:22:18.389  6501  6501 W art     : b6625000-b6626000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 18:22:18.389  6501  6501 W art     : b6626000-b6627000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 18:22:18.389  6501  6501 W art     : b6627000-b6635000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-12 18:22:18.389  6501  6501 W art     : b6635000-b6636000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6636000-b6637000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 18:22:18.389  6501  6501 W art     : b6637000-b6638000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 18:22:18.389  6501  6501 W art     : b6638000-b6641000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 18:22:18.389  6501  6501 W art     : b6641000-b6642000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 18:22:18.389  6501  6501 W art     : b6642000-b6643000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 18:22:18.389  6501  6501 W art     : b6643000-b66a9000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 18:22:18.389  6501  6501 W art     : b66a9000-b66aa000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b66aa000-b66ac000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 18:22:18.389  6501  6501 W art     : b66ac000-b66b5000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 18:22:18.389  6501  6501 W art     : b66b5000-b66b8000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b66b8000-b674f000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 18:22:18.389  6501  6501 W art     : b674f000-b6751000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-12 18:22:18.389  6501  6501 W art     : b6751000-b6752000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 18:22:18.389  6501  6501 W art     : b6752000-b6753000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6753000-b6a74000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 18:22:18.389  6501  6501 W art     : b6a74000-b6a75000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6a75000-b6a90000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 18:22:18.389  6501  6501 W art     : b6a90000-b6a94000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 18:22:18.389  6501  6501 W art     : b6a94000-b6a99000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6a99000-b6aa1000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 18:22:18.389  6501  6501 W art     : b6aa1000-b6aa2000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 18:22:18.389  6501  6501 W art     : b6aa2000-b6aa3000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 18:22:18.389  6501  6501 W art     : b6aa3000-b6ad1000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 18:22:18.389  6501  6501 W art     : b6ad1000-b6ad2000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6ad2000-b6ad9000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 18:22:18.389  6501  6501 W art     : b6ad9000-b6ada000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-12 18:22:18.389  6501  6501 W art     : b6ada000-b6b20000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 18:22:18.389  6501  6501 W art     : b6b20000-b6b21000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6b21000-b6b24000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 18:22:18.389  6501  6501 W art     : b6b24000-b6b25000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 18:22:18.389  6501  6501 W art     : b6b25000-b6b40000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 18:22:18.389  6501  6501 W art     : b6b40000-b6b44000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 18:22:18.389  6501  6501 W art     : b6b44000-b6b45000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 18:22:18.389  6501  6501 W art     : b6b45000-b6b92000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 18:22:18.389  6501  6501 W art     : b6b92000-b6b93000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6b93000-b6b9f000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-12 18:22:18.389  6501  6501 W art     : b6b9f000-b6ba0000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 18:22:18.389  6501  6501 W art     : b6ba0000-b6bad000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 18:22:18.389  6501  6501 W art     : b6bad000-b6bae000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6bae000-b6baf000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 18:22:18.389  6501  6501 W art     : b6baf000-b6bb0000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 18:22:18.389  6501  6501 W art     : b6bb0000-b6bb8000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 18:22:18.389  6501  6501 W art     : b6bb8000-b6bb9000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6bb9000-b6bba000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 18:22:18.389  6501  6501 W art     : b6bba000-b6bbb000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-12 18:22:18.389  6501  6501 W art     : b6bbb000-b6bc2000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 18:22:18.389  6501  6501 W art     : b6bc2000-b6bc3000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 18:22:18.389  6501  6501 W art     : b6bc3000-b6bc4000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 18:22:18.389  6501  6501 W art     : b6bc4000-b6bd8000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-12 18:22:18.389  6501  6501 W art     : b6bd8000-b6bda000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 18:22:18.389  6501  6501 W art     : b6bda000-b6bdb000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 18:22:18.389  6501  6501 W art     : b6bdb000-b6c03000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 18:22:18.389  6501  6501 W art     : b6c03000-b6c05000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-12 18:22:18.389  6501  6501 W art     : b6c05000-b6c06000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 18:22:18.389  6501  6501 W art     : b6c06000-b6c09000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 18:22:18.389  6501  6501 W art     : b6c09000-b6c0a000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 18:22:18.389  6501  6501 W art     : b6c0a000-b6c0b000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 18:22:18.389  6501  6501 W art     : b6c0b000-b6c14000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-12 18:22:18.389  6501  6501 W art     : b6c14000-b6c15000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 18:22:18.389  6501  6501 W art     : b6c15000-b6c16000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 18:22:18.389  6501  6501 W art     : b6c16000-b6c36000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 18:22:18.389  6501  6501 W art     : b6c36000-b6c37000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 18:22:18.389  6501  6501 W art     : b6c37000-b6c38000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 18:22:18.389  6501  6501 W art     : b6c38000-b6cab000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 18:22:18.389  6501  6501 W art     : b6cab000-b6caf000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 18:22:18.389  6501  6501 W art     : b6caf000-b6cb2000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 18:22:18.389  6501  6501 W art     : b6cb2000-b6cbc000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6cbc000-b6d44000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 18:22:18.389  6501  6501 W art     : b6d44000-b6d45000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6d45000-b6d49000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 18:22:18.389  6501  6501 W art     : b6d49000-b6d4a000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-12 18:22:18.389  6501  6501 W art     : b6d4a000-b6d4b000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6d4b000-b6d74000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 18:22:18.389  6501  6501 W art     : b6d74000-b6d75000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6d75000-b6d78000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-12 18:22:18.389  6501  6501 W art     : b6d78000-b6d79000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 18:22:18.389  6501  6501 W art     : b6d79000-b6e53000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 18:22:18.389  6501  6501 W art     : b6e53000-b6e5a000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 18:22:18.389  6501  6501 W art     : b6e5a000-b6e62000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 18:22:18.389  6501  6501 W art     : b6e62000-b6e63000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6e63000-b6e64000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:22:18.389  6501  6501 W art     : b6e64000-b6e65000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-12 18:22:18.389  6501  6501 W art     : b6e65000-b6e66000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b6e66000-b6e69000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b6e69000-b6e8e000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 18:22:18.389  6501  6501 W art     : b6e8e000-b6e8f000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6e8f000-b6e96000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-12 18:22:18.389  6501  6501 W art     : b6e96000-b6e97000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 18:22:18.389  6501  6501 W art     : b6e97000-b6e9e000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 18:22:18.389  6501  6501 W art     : b6e9e000-b6e9f000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 18:22:18.389  6501  6501 W art     : b6e9f000-b6ea0000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 18:22:18.389  6501  6501 W art     : b6ea0000-b6ea1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b6ea1000-b6eb9000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 18:22:18.389  6501  6501 W art     : b6eb9000-b6eba000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6eba000-b6ebb000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-12 18:22:18.389  6501  6501 W art     : b6ebb000-b6ebc000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 18:22:18.389  6501  6501 W art     : b6ebc000-b6eca000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 18:22:18.389  6501  6501 W art     : b6eca000-b6ecb000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6ecb000-b6ecc000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 18:22:18.389  6501  6501 W art     : b6ecc000-b6ecd000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 18:22:18.389  6501  6501 W art     : b6ecd000-b6ece000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:22:18.389  6501  6501 W art     : b6ece000-b6ed0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b6ed0000-b6ed1000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b6ed1000-b6ed2000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:22:18.389  6501  6501 W art     : b6ed2000-b6ed3000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 18:22:18.389  6501  6501 W art     : b6ed3000-b6ed4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:18.389  6501  6501 W art     : b6ed4000-b6ef4000 r--s 00000000 00:0b 6702       /dev/__properties__
08-12 18:22:18.389  6501  6501 W art     : b6ef4000-b6ef5000 r--p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6ef5000-b6ef6000 ---p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6ef6000-b6ef8000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 18:22:18.389  6501  6501 W art     : b6ef8000-b6ef9000 r-xp 00000000 00:00 0          [sigpage]
08-12 18:22:18.389  6501  6501 W art     : b6ef9000-b6f14000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 18:22:18.389  6501  6501 W art     : b6f14000-b6f15000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 18:22:18.389  6501  6501 W art     : b6f15000-b6f17000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 18:22:18.389  6501  6501 W art     : b6f17000-b6f19000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : b6f19000-b6f1e000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 18:22:18.389  6501  6501 W art     : b6f1e000-b6f1f000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 18:22:18.389  6501  6501 W art     : b6f1f000-b6f20000 rw-p 00000000 00:00 0 
08-12 18:22:18.389  6501  6501 W art     : be7f0000-be811000 rw-p 00000000 00:00 0          [stack]
08-12 18:22:18.389  6501  6501 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-12 18:22:18.429  6501  6501 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 18:22:18.439   756  3876 I ActivityManager: Start proc 6534:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-12 18:22:18.439  6534  6534 E Zygote  : v2
08-12 18:22:18.439  6534  6534 I libpersona: KNOX_SDCARD checking this for 10015
08-12 18:22:18.439  6534  6534 I libpersona: KNOX_SDCARD not a persona
08-12 18:22:18.439  6534  6534 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:18.439  6534  6534 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:18.439  6534  6534 E Zygote  : accessInfo : 0
08-12 18:22:18.439  6534  6534 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-12 18:22:18.459  6534  6534 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:18.459  6534  6534 D ActivityThread: Added TimaKeyStore provider
08-12 18:22:18.469   756  1415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7904e33 6534:com.samsung.groupcast/u0a15}
08-12 18:22:18.479  6534  6534 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-12 18:22:18.479  6501  6501 I Radio-JNI: register_android_hardware_Radio DONE
08-12 18:22:18.479  6501  6501 E AffinityControl: AffinityControl: registerfunction enter
08-12 18:22:18.499  6534  6534 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-12 18:22:18.499  6501  6501 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 18:22:18.519   756  1875 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:18.519  6534  6534 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-12 18:22:18.519  6534  6534 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-12 18:22:18.519  6534  6534 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-12 18:22:18.519  6534  6534 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-12 18:22:18.519  6534  6534 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-12 18:22:18.519  6534  6534 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-12 18:22:18.519  6534  6534 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-12 18:22:18.519  6534  6534 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 18:22:18.519  6534  6534 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 18:22:18.519  6534  6534 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:22:18.519  6534  6534 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 18:22:18.519  6534  6534 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 18:22:18.519  6534  6534 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:22:18.519  6534  6534 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-12 18:22:18.519  6534  6534 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-12 18:22:18.529   756  1875 D ActivityManager: mDVFSHelper.acquire()
08-12 18:22:18.529   756  1875 D FocusedStackFrame: Set to : 0
08-12 18:22:18.529   756  1875 V WindowManager: addAppToken: AppWindowToken{85fe5ee token=Token{f5cd769 ActivityRecord{eb705f0 u0 com.test.thalitest/.MainActivity t167}}} to stack=1 task=167 at 0
08-12 18:22:18.539   756   892 D SecWifiDisplayUtil: Metadata value : none
08-12 18:22:18.539   756   892 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b3ac4c6 V.E...... R.....ID 0,0-0,0}
08-12 18:22:18.539   756   892 D ISSUE_DEBUG: InputChannelName : aa1e7b4 Starting com.test.thalitest
08-12 18:22:18.549  6554  6554 E Zygote  : v2
08-12 18:22:18.549  6554  6554 I libpersona: KNOX_SDCARD checking this for 10004
08-12 18:22:18.549  6554  6554 I libpersona: KNOX_SDCARD not a persona
08-12 18:22:18.549  6554  6554 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:18.549  6554  6554 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:18.549   756  1875 I ActivityManager: Start proc 6554:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-12 18:22:18.549   756  1875 D InputDispatcher: Focused application set to: xxxx
08-12 18:22:18.549  6554  6554 E Zygote  : accessInfo : 0
08-12 18:22:18.549  6554  6554 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-12 18:22:18.549   756  1875 D InputDispatcher: Focus left window: 1669
08-12 18:22:18.549  6501  6501 D AndroidRuntime: Shutting down VM
08-12 18:22:18.559   756  1484 I ActivityManager: Killing 5658:com.sec.android.app.camera/u0a153 (adj 15): DHA:empty #37
08-12 18:22:18.559   756  1484 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b08c5bd 1965:com.sec.android.app.shealth:remote/u0a34}
08-12 18:22:18.559   293   293 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
08-12 18:22:18.579   756   892 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:756 uid:1000
08-12 18:22:18.579   756   892 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 18:22:18.579   756   892 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:756 uid:1000
08-12 18:22:18.579   756   892 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-12 18:22:18.579   756   892 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-12 18:22:18.589  6566  6566 E Zygote  : v2
08-12 18:22:18.589   756  3960 I ActivityManager: Start proc 6566:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-12 18:22:18.589  6566  6566 I libpersona: KNOX_SDCARD checking this for 10041
08-12 18:22:18.589  6566  6566 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:18.589  6566  6566 I libpersona: KNOX_SDCARD not a persona
08-12 18:22:18.589  6566  6566 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:18.589  6566  6566 E Zygote  : accessInfo : 0
08-12 18:22:18.589  6554  6554 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:18.589  6566  6566 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
08-12 18:22:18.589  6554  6554 D ActivityThread: Added TimaKeyStore provider
08-12 18:22:18.599   756   772 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
08-12 18:22:18.599   756  1416 V WindowOrientationListener: setCurrentAppOrientation :-1
08-12 18:22:18.599   756  1416 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=,false displayId=0
08-12 18:22:18.609   756  1416 D ActivityManager:  Launching com.test.thalitest, updated priority
08-12 18:22:18.609   756   892 V WindowStateAnimator: Finishing drawing window Window{aa1e7b4 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-12 18:22:18.609  1669  1877 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-12 18:22:18.609  1669  1669 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-12 18:22:18.619   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbed86364
08-12 18:22:18.639  6566  6566 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:18.639  6566  6566 D ActivityThread: Added TimaKeyStore provider
08-12 18:22:18.639   293   366 D libEGL  : eglTerminate EGLDisplay = 0xb69c164c
08-12 18:22:18.639   293   366 D libEGL  : eglTerminate EGLDisplay = 0xb69c164c
08-12 18:22:18.649   293   366 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-12 18:22:18.649   293  1295 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-12 18:22:18.659  2254  2268 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-12 18:22:18.659  1669  1669 V ActivityThread: updateVisibility : ActivityRecord{bf13dc7 token=android.os.BinderProxy@c257377 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-12 18:22:18.669   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed863a4
08-12 18:22:18.669  1669  1669 D Launcher: onTrimMemory. Level: 20
08-12 18:22:18.669   756   842 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-12 18:22:18.669   756   844 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{aa1e7b4 u0 d0 Starting com.test.thalitest}
08-12 18:22:18.679  1377  1377 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-12 18:22:18.679   756  2004 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c0afdd 6566:com.samsung.android.sdk.samsunglink/u0a41}
08-12 18:22:18.689  6554  6554 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-12 18:22:18.699   756  3614 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-12 18:22:18.709  6554  6554 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-12 18:22:18.719  6554  6554 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-12 18:22:18.719  6566  6566 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-12 18:22:18.729  6554  6554 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
08-12 18:22:18.769  6554  6554 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 18:22:18.769  6554  6554 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-12 18:22:18.779   756  3649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:22:18.779  6554  6554 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 7314-7318)
,08-12 18:22:18.779  6554  6554 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-12 18:22:18.799   756   765 I art     : Background partial concurrent mark sweep GC freed 129356(7MB) AllocSpace objects, 6(1836KB) LOS objects, 27% free, 42MB/58MB, paused 1.793ms total 137.155ms
,08-12 18:22:18.799  6554  6554 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {11c3747}
,08-12 18:22:18.799  6554  6554 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-12 18:22:18.799  6554  6554 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-12 18:22:18.809  6554  6580 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-12 18:22:18.809  6554  6554 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-12 18:22:18.829  6566  6566 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 18:22:18.829  6566  6566 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 18:22:18.839  6554  6554 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 18:22:18.839  6554  6554 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 18:22:18.839  6554  6554 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 18:22:18.839  6554  6554 I Adreno-EGL: Local Branch: ss
08-12 18:22:18.839  6554  6554 I Adreno-EGL: Remote Branch: 
08-12 18:22:18.839  6554  6554 I Adreno-EGL: Local Patches: 
08-12 18:22:18.839  6554  6554 I Adreno-EGL: Reconstruct Branch: 
,08-12 18:22:18.839  6554  6554 D libEGL  : eglInitialize EGLDisplay = 0xbea07dac
,08-12 18:22:18.879   756  3876 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-12 18:22:18.879   756  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-12 18:22:18.919  6554  6554 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-12 18:22:18.919  6566  6566 I SL_DEBUG: isLoggable:: isProductShip = 1
,08-12 18:22:18.919  6566  6566 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,08-12 18:22:18.929  6554  6554 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 18:22:18.929  6554  6554 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-12 18:22:18.929  6554  6554 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-12 18:22:18.929  6554  6554 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-12 18:22:18.939   756   772 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
,08-12 18:22:18.939   756  3960 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
,08-12 18:22:18.939   756  1415 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
,08-12 18:22:18.939   756  1682 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
,08-12 18:22:18.939   756  3961 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
,08-12 18:22:18.949   756  1486 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
,08-12 18:22:18.949   756  3876 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
,08-12 18:22:18.949   756  1416 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
,08-12 18:22:18.949   756  2004 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
,08-12 18:22:18.949   756  1484 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
,08-12 18:22:18.959  6554  6554 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-12 18:22:18.959  6554  6554 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-12 18:22:19.059  6554  6554 D SecWifiDisplayUtil: Metadata value : none
,08-12 18:22:19.069  6554  6554 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{627897d I.E...... R.....ID 0,0-0,0}
,08-12 18:22:19.069  6554  6612 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 18:22:19.079   756  1484 D ISSUE_DEBUG: InputChannelName : 56ecbfe com.test.thalitest/com.test.thalitest.MainActivity
,08-12 18:22:19.079   756   772 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-12 18:22:19.079   756   772 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 18:22:19.079   756   756 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 18:22:19.079   756   756 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-12 18:22:19.089  6566  6566 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
,08-12 18:22:19.099  6566  6566 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-12 18:22:19.099  6566  6566 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-12 18:22:19.099  6566  6566 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-12 18:22:19.099  6566  6566 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-12 18:22:19.099  6566  6566 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-12 18:22:19.099  6566  6566 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-12 18:22:19.099  6566  6566 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-12 18:22:19.099  6566  6566 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 18:22:19.099  6554  6554 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6554
08-12 18:22:19.099  6566  6566 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 18:22:19.099  6566  6566 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:22:19.099  6566  6566 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 18:22:19.099  6566  6566 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 18:22:19.099  6566  6566 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:22:19.099  6566  6566 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-12 18:22:19.099  6566  6566 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-12 18:22:19.099   756  1486 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6554 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 18:22:19.099   756  1330 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-12 18:22:19.099   756  1330 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-12 18:22:19.099   756  1330 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-12 18:22:19.099   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 18:22:19.099   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 18:22:19.099   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-12 18:22:19.099   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 18:22:19.099   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 18:22:19.099   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-12 18:22:19.099   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-12 18:22:19.099   756  1330 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 18:22:19.109   756  1416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c4a442a 1683:android.process.acore/u0a19}
,08-12 18:22:19.109  6554  6580 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-12 18:22:19.109   756  1875 I ActivityManager: Killing 5391:com.android.mms/u0a49 (adj 15): DHA:empty #37
,08-12 18:22:19.129  6554  6554 D SecWifiDisplayUtil: Metadata value : none
,08-12 18:22:19.129   756  1415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{302fed5 5187:com.sec.android.gallery3d/u0a47}
,08-12 18:22:19.139  5187  5187 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-12 18:22:19.149   293   293 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,08-12 18:22:19.159   756   774 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 18:22:19.159   756  1416 D CountryDetector: No listener is left
,08-12 18:22:19.159  6622  6622 E Zygote  : v2
08-12 18:22:19.159  6622  6622 I libpersona: KNOX_SDCARD checking this for 10050
08-12 18:22:19.159  6622  6622 I libpersona: KNOX_SDCARD not a persona
08-12 18:22:19.169  6622  6622 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:19.169  6622  6622 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:19.169   756  1682 D InputDispatcher: Focus entered window: 6554
08-12 18:22:19.169  6622  6622 E Zygote  : accessInfo : 0
08-12 18:22:19.169  6622  6622 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
,08-12 18:22:19.169   756   772 I ActivityManager: Start proc 6622:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
,08-12 18:22:19.169   756   892 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:756 uid:1000
,08-12 18:22:19.169  6554  6612 D libEGL  : eglInitialize EGLDisplay = 0x9ca407c4
08-12 18:22:19.169  6554  6612 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 18:22:19.169   756   892 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-12 18:22:19.169   756   892 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:756 uid:1000
08-12 18:22:19.169   756   892 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 18:22:19.179   756  3960 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
,08-12 18:22:19.199  6622  6622 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:19.199  6622  6622 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:19.209   756  1415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{95c22b0 6622:com.sec.android.app.myfiles/u0a50}
,08-12 18:22:19.219   756   774 I ActivityManager: Killing 5673:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
,08-12 18:22:19.219  6622  6622 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
,08-12 18:22:19.219  6554  6554 V ActivityThread: updateVisibility : ActivityRecord{4e7996c token=android.os.BinderProxy@69ba3d4 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-12 18:22:19.229  6554  6554 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 18:22:19.229  6622  6622 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
,08-12 18:22:19.239   756  1674 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
,08-12 18:22:19.249   756  1484 V WindowStateAnimator: Finishing drawing window Window{56ecbfe u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-12 18:22:19.249  6554  6554 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-12 18:22:19.249  6554  6554 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-12 18:22:19.249   756   772 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-12 18:22:19.249   756   892 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-12 18:22:19.259   756   756 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 18:22:19.259   756   756 I KnoxTimeoutHandler: SD activityfalse
,08-12 18:22:19.259   756   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +586ms (total +719ms)
,08-12 18:22:19.259   756   892 D ActivityManager: mDVFSHelper.release()
,08-12 18:22:19.259   756   892 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{eb705f0 u0 com.test.thalitest/.MainActivity t167} time:97798
,08-12 18:22:19.259   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbed86364
,08-12 18:22:19.269  6554  6554 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-12 18:22:19.269   756   892 D ViewRootImpl: #3 mView = null
,08-12 18:22:19.269  6554  6639 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-12 18:22:19.269   293  1294 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
,08-12 18:22:19.269   293   368 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
,08-12 18:22:19.279  6554  6639 D libEGL  : eglInitialize EGLDisplay = 0x9b1ac3ec
,08-12 18:22:19.279   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed863a4
,08-12 18:22:19.279   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbed86364
,08-12 18:22:19.289   756  1484 V WindowStateAnimator: Finishing drawing window Window{56ecbfe u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-12 18:22:19.289  6644  6644 E Zygote  : v2
,08-12 18:22:19.299  6644  6644 I libpersona: KNOX_SDCARD checking this for 10210
08-12 18:22:19.299  6644  6644 I libpersona: KNOX_SDCARD not a persona
08-12 18:22:19.299   756   842 I ActivityManager: Start proc 6644:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
,08-12 18:22:19.299  6644  6644 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:19.299  6644  6644 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:19.299  6644  6644 E Zygote  : accessInfo : 0
,08-12 18:22:19.299  6644  6644 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,08-12 18:22:19.299  6554  6554 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@69ba3d4 time:97835
,08-12 18:22:19.319  6622  6622 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-12 18:22:19.329  6644  6644 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:19.329  6644  6644 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:19.339  6554  6554 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6554
,08-12 18:22:19.339   756  1416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e076f66 5045:com.android.settings/1000}
,08-12 18:22:19.349   335   335 E installd: system dir 0 : /system/app/
08-12 18:22:19.349   335   335 E installd: system dir 1 : /system/priv-app/
08-12 18:22:19.349   335   335 E installd: system dir 2 : /vendor/app/
08-12 18:22:19.349   335   335 E installd: system dir 3 : /oem/app/
,08-12 18:22:19.349  6644  6644 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,08-12 18:22:19.359   756   917 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,08-12 18:22:19.369  6644  6644 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,08-12 18:22:19.369   756  3876 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e076f66 5045:com.android.settings/1000}
,08-12 18:22:19.369  6644  6644 D AASAservice: onCreate()
,08-12 18:22:19.379  5518  5518 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,08-12 18:22:19.389  6659  6659 E Zygote  : v2
08-12 18:22:19.389  6659  6659 I libpersona: KNOX_SDCARD checking this for 10169
08-12 18:22:19.389  6659  6659 I libpersona: KNOX_SDCARD not a persona
,08-12 18:22:19.389  6659  6659 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 18:22:19.389  6659  6659 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:19.399  6659  6659 E Zygote  : accessInfo : 0
,08-12 18:22:19.399  6659  6659 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,08-12 18:22:19.399   756   772 I ActivityManager: Start proc 6659:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,08-12 18:22:19.399   756   772 I ActivityManager: Killing 5692:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
,08-12 18:22:19.419  6659  6659 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:19.419  6659  6659 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:19.429   756  3961 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3105ae5 6659:com.samsung.android.provider.shootingmodeprovider/u0a169}
,08-12 18:22:19.429   756  1415 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-12 18:22:19.429  6554  6554 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 18:22:19.439  6659  6659 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
,08-12 18:22:19.449  6659  6659 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
,08-12 18:22:19.469   756  1484 I ActivityManager: Killing 5244:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-12 18:22:19.469   756  1484 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{19c0f26 1654:com.android.phone/1001}
,08-12 18:22:19.479   756   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c08737f 1783:com.google.android.googlequicksearchbox:search/u0a61}
,08-12 18:22:19.489   756  3960 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c08737f 1783:com.google.android.googlequicksearchbox:search/u0a61}
,08-12 18:22:19.499   756  1415 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-12 18:22:19.509   756  1875 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b29206b 6451:com.samsung.android.sm.provider/1000}
,08-12 18:22:19.519  6674  6674 E Zygote  : v2
08-12 18:22:19.519  6674  6674 I libpersona: KNOX_SDCARD checking this for 5012
08-12 18:22:19.519  6674  6674 I libpersona: KNOX_SDCARD not a persona
,08-12 18:22:19.519   756  2004 I ActivityManager: Start proc 6674:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
08-12 18:22:19.519  6674  6674 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:19.519  6674  6674 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:19.519  6674  6674 E Zygote  : accessInfo : 0
08-12 18:22:19.519  6674  6674 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
,08-12 18:22:19.529  1783  6672 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-12 18:22:19.559  6674  6674 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:22:19.559  6674  6674 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:19.579   756   772 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{62597c8 6674:com.samsung.android.sm.devicesecurity/5012}
,08-12 18:22:19.589  6674  6674 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
,08-12 18:22:19.609  6674  6674 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
,08-12 18:22:19.619  6554  6686 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1709655760
,08-12 18:22:19.619  6554  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 18:22:19.619  6554  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 18:22:19.619  6554  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 18:22:19.619  6554  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 18:22:19.619  6554  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 18:22:19.619  6554  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f13a22 added. We now have 1 listener(s)
,08-12 18:22:19.629  6554  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-12 18:22:19.629  6554  6686 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-12 18:22:19.629  6554  6686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 18:22:19.629  6554  6686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 18:22:19.629  6554  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8dd39e9 added. We now have 1 listener(s)
08-12 18:22:19.629  6554  6686 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 18:22:19.639  6554  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 18:22:19.639  6554  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-12 18:22:19.639  6554  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 18:22:19.639  6554  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 18:22:19.639  6554  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 18:22:19.639  6554  6686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 18:22:19.639  6554  6686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-12 18:22:19.649  6554  6686 D BluetoothAdapter: STATE_ON
,08-12 18:22:19.649  1783  6672 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-12 18:22:19.649  6554  6686 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 18:22:19.649  6554  6686 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:22:19.649  6554  6686 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:22:19.649  6554  6686 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 18:22:19.649  6554  6686 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:22:19.649  6554  6686 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:22:19.649  6554  6686 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:22:19.649  6554  6686 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:22:19.649  6554  6686 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 18:22:19.649  6554  6686 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 18:22:19.649  6554  6686 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 18:22:19.649  6554  6686 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 18:22:19.649  6554  6554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 18:22:19.649  6554  6554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 18:22:19.679   756  1416 I ActivityManager: Killing 5230:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-12 18:22:19.679  6554  6554 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 18:22:19.679   756  1416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{52bb57c 3190:com.android.contacts/u0a19}
,08-12 18:22:19.689  1783  6672 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-12 18:22:19.689   756  3617 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-12 18:22:19.699  6688  6688 E Zygote  : v2
08-12 18:22:19.699  6688  6688 I libpersona: KNOX_SDCARD checking this for 10049
08-12 18:22:19.699  6688  6688 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:19.699  6688  6688 I libpersona: KNOX_SDCARD not a persona
08-12 18:22:19.699  6688  6688 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:19.699  6688  6688 E Zygote  : accessInfo : 0
08-12 18:22:19.699  6688  6688 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
,08-12 18:22:19.699   756  1416 I ActivityManager: Start proc 6688:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
,08-12 18:22:19.729  6688  6688 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:22:19.729  6688  6688 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:19.739   756  1486 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{20731e3 6688:com.android.mms/u0a49}
,08-12 18:22:19.749  6688  6688 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 18:22:19.749   756  1415 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-12 18:22:19.769  6688  6688 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-12 18:22:19.769  6688  6688 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-12 18:22:19.789  6688  6688 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-12 18:22:19.799  6688  6700 D Mms/ArtClassLoader: init before art first
,08-12 18:22:19.809  6688  6688 D Mms/TelephonyPermission: start operation mode monitor
,08-12 18:22:19.809  6688  6688 D Mms/TelephonyPermission: User ID is null set current User Id
,08-12 18:22:19.819  6688  6702 D Mms/ArtClassLoader: init before art third
,08-12 18:22:19.819  6688  6688 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 18:22:19.829  6688  6688 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-12 18:22:19.829  6688  6701 D Mms/ArtClassLoader: init before art second
,08-12 18:22:19.829  6688  6702 D Mms/ArtClassLoader: init [DONE] art
,08-12 18:22:19.849  6688  6688 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-12 18:22:19.849  6688  6688 D Mms/TelephonyPermission: isDefault true
,08-12 18:22:19.849  6688  6688 D Mms/MmsApp: onCreate() com.android.mms
,08-12 18:22:19.869  1783  6672 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 346 ms] updated apps [took 346 ms] 
,08-12 18:22:19.879  6688  6688 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-12 18:22:19.889  6688  6688 D Mms/MmsApp: [start]    initCountryIso consume time = 100.780155
,08-12 18:22:19.889   756  1486 D CountryDetector: The first listener is added
,08-12 18:22:19.899  6688  6688 D Mms/MmsApp: [end]    initCountryIso consume time = 7.366667
08-12 18:22:19.899  6688  6688 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.092969
,08-12 18:22:19.909  6688  6688 D Mms/MmsConfig: before partial update
,08-12 18:22:19.959  6688  6700 D Mms/ArtClassLoader: init [DONE] art
,08-12 18:22:19.969  6688  6688 D Mms/MmsConfig: Load Resize quality : 80
,08-12 18:22:19.969  6688  6688 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 18:22:19.969  6688  6688 D EasySignUpManager_1.0.5: isAuth is false
08-12 18:22:19.969  6688  6688 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-12 18:22:19.969  6688  6688 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-12 18:22:19.969  6688  6688 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-12 18:22:19.969  6688  6688 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 18:22:19.969  6688  6688 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-12 18:22:19.969  6688  6688 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-12 18:22:19.969  6688  6688 D EasySignUpManager_1.0.5: isAuth is false
,08-12 18:22:19.969  6688  6688 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-12 18:22:19.969  6688  6688 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-12 18:22:19.989  1654  1667 D TP/MmsSmsProvider: query, match:2117, calling pid = 6688, accessRestricted = false
,08-12 18:22:19.989  1654  1667 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.201 ms
,08-12 18:22:19.989  6688  6688 E CscParser: mps_code.dat does not exist
,08-12 18:22:19.989  6688  6688 E CscParser: customer_path =/system/csc/customer.xml
08-12 18:22:19.989  6688  6688 E CscParser: fileName + /system/csc/customer.xml
,08-12 18:22:19.999  6688  6688 E CscParser: mps_code.dat does not exist
,08-12 18:22:19.999  6688  6688 E CscParser: customer_path =/system/csc/customer.xml
08-12 18:22:19.999  6688  6688 E CscParser: fileName + /system/csc/customer.xml
,08-12 18:22:19.999  6688  6701 D Mms/ArtClassLoader: init [DONE] art
,08-12 18:22:20.009  6688  6688 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-12 18:22:20.009  6688  6688 D Mms/MmsConfig:  enable multiwindow = true
,08-12 18:22:20.009  6688  6688 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-12 18:22:20.009  6688  6688 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-12 18:22:20.009  6688  6688 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-12 18:22:20.009  6688  6688 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-12 18:22:20.009  6688  6688 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-12 18:22:20.009  6688  6688 E Mms/MessageUtils: setCountryDetector : update country detector info 
,08-12 18:22:20.009  6688  6688 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-12 18:22:20.019  6688  6688 D Mms/MmsConfig: [end]    init() consume time = 119.347343
,08-12 18:22:20.019  6688  6688 D Mms/Contact: [start]    init() consume time = 3.624115
,08-12 18:22:20.029  1654  1931 D TP/MmsSmsProvider: query, match:13, calling pid = 6688, accessRestricted = false
,08-12 18:22:20.029  1654  1931 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.245 ms
,08-12 18:22:20.029  6688  6688 D Mms/Contact: [end]    init consume time = 14.059895
,08-12 18:22:20.039  6688  6709 D Mms/DraftCache: [start]    rebuildCache consume time = 1.634324
,08-12 18:22:20.039  6688  6688 D Mms:transaction: roaming -> false (slotId = 0)
,08-12 18:22:20.039  6688  6688 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-12 18:22:20.039  6688  6688 D Mms:transaction: auto download without roaming -> true
08-12 18:22:20.039  6688  6688 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-12 18:22:20.039  6688  6688 D Mms:transaction: roaming -> false (slotId = 1)
,08-12 18:22:20.039  6688  6688 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-12 18:22:20.039  6688  6688 D Mms:transaction: auto download without roaming -> true
08-12 18:22:20.039  6688  6688 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-12 18:22:20.039  6688  6688 D Mms:transaction: auto download during roaming secondary -> false
08-12 18:22:20.039  6688  6688 D Mms:transaction: mAutoDownload ------> true
,08-12 18:22:20.049  1654  1668 D TP/MmsSmsProvider: query, match:12, calling pid = 6688, accessRestricted = false
,08-12 18:22:20.049  1654  1668 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.212 ms
,08-12 18:22:20.049  6688  6709 D Mms/DraftCache: [end]    rebuildCache consume time = 13.716979
,08-12 18:22:20.059  6688  6688 D ComposerPerformance: 1471018940069 ms / [DONE] Composer constructor
,08-12 18:22:20.059  6688  6688 D CII     : Log Level [5]
,08-12 18:22:20.059  6688  6688 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
08-12 18:22:20.069  6688  6710 D Mms/Conversation: [start]    init() consume time = 15.665469
,08-12 18:22:20.069  6688  6688 I Mms/ReservationManager: ReservationManager()
,08-12 18:22:20.069  1654  1931 D TP/MmsSmsProvider: delete, match:1, calling pid = 6688
08-12 18:22:20.069  1654  1931 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-12 18:22:20.069  1654  1931 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
08-12 18:22:20.069  6688  6688 I Mms/ReservationManager: resetAfterConnected()
,08-12 18:22:20.069  1654  1931 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-12 18:22:20.069  1654  1931 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-12 18:22:20.069  1654  1931 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-12 18:22:20.069  1654  1929 D TP/MmsSmsProvider: query, match:7, calling pid = 6688, accessRestricted = false
,08-12 18:22:20.079  1654  1929 D TP/MmsSmsProvider: query, match 7:Elapsed time : 1.487 ms
,08-12 18:22:20.079  1654  1931 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-12 18:22:20.079  1456  1456 D Recents : onTaskStackChanged
,08-12 18:22:20.089  1654  1931 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
,08-12 18:22:20.089  1654  1931 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-12 18:22:20.089  1654  1931 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-12 18:22:20.089  1654  1931 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 11.679 ms
08-12 18:22:20.089  1654  1931 D TP/MmsSmsProvider: need read changed broadcast:false
,08-12 18:22:20.089  6688  6710 D Mms/Conversation: [end]    init consume time = 21.72052
,08-12 18:22:20.089  6688  6688 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-12 18:22:20.089  6688  6688 D Mms/MmsApp: [end]    onCreate() consume time = 4.386302
,08-12 18:22:20.089  6688  6688 D Mms/MmsApp: [end]    onCreate() consume time = 0.244948
,08-12 18:22:20.089  1456  1456 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-12 18:22:20.089  6688  6710 D Mms/MessagingNotification: [start]    init() consume time = 2.843958
,08-12 18:22:20.099  6688  6710 D Mms/MessagingNotification: [end]    init consume time = 8.841615
,08-12 18:22:20.109  6688  6712 D Mms/Synchronizer: [start]    doSync consume time = 5.152188
,08-12 18:22:20.109  6688  6711 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.189947
,08-12 18:22:20.109  6688  6688 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-12 18:22:20.109  1654  1667 D TP/MmsSmsProvider: query, match:0, calling pid = 6688, accessRestricted = false
,08-12 18:22:20.109  1654  1667 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-12 18:22:20.119  6688  6688 D Mms:transaction: roaming ------> false, mSimSlot = 0
,08-12 18:22:20.119  1654  1667 D TP/MmsSmsProvider: query, match 0:Elapsed time : 2.951 ms
,08-12 18:22:20.119  6713  6713 E Zygote  : v2
08-12 18:22:20.119  6713  6713 I libpersona: KNOX_SDCARD checking this for 1000
08-12 18:22:20.119  6713  6713 I libpersona: KNOX_SDCARD not a persona
,08-12 18:22:20.119  6713  6713 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:20.119  6713  6713 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:20.119  6713  6713 E Zygote  : accessInfo : 0
,08-12 18:22:20.119   756  1484 I ActivityManager: Start proc 6713:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-12 18:22:20.129  6688  6688 D Mms:transaction: roaming -> false (slotId = 0)
08-12 18:22:20.129  6688  6688 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-12 18:22:20.129  6688  6688 D Mms:transaction: auto download without roaming -> true
08-12 18:22:20.129  6688  6688 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-12 18:22:20.129  6688  6688 D Mms:transaction: mAutoDownload ------> true
,08-12 18:22:20.149  6295  6308 D BadgeProvider: query, [selection] : package=?
,08-12 18:22:20.149  1654  1931 D TP/MmsSmsProvider: update, match:300, calling pid = 6688
08-12 18:22:20.149  1654  1931 V TP/MmsSmsProvider: syncDBData start
,08-12 18:22:20.149  1654  1931 V TP/MmsSmsProvider: syncDBData sms end
,08-12 18:22:20.149  1654  1931 V TP/MmsSmsProvider: syncDBData mms end
,08-12 18:22:20.149  1654  1931 V TP/MmsSmsProvider: syncDBData end
08-12 18:22:20.149  1654  1931 D TP/MmsSmsProvider: update, match 300:Elapsed time : 1.626 ms
,08-12 18:22:20.149  1654  1668 D TP/MmsSmsProvider: query, match:400, calling pid = 6688, accessRestricted = false
,08-12 18:22:20.149  6713  6713 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:20.149  6713  6713 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:20.159   756  3960 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{967dc09 6713:com.samsung.android.bbc.bbcagent/1000}
,08-12 18:22:20.159  6688  6712 D Mms/Synchronizer: [end]    doSync consume time = 51.11125
,08-12 18:22:20.159  6688  6710 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-12 18:22:20.169  6688  6711 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 9.200105
,08-12 18:22:20.169  1654  1929 D TP/SmsProvider: query,matched:26, calling pid = 6688
,08-12 18:22:20.169  1654  1929 D TP/SmsProvider: query, match 26:Elapsed time : 0.892 ms
,08-12 18:22:20.179  6713  6713 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-12 18:22:20.179  1654  1668 D TP/MmsSmsProvider: query, match:6, calling pid = 6688, accessRestricted = false
,08-12 18:22:20.189  1654  1668 D TP/MmsSmsProvider: query, match 6:Elapsed time : 2.245 ms
,08-12 18:22:20.199  6713  6713 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-12 18:22:20.209  6725  6725 E Zygote  : v2
08-12 18:22:20.209  6725  6725 I libpersona: KNOX_SDCARD checking this for 10024
08-12 18:22:20.209  6725  6725 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:20.209  6725  6725 I libpersona: KNOX_SDCARD not a persona
08-12 18:22:20.209  6725  6725 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:20.209   756  3961 I ActivityManager: Start proc 6725:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-12 18:22:20.209  6725  6725 E Zygote  : accessInfo : 0
08-12 18:22:20.209  6725  6725 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-12 18:22:20.239  6725  6725 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:20.239  6725  6725 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:20.249   756  1486 I ActivityManager: Start proc 6737:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-12 18:22:20.249  6737  6737 E Zygote  : v2
08-12 18:22:20.249  6737  6737 I libpersona: KNOX_SDCARD checking this for 10097
08-12 18:22:20.249  6737  6737 I libpersona: KNOX_SDCARD not a persona
,08-12 18:22:20.249  6737  6737 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:20.249  6737  6737 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:20.249   756  1486 I ActivityManager: Killing 5276:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-12 18:22:20.249  6737  6737 E Zygote  : accessInfo : 0
08-12 18:22:20.249  6737  6737 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-12 18:22:20.259   756   774 I ActivityManager: Killing 4754:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-12 18:22:20.269  6725  6725 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-12 18:22:20.279   756  1674 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-12 18:22:20.289  6737  6737 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:20.289  6737  6737 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:20.289   756  1695 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-12 18:22:20.299   756  1682 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e399e0e 6737:com.google.android.apps.docs/u0a97}
,08-12 18:22:20.309  6737  6737 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 18:22:20.319  6725  6725 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-12 18:22:20.329  6737  6737 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-12 18:22:20.359  6725  6725 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-12 18:22:20.369  6688  6710 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-12 18:22:20.399  6554  6687 W jxcore-log: Initializing JXcore engine
,08-12 18:22:20.399  6554  6687 W jxcore-log: JXcore engine is ready
,08-12 18:22:20.409  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-12 18:22:20.409  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-12 18:22:20.419  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-12 18:22:20.419  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-12 18:22:20.419  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-12 18:22:20.419  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-12 18:22:20.419  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-12 18:22:20.419  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-12 18:22:20.429  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-12 18:22:20.429  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-12 18:22:20.429  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-12 18:22:20.429  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-12 18:22:20.429  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-12 18:22:20.469  2380  2380 E audit   : type=1400 msg=audit(1471018940.469:288): avc:  denied  { ioctl } for  pid=6687 comm="Thread-907" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 18:22:20.469  2380  2380 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:20.469  2380  2380 E audit   : type=1300 msg=audit(1471018940.469:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9a0863c8 items=0 ppid=356 ppcomm=main pid=6687 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-907" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 18:22:20.469  2380  2380 E audit   : type=1327 msg=audit(1471018940.469:288): proctitle="com.test.thalitest"
08-12 18:22:20.469  2380  2380 E audit   : type=1320 msg=audit(1471018940.469:288): 
,08-12 18:22:20.469  2380  2380 E audit   : type=1400 msg=audit(1471018940.469:289): avc:  denied  { ioctl } for  pid=6687 comm="Thread-907" path="socket:[39732]" dev="sockfs" ino=39732 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 18:22:20.469  2380  2380 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:20.469  2380  2380 E audit   : type=1300 msg=audit(1471018940.469:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9a0863c8 items=0 ppid=356 ppcomm=main pid=6687 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-907" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 18:22:20.469  2380  2380 E audit   : type=1327 msg=audit(1471018940.469:289): proctitle="com.test.thalitest"
08-12 18:22:20.469  2380  2380 E audit   : type=1320 msg=audit(1471018940.469:289): 
,08-12 18:22:20.479  6554  6687 W jxcore-log: Starting JXcore engine
,08-12 18:22:20.569  6554  6687 W jxcore-log: Platform android
08-12 18:22:20.569  6554  6687 W jxcore-log: 
08-12 18:22:20.569  6554  6687 W jxcore-log: Process ARCH arm
08-12 18:22:20.569  6554  6687 W jxcore-log: 
,08-12 18:22:20.669   756  3614 D SSRM:n  : SIOP:: AP = 490, PST = 456, CUR = 450, LCD = 0
,08-12 18:22:20.709  6737  6751 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-12 18:22:20.709  6737  6751 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-12 18:22:20.709  6737  6751 I GAv4    :   adb logcat -s GAv4
,08-12 18:22:20.729  6737  6751 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 18:22:20.739   756   772 V AlarmManager:  remove PendingIntent] PendingIntent{5f58d1a: PendingIntentRecord{6a7304b com.google.android.apps.docs broadcastIntent}}
,08-12 18:22:20.739  6737  6751 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-12 18:22:20.739  6737  6751 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-12 18:22:20.759  6737  6757 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-12 18:22:20.759  6554  6687 I jxcore-log: JXcore Cordova bridge is ready!
08-12 18:22:20.759  6554  6687 I jxcore-log: 
,08-12 18:22:20.759  6554  6687 W jxcore-log: JXcore engine is started
,08-12 18:22:20.759  6554  6686 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 18:22:20.769  6554  6554 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 18:22:20.839  6737  6737 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-12 18:22:20.849  4500  5094 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-12 18:22:20.849  6737  6737 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-12 18:22:20.849  6737  6751 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,08-12 18:22:20.849  6737  6751 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-12 18:22:20.849  6737  6751 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-12 18:22:20.849  6737  6751 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-12 18:22:20.919  4500  5094 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-12 18:22:20.929  6764  6764 E Zygote  : v2
08-12 18:22:20.929  6764  6764 I libpersona: KNOX_SDCARD checking this for 10098
08-12 18:22:20.929  6764  6764 I libpersona: KNOX_SDCARD not a persona
08-12 18:22:20.929  6764  6764 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:20.929  6764  6764 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:20.929   756  1415 I ActivityManager: Start proc 6764:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
08-12 18:22:20.929  6764  6764 E Zygote  : accessInfo : 0
,08-12 18:22:20.929  6764  6764 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
08-12 18:22:20.929   756  1415 I ActivityManager: Killing 5151:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-12 18:22:20.969  6764  6764 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:20.969  6764  6764 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:20.979   756  1695 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-12 18:22:20.989   756  1415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4368627 6764:com.sec.android.automotive.drivelink/u0a98}
,08-12 18:22:20.999  6764  6764 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-12 18:22:21.019   756  6431 I HarmonyEASService: Updating for all 1
,08-12 18:22:21.029  6764  6764 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-12 18:22:21.049  4500  5094 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-12 18:22:21.059  6764  6764 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-12 18:22:21.069  1979  1979 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-12 18:22:21.069  1979  1979 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-12 18:22:21.079   756  1486 V AlarmManager:  remove PendingIntent] PendingIntent{17b5dc3: PendingIntentRecord{fea8640 com.sec.android.automotive.drivelink broadcastIntent}}
08-12 18:22:21.079  6764  6780 I GMPM    : App measurement is starting up
08-12 18:22:21.079  6764  6764 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
08-12 18:22:21.089  6764  6780 E GMPM    : getGoogleAppId failed with status: 10
08-12 18:22:21.089  6764  6780 E GMPM    : Uploading is not possible. App measurement disabled
08-12 18:22:21.089   756  1486 V AlarmManager:  remove PendingIntent] PendingIntent{142d979: PendingIntentRecord{fea8640 com.sec.android.automotive.drivelink broadcastIntent}}
08-12 18:22:21.099  1979  1979 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 18:22:21.109  6764  6764 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-12 18:22:21.109  6764  6764 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-12 18:22:21.159  6786  6786 E Zygote  : v2
08-12 18:22:21.159  6786  6786 I libpersona: KNOX_SDCARD checking this for 10032
08-12 18:22:21.159  6786  6786 I libpersona: KNOX_SDCARD not a persona
,08-12 18:22:21.159   756  1416 I ActivityManager: Start proc 6786:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
08-12 18:22:21.159  6786  6786 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:21.159  6786  6786 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:21.159   756  1321 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 18:22:21.159  6786  6786 E Zygote  : accessInfo : 0
,08-12 18:22:21.159  6786  6786 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-12 18:22:21.159  6737  6752 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-12 18:22:21.179  6786  6786 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:21.179  6786  6786 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:21.189   756  1321 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-12 18:22:21.199  6786  6786 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-12 18:22:21.209  6786  6786 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
08-12 18:22:21.209  6737  6752 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-12 18:22:21.229  6737  6752 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-12 18:22:21.229  6737  6752 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-12 18:22:21.239  6737  6752 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-12 18:22:21.269  6737  6752 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-12 18:22:21.289  6764  6764 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-12 18:22:21.289  6764  6764 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-12 18:22:21.299  6764  6764 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-12 18:22:21.309  6764  6764 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDFri Aug 12 18:22:21 GMT+02:00 2016
,08-12 18:22:21.319  6786  6786 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-12 18:22:21.329  6800  6800 E Zygote  : v2
,08-12 18:22:21.329  6800  6800 I libpersona: KNOX_SDCARD checking this for 1000
08-12 18:22:21.329  6800  6800 I libpersona: KNOX_SDCARD not a persona
,08-12 18:22:21.329  6800  6800 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:21.329   756  1682 I ActivityManager: Start proc 6800:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-12 18:22:21.329  6800  6800 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:21.329   756  1682 I ActivityManager: Killing 5928:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-12 18:22:21.329  6800  6800 E Zygote  : accessInfo : 0
,08-12 18:22:21.329   756  1682 I ActivityManager: Killing 5837:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,08-12 18:22:21.339   756  2004 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-12 18:22:21.349  6764  6764 D DialogFlow: initQueue()
,08-12 18:22:21.359   756  3876 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-12 18:22:21.359  6800  6800 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:21.359  6800  6800 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:21.369   756  1695 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d7c7704 6800:com.samsung.android.app.filterinstaller/1000}
,08-12 18:22:21.369  6786  6786 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-12 18:22:21.379  6800  6800 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-12 18:22:21.389  6800  6800 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-12 18:22:21.389  6800  6800 E FilterPackageIntentReceiver: This package is not a effect filter
,08-12 18:22:21.399  6816  6816 E Zygote  : v2
08-12 18:22:21.399  6816  6816 I libpersona: KNOX_SDCARD checking this for 1000
08-12 18:22:21.399  6816  6816 I libpersona: KNOX_SDCARD not a persona
,08-12 18:22:21.399  6816  6816 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:21.399   756  1875 I ActivityManager: Start proc 6816:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
08-12 18:22:21.399  6816  6816 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:21.409  6816  6816 E Zygote  : accessInfo : 0
,08-12 18:22:21.409   756  1875 I ActivityManager: Killing 6019:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,08-12 18:22:21.429   756   774 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-12 18:22:21.449  6816  6816 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:22:21.449  6816  6816 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:21.459   756   765 I art     : Background partial concurrent mark sweep GC freed 21703(1493KB) AllocSpace objects, 6(120KB) LOS objects, 27% free, 41MB/57MB, paused 1.591ms total 107.793ms
,08-12 18:22:21.459   756  1695 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5a14ed 6816:com.samsung.helphub/1000}
,08-12 18:22:21.469  6816  6816 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-12 18:22:21.479   756  1875 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-12 18:22:21.479  6816  6816 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-12 18:22:21.499  6786  6786 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-12 18:22:21.499  6786  6786 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-12 18:22:21.509  6786  6786 D DialogFlow: initQueue()
,08-12 18:22:21.539  6828  6828 E Zygote  : v2
08-12 18:22:21.539   756  1484 I ActivityManager: Start proc 6828:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-12 18:22:21.539  6828  6828 I libpersona: KNOX_SDCARD checking this for 1000
08-12 18:22:21.539  6828  6828 I libpersona: KNOX_SDCARD not a persona
,08-12 18:22:21.539  6828  6828 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:21.539  6828  6828 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:21.539  6828  6828 E Zygote  : accessInfo : 0
,08-12 18:22:21.539   756  1484 I ActivityManager: Killing 5875:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-12 18:22:21.569   756  1415 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-12 18:22:21.569  6828  6828 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:21.569  6828  6828 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:21.579   756  1484 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{49a29c 6828:com.samsung.android.app.mirrorlink/1000}
,08-12 18:22:21.579  6828  6828 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-12 18:22:21.589   756  1363 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/167_task.xml.bak
,08-12 18:22:21.599  6828  6828 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-12 18:22:21.629  6828  6828 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-12 18:22:21.629  6828  6828 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-12 18:22:21.629   756   772 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7e2040 5940:com.google.android.apps.plus/u0a134}
,08-12 18:22:21.649   756  1875 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7e2040 5940:com.google.android.apps.plus/u0a134}
,08-12 18:22:21.659   756  1682 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7e2040 5940:com.google.android.apps.plus/u0a134}
,08-12 18:22:21.699   756  1484 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-12 18:22:21.699   756   772 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-12 18:22:21.699   756  3961 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-12 18:22:21.709   756  1416 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-12 18:22:21.709   756  3960 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-12 18:22:21.709   756  3876 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-12 18:22:21.709   756  2004 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-12 18:22:21.719   756  1484 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-12 18:22:21.729  6842  6842 E Zygote  : v2
,08-12 18:22:21.729  6842  6842 I libpersona: KNOX_SDCARD checking this for 10165
08-12 18:22:21.729  6842  6842 I libpersona: KNOX_SDCARD not a persona
,08-12 18:22:21.729  6842  6842 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-12 18:22:21.729  6842  6842 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:21.729  6842  6842 E Zygote  : accessInfo : 0
,08-12 18:22:21.729  6842  6842 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-12 18:22:21.729   756  1415 I ActivityManager: Start proc 6842:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-12 18:22:21.739   756  1416 I ActivityManager: Killing 5915:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-12 18:22:21.749   756  3960 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-12 18:22:21.759  6842  6842 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:21.759  6842  6842 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:21.769   756  2004 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4aab02b 6842:com.sec.kidsplat.installer/u0a165}
,08-12 18:22:21.769  6842  6842 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-12 18:22:21.779  6842  6842 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-12 18:22:21.789   756  1682 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4aab02b 6842:com.sec.kidsplat.installer/u0a165}
,08-12 18:22:21.789  6842  6842 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-12 18:22:21.809  6854  6854 E Zygote  : v2
08-12 18:22:21.809  6854  6854 I libpersona: KNOX_SDCARD checking this for 10142
08-12 18:22:21.809  6854  6854 I libpersona: KNOX_SDCARD not a persona
08-12 18:22:21.809  6854  6854 E Zygote  : isSdpEnabledProcess - SDP enabled
,08-12 18:22:21.809  6854  6854 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:21.809  6854  6854 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:21.809  6854  6854 E Zygote  : accessInfo : 64
08-12 18:22:21.809  6854  6854 E Zygote  : isSdpEnabledProcess - SDP enabled
08-12 18:22:21.809  6854  6854 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,08-12 18:22:21.809  6854  6854 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-12 18:22:21.809   756   774 I ActivityManager: Start proc 6854:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-12 18:22:21.809   756   774 I ActivityManager: Killing 5506:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-12 18:22:21.829   756  1695 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-12 18:22:21.849  6854  6854 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:21.849  6854  6854 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:21.859   756  3961 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a9c4c88 6854:com.sec.android.app.sbrowser/u0a142}
,08-12 18:22:21.869  6854  6854 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-12 18:22:21.879  6854  6854 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-12 18:22:21.889  6854  6854 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-12 18:22:21.899  6854  6854 D ManifestProvider: onCreate()
,08-12 18:22:21.909  6854  6854 I SBrowserUtils: getSystemProperty of sales_code : XEO
08-12 18:22:21.909  6854  6854 I SBrowserUtils: getSystemProperty of country_code : Poland
,08-12 18:22:21.909  6854  6854 I SBrowserUtils: getSystemProperty of country_code : Poland
08-12 18:22:21.909  6854  6854 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-12 18:22:21.909  6854  6854 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-12 18:22:21.909  6854  6854 D [MM]MHDataBaseProvider: onCreate()
,08-12 18:22:21.929  6854  6854 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@196bae0)
,08-12 18:22:21.969   756  1486 I ActivityManager: Killing 6082:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-12 18:22:21.979   756  1486 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c18295 1979:com.google.android.gms.persistent/u0a11}
,08-12 18:22:21.989   756  3960 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-12 18:22:21.989  4500  6869 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 18:22:21.989  4500  6868 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-12 18:22:21.999   756  2004 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b1af2e 4500:com.google.android.gms/u0a11}
,08-12 18:22:21.999  4500  6869 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 18:22:22.019  4500  6869 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 18:22:22.019  4500  4500 D AsyncTaskServiceImpl: Submit a task: nzm
,08-12 18:22:22.019  4500  6869 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-12 18:22:22.039   756  1486 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c18295 1979:com.google.android.gms.persistent/u0a11}
,08-12 18:22:22.059  4500  5150 D nzm     : Processing package: com.test.thalitest
,08-12 18:22:22.059   756   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b1af2e 4500:com.google.android.gms/u0a11}
,08-12 18:22:22.059  4500  4500 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 18:22:22.089  4500  5150 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,08-12 18:22:22.099  4500  5150 D nzm     : Found info for package com.test.thalitest in db.
,08-12 18:22:22.129  6688  6688 I Mms/MmsApp:  start initViewCache mms
,08-12 18:22:22.149   756  1674 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b2610b1 5965:com.android.vending/u0a29}
,08-12 18:22:22.199   756   772 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eef14b u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{79d5008 6326:com.sec.android.app.samsungapps/u0a39}
,08-12 18:22:22.219  5965  5965 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-12 18:22:22.229  6876  6876 E Zygote  : v2
08-12 18:22:22.229  6876  6876 I libpersona: KNOX_SDCARD checking this for 10034
,08-12 18:22:22.229  6876  6876 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:22.229  6876  6876 I libpersona: KNOX_SDCARD not a persona
08-12 18:22:22.229  6876  6876 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:22.229   756  1416 I ActivityManager: Start proc 6876:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
08-12 18:22:22.229  6876  6876 E Zygote  : accessInfo : 0
08-12 18:22:22.229  6876  6876 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-12 18:22:22.239  1979  1979 D WearableService: callingUid 10011, callindPid: 1979
,08-12 18:22:22.249  5965  5965 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-12 18:22:22.269  5965  5965 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-12 18:22:22.269  5965  5965 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-12 18:22:22.279  6876  6876 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:22:22.279  6876  6876 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:22.289   756  3960 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e361cf7 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e7c764 6876:com.sec.android.app.shealth/u0a34}
,08-12 18:22:22.309  6876  6876 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-12 18:22:22.329  6876  6876 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-12 18:22:22.329  6876  6876 I MultiDex: VM with version 2.1.0 has multidex support
,08-12 18:22:22.329  6876  6876 I MultiDex: install
08-12 18:22:22.329  6876  6876 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 18:22:22.329  6876  6876 I MultiDex: install
08-12 18:22:22.329  6876  6876 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 18:22:22.379  6786  6815 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-12 18:22:22.379  6786  6815 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 18:22:22.399   756   772 I ActivityManager: Killing 5617:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-12 18:22:22.399   756   772 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e361cf7 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b08c5bd 1965:com.sec.android.app.shealth:remote/u0a34}
,08-12 18:22:22.399  6876  6876 D HealthDataStore: Service for HealthDataStore is connected
,08-12 18:22:22.409  6786  6815 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-12 18:22:22.409  6786  6815 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-12 18:22:22.409  6786  6815 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-12 18:22:22.409   756  1415 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-12 18:22:22.409  6786  6815 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-12 18:22:22.409  6786  6815 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-12 18:22:22.419  6876  6876 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-12 18:22:22.419  6876  6876 D HealthConsole: Service for HealthDataConsole is connected
,08-12 18:22:22.439  6876  6876 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-12 18:22:22.439  6876  6876 E HealthDataStore: disconnectService: Context instance is invalid
,08-12 18:22:22.449   756  3876 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e361cf7 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b08c5bd 1965:com.sec.android.app.shealth:remote/u0a34}
,08-12 18:22:22.489   756  1484 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20ae3da u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c18295 1979:com.google.android.gms.persistent/u0a11}
,08-12 18:22:22.579  6688  6688 D Mms/BubbleViewCache: fillCache bubble = 4
,08-12 18:22:22.749  4500  6873 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 18:22:23.259  4500  5116 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-12 18:22:23.359  4500  5116 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 18:22:23.359  4500  5116 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-12 18:22:23.369  4500  5116 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-12 18:22:23.779   756  3649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:22:24.709   756  3614 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 18:22:28.579   756   917 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-12 18:22:28.599   756   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 18:22:28.779   756  3649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:22:29.379   756   917 D PackageManager: [MSG] MCS_UNBIND
,08-12 18:22:29.389   756  1484 I ActivityManager: Killing 6161:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-12 18:22:29.399   756  1484 I ActivityManager: Killing 5518:com.policydm/1000 (adj 15): DHA:empty #37
,08-12 18:22:29.429   756  3961 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-12 18:22:29.439  6644  6644 D AASAservice: onDestroy()
,08-12 18:22:29.439  6644  6644 I art     : System.exit called, status: 80
,08-12 18:22:29.439  6644  6644 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-12 18:22:29.459   756  1415 I ActivityManager: Process com.samsung.aasaservice (pid 6644)(adj 0) has died(97,739)
,08-12 18:22:29.459   756  1415 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-12 18:22:29.469   756   774 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-12 18:22:29.499   356   356 I Zygote  : Process 6644 exited cleanly (80)
,08-12 18:22:30.559   756  1235 V AlarmManager: Expired Alarm result :4
,08-12 18:22:30.589   756  1486 V AlarmManager:  remove PendingIntent] PendingIntent{47231e7: PendingIntentRecord{fde1d92 com.google.android.gms broadcastIntent}}
,08-12 18:22:30.609   756  1321 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-12 18:22:30.609   756  1321 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-12 18:22:30.629   756  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 18:22:30.629   756  1415 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4353, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 18:22:30.629   756  1415 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-12 18:22:30.629   756  1415 D BatteryService: stay LED for charging
,08-12 18:22:30.639   756   756 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 18:22:30.639  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 18:22:30.639  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-12 18:22:30.639  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 18:22:30.649  2375  2375 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 18:22:30.649  2375  2823 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 18:22:30.659   756   756 I MotionRecognitionService: Plugged
,08-12 18:22:30.659   756   756 D MotionRecognitionService:   cableConnection= 1
08-12 18:22:30.659   756   756 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 18:22:30.659   756   756 D MotionRecognitionService: skip setTransmitPower. 
,08-12 18:22:30.659   756   756 I BackgroundCompactionService: onStart. jobID=801
,08-12 18:22:30.659  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-12 18:22:30.659  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 18:22:30.659   756   756 I BackgroundCompactionService: onStart done. jobID=801
08-12 18:22:30.659  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-12 18:22:30.659   756  6940 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-12 18:22:30.659   756  6940 I BackgroundCompactionService: compact_memory command done
,08-12 18:22:30.689  3862  3862 D FactoryTest: User mode
,08-12 18:22:30.689  3862  3862 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-12 18:22:30.689  3862  3862 D MTPRx   : still no open session command from host, so toast
,08-12 18:22:30.689   756   774 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-12 18:22:30.699   756   774 D ActivityManager: mDVFSHelper.acquire()
,08-12 18:22:30.709   756   774 V WindowManager: addAppToken: AppWindowToken{6b976df token=Token{ce9417e ActivityRecord{bab2739 u0 com.samsung.android.MtpApplication/.USBConnection t168}}} to stack=1 task=168 at 0
,08-12 18:22:30.709   756   774 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-12 18:22:30.709   756  3614 D SSRM:n  : SIOP:: AP = 470, PST = 458, CUR = 450, LCD = 0
,08-12 18:22:30.719   756   842 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-12 18:22:30.729   756   774 D InputDispatcher: Focused application set to: xxxx
,08-12 18:22:30.739   756   774 D InputDispatcher: Focus left window: 6554
,08-12 18:22:30.739  3862  3862 E MTPRx   : started activity for popup
,08-12 18:22:30.739   756   892 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:756 uid:1000
08-12 18:22:30.739   756   892 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 18:22:30.739   756   892 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:756 uid:1000
08-12 18:22:30.739   756   892 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 18:22:30.749  3862  3862 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
08-12 18:22:30.749  3862  3862 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-12 18:22:30.759   756  3614 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 18:22:30.759  3862  3862 D MTPUSBConnection: onCreate in USBConnection
08-12 18:22:30.759  3862  3862 V MTPUSBConnection: Registering broadcast receiver.
,08-12 18:22:30.759  3862  3862 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-12 18:22:30.769   756  1486 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-12 18:22:30.819  3862  3862 D TAG     : dev.kiessupport is : TRUE
,08-12 18:22:30.849  3862  3862 D SecWifiDisplayUtil: Metadata value : none
,08-12 18:22:30.849  3862  3862 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{bcafac4 V.E...... R.....I. 0,0-0,0}
,08-12 18:22:30.849  3862  6945 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 18:22:30.859   756  3961 D ISSUE_DEBUG: InputChannelName : 91562d7 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-12 18:22:30.859   756   844 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{91562d7 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-12 18:22:30.859   756  3961 D InputDispatcher: Focus entered window: 3862
,08-12 18:22:30.859   756   892 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:756 uid:1000
,08-12 18:22:30.859   756   892 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 18:22:30.859   756   892 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:756 uid:1000
,08-12 18:22:30.859   756   892 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 18:22:30.859  1377  1377 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-12 18:22:30.869  3862  3862 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9ecde5c I.E...... R.....I. 0,0-0,0}
,08-12 18:22:30.869   756  1416 D ISSUE_DEBUG: InputChannelName : 524f6ad com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-12 18:22:30.869   756  3961 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-12 18:22:30.869   756  3961 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 18:22:30.869   756   756 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 18:22:30.879   756   756 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-12 18:22:30.879   756   756 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-12 18:22:30.909   293   293 I SurfaceFlinger: id=16 createSurf (145x145),1 flag=4, VSBConnecti
,08-12 18:22:30.929  3862  6945 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 18:22:30.929  3862  6945 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 18:22:30.929  3862  6945 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 18:22:30.929  3862  6945 I Adreno-EGL: Local Branch: ss
08-12 18:22:30.929  3862  6945 I Adreno-EGL: Remote Branch: 
08-12 18:22:30.929  3862  6945 I Adreno-EGL: Local Patches: 
08-12 18:22:30.929  3862  6945 I Adreno-EGL: Reconstruct Branch: 
,08-12 18:22:30.939  3862  6945 D libEGL  : eglInitialize EGLDisplay = 0x9f0557c4
08-12 18:22:30.939  3862  6945 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 18:22:30.969   293   293 I SurfaceFlinger: id=17 createSurf (193x193),1 flag=4, VSBConnecti
,08-12 18:22:30.979  3862  3862 V ActivityThread: updateVisibility : ActivityRecord{1b4eeeb token=android.os.BinderProxy@56cadad {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-12 18:22:30.989  3862  3862 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 18:22:31.059   756  1415 V WindowStateAnimator: Finishing drawing window Window{91562d7 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 18:22:31.059  3862  3862 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 18:22:31.069   756  1674 V WindowStateAnimator: Finishing drawing window Window{524f6ad u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 18:22:31.069  3862  3862 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-12 18:22:31.069  3862  3862 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-12 18:22:31.069   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbed86364
,08-12 18:22:31.069   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbed86364
,08-12 18:22:31.069   756  3960 V WindowStateAnimator: Finishing drawing window Window{91562d7 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-12 18:22:31.069   756   892 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 18:22:31.069   756   756 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-12 18:22:31.069   756   892 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +345ms (total +369ms)
,08-12 18:22:31.079   756  3961 V WindowStateAnimator: Finishing drawing window Window{524f6ad u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-12 18:22:31.079  3862  3862 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@56cadad time:109611
,08-12 18:22:31.079   756   756 I KnoxTimeoutHandler: SD activityfalse
,08-12 18:22:31.079   756   892 D ActivityManager: mDVFSHelper.release()
08-12 18:22:31.079   756   892 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bab2739 u0 com.samsung.android.MtpApplication/.USBConnection t168} time:109612
,08-12 18:22:31.089   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbed86364
,08-12 18:22:31.269  6554  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 18:22:31.269  6554  6687 I jxcore-log: 
,08-12 18:22:31.269  6554  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 18:22:31.269  6554  6687 I jxcore-log: 
,08-12 18:22:31.269  6554  6687 D BluetoothAdapter: STATE_ON
,08-12 18:22:31.279  6554  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:22:31.279  6554  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:22:31.279  6554  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 18:22:31.279  6554  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:22:31.279  6554  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:22:31.279  6554  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:22:31.279  6554  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:22:31.279  6554  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 18:22:31.279  6554  6687 D BluetoothAdapter: STATE_ON
,08-12 18:22:31.279  6554  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 18:22:31.279  6554  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 18:22:31.279  6554  6687 I jxcore-log: 
,08-12 18:22:31.279  6554  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 18:22:31.279  6554  6687 I jxcore-log: 
,08-12 18:22:31.629  6554  6687 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 18:22:31.629  6554  6687 I jxcore-log: Failed to execute UT.
08-12 18:22:31.629  6554  6687 I jxcore-log: 
08-12 18:22:31.629  6554  6687 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 18:22:31.629  6554  6687 I jxcore-log: 
,08-12 18:22:31.639  6554  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 18:22:31.639  6554  6687 I jxcore-log: 
08-12 18:22:31.649  6554  6554 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 18:22:31.739   756  3617 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-12 18:22:31.879  1456  1456 D Recents : onTaskStackChanged
,08-12 18:22:31.879  1456  1456 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-12 18:22:32.599  2380  2380 E audit   : type=1400 msg=audit(1471018952.599:290): avc:  denied  { execmod } for  pid=6956 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 18:22:32.599  2380  2380 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:32.609  2380  2380 E audit   : type=1300 msg=audit(1471018952.599:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fbe000 a1=51000 a2=5 a3=4 items=0 ppid=3760 ppcomm=adbd pid=6956 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-12 18:22:32.609  2380  2380 E audit   : type=1327 msg=audit(1471018952.599:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-12 18:22:32.609  2380  2380 E audit   : type=1320 msg=audit(1471018952.599:290): 
,08-12 18:22:32.659  2380  2380 E audit   : type=1400 msg=audit(1471018952.659:291): avc:  denied  { execmod } for  pid=6956 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 18:22:32.659  2380  2380 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:32.659  2380  2380 E audit   : type=1300 msg=audit(1471018952.659:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f80000 a1=51000 a2=5 a3=4 items=0 ppid=3760 ppcomm=adbd pid=6956 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 18:22:32.659  2380  2380 E audit   : type=1327 msg=audit(1471018952.659:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 18:22:32.659  2380  2380 E audit   : type=1320 msg=audit(1471018952.659:291): 
,08-12 18:22:32.699  2380  2380 E audit   : type=1400 msg=audit(1471018952.699:292): avc:  denied  { execmod } for  pid=6956 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 18:22:32.699  2380  2380 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:32.699  6956  6956 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 18:22:32.709  2380  2380 E audit   : type=1300 msg=audit(1471018952.699:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f80000 a1=51000 a2=5 a3=4 items=0 ppid=3760 ppcomm=adbd pid=6956 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-12 18:22:32.709  2380  2380 E audit   : type=1327 msg=audit(1471018952.699:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 18:22:32.709  2380  2380 E audit   : type=1320 msg=audit(1471018952.699:292): 
,08-12 18:22:32.709  6956  6956 D AndroidRuntime: CheckJNI is OFF
,08-12 18:22:32.709  6956  6956 D AndroidRuntime: readGMSProperty: start
08-12 18:22:32.709  6956  6956 D AndroidRuntime: readGMSProperty: already setted!!
08-12 18:22:32.709  6956  6956 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 18:22:32.709  6956  6956 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 18:22:32.709  6956  6956 D AndroidRuntime: readGMSProperty: end
08-12 18:22:32.709  6956  6956 D AndroidRuntime: addProductProperty: start
,08-12 18:22:32.719  6956  6956 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art,
08-12 18:22:32.719  6956  6956 W art     : aede5000-b1d0b000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-12 18:22:32.719  6956  6956 W art     : b1d0b000-b3f7a000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 18:22:32.719  6956  6956 W art     : b3f7a000-b3f7b000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
,08-12 18:22:32.719  6956  6956 W art     : b3f7b000-b3f7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.719  6956  6956 W art     : b42ba000-b42e3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
,08-12 18:22:32.719  6956  6956 W art     : b42e3000-b4731000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-12 18:22:32.719  6956  6956 W art     : b4731000-b4732000 ---p 00000000 00:00 0 
08-12 18:22:32.719  6956  6956 W art     : b4732000-b473c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
,08-12 18:22:32.719  6956  6956 W art     : b473c000-b473d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-12 18:22:32.719  6956  6956 W art     : b473d000-b473f000 rw-p 00000000 00:00 0 
08-12 18:22:32.719  6956  6956 W art     : b473f000-b4740000 r--p 00000000 00:00 0 
,08-12 18:22:32.719  6956  6956 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-12 18:22:32.719  6956  6956 W art     : b484d000-b4850000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 18:22:32.719  6956  6956 W art     : b4850000-b4851000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-12 18:22:32.719  6956  6956 W art     : b4851000-b4852000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so,
08-12 18:22:32.719  6956  6956 W art     : b4852000-b4853000 r--p 00000000 00:00 0 
08-12 18:22:32.719  6956  6956 W art     : b4853000-b4873000 r--s 00000000 00:0b 6702       /dev/__properties__
08-12 18:22:32.719  6956  6956 W art     : b4873000-b5284000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 18:22:32.719  6956  6956 W art     : b5284000-b5285000 ---p 00000000 00:00 0 
08-12 18:22:32.719  6956  6956 W art     : b5285000-b52ce000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so,
08-12 18:22:32.719  6956  6956 W art     : b52ce000-b52cf000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 18:22:32.719  6956  6956 W art     : b52cf000-b52d7000 rw-p 00000000 00:00 0 
,08-12 18:22:32.719  6956  6956 W art     : b52d7000-b52d8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.719  6956  6956 W art     : b52d8000-b530d000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 18:22:32.719  6956  6956 W art     : b530d000-b530e000 ---p 00000000 00:00 0 
,08-12 18:22:32.719  6956  6956 W art     : b530e000-b530f000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 18:22:32.719  6956  6956 W art     : b530f000-b5310000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 18:22:32.719  6956  6956 W art     : b5310000-b5368000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
,08-12 18:22:32.719  6956  6956 W art     : b5368000-b5369000 ---p 00000000 00:00 0 
08-12 18:22:32.719  6956  6956 W art     : b5369000-b536a000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 18:22:32.719  6956  6956 W art     : b536a000-b536b000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 18:22:32.719  6956  6956 W art     : b536c000-b5372000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-12 18:22:32.719  6956  6956 W art     : b5372000-b5373000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 18:22:32.719  6956  6956 W art     : b5373000-b5374000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 18:22:32.719  6956  6956 W art     : b5374000-b5376000 rw-p 00000000 00:00 0 
08-12 18:22:32.719  6956  6956 W art     : b5377000-b5381000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
,08-12 18:22:32.719  6956  6956 W art     : b5381000-b5384000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 18:22:32.719  6956  6956 W art     : b5384000-b5385000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
,08-12 18:22:32.719  6956  6956 W art     : b5386000-b539d000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 18:22:32.719  6956  6956 W art     : b539d000-b539e000 ---p 00000000 00:00 0 
08-12 18:22:32.719  6956  6956 W art     : b539e000-b539f000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 18:22:32.719  6956  6956 W art     : b539f000-b53a0000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-12 18:22:32.719  6956  6956 W art     : b53a1000-b53ab000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 18:22:32.719  6956  6956 W art     : b53ab000-b53ac000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 18:22:32.719  6956  6956 W art     : b53ac000-b53ad000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
,08-12 18:22:32.719  6956  6956 W art     : b53ad000-b53b1000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 18:22:32.719  6956  6956 W art     : b53b1000-b53b2000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 18:22:32.719  6956  6956 W art     : b53b2000-b53b3000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 18:22:32.719  6956  6956 W art     : b53b3000-b53c9000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
,08-12 18:22:32.719  6956  6956 W art     : b53c9000-b53ca000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 18:22:32.719  6956  6956 W art     : b53ca000-b53cb000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 18:22:32.719  6956  6956 W art     : b53cb000-b53d8000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
,08-12 18:22:32.719  6956  6956 W art     : b53d8000-b53d9000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 18:22:32.719  6956  6956 W art     : b53d9000-b53da000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 18:22:32.719  6956  6956 W art     : b53da000-b543a000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-12 18:22:32.719  6956  6956 W art     : b543a000-b543d000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
,08-12 18:22:32.719  6956  6956 W art     : b543d000-b5441000 rw-p 00000000 00:00 0 
08-12 18:22:32.719  6956  6956 W art     : b5441000-b54a2000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 18:22:32.719  6956  6956 W art     : b54a2000-b54a3000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 18:22:32.719  6956  6956 W art     : b54a3000-b54f2000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
,08-12 18:22:32.719  6956  6956 W art     : b54f2000-b54f4000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-12 18:22:32.719  6956  6956 W art     : b54f4000-b54f5000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 18:22:32.719  6956  6956 W art     : b54f5000-b54f6000 rw-p 00000000 00:00 0 
,08-12 18:22:32.719  6956  6956 W art     : b54f6000-b54fd000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 18:22:32.719  6956  6956 W art     : b54fd000-b54fe000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 18:22:32.719  6956  6956 W art     : b54fe000-b54ff000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 18:22:32.719  6956  6956 W art     : b5500000-b5503000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-12 18:22:32.719  6956  6956 W art     : b5503000-b5504000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 18:22:32.719  6956  6956 W art     : b5504000-b5505000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 18:22:32.719  6956  6956 W art     : b5506000-b550a000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 18:22:32.719  6956  6956 W art     : b550a000-b550b000 ---p 00000000 00:00 0 
,08-12 18:22:32.719  6956  6956 W art     : b550b000-b550c000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-12 18:22:32.719  6956  6956 W art     : b550c000-b550d000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-12 18:22:32.719  6956  6956 W art     : b550e000-b552b000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
,08-12 18:22:32.719  6956  6956 W art     : b552b000-b552c000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 18:22:32.719  6956  6956 W art     : b552c000-b552d000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 18:22:32.719  6956  6956 W art     : b552e000-b5533000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 18:22:32.719  6956  6956 W art     : b5533000-b5534000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-12 18:22:32.719  6956  6956 W art     : b5534000-b5535000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 18:22:32.719  6956  6956 W art     : b5536000-b5567000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
,08-12 18:22:32.719  6956  6956 W art     : b5567000-b556a000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 18:22:32.719  6956  6956 W art     : b556a000-b556b000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 18:22:32.719  6956  6956 W art     : b556c000-b55a7000 r-xp 00000000 b3:17 893        /system/lib/libopus.so,
08-12 18:22:32.719  6956  6956 W art     : b55a7000-b55a8000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-12 18:22:32.719  6956  6956 W art     : b55a8000-b55a9000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
,08-12 18:22:32.719  6956  6956 W art     : b55aa000-b55b1000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
,08-12 18:22:32.719  6956  6956 W art     : b55b1000-b55b2000 ---p 00000000 00:00 0 
,08-12 18:22:32.719  6956  6956 W art     : b55b2000-b55b3000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-12 18:22:32.719  6956  6956 W art     : b55b3000-b55b4000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
,08-12 18:22:32.719  6956  6956 W art     : b55b4000-b55b5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.719  6956  6956 W art     : b55b5000-b55cc000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
,08-12 18:22:32.719  6956  6956 W art     : b55cc000-b55cd000 ---p 00000000 00:00 0 
,08-12 18:22:32.719  6956  6956 W art     : b55cd000-b55d0000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
,08-12 18:22:32.719  6956  6956 W art     : b55d0000-b55d1000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
,08-12 18:22:32.719  6956  6956 W art     : b55d1000-b55f0000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
,08-12 18:22:32.719  6956  6956 W art     : b55f0000-b55f1000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
,08-12 18:22:32.719  6956  6956 W art     : b55f1000-b55f2000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-12 18:22:32.719  6956  6956 W art     : b55f2000-b5630000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 18:22:32.719  6956  6956 W art     : b5630000-b5631000 ---p 00000000 00:00 0 
08-12 18:22:32.719  6956  6956 W art     : b5631000-b5633000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 18:22:32.719  6956  6956 W art     : b5633000-b5634000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 18:22:32.719  6956  6956 W art     : b5635000-b563c000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so,
08-12 18:22:32.719  6956  6956 W art     : b563c000-b563d000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 18:22:32.719  6956  6956 W art     : b563d000-b563e000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 18:22:32.719  6956  6956 W art     : b563f000-b5642000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 18:22:32.719  6956  6956 W art     : b5642000-b5643000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 18:22:32.719  6956  6956 W art     : b5643000-b5644000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
,08-12 18:22:32.719  6956  6956 W art     : b5644000-b564a000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 18:22:32.719  6956  6956 W art     : b564a000-b564b000 ---p 00000000 00:00 0 
08-12 18:22:32.719  6956  6956 W art     : b564b000-b564c000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 18:22:32.719  6956  6956 W art     : b564c000-b564d000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 18:22:32.719  6956  6956 W art     : b564d000-b5656000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 18:22:32.719  6956  6956 W art     : b5656000-b5657000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
,08-12 18:22:32.719  6956  6956 W art     : b5657000-b5658000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 18:22:32.719  6956  6956 W art     : b5658000-b56e9000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 18:22:32.719  6956  6956 W art     : b56e9000-b56ea000 ---p 00000000 00:00 0 
08-12 18:22:32.719  6956  6956 W art     : b56ea000-b56f5000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 18:22:32.719  6956  6956 W art     : b56f5000-b56f6000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 18:22:32.719  6956  6956 W art     : b56f7000-b5709000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
,08-12 18:22:32.719  6956  6956 W art     : b5709000-b570a000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 18:22:32.719  6956  6956 W art     : b570a000-b570b000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-12 18:22:32.729  6956  6956 W art     : b570c000-b5711000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-12 18:22:32.729  6956  6956 W art     : b5711000-b5712000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 18:22:32.729  6956  6956 W art     : b5712000-b5713000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 18:22:32.729  6956  6956 W art     : b5714000-b5781000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
,08-12 18:22:32.729  6956  6956 W art     : b5781000-b5782000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b5782000-b5784000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 18:22:32.729  6956  6956 W art     : b5784000-b5785000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 18:22:32.729  6956  6956 W art     : b5785000-b5786000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.729  6956  6956 W art     : b5786000-b578d000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 18:22:32.729  6956  6956 W art     : b578d000-b578e000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-12 18:22:32.729  6956  6956 W art     : b578e000-b578f000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 18:22:32.729  6956  6956 W art     : b5790000-b5810000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 18:22:32.729  6956  6956 W art     : b5810000-b5811000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b5811000-b5812000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 18:22:32.729  6956  6956 W art     : b5812000-b5813000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 18:22:32.729  6956  6956 W art     : b5813000-b582a000 rw-p 00000000 00:00 0 
,08-12 18:22:32.729  6956  6956 W art     : b582a000-b5861000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 18:22:32.729  6956  6956 W art     : ib/libqc-opt.so
08-12 18:22:32.729  6956  6956 W art     : b5861000-b5862000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 18:22:32.729  6956  6956 W art     : b5862000-b5863000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
,08-12 18:22:32.729  6956  6956 W art     : b5863000-b587f000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 18:22:32.729  6956  6956 W art     : b587f000-b5880000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 18:22:32.729  6956  6956 W art     : b5880000-b5881000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
,08-12 18:22:32.729  6956  6956 W art     : b5882000-b58e3000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 18:22:32.729  6956  6956 W art     : b58e3000-b58e5000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 18:22:32.729  6956  6956 W art     : b58e5000-b58e6000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 18:22:32.729  6956  6956 W art     : b58e7000-b590e000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
,08-12 18:22:32.729  6956  6956 W art     : b590e000-b590f000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b590f000-b5910000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
,08-12 18:22:32.729  6956  6956 W art     : b5910000-b5911000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 18:22:32.729  6956  6956 W art     : b5912000-b591a000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 18:22:32.729  6956  6956 W art     : b591a000-b591c000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 18:22:32.729  6956  6956 W art     : b591c000-b591d000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
,08-12 18:22:32.729  6956  6956 W art     : b591e000-b5921000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 18:22:32.729  6956  6956 W art     : b5921000-b5922000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 18:22:32.729  6956  6956 W art     : b5922000-b5923000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
,08-12 18:22:32.729  6956  6956 W art     : b5923000-b5927000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 18:22:32.729  6956  6956 W art     : b5927000-b5928000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b5928000-b5929000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 18:22:32.729  6956  6956 W art     : b5929000-b592a000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 18:22:32.729  6956  6956 W art     : b592a000-b593a000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
,08-12 18:22:32.729  6956  6956 W art     : b593a000-b593b000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 18:22:32.729  6956  6956 W art     : b593b000-b593c000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 18:22:32.729  6956  6956 W art     : b593c000-b5982000 rw-p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b5982000-b598b000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 18:22:32.729  6956  6956 W art     : b598b000-b598c000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 18:22:32.729  6956  6956 W art     : b598c000-b598d000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-12 18:22:32.729  6956  6956 W art     : b598e000-b5993000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
,08-12 18:22:32.729  6956  6956 W art     : b5993000-b5994000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 18:22:32.729  6956  6956 W art     : b5994000-b5995000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 18:22:32.729  6956  6956 W art     : b5995000-b5998000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 18:22:32.729  6956  6956 W art     : b5998000-b5999000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b5999000-b599a000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 18:22:32.729  6956  6956 W art     : b599a000-b599b000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
,08-12 18:22:32.729  6956  6956 W art     : b599c000-b59b4000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 18:22:32.729  6956  6956 W art     : b59b4000-b59b5000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b59b5000-b59b6000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 18:22:32.729  6956  6956 W art     : b59b6000-b59b7000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 18:22:32.729  6956  6956 W art     : b59b8000-b5b52000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 18:22:32.729  6956  6956 W art     : b5b52000-b5b53000 ---p 00000000 00:00 0 
,08-12 18:22:32.729  6956  6956 W art     : b5b53000-b5b60000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 18:22:32.729  6956  6956 W art     : b5b60000-b5b61000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 18:22:32.729  6956  6956 W art     : b5b61000-b5b65000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 18:22:32.729  6956  6956 W art     : b5b65000-b5b66000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b5b66000-b5b67000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 18:22:32.729  6956  6956 W art     : b5b67000-b5b68000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
,08-12 18:22:32.729  6956  6956 W art     : b5b68000-b5b7b000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 18:22:32.729  6956  6956 W art     : b5b7b000-b5b7c000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 18:22:32.729  6956  6956 W art     : b5b7c000-b5b7d000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 18:22:32.729  6956  6956 W art     : b5b7e000-b5bc9000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 18:22:32.729  6956  6956 W art     : b5bc9000-b5bca000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 18:22:32.729  6956  6956 W art     : b5bca000-b5bcb000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 18:22:32.729  6956  6956 W art     : b5bcb000-b5bcd000 rw-p 00000000 00:00 0 
,08-12 18:22:32.729  6956  6956 W art     : b5bcd000-b5bce000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:22:32.729  6956  6956 W art     : b5bce000-b5bdf000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 18:22:32.729  6956  6956 W art     : b5bdf000-b5be0000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b5be0000-b5be1000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 18:22:32.729  6956  6956 W art     : b5be1000-b5be2000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 18:22:32.729  6956  6956 W art     : b5be3000-b5bed000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
,08-12 18:22:32.729  6956  6956 W art     : b5bed000-b5bef000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 18:22:32.729  6956  6956 W art     : b5bef000-b5bf0000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 18:22:32.729  6956  6956 W art     : b5bf0000-b5c09000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 18:22:32.729  6956  6956 W art     : b5c09000-b5c0a000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 18:22:32.729  6956  6956 W art     : b5c0a000-b5c0d000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 18:22:32.729  6956  6956 W art     : b5c0d000-b5c11000 rw-p 00000000 00:00 0 
,08-12 18:22:32.729  6956  6956 W art     : b5c11000-b5c85000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 18:22:32.729  6956  6956 W art     : b5c85000-b5c86000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b5c86000-b5c89000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 18:22:32.729  6956  6956 W art     : b5c89000-b5c8a000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
,08-12 18:22:32.729  6956  6956 W art     : b5c8b000-b5c8e000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-12 18:22:32.729  6956  6956 W art     : b5c8e000-b5c8f000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 18:22:32.729  6956  6956 W art     : b5c8f000-b5c90000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 18:22:32.729  6956  6956 W art     : b5c90000-b5c91000 r--p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b5c91000-b5c96000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 18:22:32.729  6956  6956 W art     : b5c96000-b5c97000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
,08-12 18:22:32.729  6956  6956 W art     : b5c97000-b5c98000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 18:22:32.729  6956  6956 W art     : b5c98000-b5c99000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.729  6956  6956 W art     : b5c99000-b5c9c000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 18:22:32.729  6956  6956 W art     : b5c9c000-b5c9d000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 18:22:32.729  6956  6956 W art     : b5c9d000-b5c9e000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 18:22:32.729  6956  6956 W art     : b5c9e000-b5c9f000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 18:22:32.729  6956  6956 W art     : b5c9f000-b5ca3000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 18:22:32.729  6956  6956 W art     : b5ca3000-b5ca4000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 18:22:32.729  6956  6956 W art     : b5ca4000-b5ca5000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 18:22:32.729  6956  6956 W art     : b5ca5000-b5ca6000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:22:32.729  6956  6956 W art     : b5ca6000-b5caa000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 18:22:32.729  6956  6956 W art     : b5caa000-b5cab000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
,08-12 18:22:32.729  6956  6956 W art     : b5cab000-b5cac000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 18:22:32.729  6956  6956 W art     : b5cac000-b5cad000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.729  6956  6956 W art     : b5cad000-b5cbb000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 18:22:32.729  6956  6956 W art     : b5cbb000-b5cbc000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b5cbc000-b5cbd000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 18:22:32.729  6956  6956 W art     : b5cbd000-b5cbe000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 18:22:32.729  6956  6956 W art     : b5cbe000-b5cc8000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
,08-12 18:22:32.729  6956  6956 W art     : b5cc8000-b5ccb000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 18:22:32.729  6956  6956 W art     : b5ccb000-b5ccc000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 18:22:32.729  6956  6956 W art     : b5ccc000-b5ccd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.729  6956  6956 W art     : b5ccd000-b5cd7000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 18:22:32.729  6956  6956 W art     : b5cd7000-b5cda000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 18:22:32.729  6956  6956 W art     : b5cda000-b5cdb000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
,08-12 18:22:32.729  6956  6956 W art     : b5cdb000-b5cdf000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 18:22:32.729  6956  6956 W art     : b5cdf000-b5ce0000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 18:22:32.729  6956  6956 W art     : b5ce0000-b5ce1000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 18:22:32.729  6956  6956 W art     : b5ce1000-b5ce2000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 18:22:32.729  6956  6956 W art     : b5ce2000-b5cef000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 18:22:32.729  6956  6956 W art     : b5cef000-b5cf1000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 18:22:32.729  6956  6956 W art     : b5cf1000-b5cf2000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 18:22:32.729  6956  6956 W art     : b5cf2000-b6104000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 18:22:32.729  6956  6956 W art     : b6104000-b6105000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6105000-b610e000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 18:22:32.729  6956  6956 W art     : b610e000-b6112000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 18:22:32.729  6956  6956 W art     : b6112000-b6113000 rw-p 00000000 00:00 0 
,08-12 18:22:32.729  6956  6956 W art     : b6113000-b611a000 r-xp 00000000 b3:17 2571       /system/lib/libaud
08-12 18:22:32.729  6956  6956 W art     : ioutils.so
08-12 18:22:32.729  6956  6956 W art     : b611a000-b611b000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 18:22:32.729  6956  6956 W art     : b611b000-b611c000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 18:22:32.729  6956  6956 W art     : b611c000-b611d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.729  6956  6956 W art     : b611d000-b6138000 r-xp 00000000
08-12 18:22:32.729  6956  6956 W art     :  b3:17 1184       /system/lib/libz.so
,08-12 18:22:32.729  6956  6956 W art     : b6138000-b6139000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 18:22:32.729  6956  6956 W art     : b6139000-b613a000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 18:22:32.729  6956  6956 W art     : b613a000-b613b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.729  6956  6956 W art     : b613b000-b6187000 r-xp 00000000 b3:17 994        
08-12 18:22:32.729  6956  6956 W art     : /system/lib/libharfbuzz_ng.so
08-12 18:22:32.729  6956  6956 W art     : b6187000-b6188000 ---p 00000000 00:00 0 
,08-12 18:22:32.729  6956  6956 W art     : b6188000-b6189000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 18:22:32.729  6956  6956 W art     : b6189000-b618a000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 18:22:32.729  6956  6956 W art     : b618a000-b618b000 r--p 00000000 00:00 0          [anon:li
08-12 18:22:32.729  6956  6956 W art     : nker_alloc]
08-12 18:22:32.729  6956  6956 W art     : b618b000-b618f000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 18:22:32.729  6956  6956 W art     : b618f000-b6190000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6190000-b6191000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
,08-12 18:22:32.729  6956  6956 W art     : b6191000-b6192000 rw-p 00005000 b3:17 2681       /system/lib/libu
08-12 18:22:32.729  6956  6956 W art     : sbhost.so
08-12 18:22:32.729  6956  6956 W art     : b6192000-b61ca000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 18:22:32.729  6956  6956 W art     : b61ca000-b61cb000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 18:22:32.729  6956  6956 W art     : b61cb000-b61cc000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 18:22:32.729  6956  6956 W art     : b61cc000-b61cd000 r--p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     :          [anon:linker_alloc]
,08-12 18:22:32.729  6956  6956 W art     : b61cd000-b626b000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 18:22:32.729  6956  6956 W art     : b626b000-b626c000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b626c000-b628a000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 18:22:32.729  6956  6956 W art     : b628a000-b628b000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
08-12 18:22:32.729  6956  6956 W art     : .so
08-12 18:22:32.729  6956  6956 W art     : b628b000-b63fe000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 18:22:32.729  6956  6956 W art     : b63fe000-b6409000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
,08-12 18:22:32.729  6956  6956 W art     : b6409000-b640a000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 18:22:32.729  6956  6956 W art     : b640a000-b6521000 r-xp 00000000
08-12 18:22:32.729  6956  6956 W art     :  b3:17 2041       /system/lib/libicuuc.so
08-12 18:22:32.729  6956  6956 W art     : b6521000-b652c000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 18:22:32.729  6956  6956 W art     : b652c000-b652d000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 18:22:32.729  6956  6956 W art     : b652d000-b6531000 rw-p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6531000-b6555000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
,08-12 18:22:32.729  6956  6956 W art     : o
08-12 18:22:32.729  6956  6956 W art     : b6555000-b6557000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 18:22:32.729  6956  6956 W art     : b6557000-b6558000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 18:22:32.729  6956  6956 W art     : b6558000-b65fe000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 18:22:32.729  6956  6956 W art     : b65fe000-b660b000 r--p 000a5000 b3:17 13
08-12 18:22:32.729  6956  6956 W art     : 2        /system/lib/libcrypto.so
08-12 18:22:32.729  6956  6956 W art     : b660b000-b660c000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
,08-12 18:22:32.729  6956  6956 W art     : b660c000-b660d000 rw-p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b660d000-b6660000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 18:22:32.729  6956  6956 W art     : b6660000-b6661000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6661000-b6662000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 18:22:32.729  6956  6956 W art     : b6662000-b6663000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 18:22:32.729  6956  6956 W art     : b6663000-b6668000 rw-p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6668000-b667a000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
,08-12 18:22:32.729  6956  6956 W art     : b667a000-b667b000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b667b000-b667c000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-12 18:22:32.729  6956  6956 W art     : b667c000-b667d000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 18:22:32.729  6956  6956 W art     : b667d000-b6684000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 18:22:32.729  6956  6956 W art     : b6684000-b6685000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 18:22:32.729  6956  6956 W art     : b6685000-b6686000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 18:22:32.729  6956  6956 W art     : b6686000-b6687000 rw-p 00000000 00:00 0 
,08-12 18:22:32.729  6956  6956 W art     : b6687000-b668a000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 18:22:32.729  6956  6956 W art     : b668a000-b668b000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 18:22:32.729  6956  6956 W art     : b668b000-b668c000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-12 18:22:32.729  6956  6956 W art     : b668c000-b6690000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 18:22:32.729  6956  6956 W art     : b6690000-b6691000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 18:22:32.729  6956  6956 W art     : b6691000-b6692000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 18:22:32.729  6956  6956 W art     : b6692000-b66a0000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
,08-12 18:22:32.729  6956  6956 W art     : b66a0000-b66a1000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b66a1000-b66a2000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 18:22:32.729  6956  6956 W art     : b66a2000-b66a3000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 18:22:32.729  6956  6956 W art     : b66a3000-b66ac000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 18:22:32.729  6956  6956 W art     : b66ac000-b66ad000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 18:22:32.729  6956  6956 W art     : b66ad000-b66ae000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 18:22:32.729  6956  6956 W art     : b66ae000-b6714000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 18:22:32.729  6956  6956 W art     : b6714000-b6715000 ---p 00000000 00:00 0 
,08-12 18:22:32.729  6956  6956 W art     : b6715000-b6717000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 18:22:32.729  6956  6956 W art     : b6717000-b6720000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 18:22:32.729  6956  6956 W art     : b6720000-b6723000 rw-p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6723000-b67ba000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 18:22:32.729  6956  6956 W art     : b67ba000-b67bc000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-12 18:22:32.729  6956  6956 W art     : b67bc000-b67bd000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 18:22:32.729  6956  6956 W art     : b67bd000-b67be000 rw-p 00000000 00:00 0 
,08-12 18:22:32.729  6956  6956 W art     : b67be000-b6adf000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 18:22:32.729  6956  6956 W art     : b6adf000-b6ae0000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6ae0000-b6afb000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 18:22:32.729  6956  6956 W art     : b6afb000-b6aff000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 18:22:32.729  6956  6956 W art     : b6aff000-b6b04000 rw-p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6b04000-b6b0c000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
,08-12 18:22:32.729  6956  6956 W art     : b6b0c000-b6b0d000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 18:22:32.729  6956  6956 W art     : b6b0d000-b6b0e000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 18:22:32.729  6956  6956 W art     : b6b0e000-b6b3c000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 18:22:32.729  6956  6956 W art     : b6b3c000-b6b3d000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6b3d000-b6b44000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 18:22:32.729  6956  6956 W art     : b6b44000-b6b45000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
,08-12 18:22:32.729  6956  6956 W art     : b6b45000-b6b8b000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 18:22:32.729  6956  6956 W art     : b6b8b000-b6b8c000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6b8c000-b6b8f000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 18:22:32.729  6956  6956 W art     : b6b8f000-b6b90000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 18:22:32.729  6956  6956 W art     : b6b90000-b6bab000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
,08-12 18:22:32.729  6956  6956 W art     : b6bab000-b6baf000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 18:22:32.729  6956  6956 W art     : b6baf000-b6bb0000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 18:22:32.729  6956  6956 W art     : b6bb0000-b6bfd000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 18:22:32.729  6956  6956 W art     : b6bfd000-b6bfe000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6bfe000-b6c0a000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-12 18:22:32.729  6956  6956 W art     : b6c0a000-b6c0b000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
,08-12 18:22:32.729  6956  6956 W art     : b6c0b000-b6c18000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 18:22:32.729  6956  6956 W art     : b6c18000-b6c19000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6c19000-b6c1a000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 18:22:32.729  6956  6956 W art     : b6c1a000-b6c1b000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 18:22:32.729  6956  6956 W art     : b6c1b000-b6c23000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 18:22:32.729  6956  6956 W art     : b6c23000-b6c24000 ---p 00000000 00:00 0 
,08-12 18:22:32.729  6956  6956 W art     : b6c24000-b6c25000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 18:22:32.729  6956  6956 W art     : b6c25000-b6c26000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-12 18:22:32.729  6956  6956 W art     : b6c26000-b6c2d000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 18:22:32.729  6956  6956 W art     : b6c2d000-b6c2e000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 18:22:32.729  6956  6956 W art     : b6c2e000-b6c2f000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 18:22:32.729  6956  6956 W art     : b6c2f000-b6c43000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
,08-12 18:22:32.729  6956  6956 W art     : b6c43000-b6c45000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 18:22:32.729  6956  6956 W art     : b6c45000-b6c46000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 18:22:32.729  6956  6956 W art     : b6c46000-b6c6e000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 18:22:32.729  6956  6956 W art     : b6c6e000-b6c70000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
,08-12 18:22:32.729  6956  6956 W art     : b6c70000-b6c71000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 18:22:32.729  6956  6956 W art     : b6c71000-b6c74000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 18:22:32.729  6956  6956 W art     : b6c74000-b6c75000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 18:22:32.729  6956  6956 W art     : b6c75000-b6c76000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 18:22:32.729  6956  6956 W art     : b6c76000-b6c7f000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-12 18:22:32.729  6956  6956 W art     : b6c7f000-b6c80000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
,08-12 18:22:32.729  6956  6956 W art     : b6c80000-b6c81000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 18:22:32.729  6956  6956 W art     : b6c81000-b6ca1000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 18:22:32.729  6956  6956 W art     : b6ca1000-b6ca2000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 18:22:32.729  6956  6956 W art     : b6ca2000-b6ca3000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 18:22:32.729  6956  6956 W art     : b6ca3000-b6d16000 r-xp 00000000 b3:17 860        /system/lib/libc.so
,08-12 18:22:32.729  6956  6956 W art     : b6d16000-b6d1a000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 18:22:32.729  6956  6956 W art     : b6d1a000-b6d1d000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 18:22:32.729  6956  6956 W art     : b6d1d000-b6d27000 rw-p 00000000 00:00 0 
,08-12 18:22:32.729  6956  6956 W art     : b6d27000-b6daf000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 18:22:32.729  6956  6956 W art     : b6daf000-b6db0000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6db0000-b6db4000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
,08-12 18:22:32.729  6956  6956 W art     : b6db4000-b6db5000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-12 18:22:32.729  6956  6956 W art     : b6db5000-b6db6000 rw-p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6db6000-b6ddf000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 18:22:32.729  6956  6956 W art     : b6ddf000-b6de0000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6de0000-b6de3000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-12 18:22:32.729  6956  6956 W art     : b6de3000-b6de4000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
,08-12 18:22:32.729  6956  6956 W art     : b6de4000-b6ebe000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 18:22:32.729  6956  6956 W art     : b6ebe000-b6ec5000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 18:22:32.729  6956  6956 W art     : b6ec5000-b6ecd000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 18:22:32.729  6956  6956 W art     : b6ecd000-b6ece000 rw-p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6ece000-b6ecf000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:22:32.729  6956  6956 W art     : b6ecf000-b6ed0000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
,08-12 18:22:32.729  6956  6956 W art     : b6ed0000-b6ed1000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.729  6956  6956 W art     : b6ed1000-b6ed4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.729  6956  6956 W art     : b6ed4000-b6ef9000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 18:22:32.729  6956  6956 W art     : b6ef9000-b6efa000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6efa000-b6f01000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-12 18:22:32.729  6956  6956 W art     : b6f01000-b6f02000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
,08-12 18:22:32.729  6956  6956 W art     : b6f02000-b6f09000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 18:22:32.729  6956  6956 W art     : b6f09000-b6f0a000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 18:22:32.729  6956  6956 W art     : b6f0a000-b6f0b000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 18:22:32.729  6956  6956 W art     : b6f0b000-b6f0c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.729  6956  6956 W art     : b6f0c000-b6f24000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
,08-12 18:22:32.729  6956  6956 W art     : b6f24000-b6f25000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6f25000-b6f26000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-12 18:22:32.729  6956  6956 W art     : b6f26000-b6f27000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 18:22:32.729  6956  6956 W art     : b6f27000-b6f35000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
,08-12 18:22:32.729  6956  6956 W art     : b6f35000-b6f36000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6f36000-b6f37000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 18:22:32.729  6956  6956 W art     : b6f37000-b6f38000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 18:22:32.729  6956  6956 W art     : b6f38000-b6f39000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:22:32.729  6956  6956 W art     : b6f39000-b6f3b000 r--p 00000000 00:00 0          [anon:linker_alloc],
08-12 18:22:32.729  6956  6956 W art     : b6f3b000-b6f3c000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 18:22:32.729  6956  6956 W art     : b6f3c000-b6f3d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 18:22:32.729  6956  6956 W art     : b6f3d000-b6f3e000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 18:22:32.729  6956  6956 W art     : b6f3e000-b6f3f000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 18:22:32.729  6956  6956 W art     : b6f3f000-b6f5f000 r--s 00000000 00:0b 6702       /dev/__properties__
08-12 18:22:32.729  6956  6956 W art     : b6f5f000-b6f60000 r--p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6f60000-b6f61000 ---p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6f61000-b6f63000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 18:22:32.729  6956  6956 W art     : b6f63000-b6f64000 r-xp 00000000 00:00 0          [sigpage]
,08-12 18:22:32.729  6956  6956 W art     : b6f64000-b6f7f000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 18:22:32.729  6956  6956 W art     : b6f7f000-b6f80000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 18:22:32.729  6956  6956 W art     : b6f80000-b6f82000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 18:22:32.729  6956  6956 W art     : b6f82000-b6f84000 rw-p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : b6f84000-b6f89000 r-xp 00000000 b3:17 978        /system/bin/app_process32
,08-12 18:22:32.729  6956  6956 W art     : b6f89000-b6f8a000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 18:22:32.729  6956  6956 W art     : b6f8a000-b6f8b000 rw-p 00000000 00:00 0 
08-12 18:22:32.729  6956  6956 W art     : bec17000-bec38000 rw-p 00000000 00:00 0          [stack]
08-12 18:22:32.729  6956  6956 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-12 18:22:32.799  6956  6956 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat,
,08-12 18:22:32.849  6956  6956 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 18:22:32.859  6956  6956 E AffinityControl: AffinityControl: registerfunction enter
,08-12 18:22:32.879  6956  6956 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 18:22:32.889   756  1416 D PackageManager: START PACKAGE DELETE: observer{179564002}
08-12 18:22:32.889   756  1416 D PackageManager: pkg{<packageName>}
08-12 18:22:32.889   756  1416 D PackageManager: user{0}
08-12 18:22:32.889   756  1416 D PackageManager: caller{2000}
08-12 18:22:32.889   756  1416 D PackageManager: flags{2}
,08-12 18:22:32.899   756  1416 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-12 18:22:32.899   756  1416 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-12 18:22:32.899   756  1416 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-12 18:22:32.899   756  1416 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-12 18:22:32.899   756  1416 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-12 18:22:32.899   756   917 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-12 18:22:32.899   756   917 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-12 18:22:32.899   756   917 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-12 18:22:32.899   756   917 D ApplicationPolicy: getApplicationUninstallationEnabled
08-12 18:22:32.899   756   917 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-12 18:22:32.899   756   917 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-12 18:22:32.899   756   917 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-12 18:22:32.899   756   917 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-12 18:22:32.899   756   842 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-12 18:22:32.899   756   842 I ActivityManager: Killing 6554:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
08-12 18:22:32.899   756   917 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-12 18:22:32.899   756   917 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-12 18:22:32.909   756   842 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 18:22:32.909   756   842 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-12 18:22:32.929   756   842 I ActivityManager: Start proc 6965:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-12 18:22:32.929  6965  6965 E Zygote  : v2
08-12 18:22:32.929  6965  6965 I libpersona: KNOX_SDCARD checking this for 10004
08-12 18:22:32.929  6965  6965 I libpersona: KNOX_SDCARD not a persona
,08-12 18:22:32.929  6965  6965 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:32.929  6965  6965 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 18:22:32.929  6965  6965 E Zygote  : accessInfo : 0
08-12 18:22:32.929  6965  6965 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-12 18:22:32.929   756   842 I ActivityManager:   Force finishing activity ActivityRecord{eb705f0 u0 com.test.thalitest/.MainActivity t167}
,08-12 18:22:32.939   293  1295 I SurfaceFlinger: id=15 Removed NainActivit (4/10)
,08-12 18:22:32.939   293   366 I SurfaceFlinger: id=15 Removed NainActivit (-2/10)
,08-12 18:22:32.939   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed8638c
,08-12 18:22:32.939   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed8638c
,08-12 18:22:32.949   756   917 D AASAinstall: there is not AASApackages.xml file
,08-12 18:22:32.979  6965  6965 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 18:22:32.979  6965  6965 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:32.989   756  3876 D GraphicsStats: Buffer count: 4
,08-12 18:22:32.989   756   772 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@fe35573)
,08-12 18:22:32.989   756  1330 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 18:22:32.989   756  1330 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-12 18:22:32.989   756  1330 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 18:22:33.249   756   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-12 18:22:33.329   756   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 18:22:33.349  6965  6965 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 18:22:33.349  6965  6965 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,08-12 18:22:33.349  6965  6965 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-12 18:22:33.359   337   337 W keystore: ENTER clear_uid from uid 1000 for 10004
08-12 18:22:33.359  6965  6965 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-12 18:22:33.359  6965  6965 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-12 18:22:33.359   756   917 I art     : Starting a blocking GC Explicit
,08-12 18:22:33.389  6965  6965 D AndroidRuntime: Shutting down VM
,08-12 18:22:33.389  6965  6965 E AndroidRuntime: FATAL EXCEPTION: main
08-12 18:22:33.389  6965  6965 E AndroidRuntime: Process: com.test.thalitest, PID: 6965
08-12 18:22:33.389  6965  6965 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-12 18:22:33.389  6965  6965 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-12 18:22:33.389  6965  6965 E AndroidRuntime: 	... 9 more
,08-12 18:22:33.409  6986  6986 E Zygote  : v2
,08-12 18:22:33.409  6986  6986 I libpersona: KNOX_SDCARD checking this for 1000
08-12 18:22:33.409  6986  6986 I libpersona: KNOX_SDCARD not a persona
08-12 18:22:33.409  6986  6986 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 18:22:33.419  6986  6986 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 18:22:33.419  6986  6986 E Zygote  : accessInfo : 0
,08-12 18:22:33.419   756   842 I ActivityManager: Start proc 6986:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,08-12 18:22:33.419  6965  6965 I Process : Sending signal. PID: 6965 SIG: 9
,08-12 18:22:33.439   756  1674 I ActivityManager: Process com.test.thalitest (pid 6965)(adj 9) has died(143,752)
,08-12 18:22:33.439   756  1674 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 18:22:33.439   756  1674 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-12 18:22:33.439   756  1674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26661 com.android.server.am.ActivityManagerService.appDiedLocked:7558 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,08-12 18:22:33.439  6986  6986 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-12 18:22:33.439  6986  6986 D ActivityThread: Added TimaKeyStore provider
,08-12 18:22:33.449   756   842 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
08-12 18:22:33.449   756   842 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,08-12 18:22:33.449   756   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1c69c30 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{24750a9 6986:com.samsung.android.sm/1000}
,08-12 18:22:33.459  6986  6986 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-12 18:22:33.499  6986  6986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-12 18:22:33.509   756  1682 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1c69c30 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b1af2e 4500:com.google.android.gms/u0a11}
,08-12 18:22:33.529   756   917 I art     : Explicit concurrent mark sweep GC freed 99081(4MB) AllocSpace objects, 15(300KB) LOS objects, 27% free, 41MB/57MB, paused 3.558ms total 165.272ms
,08-12 18:22:33.569   756   917 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 18:22:33.569   756   917 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-12 18:22:33.569   756   917 D AASAinstall: there is not AASApackages.xml file
,08-12 18:22:33.569   756   917 D PackageManager: result of delete: 1{179564002}
,08-12 18:22:33.569  6956  6956 I art     : System.exit called, status: 0
08-12 18:22:33.569  6956  6956 I AndroidRuntime: VM exiting with result code 0.
,08-12 18:22:33.569   756   917 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-12 18:22:33.569   756   917 D PackageManager: userId{-1}
08-12 18:22:33.569   756   917 D PackageManager: andCode{true}
,08-12 18:22:33.589   756   917 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-12 18:22:33.609  6142  7011 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-12 18:22:33.609  6142  7011 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-12 18:22:33.609  6142  7011 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-12 18:22:33.639   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.649  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-12 18:22:33.649  1377  1377 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-12 18:22:33.649   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.649   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.649   756   892 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.649  1946  1946 E SamsungIME: mOCRHelper is null
,08-12 18:22:33.659   756   827 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.659   756  1320 V NetworkStats: removeUidsLocked() for UIDs [10004]
,08-12 18:22:33.659   756  1320 V NetworkStats: performPollLocked(flags=0x3)
08-12 18:22:33.659   756  1320 D NtpTrustedTime: currentTimeMillis() cache hit
,08-12 18:22:33.669  1979  2223 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 18:22:33.669   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.669   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.669   756   842 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{776be1 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b3025b 3293:com.samsung.klmsagent/u0a18}
,08-12 18:22:33.679   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.679   756   892 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.679   756  1320 V NetworkStats: performPollLocked() took 12ms
08-12 18:22:33.679   756  1320 D NtpTrustedTime: currentTimeMillis() cache hit
,08-12 18:22:33.679   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.679   756  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 18:22:33.679   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.679   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.679   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.679   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.679   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.679   756   756 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.689   756   756 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.689   756   756 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.689  1654  1654 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 18:22:33.689   756  1321 D NtpTrustedTime: currentTimeMillis() cache hit
08-12 18:22:33.689   756  1321 D NtpTrustedTime: currentTimeMillis() cache hit
,08-12 18:22:33.689   756   756 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.689   756   756 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.689   756   756 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.689   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.699   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.699   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.699   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.699   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.699   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.699   756   756 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.699  3293  3293 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Fri Aug 12 18:22:33 GMT+02:00 2016
,08-12 18:22:33.699   756   756 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.699   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.699   756  1363 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/167_task.xml
,08-12 18:22:33.709  3190  3205 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 18:22:33.709   756  1363 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/167_task_thumbnail.png
,08-12 18:22:33.709  3190  3205 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 18:22:33.709  3190  3205 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 18:22:33.709  3190  3205 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 18:22:33.719   756  1875 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-12 18:22:33.719  3293  3293 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-12 18:22:33.719   756  1484 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{776be1 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c8c7d7 756:system/1000}
,08-12 18:22:33.729   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.729   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.729  3293  3293 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-12 18:22:33.729  3293  3293 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-12 18:22:33.729  3293  3293 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-12 18:22:33.729  3293  7020 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-12 18:22:33.729  3293  7020 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-12 18:22:33.729  3293  7020 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
08-12 18:22:33.729  3293  7020 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-12 18:22:33.729  3293  7020 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
,08-12 18:22:33.729  3293  7020 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-12 18:22:33.739  3293  7020 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-12 18:22:33.739  3293  7020 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-12 18:22:33.739   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.739   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.739   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.739   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.739   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.739   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.739  1645  7019 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.749  1645  7019 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.749  1645  7019 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
,08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.749  1645  7019 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
,08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.749  1645  7019 D RegisteredComponentCache: Collect Tech packages for Knox
,08-12 18:22:33.749  3293  7020 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.749  3293  7020 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
08-12 18:22:33.749   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.759   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.759   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.759  3293  7020 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2d9f3f4 in tid 7020 (IntentService[K)
08-12 18:22:33.759   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.759   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.759   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.759  2380  2380 E audit_log: File locking failed. error= Bad file descriptor
,08-12 18:22:33.759  2380  2380 E audit_log: File locking failed. error= Bad file descriptor
,08-12 18:22:33.759   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.759   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.759   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.759   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.769   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.769   756   756 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.769   756  1297 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-12 18:22:33.779   756   756 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.779   756   756 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.779   756   756 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.779   756   756 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.779   756  3649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 18:22:33.789   756   827 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.789   756   827 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.789   756  1682 I ActivityManager: Process com.samsung.klmsagent (pid 3293)(adj 5) has died(169,738)
08-12 18:22:33.789   756   756 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.789   756   756 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.789   756  1682 D ActivityManager: isAutoRunBlockedApp:: com.samsung.klmsagent, Auto Run ON
,08-12 18:22:33.789   756  1682 I ActivityManager: isWidgetUsingPkg : com.samsung.klmsagent no widget is using.
,08-12 18:22:33.789   756   756 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.789   756   756 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.789  1979  1991 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9d82a374 in tid 1991 (Binder_1)
08-12 18:22:33.789  1979  1991 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 18:22:33.789  2380  2380 E audit_log: File locking failed. error= Bad file descriptor
,08-12 18:22:33.799   756   756 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.799   756   756 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.809   756   756 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.809   756   756 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.809   756  1297 I EventHub: Removing device '/dev/input/event5' due to inotify event
08-12 18:22:33.809   756   756 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.809   756   756 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.809   756   756 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.809   756   756 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.809   756   756 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.809   756   756 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.809   756   756 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.809   756   756 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.819   756   756 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-12 18:22:33.819   756   774 D LocationManagerService: Location listener died
08-12 18:22:33.819   756  1695 D GpsStatusListenerHelper: Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@587986d
08-12 18:22:33.819   756   774 I LocationManagerService: remove 9309b70 by com.google.android.gms
08-12 18:22:33.819   756  1695 D LocationManagerService: Location listener died
,08-12 18:22:33.819   756   774 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
,08-12 18:22:33.819   756  1695 I LocationManagerService: remove e04660a by com.google.android.gms
,08-12 18:22:33.819   756  1695 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
,08-12 18:22:33.819  6226  6226 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9df09b6d in tid 6226 (.apps.magazines)
08-12 18:22:33.819  6226  6226 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 18:22:33.819  2380  2380 E audit_log: File locking failed. error= Bad file descriptor
08-12 18:22:33.819   756  1674 I ActivityManager: Process com.google.android.gms.persistent (pid 1979)(adj 1) has died(184,738)
08-12 18:22:33.819   756   756 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.819   756  1674 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gms, Auto Run ON
08-12 18:22:33.819   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
,08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.HardwareArProviderService in 11000ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 21000ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829  4500  4500 E GmsClient: service descriptor mismatch: com.google.android.gms.phenotype.internal.IPhenotypeService vs. 
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.nearby.discovery.service.ScreenOnListenerService in 30999ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 40999ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.usagereporting.service.UsageReportingService in 50999ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.lockbox.service.LockboxBrokerService in 60999ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.backup.BackupTransportService in 70999ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 80999ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 90999ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.setup.devicesignals.LockScreenService in 100999ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.phenotype.service.PhenotypeService in 110998ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 120998ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService in 130998ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no, widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 140998ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   356   356 I Zygote  : Process 3293 exited due to signal (7)
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 150998ms
08-12 18:22:33.829   756  1674 I ActivityManager: isWidgetUsingPkg : com.google.android.gms no widget is using.
08-12 18:22:33.829   756  1674 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.common.stats.GmsCoreStatsService in 160998ms
08-12 18:22:33.829  4500  4500 E GmsClient: service descriptor mismatch: com.google.android.gms.clearcut.internal.IClearcutLoggerService vs. 
08-12 18:22:33.829  4500  4500 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9a6e617d in tid 4500 (gle.android.gms)
08-12 18:22:33.829  4500  4500 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 18:22:33.829  2380  2380 E audit_log: File locking failed. error= Bad file descriptor
08-12 18:22:33.829   756   756 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.829   756   756 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.839   756   756 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.849   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.859   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-12 18:22:33.859   756   756 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
08-12 18:22:33.859   356   356 I Zygote  : Process 1979 exited due to signal (7)
08-12 18:22:33.859   756  1297 I EventHub: Removing device '/dev/input/event6' due to inotify event
08-12 18:22:33.859   756   756 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9d729aeb in tid 756 (system_server)
08-12 18:22:33.859   756   756 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 18:22:33.859  2380  2380 E audit_log: File locking failed. error= Bad file descriptor
,08-12 18:22:33.899   356   356 I Zygote  : Process 4500 exited due to signal (7)
,08-12 18:22:33.919   356   356 I Zygote  : Process 6226 exited due to signal (7)
,08-12 18:22:33.929   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'textservices' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'network_score' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'netstats' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'netpolicy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'wifip2p' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'wifi' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'wifihs20' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'wifiscanner' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'rttmanager' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'ethernet' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'connectivity' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'sb_service' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'servicediscovery' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'updatelock' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'notification' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'devicestoragemonitor' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'location' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'country_detector' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'sec_location' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'search' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'execute' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'dropbox' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'wallpaper' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'audio' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'DockObserver' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'midi' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'usb' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'serial' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'kiesusb' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'jobscheduler' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'backup' died
08-12 18:22:33.929   331  2079 W AudioFlinger: power manager service died !!!
08-12 18:22:33.929   292   292 I ServiceManager: service 'appwidget' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'voiceinteraction' died
08-12 18:22:33.929   331  2079 W AudioFlinger: power manager service died !!!
08-12 18:22:33.929   292   292 I ServiceManager: service 'SecExternalDisplayService' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'diskstats' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'mDNIe' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'AAS' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'MSCS' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'spengestureservice' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'quickconnect' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'samplingprofiler' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'commontime_management' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'dreams' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'graphicsstats' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'print' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'restrictions' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'media_session' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'media_router' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'trust' died
08-12 18:22:33.929   292   292 ,I ServiceManager: service 'fingerprint' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'launcherapps' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'voip' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'media_projection' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'lpnet' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'imms' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'sec_analytics' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'telecom' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'enterprise_license_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'application_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'wifi_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'remoteinjection' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'knox_ucsm_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'edm_proxy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'mum_container_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'otp_service' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'enterprise_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'statusbar' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'clipboard' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'clipboardEx' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'network_management' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'context_aware' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'scontext' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'barbeam' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'multiwindow_facade' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'window' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'input' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'bluetooth_manager' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'rcp' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'input_method' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'accessibility' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'cover' died
,08-12 18:22:33.929   292   292 I ServiceManager: service 'mount' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'persona_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'activity' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'user' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'procstats' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'meminfo' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'gfxinfo' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'dbinfo' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'cpuinfo' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'permission' died
,08-12 18:22:33.929   292   292 I ServiceManager: service 'processinfo' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'sensorservice' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'mdm.remotedesktop' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'battery' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'usagestats' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'webviewupdate' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'scheduling_policy' died
,08-12 18:22:33.929   292   292 I ServiceManager: service 'telephony.registry' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'persona' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'deviceidle' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'uimode' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'lock_settings' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'device_policy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'harmony_eas_service' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'sdp' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'sdp_log' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'dlp' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'log_manager_service' died
,08-12 18:22:33.929   292   292 I ServiceManager: service 'edmnativehelper' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'SEAMService' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'media.camera.proxy' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'account' died
,08-12 18:22:33.929   292   292 I ServiceManager: service 'content' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'DirEncryptService' died
,08-12 18:22:33.929   292   292 I ServiceManager: service 'LSManager' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'ReactiveService' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'DeviceRootKeyService' died
,08-12 18:22:33.929   292   292 I ServiceManager: service 'EngineeringModeService' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'SatsService' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'sedenial' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'vibrator' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'tw_toolbox' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'tima' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'iccc' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'cepproxyks' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'emailksproxy' died
,08-12 18:22:33.929   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'consumer_ir' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'alarm' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'batterystats' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'appops' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'power' died
08-12 18:22:33.929   292   292 I ServiceManager: service 'package' died
,08-12 18:22:33.929   292   292 I ServiceManager: service 'display' died
08-12 18:22:33.929  1669  1680 W Sensors : sensorservice died [0xad39c180]
08-12 18:22:33.929  1377  2175 W Sensors : sensorservice died [0xaadd4e40]
08-12 18:22:33.929  2420  2450 W Sensors : sensorservice died [0xa917da00]
08-12 18:22:33.929  1654  1654 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
,08-12 18:22:33.939  1377  1607 E WifiManager: Channel connection lost
08-12 18:22:33.939   293  1295 I SurfaceFlinger: restart the boot-animation @ binderDied
08-12 18:22:33.939  1654  2171 E WifiManager: Channel connection lost
08-12 18:22:33.939   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
08-12 18:22:33.939   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=2 Removed GocusedStac (4/9)
,08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/8)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=4 Removed EimLayer(An (0/7)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=9 Removed EimLayer(Di (3/6)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=10 Removed EimLayer(An (0/5)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
,08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=5 Removed TtatusBar (3/4)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=5 Removed TtatusBar (-2/4)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=6 Removed JmageWallpa (0/3)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=6 Removed JmageWallpa (-2/3)
08-12 18:22:33.939   293   368 D libEGL  : eglTerminate EGLDisplay = 0xb677f6fc
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=13 Removed DolorFade (2/2)
,08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=13 Removed DolorFade (-2/2)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=9 Removed EimLayer(Di (-2/2)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=10 Removed EimLayer(An (-2/2)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=16 Removed VSBConnecti (1/1)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=17 Removed VSBConnecti (0/0)
08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/0)
,08-12 18:22:33.939   293  1294 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/0)
08-12 18:22:33.939  2375  2375 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ede430a in tid 2375 (droid.bluetooth)
08-12 18:22:33.939  1965  1978 W Sensors : sensorservice died [0xa91bdc40]
08-12 18:22:33.949   335   335 E installd: eof
08-12 18:22:33.949   335   335 E installd: failed to read size
08-12 18:22:33.949   335   335 I installd: closing connection
,08-12 18:22:33.949  1783  1917 E WifiManager: Channel connection lost
,08-12 18:22:33.949  2375  2375 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 18:22:33.949  2380  2380 E audit_log: File locking failed. error= Bad file descriptor
,08-12 18:22:33.949  5756  5835 E WifiManager: Channel connection lost
,08-12 18:22:33.969  2412  2412 D BluetoothA2dp: Proxy object disconnected
08-12 18:22:33.969  5045  5045 D BluetoothA2dp: Proxy object disconnected
08-12 18:22:33.969  5045  5045 D A2dpProfile: Bluetooth service disconnected
,08-12 18:22:33.969  5045  5045 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-12 18:22:33.969  5045  5045 D PanProfile: Bluetooth service disconnected
08-12 18:22:33.969  5045  5045 D BluetoothMap: Proxy object disconnected
08-12 18:22:33.969  5045  5045 D MapProfile: Bluetooth service disconnected
,08-12 18:22:33.969  5045  5045 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b9172bd in tid 5045 (ndroid.settings)
,08-12 18:22:33.969  5045  5045 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 18:22:33.969  2380  2380 E audit_log: File locking failed. error= Bad file descriptor
,08-12 18:22:34.039   356   356 I Zygote  : Process 2375 exited due to signal (7)
,08-12 18:22:34.039   356   356 I Zygote  : Process 5045 exited due to signal (7)
,08-12 18:22:34.129   291   291 I lowmemorykiller: ActivityManager disconnected
08-12 18:22:34.129   291   291 I lowmemorykiller: Closing Activity Manager data connection
,08-12 18:22:34.189   293   549 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,08-12 18:22:34.189   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-12 18:22:34.189   293   567 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
,08-12 18:22:34.189   293   567 E SurfaceFlinger: eventControl(0, 1) failed Operation not permitted
,08-12 18:22:34.409   293   549 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 18:22:34.439   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-12 18:22:34.439   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed863a4
,08-12 18:22:34.439   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed8638c
,08-12 18:22:34.439   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed8638c
,08-12 18:22:34.439   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed8638c
,08-12 18:22:34.449   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed8638c
,08-12 18:22:34.449   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed863a4
,08-12 18:22:34.449   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbed8638c

```
