# 加载子目录
subdir('driver')
subdir('rtt')
subdir('rtos')

# 添加依赖
libs_dep = declare_dependency(
    dependencies : [
        driver_dep,
        rtt_dep,
        rtos_dep,
    ],
)
