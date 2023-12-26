Cloudmesh Command progress
=====================

[![GitHub Repo](https://img.shields.io/badge/github-repo-green.svg)](https://github.com/cloudmesh/cloudmesh-progress)
[![image](https://img.shields.io/pypi/pyversions/cloudmesh-progress.svg)](https://pypi.org/project/cloudmesh-progress)
[![image](https://img.shields.io/pypi/v/cloudmesh-progress.svg)](https://pypi.org/project/cloudmesh-progress/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

[![General badge](https://img.shields.io/badge/Status-Production-<COLOR>.svg)](https://shields.io/)
[![GitHub issues](https://img.shields.io/github/issues/cloudmesh/cloudmesh-progress.svg)](https://github.com/cloudmesh/cloudmesh-progress/issues)
[![Contributors](https://img.shields.io/github/contributors/cloudmesh/cloudmesh-progress.svg)](https://github.com/cloudmesh/cloudmesh-progress/graphs/contributors)
[![General badge](https://img.shields.io/badge/Other-repos-<COLOR>.svg)](https://github.com/cloudmesh/cloudmesh)


[![Linux](https://img.shields.io/badge/OS-Linux-orange.svg)](https://www.linux.org/)
[![macOS](https://img.shields.io/badge/OS-macOS-lightgrey.svg)](https://www.apple.com/macos)
[![Windows](https://img.shields.io/badge/OS-Windows-blue.svg)](https://www.microsoft.com/windows)





## Manual Page

<!-- START-MANUAL -->
```
Command progress
================

::

  Usage:
        progress PROGRESS [--status=STATUS] [--pid=PID] [--now] [KEY=VALUE...] [--sep=SEP] [--banner]

  Prints a progress line of the form


   "# cloudmesh status=ready progress=0 pid=$$ time='2022-08-05 16:29:40.228901' key1=value1 key2=value2"

  Arguments:
      PROGRESS   the progess in value from 0 to 100
      KEY=VALUE   the key value pars to be added

  Options:
      --status=STATUS      the status [default: running]
      --pid=PID            the PID
      --now                add a time of now
      --sep=SEP            separator when adding key=values
      --banner             creates also a banner when specified [default: None]

  Description:

    The example
        progress 50 --status=running --pid=101 --now user=gregor
    produces
        # cloudmesh status=running progress=0 pid=123 time='2022-08-05 16:29:40.228901' user=gregor
```
<!-- STOP-MANUAL -->