-----------------------------------------------------------------------------

<p align="center">
 <img src="https://github.com/SuperiorOS-beta/manifest/blob/twelve/superior.jpg" > 
</p>

-----------------------------------------------------------------------------
Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)

-----------------------------------------------------------------------------

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

Sync Source:-
=================

```bash
    repo init -u git://github.com/SuperiorOS-beta/manifest.git -b twelve
```
```bash
    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

Start the build:-
=================

```bash
  . build/envsetup.sh
  lunch superior_<devicecodename>-userdebug
  mka bacon -jx
```
-----------------------------------------------------------------------------

Some Links:-
============
* [**Telegram Public Chat**](https://t.me/superioros)
* [**Telegram Channel**](https://t.me/superior_os)
* [**Jenkins**](https://jenkins.superioros.org)
* [**Gerrit**](https://gerrit.superioros.org)
* [**Crowdin**](https://translations.superioros.org)
----------------------------------------------------------------------------

Download Stats
==============

[![Download Superior](https://img.shields.io/sourceforge/dd/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download)

[![Download Superior](https://img.shields.io/sourceforge/dw/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download)

[![Download Superior](https://img.shields.io/sourceforge/dm/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download)

[![Download Superior](https://img.shields.io/sourceforge/dt/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download)
---------------------------------------------------------------------------------

