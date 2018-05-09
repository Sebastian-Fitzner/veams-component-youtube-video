<p align="right">
    <a href="https://badge.fury.io/js/@veams/component-youtube-video"><img src="https://badge.fury.io/js/@veams/component-youtube-video.svg" alt="npm version" height="18"></a>
    <a href="https://gitter.im/Sebastian-Fitzner/Veams?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge"><img src="https://badges.gitter.im/Sebastian-Fitzner/Veams.svg" alt="Gitter Chat" /></a>
</p>

# Youtube Video

## Description

A youtube video component.

-----------

## Installation

### Installation with Veams

```bash
veams install component youtube-video
```
``` bash 
veams -i c youtube-video
```

-----------

## Fields

### `youtube-video.hbs`

#### Settings

| Parameter | Type | Value | Description |
|:--- | :---: |:---: | :--- |
| settings.youtubeVideoContextClass | String | `default` | Context class of component. |
| settings.youtubeVideoClasses | String | | Modifier classes for component. |

#### Content

| Parameter | Type | Description |
|:--- | :---: | :--- |
| content.youtubeVideoUrl | String |  Url to video file. |
| content.youtubeVideoWidth | String |  Width of the video. |
| content.youtubeVideoHeight | Object |  Height of the video. |
