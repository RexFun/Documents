# P35

## 背部旋转传递（即：关节1 90度，关节2 80度，关节3 70度）

###### Step1. 【backBone1】+【backBone2】-> CTRL+SHIFT+C -> 【Child Of】

###### Step2. 【backBone2】->【BoneConstraints】->【Set Inverse】，【右视图】选中【backBone1】做旋转测试

###### Step3. 复制约束：【backBone3】+【backBone2】->【Pose】->【Constraints】->【Copy Constraints to Selected】（即:backBone2的约束复制到backBone3）
