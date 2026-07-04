# 加载子目录
subdir('cmsis')
subdir('std')
# subdir('usb')

# 添加依赖
driver_dep = declare_dependency(
    dependencies : [
        cmsis_dep,
        std_dep,
        # usb_dep,
    ],
)
