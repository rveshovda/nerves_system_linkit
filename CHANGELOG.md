# Changelog

## v0.6.3-dev

## v0.6.2

  * Bug fixes
    * Enable /dev/mem
    * Move Linux kernel to /boot, since that turned out to be an easier way to
      update in the near-term

## v0.6.1

  * Package versions
    * Nerves.System.BR v0.6.1
    * Linux 4.4

  * New features
    * On board wi-fi works

## v0.6.0
  * Nerves.System.BR v0.6.0
    * Package updates
      * Erlang OTP 19
      * Elixir 1.3.1
      * fwup 0.8.0
      * erlinit 0.7.3
      * bborg-overlays (pull in I2C typo fix from upstream)
    * Bug fixes
      * Synchronize file system kernel configs across all platforms

## v0.5.0

  * Nerves.System.BR v0.4.1
    * Bug fixes
      * syslinux fails to boot when compiled on some gcc 5 systems
      * Fixed regression when booting off eMMC on the BBB

    * Package updates
      * Erlang 18.3
      * Elixir 1.2.5
  * Enhancements
    * Includes config-pin for controlling pin muxing. more info: https://github.com/cdsteinkuehler/beaglebone-universal-io
