��ǰmpp�汾ͬʱ֧�� ��ϵͳlinux���� �� linux+liteOS˫ϵͳ��������������mppĿ¼��ͬʱ�� cfg.mak.single��cfg.mak.biglittle��cfg.mak.multicore ����cfg�ļ���ʹ�÷����ǣ�

��һ�����ʹ�õ��� ��ϵͳlinux��������Ҫ��cfg.mak.multicore�ļ�����Ϊcfg.mak��Ȼ����sample��toolĿ¼��ȥ����

���������ʹ�õ��� linux+liteOS˫ϵͳ��������
    ��1�����Ҫ����A53UP LiteOS�����е�ģ�飬��vi��vo��venc�ȣ���Ҫ�Ƚ�cfg.mak.single�ļ�����Ϊcfg.mak���ٽ��б���
    ��2�����Ҫ����A73MP Linux�����е�ģ�飬��SVP�ȣ���Ҫ�Ƚ�cfg.mak.biglittle�ļ�����Ϊcfg.mak���ٽ��б���


MPP package supports both single-system linux program and linux+liteOS dual-system program, the mpp package at the same time includes cfg.mak.single, cfg.mak.biglittle and cfg.mak.multicore three cfg files. How to use:

(A) If you are using the single-system linux program, you need to rename cfg.mak.multicore to cfg.mak, and then compile in the sample, tool directory.
(B) If you are using linux+liteOS dual-system program, then:
    (1) If you want to compile modules running on A53UP LiteOS, such as vi, vo, venc, etc., you need to first renamed cfg.mak.single to cfg.mak, and then compile.
    (2) If you want to compile modules running on A73MP Linux, such as SVP, you need to first renamed cfg.mak.biglittle to cfg.mak, and then compile.
