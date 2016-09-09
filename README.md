# Focal-Mechanism-Solution-Tool
#
#简单的说明

faultpoltc.m: 绘制点源滑动模型;
faultpoltc.m: 绘制有限断层滑动模型;
az2pl.m: 根据T,B和P轴的方位角计算T,B和P轴的俯角;
caldccd.m: 计算地震矩张量中CLVD和DC成分各自所占的比重;
caldcm.m: 根据地震矩张量求解地震节面参数和标量地震矩(与calsdrm.m不同的是,该函数从地震矩张量中提取双力偶成分,
然后直接解算地震节面参数,其局限性在于不能求解倾角等于0或90的地震节面的走向,倾角和滑动角);
calsdr.m: 根据滑动矢量和节面外法向求解地震节面的走向,倾角和滑动角;
calsdrm.m: 根据地震矩张量求解节面走向,倾角和滑动角以及标量地震矩;
dc3d.m:绘制双力偶源三维辐射花样和地震节面的空间位置;
fm3d.m: 绘制三维辐射因子和两个地震节面的空间位置;fp3d.m: 绘制地震节面的空间位置;
mnez.m: 坐标变换;
muse.m: 坐标变换;
mt2tbp.m: 根据地震矩张量求解T,B和P轴的俯角和方位角;
pattern3d.m: 绘制P,S,SH和SV波的辐射花样;
tbp2sdr.m: 根据T,B和P轴中任意两个轴的俯角和方位角求解地震节面参数;
vbplot.m: 绘制沙滩排球;
