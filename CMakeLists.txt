idf_component_register(SRC_DIRS "src"
                INCLUDE_DIRS "include"
                PRIV_INCLUDE_DIRS "src")

target_compile_options(${COMPONENT_TARGET} PUBLIC -DBACDL_MSTP -DMAX_TSM_TRANSACTIONS=10)
