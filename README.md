<p align="center">
  <img align="center" src="img/icon.png">
</p>

<p align="center">
  🔍 An in-game UI for exploring, debugging and modifying Unity games.
</p>
<p align="center">
  ✔️ Supports most Unity versions from 5.2 to 2021+ (IL2CPP and Mono).
</p>
<p align="center">
  ✨ Powered by <a href="https://github.com/blackjack4494/UniverseLib">*Forked* UniverseLib</a>
</p>

## BepInEx

<b>This is a precompiled version! Feel free to build it yourself (see [Building](#building) section) </b>

| Release | IL2CPP |
| ------- | ------ |
| BIE 6.X | ✅ [link](https://locoserver.net/dl/unityexplorer_bie6.zip) | 

1. Unzip the release file into a folder
2. Take the `plugins/sinai-dev-UnityExplorer` folder and place it in `BepInEx/plugins/`

<i>Note: BepInEx 6 is obtainable via [builds.bepinex.dev](https://builds.bepinex.dev/projects/bepinex_be)</i>

# Building

1. Run the `betterbuild.ps1` powershell script to build UnityExplorer. Releases are found in the `Release` folder.



# Acknowledgments

* [ManlyMarco](https://github.com/ManlyMarco) for [Runtime Unity Editor](https://github.com/ManlyMarco/RuntimeUnityEditor) \[[license](THIRDPARTY_LICENSES.md#runtimeunityeditor-license)\], the ScriptEvaluator from RUE's REPL console was used as the base for UnityExplorer's C# console.
* [Geoffrey Horsington](https://github.com/ghorsington) for [mcs-unity](https://github.com/sinai-dev/mcs-unity) \[no license\], used as the `Mono.CSharp` reference for the C# Console.

### Disclaimer

UnityExplorer is in no way associated with Unity Technologies. "Unity", Unity logos, and other Unity trademarks are trademarks or registered trademarks of Unity Technologies or its affiliates in the U.S. and elsewhere.
