# 私有源文件
_gd32f4xx_src = files('./src/system_gd32f4xx.c', './src/reset.c', './src/gcc/vector_table.c')

# 私有头文件路径
_gd32f4xx_inc = include_directories('./inc')

# 链接脚本文件的绝对路径
linker_script_path = meson.current_source_dir() / 'src/gcc/link/link.ld'

# 添加依赖
hc32f4xx_dep = declare_dependency(
    compile_args : [
        '-DUSE_STDPERIPH_DRIVER',
        '-DGD32F450',
    ],
    link_args : ['-T', linker_script_path],
    sources : _gd32f4xx_src,
    include_directories : _gd32f4xx_inc,
)