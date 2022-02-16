# Fujitsu S1300 Drivers for Arch

## Setup

1. install this package.
1. ensure that the file `/etc/sane.d/epjitsu.conf` contains this block:
    ```
    # Fujitsu S1300
    firmware /usr/share/sane/epjitsu/1300_0C26.nal
    usb 0x04c5 0x11ed
    ```
1. discover the scanner with `sudo sane-find-scanner`
1. test with `scanimage -L` this didn't work for me..
1. test with
    * `scanimage -L` (didn't work for me)
    * the **Simple Scan** app (can only do single-side scans)
    * the **gscan2pdf** app (can do double-side scans! 🎊)


## Links

- https://www.josharcher.uk/code/install-scansnap-s1300-drivers-linux/
- https://github.com/mkortekaas/linux-scansnap
- https://blog.dtpnk.tech/en/install_snapscan/#
