# linux_binary_cache

## Overview

This repository contains Linux kernels for benchmarks which need Linux VMs as baselines.

`6.16.0/vmlinuz` is compiled from Linux 6.16.0 source code with TDX host settings enabled and Ext2 file system enabled. It additionally enables the built-in virtio-fs and vhost-vsock support required by Asterinas benchmarks. Its full kernel configuration is stored in `6.16.0/.config`.
