###### step1 MagicaVoxel 建模，导出*.obj,*.mtl,*.png至本地目录
###### step2 Blender 减面，导入MagicaVoxel目录中的*.obj，导出*.fbx至本地目录
###### step3 Mixamo 绑定骨骼，导入Blender目录中的*.fbx，选中[T-POS]和[with skin]，导出*_t_pos.fbx至本地目录
###### step4 Blender 刷权重，导入Mixamo目录中的*_t_pos.fbx，导出*_t_pos.fbx至本地目录
###### step5 Unreal4 导入Blender目录中的*_t_pos.fbx
###### step6 Mixamo 继续绑定骨骼动画，【Download】选【Without Skin】，导出*_anim.fbx至本地目录
###### step7 Unreal4 导入Mixamo目录中的*_anim.fbx，【Mesh】【Skeleton】指定之前的*_t_pos_Skeleton
###### step8 重复 6，7
