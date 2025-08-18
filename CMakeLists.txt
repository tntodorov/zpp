#
# Prefer Kconfig selection, which ensures
# that all needed options are set
#
if (CONFIG_ZPP_LIB)
  zephyr_include_directories(include)
endif()
