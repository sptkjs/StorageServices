# Azure Storage Services for Unity3d
Save and load image textures, audio files, json or xml data files for use in Unity.
You can also store Unity Asset Bundles to load Prefabs with referenced scripts to work in your game / application.

## Prerequisites
* Unity v5.5+
 - [UnityWebRequest](https://docs.unity3d.com/Manual/UnityWebRequest.html) and [JsonUtility](https://docs.unity3d.com/ScriptReference/JsonUtility.html) features are used. Unity will be extending platform support for UnityWebRequest so keep Unity up to date if you need to support these additional platforms.

## How to setup Storage Services with a new Unity project
1. [Download StorageServices](https://github.com/Unity3dAzure/StorageServices/archive/master.zip)  
	* Copy 'StorageServices' into project `Assets` folder.
2. Create [Azure](https://portal.azure.com) Storage Service

## Supported platforms
Will work on all the platforms [UnityWebRequest](https://docs.unity3d.com/Manual/UnityWebRequest.html) supports including:
* Unity Editor and Standalone players
* iOS
* Android
* Windows

## Notes
This library is currently in early beta, so not all APIs are supported yet and some things may change.

Questions or tweet #Unity #Azure [@deadlyfingers](https://twitter.com/deadlyfingers)
