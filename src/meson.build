# 加载子目录
subdir('libs')
subdir('bsp')
subdir('app')
subdir('config')

# 添加依赖
src_dep = declare_dependency(
    dependencies : [
        ibs_dep,
        bsp_dep,
        app_dep,
        config_dep,
    ],
)