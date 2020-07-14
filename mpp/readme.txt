当前mpp版本同时支持 单系统linux方案 和 linux+liteOS双系统方案，发布包的mpp目录下同时有 cfg.mak.single、cfg.mak.biglittle和cfg.mak.multicore 三个cfg文件。使用方法是：

（一）如果使用的是 单系统linux方案，需要将cfg.mak.multicore文件更名为cfg.mak，然后在sample、tool目录下去编译

（二）如果使用的是 linux+liteOS双系统方案，则：
    （1）如果要编译A53UP LiteOS上运行的模块，如vi、vo、venc等，需要先将cfg.mak.single文件更名为cfg.mak，再进行编译
    （2）如果要编译A73MP Linux上运行的模块，如SVP等，需要先将cfg.mak.biglittle文件更名为cfg.mak，再进行编译


MPP package supports both single-system linux program and linux+liteOS dual-system program, the mpp package at the same time includes cfg.mak.single, cfg.mak.biglittle and cfg.mak.multicore three cfg files. How to use:

(A) If you are using the single-system linux program, you need to rename cfg.mak.multicore to cfg.mak, and then compile in the sample, tool directory.
(B) If you are using linux+liteOS dual-system program, then:
    (1) If you want to compile modules running on A53UP LiteOS, such as vi, vo, venc, etc., you need to first renamed cfg.mak.single to cfg.mak, and then compile.
    (2) If you want to compile modules running on A73MP Linux, such as SVP, you need to first renamed cfg.mak.biglittle to cfg.mak, and then compile.
