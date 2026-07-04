# 加载子目录
subdir('dev')

# 私有头文件路径
_cmsis_inc = include_directories('./inc')

# 添加依赖
cmsis_dep = declare_dependency(
    include_directories : _cmsis_inc,
    dependencies : dev_dep,
)