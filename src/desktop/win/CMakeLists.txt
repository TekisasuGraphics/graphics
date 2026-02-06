# Desktop Integration
# Copyright (C) 2025 Igara Studio S.A.
# Copyright (C) 2017-2018 David Capello

add_library(tekisasugraphics-thumbnailer SHARED
  dllmain.cpp
  exports.def
  thumbnail_handler.cpp)

target_link_libraries(tekisasugraphics-thumbnailer
  laf-base
  dio-lib
  render-lib
  shlwapi)
