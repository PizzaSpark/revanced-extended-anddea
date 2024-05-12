# ReVanced Module
[![CI](https://github.com/PizzaSpark/revanced-extended-builds/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/PizzaSpark/revanced-extended-builds/actions/workflows/ci.yml)

Extensive ReVanced builder for inotia00 and anddea patches

Get the [latest CI release](https://github.com/PizzaSpark/revanced-extended-builds/releases).

<details><summary><big>Features</big></summary>
<ul>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimize APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> recompile invalidated odex for faster usage</li>
     <li> handle installation of the correct version of the stock app and all that</li>
     <li> support Magisk and KernelSU</li>
    </ul>
</ul>

## To include/exclude patches or patch other apps
[**See the list of patches**](https://j-hc.github.io/rvmm-config-gen/)

 * Star the repo :eyes:
 * Use the repo as a [template](https://github.com/new?template_name=revanced-magisk-module&template_owner=j-hc)
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also see here [`CONFIG.md`](./CONFIG.md)
