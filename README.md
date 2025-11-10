# HydropowerModel
水电机组模型



1. init.slx为最初的模型，其他模型为在此基础上修改模块后的模型，根据修改的模块来命名新模型，如：仅修改水库Reservoir模块，可命名为Reservoir2.slx；修改了水库Reservoir、进水道InletRace和水轮机Turbine三个模块可命名为Reservoir2InletRace2Turbine2.slx。目录1、2、3、4、5表示其中模型修改的模块个数。
2. 目前不同模块有：水库Reservoir两个、进水道InletRace两个、水轮机Turbine三个、虚拟同步发电机VSG五个、电网Grid三个。排列组合共计180个。
