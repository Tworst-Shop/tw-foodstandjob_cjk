# tw-foodstandjob_cjk

Optional 3D Chinese letters for the stand name sign of **Tworst Food Stands** (`tw-foodstandjob`). Free download.

The stand owner can name the stand in any alphabet. Latin names use the 3D letters of the job.
A Chinese name shows on a flat name card on the sign. Install this resource to spell Chinese names with 3D letters instead.

* 3755 common Chinese characters (GB2312 level 1).
* About 30 MB that every player downloads. Install it only if your players use Chinese names.
* A name with a character that is not in the set (Japanese kana, Korean, a rare character) still shows on the name card. Nothing breaks.

## Install

1. Download **`tw-foodstandjob_cjk-<version>.zip` from [Releases](https://github.com/Tworst-Shop/tw-foodstandjob_cjk/releases/latest)**.
2. Extract it into `resources/[tw-foodstand]/`. You get `resources/[tw-foodstand]/tw-foodstandjob_cjk/`.
3. In `server.cfg`, add the line before `ensure tw-foodstandjob`:
   ```
   ensure tw-foodstandjob_cjk
   ensure tw-foodstandjob
   ```
4. Restart the server.

To remove it, delete the folder and the `ensure` line. Chinese names go back to the name card.

## `dui = false`

With `Config.StandProps.sign.dui = false` there is no name card. Then this resource is required for Chinese names: without it, a Chinese name does not show on the sign.

## Compatibility

Works with `tw-foodstandjob` 1.0.1 and newer.
