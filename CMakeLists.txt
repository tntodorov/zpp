#
# Prefer Kconfig selection, which ensures
# that all needed options are set
#
if (CONFIG_LIB_ZPP)
  zephyr_include_directories(include)
endif()
