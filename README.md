<h1 align="center">Jellyfin TMDb Box Sets Plugin</h1>
<h3 align="center">Part of the <a href="https://jellyfin.media">Jellyfin Project</a></h3>

<p align="center">
<img alt="Plugin Banner" src="https://raw.githubusercontent.com/jellyfin/jellyfin-ux/master/plugins/SVG/jellyfin-plugin-tmdbboxsets.svg?sanitize=true"/>
<br/>
<br/>
<a href="https://github.com/jellyfin/jellyfin-plugin-tmdbboxsets/actions?query=workflow%3A%22Test+Build+Plugin%22">
<img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/jellyfin/jellyfin-plugin-tmdbboxsets/Test%20Build%20Plugin.svg">
</a>
<a href="https://github.com/jellyfin/jellyfin-plugin-tmdbboxsets">
<img alt="MIT License" src="https://img.shields.io/github/license/jellyfin/jellyfin-plugin-tmdbboxsets.svg"/>
</a>
<a href="https://github.com/jellyfin/jellyfin-plugin-tmdbboxsets/releases">
<img alt="Current Release" src="https://img.shields.io/github/release/jellyfin/jellyfin-plugin-tmdbboxsets.svg"/>
</a>
</p>

## About
Jellyfin TMDb Box Sets plugin is a plugin built with .NET that automatically creates Box Sets and Collections based on TMDb's collection IDs.

## Build Process

1. To build and run this plugin you will need [jprm](https://github.com/oddstr13/jellyfin-plugin-repository-manager) as well as [.Net Core 5.x](https://dotnet.microsoft.com/download/dotnet/5.0).

2. Run the build via `jprm`
  ```
  jprm plugin build --output=../artifacts
  ```

3. Place the resulting file in the `plugins` folder of your JF install
