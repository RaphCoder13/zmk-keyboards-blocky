if(CONFIG_SHIELD_BLOCKY_LEFT OR CONFIG_SHIELD_BLOCKY_RIGHT)
  zephyr_include_directories(.)
endif()

add_subdirectory_ifdef(CONFIG_SHIELD_BLOCKY_LEFT OR CONFIG_SHIELD_BLOCKY_RIGHT boards/shields/blocky)
