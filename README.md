To Fix :
========

imoz7.mk


kernel
======

	export PATH=~/Your_Toolchain_PATH/ 
	for_example  /alps/prebuilt/linux-x86/toolchain/arm-linux-androideabi-4.4.x/bin:$PATH
	cd <kernel path>
	cp mediatek-configs .config
	TARGET_PRODUCT=imoz7 MTK_ROOT_CUSTOM=../mediatek/custom make
