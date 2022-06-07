- OBS-Stats - All the stats that I could find for your OBS is here with streamer.bot
  * [GetCurrentProfile](#getcurrentprofile)
  * [GetCurrentSceneCollection](#getcurrentscenecollection)
  * [GetCurrentTransition](#getcurrenttransition)
  * [GetRecordingStatus](#getrecordingstatus)
  * [GetStats N/A](#getstats)
  * [GetStreamingStatus](#getstreamingstatus)
  * [GetStudioModeStatus](#getstudiomodestatus)
  * [GetVersion](#getversion)
  * [GetVideoInfo](#getvideoinfo)
  * [GetVirtualCamStatus](#getvirtualcamstatus)
  * [SceneCount](#scenecount)
  * [SourceCount](#sourcecount)

---

## GetCurrentProfile
This gets the current profile your obs is currently on.

Message: "The current obs profile is: {profileName}

---

## GetCurrentSceneCollection
This gets the current scene collection your obs is currently on.

Message: "The current scene collection is: {sceneCollectionName}"

---

## GetCurrentTransition
This gets the current transition of your obs with the duration of it as well.

Message: "The current obs transition is: {name} with the duration of: {duration}"

---

## GetRecordingStatus
This gets the current recording status of your obs.

Message: "The current recording status is: {isRecording}"

---

## GetStreamingStatus
This gets the current streaming status of your obs.

Message: "The current streaming status is: {streaming}"

---

## GetStudioModeStatus
This gets the current studio mode status of your obs.

Message: "The current studio mode status is: {studioMode}"

---

## GetVersion
This gets the current version of your obs.

Message: "The OBS version of my OBS is: {obsVersion}"

---

## GetVideoInfo
This gets the current video info of your obs.

Message: "The video info of my OBS is: {baseWidth}x{baseHeight} {fps} fps"

---

## GetVirtualCamStatus
This gets the current virtual cam status of your obs.

Message: "The current virtual cam status is: {isVirtualCam}"

---

## SceneCount
This gets the current scene count of your obs.

Message: "The scene count is: {scenes.Count}"

---

## SourceCount
This gets the current source count of your obs.

Message: The source count is: {sources.Count}"

---

## GetStats
This gets some stats of your obs (fps, cpu-usage). N/A

Message: "The stats of my OBS are: {fps} fps, {cpuUsage} cpu-usage"
