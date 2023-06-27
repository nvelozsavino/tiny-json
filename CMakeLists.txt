#
# Copyright (c) 2020 Circuit Dojo LLC
#
# SPDX-License-Identifier: Apache-2.0
#



zephyr_library()

zephyr_library_sources_ifdef(CONFIG_TINY_JSON tiny-json.c)
zephyr_include_directories_ifdef(CONFIG_TINY_JSON .)
