# Copyright (c) 2020 ARM Limited. All rights reserved.
# SPDX-License-Identifier: Apache-2.0

# set(MBED_PATH "../../../Externals/mbed-os" CACHE INTERNAL "")
add_subdirectory(TARGET_PYBOARD_V11) # This is the new line to add
add_subdirectory(${MBED_PATH})          # This line already exists