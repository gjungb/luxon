# Changelog

## 0.0.19
 * Fixed parsing for ordinals
 * Made parsing stricter

## 0.0.18
 * Fixed formatting for non-hour aligned fixed-offset zones
 * Fixed longterm conversion accuracy option in diffs
 * Fixed invalid handling in `Interval#set`

## 0.0.17
 * Fixing formatting for fixed-offset zones

## 0.0.16
 * Fixes for IE 9 & 10

## 0.0.15
 * Fixing busted release 0.0.14

## 0.0.13

 * toLocaleString() and others default to the system's locale
 * support for ISO week durations in `Duration.fromISO`

## 0.0.12

 * Improve non-Intl fallbacks for toLocaleString
 * Fix `offsetNameShort` and `offsetNameLong` for non-Intl environments
 * Added `weekdayShort`, `weekdayLong`, `monthShort`, `monthLong` DateTime getters

## 0.0.10

 * Only include build dir in NPM module

## 0.0.9

 * Move to Moment Github org

## 0.0.8

 * The local zone can now report its IANA name
 * Fixed parsing bug for `yy` and `kk`
 * Improved test coverage

## 0.0.7

 * Added `toLocaleParts`
 * Slighly more friendly month/weekday parsing
 * Default locale setting

## 0.0.6

 * Stricter `toJSDate`
 * `fromISO` now supports `year` and `year-month` formats
 * More graceful degradation in the absence of platform features

## 0.0.5

Experimental, but now broadly useful.
