# SPDX-License-Identifier: BSD-3-Clause
# Copyright(c) 2017 Intel Corporation

sources = files(
        'sw_evdev_scheduler.c',
        'sw_evdev_selftest.c',
        'sw_evdev_worker.c',
        'sw_evdev_xstats.c',
        'sw_evdev.c',
)
deps += ['hash', 'bus_vdev']
require_iova_in_mbuf = false
cflags += no_wvla_cflag
