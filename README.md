# UE4 Extracted String Inventory — Individual Explanations

## Scope and interpretation

This document explains every non-empty entry from the supplied `paths.txt` inventory, one by one, in its original order. The list appears to contain strings associated with an Unreal Engine 4 game build, including source-path remnants, engine/plugin paths, asset references, runtime paths, and other identifiers.

**Important limitation:** these are interpretations based on the string and its path/name. A string extracted from a binary does not prove that the named source file was shipped, that the referenced code is reachable, or that the behavior implied by a name is implemented exactly as described. Confirm behavior with disassembly, cross-references, symbols, and runtime evidence. Security-related names are flagged as leads, not proof of a protection mechanism.

**Inventory entries:** 2656 (including repeated entries, if any).

## 1. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Launch\Private\Android\AndroidJNI.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\CharacterAnimState\Vehicle\VehicleCharacterAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 3. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\ModifyAdditivePose\STExtraBaseCharacter_AdditivePose.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 4. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Actor\Action\ModelActor_AutoDestroy.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 5. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\AnimInt\STExtraBagPetAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 6. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Custom\Custom_Particle.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 7. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AvatarDIY\Action\AvatarAction_ApplyWeaponHandle.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 8. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\Interface\BackpackClearAndRecoverProxy.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 9. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Buff\GSListener_GunReload.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 10. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\FootprintInstanceActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 11. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\IdeaDecalActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 12. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\PostProcessManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 13. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CustomParticleSystemComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 14. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\GeneralSMComponent\GeneralSMComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 15. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\MovementComponent\ZiplineMovementComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 16. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\NewbieGuideComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 17. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameLua\GameLuaAPI.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 18. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameLua\LuaTimerEnv.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 19. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\SingleTraining\SingleTrainingGameState.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 20. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\House\STExtraBreakableHouseActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 21. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\PetEventManagerComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 22. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\STExtraPlayerState.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 23. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Private\GameMode\HardPoint\BRGameModeTeam_HardPoint.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 24. `/Game/Mod/TDM/BluePrints/UI/PointMode/PMode_EnemyItem_UIBP.PMode_EnemyItem_UIBP_C`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 25. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Assist\UAERecastNavMeshDynamic.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 26. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\AvatarAction\UTAvatarAction_AttachMesh.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 27. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\MainSoundVisualizationWidget.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 28. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\Map\MapUIBase.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 29. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Utility\AvatarRuntimeUtils.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 30. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Tank\VehicleProtectionComponentTank.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 31. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleDamageComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 32. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\LaserSeekAndLockWeaponComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 33. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\AIActionExecutionComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 34. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTaskNode_FindItemSpot.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 35. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_ChangeAvatarMaterials.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 36. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_JumpByStages.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 37. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_JumpToRandomPhase.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 38. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UTSkillAppearance_SimpleParticleSystem.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 39. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SmartBearer\SmartBearerContext.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 40. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\FreeWallClimbing\AnimInstance_FreeWallClimbing.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 41. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\NinjaMove\NinjaMoveAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 42. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Spectating\OB\SyncOBDataActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 43. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\BioSpecialMoves\BioSpecialMove_Fly.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 44. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Components\BioVehicleLagCompensationComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 45. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\LandingCreatures\TyrannosaurusRex\TyrannosaurusRexVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 46. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\HAL\MallocBinned.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 47. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Misc\App.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 48. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Misc\FeatureFlagGuard.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 49. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\ScriptCore.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 50. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateCore\Private\Layout\Clipping.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 51. `/Docking/TabContentArea`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 52. `/Docking/AppTab_Active`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 53. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\Docking\TabManager.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 54. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/PostProcess/PostProcessFFTBloom.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 55. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Landscape\Private\LandscapeGrass.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 56. `/etc/ssl/certs/ca-certificates.crt`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 57. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\Image.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 58. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\UniformGridPanel.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 59. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\DSPVS\Private\DSPVSArchive.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 60. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SynthBenchmark\Private\SynthBenchmarkPrivate.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 61. `/Script/GameplayTasks`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 62. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\Skeleton.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 63. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Commandlets\PluginCommandlet.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 64. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\SkinnedMeshComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 65. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\GameMode.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 66. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\GameViewportClient.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 67. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\PhysXCookHelper.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 68. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\TimelineTemplate.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 69. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\OpenGLDrv\Private\OpenGLQuery.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 70. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Android\AndroidAudio\Private\AndroidAudioSource.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 71. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\IfElse.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 72. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\IfElseCondition.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 73. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\ScriptGen/Expressions.h`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 74. `/Script/MediaAssets`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 75. `D:\Release4.6.0\AS\Survive\Plugins\WWise\Source\AkAudio\Private\AkRoomComponent.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 76. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\TweenFactory\Standard\TweenRotatorStandardFactory.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 77. `D:\Release4.6.0\AS\Survive\Plugins\KantanCharts\Source\KantanChartsUMG\Private\KantanBarChartBase.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 78. `/Script/GenericActorEditor`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 79. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\2D\Paper2D\Source\Paper2D\Private\Terrain\PaperTerrainComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 80. `D:\Release4.6.0\AS\Survive\Plugins\AutoRobot\Source\AutoRobot\AutoRobotEntry.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 81. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraModule.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 82. `D:\Release4.6.0\AS\Survive\Plugins\CustomLayout\Source\CustomLayout\Private\Tool\CustomLayoutUserSetting.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 83. `D:\Release4.6.0\AS\Survive\Plugins\BuildSystem\Source\BuildSystem\Private\BuildingActorBase.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 84. `D:\Release4.6.0\AS\Survive\Plugins\DNS_OneSDK\Source\DNS_OneSDK\Private\DNS_MessageCenter.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 85. `/Script/CommonGameFeatures`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 86. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\OnlineSessionClient.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 87. `/Script/MMKVUnreal`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 88. `/usr/local/share/lua/5.3/?.lua;/usr/local/share/lua/5.3/?/init.lua;/usr/local/lib/lua/5.3/?.lua;/usr/local/lib/lua/5.3/?/init.lua;./?.lua;./?/init.lua`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 89. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\SpineObject.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 90. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Aiming\WeaponAutoAimingComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 91. `D:\Release4.6.0\AS\Survive\Source\Shado`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 92. `D:\Release4.6.0\AS\Survive\Source\Basic\TickOptimization\TickOptimizationAnimComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 93. `D:\Release4.6.0\AS\Survive\Source\Client\Private\PublishAreaMgr.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 94. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\GCDolphinCallback.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 95. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\HDmpveConfig.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 96. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\UAEPlayerController.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 97. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\Mod\MLAINearbyMonsterInfoCollector.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 98. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_Escape.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 99. `/Script/AI`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 100. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Components\UAERotatingMovementComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 101. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ActorJump.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 102. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_CallAVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 103. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_PlayMontageWithSection.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 104. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_SpawnBeamEffectActor.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 105. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_SwitchCameraViewTarget.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 106. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\LuaCustom\LuaCustomMoveObj.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 107. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Horse\Components\HorseSeatComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 108. `/sdcard/Android/data/com.rekoo.pubgm/files/ansi.flag`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 109. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Containers\Algo\AlgosTest.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 110. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\GenericPlatform\GenericPlatformProcess.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 111. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Misc\ConfigCacheIni.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 112. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateCore\Private\Styling\SlateStyleSet.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 113. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\RHI\Private\PipelineFileCache.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 114. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ShaderCore\Private\ShaderPipelineCache.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 115. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Online\HTTP\Private\Curl\CurlHttpThread.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 116. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AnimGraphRuntime\Private\AnimSequencerInstanceProxy.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 117. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\Slider.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 118. `/Script/EngineSettings`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 119. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\GameplayTasks\Private\GameplayTaskResource.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 120. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\CharacterMovementComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 121. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\GameNetworkManager.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 122. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\PhysDrawing.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 123. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\PhysUtils.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 124. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Player.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 125. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\TextureCube.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 126. `D:\Release4.6.0\AS\Survive\Plugins\PhotonBlast\Source\PhotonBlast\Private\PhotonFracturedMesh\PhotonDestructibleMeshComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 127. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\2D\Paper2D\Source\Paper2D\Private\PaperGeomTools.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 128. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraEmitter.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 129. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraSystemInstance.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 130. `/Script/BuildSystem`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 131. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\PlanCH\Source\PlanCHRuntime\GameCore\PlanCH_GameState.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 132. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdRes\PxResFont.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 133. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUIRHI\Private\PxRHIRenderImp.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 134. `D:\Release4.6.0\AS\Survive\Plugins\GCloudSDK\Source\GCloudSDK\Private\GCloudSDKModule.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 135. `D:\Release4.6.0\AS\Survive\Plugins\QDevKit\Source\QDevKit\Private\GCBGDwonloadHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 136. `D:\Release4.6.0\AS\Survive\Plugins\SpawnSystem\Source\SpawnSystem\Private\Strategy\Timing\STStrategyTiming_Wave.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 137. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\AndroidPermission\Source\AndroidPermission\Private\AndroidPermissionCallbackProxy.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 138. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\CharacterEffectCfg\CharacterEffect_Fairy.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 139. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\CaveStoneActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 140. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\DynamicWeatherMgr.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 141. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CameraOverlapEffectComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 142. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CharacterComponent\CharacterMaterialComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 143. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CustomSpringArmComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 144. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\Throw\ThrowComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 145. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\WorldActorFlagComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 146. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Effect\EffectWeaponReload.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 147. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\PartnerGhostCharacter.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 148. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\PlayerTypeDefine.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 149. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\PVS\PVSCheckComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 150. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UTSkillLocationPicker_SweepForEmptySpace.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 151. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\UIBPFunctionLibrary.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 152. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\Map\OBEntireMapUIWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 153. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\Map\OBMiniMapUIWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 154. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\AI\Tasks\BTTask_WheeledVehicleNavigatePath.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 155. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Bike\VehicleBike.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 156. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\UAV\STExtraUCAV.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 157. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\Grenade/ExplosionFinder.h`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 158. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\ShootWeaponEffectComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 159. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\STExtraFlareGunBullet.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 160. `D:\Release4.6.0\AS\Survive\Source\Basic\TickOptimization\TickOptimizationTargetComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 161. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\AsyncSavedLoader.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 162. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\WidgetComponent.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 163. `/Script/CinematicCamera`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 164. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AssetRegistry\Private\AssetRegistryState.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 165. `/Script/ClothingSystemRuntimeInterface`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 166. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimNotifyState_TimedParticleEffect.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 167. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AudioDevice.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 168. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AudioEffect.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 169. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\CheatManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 170. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\ActorComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 171. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\ModelComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 172. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\DeviceProfiles\DeviceProfileManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 173. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Particles\ParticleEmitterInstances.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 174. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ClothingSystemRuntime\Private\Assets\ClothingAsset.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 175. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\OpenGLDrv\Private\Android\AndroidEGL.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 176. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\OpenGLDrv\Private\OpenGLDrv.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 177. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\BlockyMenuWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 178. `D:\Release4.6.0\AS\Survive\Plugins\GameMaster\Source\GameMaster\Private\GameMasterHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 179. `v:/devel/projects/oodle2/core/lznacompressvfast.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 180. `v:\devel\projects\oodle2\core\newlz_arrays_tans.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 181. `v:/devel/projects/oodle2/core/lznib_fast.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 182. `v:/devel/projects/oodle2/core/rrlzhcompressfast.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 183. `/usr/share/zoneinfo/`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 184. `/usr/local/ssl/lib/engines`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 185. `D:\Release4.6.0\AS\Survive\Plugins\WWise\Source\AkAudio\Private\AkGameplayStatics.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 186. `/Script/AkAudio`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 187. `/Script/SceneCaptureWidgetPlugin`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 188. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeInstanceManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 189. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Utility\CreativeBlueprintLibrary.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 190. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\CreativeLua\CreativeLuaCodeManager.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 191. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\CreativeLua\Object\CreativeApiObject.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 192. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\2D\Paper2D\Source\Paper2D\Private\PaperSprite.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 193. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraDataInterface.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 194. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Experimental\GameFeatures\Source\GameFeatures\Private\GameFeatureData.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 195. `D:\Release4.6.0\AS\Survive\Plugins\CustomLayout\Source\CustomLayout\Private\Tool\DynamicCustomIndexer.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 196. `D:\Release4.6.0\AS\Survive\Plugins\bp_plugin\Source\bp_plugin\Private\Android\bp_plugin.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 197. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\MainCity\Source\MainCity\Animation\CarryBackMCAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 198. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\OnlineBeaconHostObject.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 199. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\TPlanGame\Source\TPlanGame\Game\BackPack\BackpackComponentTPlan.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 200. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxExtBpCall\PxExtBpItemInterface.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 201. `/Script/PixUIFileDialog`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 202. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\GameletPuerts\Source\GameletJsEnv\Private/ContainerWrapper.h`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 203. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PandoraPickerPlugin\Source\PandoraPickerPlugin\Private\PandoraPicker\PandoraPicker_Android.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 204. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Compression\OodleNetwork\Source\Private\OodleNetworkHandlerComponent.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 205. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemNull\Source\Private\OnlineSubsystemModuleNull.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 206. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\AndroidMoviePlayer\Source\AndroidMoviePlayer\Private\AndroidMovieStreamer.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 207. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\CustomMeshLoader\Source\CustomMeshLoader\Private\RuntimeMeshBuilder.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 208. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\DataDriverAnim\DataDriverAnimShareParamsComp.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 209. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\Manager\AnimContext.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 210. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\CharacterEffectCfg\CharacterEffect_PostLuaEvent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 211. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Custom\CustomBase.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 212. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Grenade\ConsumableAvatarComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 213. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AvatarDIY\Action\AvatarAction_ApplyDIYMirroParam.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 214. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AvatarDIY\Lobby\UDIYLua.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 215. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STExtraBaseCharacter_Peek.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 216. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\AirAttackLocatorCalledActor.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 217. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\AirAttackCS.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 218. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CharacterPendantEntity.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 219. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\GeneralSMComponent\Task\GeneralSMTask_SetComponentsActive.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 220. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\ObserverCameraComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 221. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\PVE\Level\MonsterAnimGroupComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 222. `/Game/BluePrints/Core/Forest/GameModeConfigComp_BP.GameModeConfigComp_BP_C`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 223. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\BattleRoyaleGameModeTeam.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 224. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Lobby\LobbyModelCommonActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 225. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\PetSpectator\PlayerPetMovementComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 226. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Component\AIHoleUpComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 227. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\GameReplay.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 228. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\ReplayUIManager.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 229. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UTSkillLocationPicker_RangedRnd.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 230. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Templates\TemplateMgr.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 231. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Templates\TemplateUtil.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 232. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\Map\EntireMapUI.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 233. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\ParachutingWidget.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 234. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Utility\UIDuplicatedItemPool.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 235. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Cabriolet\VehicleCabrioletComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 236. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\STExtraVehicleBase_Trailer.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 237. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleBalanceComponentBike.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 238. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\ExplosionProjectileBullet.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 239. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\MultiBulletComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 240. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\PostFillGasWeaponState.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 241. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\Projectile\STProjectileBase.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 242. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\WeaponPreFireState.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 243. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\WeaponWarmUpState.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 244. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\UAEGameInstance.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 245. `D:\Release4.6.0\AS\Survive\Source\Client\HotUpdate\Translator.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 246. `D:\Release4.6.0\AS\Survive\Source\Client\Private\ScreenInput.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 247. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\LoadTexture.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 248. `/Game/BluePrints/Vibrate/BP_VibrateSystemManager.BP_VibrateSystemManager_C`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 249. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\VehicleGeneratorComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 250. `/Script/TableResInclude`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 251. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Service\BTService_OccupyHandler.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 252. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_GeneralExecuteEventsOfWayPointNew.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 253. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\AI\Zombies\ZombiesHitVHComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 254. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_ChangePoseState.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 255. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_ReplaceCharAvatarAnim.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 256. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_SetEyeEffect.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 257. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_SetMovementMode.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 258. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\CustomActor\BirdCage.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 259. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\CustomActor\RewindActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 260. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_JumpPhase.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 261. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_PlayWeaponMontage.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 262. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillConditions\UAESkillCondition_CheckCarryBackState.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 263. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\LandingCreatures\Panda\PandaVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 264. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Pterosaur\PterosaurMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 265. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Mecha\Animation\MechaAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 266. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Mecha\Components\MechaSeatComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 267. `/sdcard/Android/data/com.tencent.igfit/files`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 268. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Misc\AssertionMacros.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 269. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\Misc\CrashContextCollector.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 270. `/Docking/DockingIndicator_Center`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 271. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Layout\SWindowTitleBarArea.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 272. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Views\SHeaderRow.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 273. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/SystemTextures.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 274. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/PostProcess/PostProcessing.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 275. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Online\HTTP\Private\HttpThread.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 276. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\MovieScene\Private\Tests\MovieSceneBlendingTests.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 277. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateRHIRenderer\Private\SlateRHIRenderingPolicy.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 278. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Slate\SMeshWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 279. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\GameplayTags\Private\GameplayTagsManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 280. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\Blueprint\AIBlueprintHelperLibrary.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 281. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AI\Navigation\NavigationData.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 282. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\PrimitiveComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 283. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\DataReplication.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 284. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\DebugCameraController.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 285. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\LevelActorContainer.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 286. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SkeletalMeshMerge.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 287. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SoundGroups.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 288. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SoundNodeMature.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 289. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SparseVolumeTexture\SparseVolumeTextureUpload.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 290. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\StaticMeshRender.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 291. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ClothingSystemRuntime\Private\NvCloth\SwFactory.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 292. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ClothingSystemRuntime\Private\NvCloth\SwSolver.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 293. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Online\Voice\Private\Android\VoiceModuleAndroid.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 294. `D:/Release4.6.0/AS/Survive/Source/UnrealArchExt/Private/LogicManagerBase.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 295. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\ApexDestruction\Source\ApexDestruction\Private\DestructibleComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 296. `D:\Release4.6.0\AS\Survive\Plugins\resetcore-unreal\CommonLib\Source\CommonLib\Private\Network\NetPakageHandler\JsonPackageHandler.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 297. `/Script/VectorVM`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 298. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\BlockyLuaConfig.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 299. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\ScriptGen/Reflector.h`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 300. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\Search\BlockyRichTextBlock.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 301. `D:\Release4.6.0\AS\Survive\Source\Development\GMCheat\GMCheatCharacter.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 302. `v:/devel/projects/oodle2/core/lzacompressfast.h`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 303. `v:\devel\projects\oodle2\core\lzblw.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 304. `D:\Release4.6.0\AS\Survive\Plugins\QDevKit\Source\QDevKit\Private\Android\PhotoAlbumHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 305. `D:\Release4.6.0\AS\Survive\Plugins\QDevKit\Source\QDevKit\Private\LocationHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 306. `/Script/SpawnSystem`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 307. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\Json.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 308. `D:\Release4.6.0\AS\Survive\Plugins\UnrealAgent\Source\HTTPServer\Private\HttpServerModule.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 309. `D:\Release4.6.0\AS\Survive\Plugins\WebCameraFeed\Source\WebCameraFeed\Private\AndroidVideoGrabber.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 310. `v:\devel\projects\oodle2\network\rrtans.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 311. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\MeshOptimizer\Source\MeshOptimizer\Classes\MeshOpt.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 312. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanTexture.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 313. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Activity\InteractiveComponentBase.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 314. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STExtraBaseCharacter_WeaponSpawn.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 315. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\STBuildingActor_IceWall.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 316. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\SwimRingActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 317. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\MultiNavDataComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 318. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Effect\EffectTacticalReloadWait.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 319. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Interface\PlayEmoteInterface.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 320. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\PetAnim\STExtraPetAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 321. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\PlayerAutoNavComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 322. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\STExtraPlayerCharacter_Parachute.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 323. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Private\GameMode\TeamDeathMatch\Component\DeathMatchWWISEManagerComponent.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 324. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Navigation\UAENavigationSystem.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 325. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\PlaybackHelper.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 326. `D:\Release4.6.0\AS\UE4181\Engine\Source\..\..\..\Survive\Source\ShadowTrackerExtra\Skill/UAEBaseSkill.h`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 327. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UTSkillLocationPicker_RangedFan.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 328. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\HandwritingDrawWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 329. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\TeammatePositionWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 330. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\UAECanvasPanelHandleState.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 331. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Utility\NetworkOnlineDriver.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 332. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Effect\VehicleParticles.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 333. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Tank\VehicleCommonComponentTank.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 334. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Wheeled\WheeledNeutralThrottleComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 335. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\STExtraShootWeapon_DualWielding.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 336. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\STExtraShootWeaponComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 337. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\GameModeEnvUtil.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 338. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\UAENetDriver.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 339. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\GroupSpotSceneComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 340. `D:\Release4.6.0\AS\Survive\Source\AI\AIVehicle\BTService_Tank_Shooting.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 341. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\MLAITrainingComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 342. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_GeneralExecuteEventsOfWayPoint.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 343. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_DisableBioVehicleState.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 344. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_EnableEnemyPosMark.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 345. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_PlayEmote.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 346. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_UseControlRot.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 347. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\FlowerWing\FlowerWingCharacterAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 348. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\SpecialMoveObj_LeggedAnimal.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 349. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\SplineMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 350. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Components\BioVehicleDamageComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 351. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Myriapod\MyriaPodVehicleSeatComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 352. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Myriapod\VehicleDamageComponentLionDance.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 353. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ClothingSystemRuntime\Private\ClothingSimulation.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 354. `/Script/AudioMixer`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 355. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\LogicCompare.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 356. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\ScriptGen\xnd\vfxxnd.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 357. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\Widgets\BlockyBlockListItemObjects\BlockyBlockListItemObject.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 358. `D:\Release4.6.0\AS\Survive\Plugins\UIParticle\Source\UIParticle\Private\Widget\UIParticleEmitter.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 359. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\TweenFactory\Standard\TweenFloatStandardFactory.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 360. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\GameplayEffectAggregator.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 361. `/Script/slua_unreal`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 362. `D:\Release4.6.0\AS\Survive\Plugins\GenericActorEditor\Source\GenericActorEditor\Private\ActorEditorStaticMeshComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 363. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeBinaryDataManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 364. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\CreativeLua\CreativeLuaEntityManager.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 365. `D:\Release4.6.0\AS\Survive\Plugins\PhotonBlast\Source\PhotonBlast\Private\PhotonFracturedMesh\PhotonHierarchicalInstancedDestructibleMeshComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 366. `/Game/Arts_PlayerBluePrints/Vehicle/UAZ01/VH_UAZ01_New.VH_UAZ01_New_C`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 367. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\PhysXVehicles\Source\PhysXVehicles\Private\VehicleWheel.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 368. `/Script/AWSHelper`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 369. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\MainCity\Source\MainCity\Animation\CharMainMCAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 370. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystem\Source\Private\LANBeacon.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 371. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\TPlanGame\Source\TPlanGame\Game\GameMode\XTPlayerState.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 372. `D:\Release4.6.0\AS\Survive\Plugins\SpawnSystem\Source\SpawnSystem\Private\Spawner\STSpawnerBase.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 373. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\ClippingAttachment.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 374. `D:\Release4.6.0\AS\Survive\Plugins\WebCameraFeed\Source\WebCameraFeed\Private\SWebCameraImage.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 375. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\FrameCapturer\Source\FrameCapturerPlugin\Private\FrameCapturerPluginModule.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 376. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\CharacterAnimState\CharacterAnimStateBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 377. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\Monster\MonsterAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 378. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\BackpackWeaponAttachHandle.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 379. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STExtraBaseCharacter_PlayEmote.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 380. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\AirDropPlane.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 381. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\STDamageableMeshComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 382. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Effect\EffectConsumeItem.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 383. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\DSCommand\DSCommandManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 384. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\PVE\PointEnterArea.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 385. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\Assist\WorldLevelProbeComponent.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 386. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Landscape\LandscapeRuntimeChange.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 387. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Lobby\LobbyCharacter\STExtraLobbyCharacter.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 388. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\PetTransform\PetTransformAvatarComp.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 389. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\STExtraPlayerController.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 390. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Props\PlayerTombBox.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 391. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Utils\AIWayPointUtils.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 392. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\ReplayRecorders\TlogCapsuleRecorder.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 393. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UAECharacterSkillManagerComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 394. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UAESkillPhase.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 395. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Utility\ActorCacheMgr.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 396. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\PhysicsBalance\PhysicsBalanceComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 397. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Floating\STExtraAdvancedFloatingVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 398. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Hlicopter\STExtraHelicopterVehicle_AutoDrive.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 399. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Wheeled\VehicleAccelerateComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 400. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\FillGasWeaponState.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 401. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\GrenadeLaunchComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 402. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\STExtraWeapon.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 403. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\BattleItem.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 404. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\DSOptimGrayPublishFlags.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 405. `D:\Release4.6.0\AS\Survive\Source\Basic\Table\UAETableManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 406. `D:\Release4.6.0\AS\Survive\Source\Client\LiveBroadcast\LiveBroadcast.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 407. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\VoiceDeviceManager.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 408. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\UAECharacter.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 409. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\MLAISubSystem.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 410. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Service\BTService_CJChooseEnemy.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 411. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_FinishOrder.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 412. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTaskNode_CharacterCastOnTargetSkill.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 413. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTaskNode_PickItemsAtSpot.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 414. `D:\Release4.6.0\AS\Survive\Source\Security\HiggsBoson\Private\SecurityPak.cpp`

Security/anti-cheat-related component by name. It may collect, evaluate, or report integrity/gameplay signals, but the filename alone cannot establish its checks or enforcement behavior.

## 415. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ApplyVehicleWeaponBoard.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 416. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_AttachPawnPlayMontageByTable.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 417. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_AttackAdsorb.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 418. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ConsumeHandleItem.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 419. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_FlySprint.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 420. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_JumpPhaseWithState.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 421. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\OceanVehicle\OceanVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 422. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Tiger\TigerVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 423. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\UAVDeer\UAVDeer.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 424. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\HAL\IPlatformFileLogWrapper.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 425. `/Docking/Tab_Active`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 426. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\MultiBox\MultiBoxBuilder.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 427. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\MultiBox\SEditableTextBlock.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 428. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Notifications\SPopUpErrorText.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 429. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/VRSManager.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 430. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\ComboBoxString.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 431. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Navmesh\Private\Detour\DetourNavMeshQuery.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 432. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\AIModule.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 433. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\BehaviorTree\BlackboardComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 434. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\GameFramework\RootMotionSource.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 435. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Net\NetFrameBudget.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 436. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\PhysAnim.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 437. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\PhysicsReplication.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 438. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\OpenGLDrv\Private\OpenGLProgramCache.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 439. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AudioMixer\Private\AudioMixerDevice.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 440. `/Script/AndroidRuntimeSettings`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 441. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\NumFromTo.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 442. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\AndroidDeviceProfileSelector\Source\AndroidDeviceProfileSelector\Private\AndroidDeviceProfileSelectorModule.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 443. `D:\Release4.6.0\AS\Survive\Plugins\WWise\Source\AkAudio\Private\AkAudioBank.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 444. `D:\Release4.6.0\AS\Survive\Plugins\KantanCharts\Source\KantanChartsUMG\Private\KantanChartLegend.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 445. `D:\Release4.6.0\AS\Survive\Plugins\slua_unreal\Source\slua_unreal\Private\LuaUserWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 446. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Object\CreativeBaseWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 447. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\AORepInterface.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 448. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\MultiVersionConfig.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 449. `D:\Release4.6.0\AS\Survive\Source\Client\Public\UUDPPingCollector.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 450. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\ImageDownloader.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 451. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\UAEGameState.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 452. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\Mod\MLAILandScapeInfoCollector.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 453. `D:\Release4.6.0\AS\Survive\Source\AI\SpawnSystem\Strategy\Timing\STStrategyTiming_Event.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 454. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\AI\NTFox\AIMob_NTFox.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 455. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Animation\AnimCore\IKCoreUtil.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 456. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_AddRemoveMapMarkForActorClass.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 457. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\AESkillAction_SetAnimMoveLayer.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 458. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_TakeDamage.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 459. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\AdditiveCurveMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 460. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Spectating\OB\OBHttpComponent.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 461. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Traversal\Ladder\LadderMovementComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 462. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Components\BioVehicleMovementComponent_Physics.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 463. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\HoverVehicle\HoveringVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 464. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Mecha\Components\MechaWeaponSeekAndLockUI.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 465. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Mecha\HoveringMecha.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 466. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Misc\InteractiveProcess.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 467. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\Docking\SDockingTabStack.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 468. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\MultiBox\SToolBarComboButtonBlock.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 469. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\Overlay.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 470. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\WeakRefImage.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 471. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\BehaviorTree\Services\BTService_BlueprintBase.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 472. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\BehaviorTree\Tasks\BTTask_RunEQSQuery.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 473. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\PakFile\Private/Unreal`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 474. `D:\Release4.6.0\AS\Survive\Plugins\WWise\Source\AkAudio\Private\AkAreaCheckVolumeBase.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 475. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\ScriptPlugin\ScriptPlugin\Source\ScriptPlugin\Private\LuaIntegration.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 476. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PandoraVideoPlayer\Source\PandoraVideoPlayer\Private\PVideoPlayer.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 477. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\CommonGameFeatures\Source\CommonGameFeatures\RepControl\RepControlActorBase.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 478. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\VoiceInterfaceImpl.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 479. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystem\Source\Private\OnlineSubsystem.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 480. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxExtBpCall\PxExtBpItemObject.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 481. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxLibAsync\PxLibViewAsyncProxy.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 482. `D:\Release4.6.0\AS\Survive\Plugins\GVoiceSDK\Source\GVoiceSDK\Private\GVoiceSDKHelper.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 483. `D:\Release4.6.0\AS\Survive\Plugins\UnrealAgent\Source\HTTPServer\Private\HttpConnectionRequestReadContext.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 484. `/Script/OodleNetworkHandlerComponent`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 485. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\ImmediatePhysics\Source\ImmediatePhysics\Private\BoneControllers\AnimNode_RigidBody.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 486. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Launch\Private\LaunchEngineLoop.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 487. `/Game/Arts_Player/Characters/Mesh/Male/Head/Mesh/CharacterFakeHeadMeshNoPhysics.CharacterFakeHeadMeshNoPhysics`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 488. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\Helpers\AnimationRuntimeHelper.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 489. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\CharacterAnimState\Vehicle/VehicleCharacterAnimInstanceBase.h`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 490. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Anim\XSuitAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 491. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\AvatarUtils.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 492. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Vehicle\ItemAvatarComponentBase.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 493. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_CPCharacterMontage.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 494. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_HideParticle.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 495. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_LoadDependResource.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 496. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_LoadLevel.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 497. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_SetNearClipPlane.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 498. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_TickMatParam.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 499. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\Interface\BackpackTakeInProxy.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 500. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\ChangeWearingComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 501. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\GameModeStateFightingTeam.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 502. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\ModLogicSwitch\STExtraModLogicSwitch.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 503. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\HurtAppearance\HurtAppearanceSubsystem.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 504. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\PetEntityComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 505. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Private\GameMode\TeamDeathMatch\BRGameStateTeam_DeathMatch.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 506. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Private\Physics\PhysicsInterface.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 507. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Props\PickUpListWrapperActor.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 508. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Props\PickupWrapperManagerComponent.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 509. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Assist\AIActingCachedCharacter.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 510. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Component\FlyingPathFollowingComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 511. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UAESkillPicker_Capsule.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 512. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Effect\VehicleEffectsComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 513. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Floating/STExtraFloatingVehicleMovementComponentBase.h`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 514. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\MovementLOD\VehicleMovementLODManagerComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 515. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Tank\VehicleTank.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 516. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleShootDriverComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 517. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleUtils.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 518. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\AI\BioVehicles\BioVehicleAIController.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 519. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\AI\VisualDebug\VisualDebugComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 520. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_DirectMove.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 521. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_Log.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 522. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_SpawnActor.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 523. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffConditions\STBuffCondition_MovementMode.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 524. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_QuickMove.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 525. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\NinjaMove\NinjaMoveComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 526. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\ReindeerCart\Components\ReindeerSeatComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 527. `/sdcard/Android/data/com.vng.pubgmobile/files/ansi.flag`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 528. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\GenericPlatform\GenericPlatformOutputDevices.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 529. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Misc\Compression.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 530. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateCore\Private\Application\SlateApplicationBase.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 531. `/Docking/Tab_ColorOverlayIcon`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 532. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\Application\MenuStack.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 533. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\MultiBox\SGroupMarkerBlock.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 534. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Sockets\Private\Android\SocketSubsystemAndroid.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 535. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/GlobalDistanceField.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 536. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Landscape\Private\LandscapeRender.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 537. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AnimGraphRuntime\Private\AnimCustomInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 538. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AnimGraphRuntime\Private\BoneControllers\AnimNode_LookAt.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 539. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\ShareWidgetRTManager.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 540. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AssetRegistry\Private/AssetRegistryConsoleCommands.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 541. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\ADPCMAudioInfo.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 542. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimBlueprintGeneratedClass.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 543. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimSequence.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 544. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\BlueprintGeneratedClass.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 545. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Collision\PhysXCollision.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 546. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Controller.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 547. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\ConstraintInstance.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 548. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\PhysicsSerializer.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 549. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SparseVolumeTexture\SparseVolumeTextureTileDataTexture.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 550. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ClothingSystemRuntime\Private\EnvironmentalCollisions.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 551. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\BlockyBlockDisplayWidgets\BlockyBlockDisplayWidget_Variable.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 552. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\BlockyLogWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 553. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Online\ICMP\Private\UDPPing.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 554. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\MediaAssets\Private\Assets\MediaPlayer.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 555. `v:\devel\projects\oodle2\core\newlzhc.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 556. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\ScriptPlugin\ScriptPlugin\Source\ScriptPlugin\Private\LuaContext.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 557. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\GameplayAbilityTargetTypes.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 558. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Object\CreativeCameraDeviceActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 559. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Widget\CreativeModeChatBubbleUI.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 560. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\CreativeLua\Object\CreativeGlobalApiObject.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 561. `D:\Release4.6.0\AS\Survive\Plugins\ClusterReplication\Source\Private\AOICluster.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 562. `D:\Release4.6.0\AS\Survive\Plugins\AutoRobot\Source\AutoRobot\UITestHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 563. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NDISkeletalMesh_TriangleSampling.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 564. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 565. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraDataSet.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 566. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxExtBpCall\PxExtBpCall.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 567. `D:\Release4.6.0\AS\Survive\Plugins\MMKVUnreal\Source\MMKVUnreal\Private\InterProcessLock.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 568. `D:\Release4.6.0\AS\Survive\Plugins\QDevKit\Source\QDevKit\Private\Android\LocationHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 569. `D:\Release4.6.0\AS\Survive\Plugins\TApm\Source\TApm\Private\Android\TApm.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 570. `D:\Release4.6.0\AS\Survive\Source\Basic\Buff\BuffConfigSubsystem.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 571. `D:\Release4.6.0\AS\Survive\Source\Basic\Buff\STBuffAction.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 572. `D:\Release4.6.0\AS\Survive\Source\Basic\Lua\LuaAsyncTaskSubsystem.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 573. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\POManagerInterface.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 574. `/Script/Basic`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 575. `D:\Release4.6.0\AS\Survive\Source\Client\Lobby\component\LobbyDecalBakingComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 576. `D:\Release4.6.0\AS\Survive\Source\Client\Private\GameFrontendHUD.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 577. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Network\NetworkExceptionHandleSubsystem.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 578. `/Game/Arts_PlayerBluePrints/Weapon/Ammo/BP_Ammo_300Magnum_Pickup.BP_Ammo_300Magnum_Pickup_C`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 579. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\ItemGroupRepeatSpotComponent.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 580. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\MLAIUtils.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 581. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\Mod\AIStateInfoComponentBase.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 582. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Decorator\BTDecorator_IsWayPointNeedRotate.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 583. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Service\BTService_TargetAngleCheck.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 584. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_TeleportToSpecLoc.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 585. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTaskNode_FindBuilding.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 586. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Components\ConvertInputComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 587. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_CircleMove.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 588. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_PutDown.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 589. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_SetBioVehicleState.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 590. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillConditions\UAESkillCondition_CheckCanCarryBack.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 591. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillConditions\UAESkillCondition_IsUnderLandscape.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 592. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Components\BioVehicleStateComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 593. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Scorpion\ScorpionVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 594. `/Script/Addons`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 595. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Misc\FileHelper.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 596. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Misc\NetworkVersion.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 597. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\PropertyBool.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 598. `D:/Release4.6.0/AS/UE4181/Engine/Source\Runtime/CoreUObject/Private/UObject/LinkerPlaceholderBase.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 599. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\UObjectGlobals.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 600. `/Docking/CloseApp_Pressed`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 601. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\MultiBox\MultiBoxCustomization.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 602. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Notifications\SNotificationList.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 603. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AnimGraphRuntime\Private\RBF\RBFSolver.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 604. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\MovieSceneTracks\Private\Evaluation\MovieSceneEventTemplate.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 605. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\PakFile\Private\SignedArchiveWriter.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 606. `/Script/MovieSceneCapture`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 607. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\ChartCreation.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 608. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\FontFace.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 609. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\HighResScreenshot.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 610. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\KismetTraceUtils.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 611. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\LatentActionManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 612. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\NewObjectPool\NewObjectPool.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 613. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Particles\ParticleGpuSimulation.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 614. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\ShaderCompiler\ShaderCompilerBK.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 615. `D:\Release4.6.0\AS\Survive\Plugins\SkillEditor\Source\Skill\Private\UTSkill.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 616. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeOctreeSyncManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 617. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Object\CreativeDestructibleMeshBatchActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 618. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Object\CreativeWidgetObject.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 619. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\CreativeLua\Object\CreativeTimerApiObject.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 620. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\CustomAsset\CustomAnim\CustomAssetAnimManager.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 621. `D:\Release4.6.0\AS\Survive\Plugins\CreativeLua\Source\CreativeLua\Private\CreativeEnvLuaVM.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 622. `D:\Release4.6.0\AS\Survive\Plugins\AutoRobot\Source\AutoRobot\AutoTestSubsystem.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 623. `/Script/ReAutomatic`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 624. `D:\Release4.6.0\AS\Survive\Plugins\CrashSight\Source\CrashSight\Private\CrashSightModule.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 625. `/Script/EventTrackEx`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 626. `D:\Release4.6.0\AS\Survive\Plugins\EZUMG\Source\EZUMG\Private\Widget\VerticalSelector.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 627. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\MainCity\Source\MainCity\GameMode\MainCityGameMode.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 628. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\OnlineBeaconClient.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 629. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\PlanPH\Source\PlanPHRuntime\MiniMap\MapBarrier\MapBarrierWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 630. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxLibCore\1_0_0\PxKit100Api.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 631. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdObject\PxObjectProxy\PxViewWrapper.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 632. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdRes\PxBrush\PxMatBrush.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 633. `/Script/PixUIRHI`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 634. `/Script/CustomMeshLoader`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 635. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\Trace\Source\TraceDataHandler\Private\TraceWorker.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 636. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanPipeline.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 637. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\AircraftAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 638. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\AnimAbility\AnimAbility.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 639. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\CharacterAnimState\Feature\AnimInstanceLocomotion.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 640. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\Monster\UAEMonsterAnimListComponentBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 641. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Grenade\GrenadeAvatarComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 642. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Vehicle\VehicleLicenseNumberComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 643. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_MeshAnimMontage.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 644. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STExtraHPBarInterface.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 645. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\DynamicWeatherExMgr.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 646. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\SimpleHelicopter.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 647. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\PlayerMantleComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 648. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Emote\EmoteSubsystem.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 649. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\PVE\Unit\MonsterAttributeComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 650. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\PetAvatar\CustomAnimAvatarComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 651. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\STExtraFightPetComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 652. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pickup\PickupItemUsefulSubsystem.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 653. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Private\GameMode\TeamDeathMatch\BRPlayerStateTeam_DeathMatch.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 654. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Security\PlayerAntiCheatManager.cpp`

Security/anti-cheat-related component by name. It may collect, evaluate, or report integrity/gameplay signals, but the filename alone cannot establish its checks or enforcement behavior.

## 655. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UAESkillPoolSubsystem.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 656. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Subsystem\DamageManagerSubSystem.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 657. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\UMG\CircleChooseWidgetBase.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 658. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Airdrop\VehicleAirdropComponentBase.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 659. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Transform\VehicleTransformComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 660. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Floating\FloatLogic.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 661. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Wheeled\STExtraVehicleMovementComponent4W_ShootDrive.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 662. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\IdleWeaponState.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 663. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\PublishRegion.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 664. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\GenericPlatform\GenericPlatformFile.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 665. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\HAL\ExceptionHandling.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 666. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\HAL\MallocSwap.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 667. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Internationalization\StringTableRegistry.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 668. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Logging\LogSuppressionInterface.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 669. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Stats\StatsMisc.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 670. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Projects\Private\PluginManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 671. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ApplicationCore\Private\Android\AndroidWindow.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 672. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\Commands\InputBindingManager.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 673. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\Docking\SDockingTarget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 674. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Input\SComboButton.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 675. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/LandscapeInstancingRender.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 676. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Online\HTTP\Private\NullHttp.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 677. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AnimGraphRuntime\Private\BoneControllers\AnimNode_RotationLimit.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 678. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\MenuAnchor.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 679. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\Spacer.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 680. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\TileView.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 681. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Analytics\AnalyticsET\Private\IAnalyticsProviderET.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 682. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\BehaviorTree\BTNode.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 683. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\ActorSpawnQueue\ActorSpawnQueue.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 684. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimNode_StateMachine.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 685. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimSingleNodeInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 686. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\BlendSpaceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 687. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\DataChannel.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 688. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\GameInstance.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 689. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Interpolation.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 690. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Materials\Material.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 691. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\ObjectPool.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 692. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PendingNetGame.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 693. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PlayerController.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 694. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\WorldComposition.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 695. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AudioMixer\Private\AudioMixer.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 696. `D:\Release4.6.0\AS\Survive\Plugins\ZLevelEditor\Source\ZLevel\Private\ZLevelData.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 697. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\BlockyGraph.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 698. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\Custom\CustomAction.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 699. `/Script/BlockyLuaCore`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 700. `D:\Release4.6.0\AS\Survive\Source\Development\GMCheat\GMCheatDump.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 701. `v:\devel\projects\oodle2\core\oodlemalloc.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 702. `v:\devel\projects\oodle2\core\rrhuffmandecode.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 703. `/dev/egd-pool`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 704. `D:\Release4.6.0\AS\Survive\Plugins\OceanPlugin\Source\OceanPlugin\Private\BuoyantMesh\BuoyantMeshComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 705. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\GameplayCueNotify_Static.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 706. `/Script/GameplayAbilities`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 707. `/Script/Skill`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 708. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Component\CustomAssetMountStateComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 709. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeObjectManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 710. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeWebSocketManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 711. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Object\CreativePhysicsBatchActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 712. `D:\Release4.6.0\AS\Survive\Plugins\ClusterReplication\Source\Private\AOIClusterManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 713. `/Script/ModularGameplay`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 714. `D:\Release4.6.0\AS\Survive\Plugins\EZUMG\Source\EZUMG\Private\Widget\EnhancedButton.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 715. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\MainCity\Source\MainCity\GameMode\MainCityGameState.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 716. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\PartyBeaconClient.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 717. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxUtil.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 718. `/Script/PixUILog`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 719. `/Script/GeneralNode`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 720. `D:\Release4.6.0\AS\Survive\Plugins\MMKVUnreal\Source\MMKVUnreal\Private\ThreadLock.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 721. `/Script/STestKitMobile`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 722. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\CustomMeshLoader\Source\CustomMeshLoader\Private\CustomMeshLoaderModule.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 723. `/Script/ImmediatePhysics`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 724. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\Trace\Source\TraceDataHandler\Private\DataHandler\TraceDataSocketHandler.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 725. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\BackpackAvatarItemCustom.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 726. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\SpecialMovement\AirBorneMoveObj.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 727. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STExtraBaseCharacter_ChangeWearing.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 728. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STSearchResultNotifier.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 729. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\BattleSceneAvatarDisplayPoseComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 730. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\PartHitZombieComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 731. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\SoundFilterComponent.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 732. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\STExtraUnderWaterEffectComp.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 733. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\EnergySaving\EnergySavingManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 734. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\FourInOne\FourInOneGameState.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 735. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\GameModeState_Challenge.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 736. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\PlaneAvatarComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 737. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\SocialIsland\SIslandDuelComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 738. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UTSkillLocationPicker_OutdoorLoc.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 739. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\HUD\SurviveHUD.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 740. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\MyDraggableButton.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 741. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\SCustomScrollBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 742. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Aircraft\VehicleSyncComponentAircraft.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 743. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\FireWeaponState.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 744. `D:\Release4.6.0\AS\Survive\Source\Basic\Buff\BuffUtils.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 745. `D:\Release4.6.0\AS\Survive\Source\Basic\Lua\LuaLogTree.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 746. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\MessageCodec.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 747. `D:\Release4.6.0\AS\Survive\Source\Client\IOMux\FIOMuxMgr.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 748. `D:\Release4.6.0\AS\Survive\Source\Client\Private\TssManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 749. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\VoiceRoom.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 750. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\UAEOBState.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 751. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\MLAIParachuteJumpComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 752. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_GeneralActivateNextWayPoint.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 753. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_WeaponAttrModifier.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 754. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ContinuousForce.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 755. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ScopeEnemy.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 756. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UTSkillAppearance_AnimHurtingState.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 757. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillConditions\UAESkillCondition_MovementDir.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 758. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Camel\CamelVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 759. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Mecha\MechaVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 760. `/sdcard/Android/data/com.rekoo.pubgm/files`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 761. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Serialization\BitWriter.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 762. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\InputCore\Private\InputCoreTypes.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 763. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ImageWrapper\Private\Formats\BmpImageWrapper.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 764. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\Docking\SDockingArea.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 765. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\MultiBox\SMenuEntryBlock.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 766. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Layout\SExpandableArea.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 767. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Sockets\Private\BSDIPv6Sockets\SocketSubsystemBSDIPv6.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 768. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/DistanceFieldGlobalIllumination.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 769. `/Script/AnimGraphRuntime`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 770. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\ListView.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 771. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\ProgressBar.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 772. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\WrapBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 773. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Slate\WidgetRenderer.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 774. `/Script/JsonUtilities`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 775. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\BehaviorTree\Tasks\BTTask_BlackboardBase.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 776. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\MeshDescription\Private\MeshDescription.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 777. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\InputComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 778. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\GameModeBase.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 779. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\InstancedStaticMesh.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 780. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PrimitiveComponentPhysics.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 781. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\RepLayout.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 782. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SparseVolumeTexture\SparseVolumeTexture.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 783. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ClothingSystemRuntime\Private\NvCloth\Factory.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 784. `/Script/ApexDestruction`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 785. `D:\Release4.6.0\AS\Survive\Plugins\resetcore-unreal\CommonLib\Source\CommonLib\Private\Utility\ServiceManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 786. `/Script/ZLevel`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 787. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\Custom\CustomValueImp.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 788. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\Executeable.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 789. `D:\Release4.6.0\AS\Survive\Source\Development\GMCheat\GMCheatGameFlow.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 790. `/dev/urandom`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 791. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\GenericFeatures\Source\GenericFeatures\Private\Character\State\StateReflectComp.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 792. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Component\CreativePhysicsComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 793. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Gameplay\ShowAllPlayerManagerActor.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 794. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeStreamingManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 795. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Widget\CreativeUMGCanvasPanel.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 796. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\CreativeLua\CreativeLuaVMManager.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 797. `D:\Release4.6.0\AS\Survive\Plugins\PhotonBlast\Source\PhotonBlast\Private\PhotonFracturedMesh\PhotonInstancedDestructibleMeshComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 798. `D:\Release4.6.0\AS\Survive\Plugins\CreativeLua\Source\CreativeLua\Private\CreativeLua.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 799. `/Script/CreativeLua`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 800. `D:\Release4.6.0\AS\Survive\Plugins\AutoRobot\Source\AutoRobot\AutoRobotThread4Sync.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 801. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\PhysXVehicles\Source\PhysXVehicles\Private\PhysXVehicleManager.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 802. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraDataInterfaceCurve.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 803. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraEmitterInstance.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 804. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraSystemSimulation.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 805. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Experimental\GameFeatures\Source\GameFeatures\Private\GameFeaturesProjectPolicies.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 806. `D:\Release4.6.0\AS\Survive\Plugins\bp_plugin\Source\bp_plugin\Private\bp_pluginBPLibrary.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 807. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\MainCity\Source\ReplayRecover\ReplayRecoverSubsystem.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 808. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 809. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxExtBpCall\PxExtBpItemMulticastDelegate.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 810. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdObject\PxCustomInterfaceDyImp.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 811. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdObject\PxObjectProxy\PxScriptVMWrapper.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 812. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\GameletPuerts\Source\GameletJsEnv\Private\GameletTypeScriptGeneratedClass.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 813. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PandoraPickerPlugin\Source\PandoraPickerPlugin\Private\BP_PandoraPickerLibraryLibrary.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 814. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PandoraPickerPlugin\Source\PandoraPickerPlugin\Private\IPandoraPicker.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 815. `D:\Release4.6.0\AS\Survive\Plugins\QDevKit\Source\QDevKit\Private\QPlatformMisc.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 816. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\Skeleton.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 817. `/Script/UAEStateMachine`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 818. `/Script/CableComponent`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 819. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanSwapChain.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 820. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\Monster\MonsterAnimListComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 821. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_CharacterMontage.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 822. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\MileStone\EmoteAction_MileStoneWeapon.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 823. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Buff\GSListener_FireBtnHitted.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 824. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Buff\STBuffApplifierSpreading.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 825. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\CharacterWeaponManagerComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 826. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\MobMoveBatchSyncManager.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 827. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\PUBGDoorNormal.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 828. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\STBuildingActorBase_RandomRocket.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 829. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CharacterComponent\EmoteDriverComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 830. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CommonBtnComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 831. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\DynamicRainController.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 832. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\GameEventListener.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 833. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\TimerRegistComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 834. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\FourInOne\PolygonSoftBoundaryActor.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 835. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\SocialIsland\SocialIslandGameState.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 836. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Online\STExtraOnlineSession.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 837. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\PetAI\PetBTTask_PetFalling.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 838. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\STExtraOBState.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 839. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Utils\AIUtilsLibrary.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 840. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Security\Weapon\DefaultAntiCheatComponent.cpp`

Security/anti-cheat-related component by name. It may collect, evaluate, or report integrity/gameplay signals, but the filename alone cannot establish its checks or enforcement behavior.

## 841. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\UIManager\MapUIMarkManager.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 842. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\PickUp\PickupListWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 843. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Utility\TriggerAction_SpawnItemUtils.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 844. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Floating\FloatingVehicleVehicleMovementComponent2.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 845. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\STExtraVehicleBase.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 846. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleAvatarComponentBattle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 847. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleSeatComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 848. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleSeatComponent_Camera.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 849. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\STExtraShootWeapon.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 850. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\STExtraShootWeaponBulletBase.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 851. `/proc/%d/maps`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 852. `/sdcard/Android/data/com.pubg.ilite/files/ansi.flag`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 853. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Internationalization\ICUText.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 854. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\ProfilingDebugging\InstanceCounter.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 855. `/Docking/AppTab_Foreground`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 856. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\Commands\UICommandDragDropOp.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 857. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Landscape\Private\LandscapeRenderMobile.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 858. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateRHIRenderer\Private\SlateRHIRenderer.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 859. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\ScaleBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 860. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\VerticalBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 861. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\PreCreateWidgetCache.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 862. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\BehaviorTree\Decorators\BTDecorator_BlackboardBase.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 863. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\PacketHandlers\PacketHandler\Private\PacketHandler.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 864. `/Script/PacketHandler`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 865. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Advertising\Advertising\Private\Advertising.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 866. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\ActorConstruction.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 867. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AI\Navigation\PImplRecastNavMesh.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 868. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimSequenceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 869. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AssetManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 870. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AudioThread.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 871. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\StaticMeshComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 872. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\GameSession.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 873. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\NetworkDriver.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 874. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Scalability.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 875. `/Script/MoviePlayer`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 876. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Online\Voice\Private\VoiceModule.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 877. `D:/Release4.6.0/AS/Survive/Source/UnrealArchExt/Private/FrontendHUD.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 878. `/Script/CommonLib`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 879. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VectorVM\Private\VectorVM.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 880. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\NetworkReplayStreaming\InMemoryNetworkReplayStreaming\Private\InMemoryNetworkReplayStreaming.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 881. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\RepeatFunction.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 882. `v:/devel/projects/oodle2/core/ctmf.h`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 883. `v:\devel\projects\oodle2\core\newlz_tans.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 884. `/usr/local/ssl/certs`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 885. `D:\Release4.6.0\AS\Survive\Plugins\OceanPlugin\Source\OceanPlugin\Private\BuoyantMesh\WaterHeightmapComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 886. `/Script/GEM`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 887. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\TweenFactory\Latent\TweenVector2DLatentFactory.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 888. `D:\Release4.6.0\AS\Survive\Plugins\KantanCharts\Source\KantanChartsSlate\Private\KantanChartsSlateModule.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 889. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\AbilitySystemBlueprintLibrary.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 890. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\GenericFeatures\Source\GenericFeatures\Private\Character\State\StateRelationDataAsset.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 891. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Utility\Tests\CreativeSceneDetectTests.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 892. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\CreativeLua\CreativeLuaSignalManager.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 893. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\CustomAsset\CustomAssetManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 894. `/Script/PhotonBlast`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 895. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraCommon.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 896. `/Script/Niagara`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 897. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Experimental\GameFeatures\Source\GameFeatures\Private\GameFeatureAction_AddComponents.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 898. `D:\Release4.6.0\AS\Survive\Plugins\BuildSystem\Source\BuildSystem\Private\BuildSystemComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 899. `D:\Release4.6.0\AS\Survive\Plugins\EventTrackEx\Source\EventTrackEx\Private\MovieSceneXTEventTemplate.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 900. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\IpConnection.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 901. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\TPlanGame\Source\TPlanGame\Game\GameMode\XTGameMode.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 902. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\Gamelet\Source\Private\GameletLog.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 903. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdObject\PxObjectProxy\PxScriptVMProxy.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 904. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdRes.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 905. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\GameletPuerts\Source\GameletJsEnv\Private\GameletJSGeneratedClass.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 906. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\GameletPuerts\Source\GameletJsEnv\Private\JsEnvModule.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 907. `D:\Release4.6.0\AS\Survive\Plugins\QDevKit\Source\QDevKit\Private\AndroidFileShare.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 908. `D:/Release4.6.0/AS/Survive/Plugins/SpinePlugin/Source/SpinePlugin/Public/spine-cpp/include\spine/HashMap.h`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 909. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Media\ImgMedia\Source\ImgMedia\Private\Readers\GenericImgMediaReader.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 910. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\MovieScene\ActorSequence\Source\ActorSequence\Private\ActorSequenceComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 911. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Launch\Private\Android\AndroidEventManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 912. `/sys/devices/system/cpu/possible`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 913. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanMemory.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 914. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanQueue.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 915. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\DataDriverAnim\DataDriverAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 916. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\STPawnAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 917. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AnimNotify\AnimNotifyState_SubActorAnim.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 918. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Interface\AvatarCharacterEffect.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 919. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Interface\AvatarVehicleEffect.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 920. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AvatarDIY\Entity\VehicleDIYEntity.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 921. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STCharFollowExComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 922. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\MapMarkSync\MapMarkSyncManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 923. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\PUBGSlideDoor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 924. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\Audio\AudioRegionMgrComponent.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 925. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\LuaTaskComponent.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 926. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\ParachuteFollowComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 927. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\VehicleRadarSearchComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 928. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\STExtraNetGuidNewObjectPool.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 929. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Lobby\component\LobbyWeaponManagerComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 930. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\PetAI\PetBTTask_PetFlyToOwner.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 931. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\FourInOne\FourInOneSoftBoundCheckComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 932. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\GroupBackpackComp.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 933. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\State\StatePC_Fight.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 934. `D:\Release4.6.0\AS\Survive\Source\Basic\Framework\OnlyActorComponent\OnlyActorCompManagerComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 935. `D:\Release4.6.0\AS\Survive\Source\Basic\Lua\LuaSuperData.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 936. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\CompressTextureHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 937. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\SpecialZoneActor.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 938. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Decorator\BTDecorator_CheckEnvironment.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 939. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Decorator\BTDecorator_GeneralLineTrace.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 940. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Service\BTService_HealthCheck.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 941. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_PlayEmoteAndVoice.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 942. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\SpiderSwing\SpiderSwingMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 943. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\AircastVehicle\AircraftVehicleBase.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 944. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\BioSpecialMoves\BioSpecialMoveCompBase.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 945. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Effect\BioVehicleGroundDust.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 946. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BlanketVehicle\BlanketVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 947. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BroomVehicle\BroomVehicleMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 948. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\SnowBall\SnowBallMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 949. `/sdcard/Android/data/com.tencent.ig/files/ansi.flag`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 950. `/sdcard/Android/data/com.tencent.igce/files`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 951. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\HAL\Allocators\CachedOSPageAllocator.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 952. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\HAL\MallocBinned2.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 953. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\Serialization\DuplicateDataReader.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 954. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\Linker.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 955. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\PropertyByte.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 956. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\PropertySet.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 957. `/Docking/ShowTabwellButton_Hovered`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 958. `/Docking/AppTab_ColorOverlay`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 959. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Views\SExpanderArrow.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 960. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/SceneCaptureRendering.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 961. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/SceneRendering.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 962. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Landscape\Private\Landscape.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 963. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Online\HTTP\Private\Curl\CurlHttp.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 964. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\CanvasPanel.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 965. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\SpinBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 966. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\TextBlock.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 967. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\Throbber.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 968. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\WindowTitleBarArea.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 969. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\WidgetBlueprintGeneratedClass.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 970. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\EnvironmentQuery\EnvQueryInstance.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 971. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\NetworkReplayStreaming\NullNetworkReplayStreaming\Private\NullNetworkReplayStreaming.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 972. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimNotify_PlayParticleEffect.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 973. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Rendering\ColorVertexBuffer.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 974. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SkeletalMeshComponentPhysics.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 975. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Slate\SGameLayerManager.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 976. `D:\Release4.6.0\AS\Survive\Plugins\QRCodeUtility\Source\QRCodeUtility\Private\VideoThumbnailGenerator.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 977. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\CommonGameFeatures\Source\CommonGameFeatures\RepControl\ActorRepControlComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 978. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\OnlineSubsystemUtils.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 979. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\PlanPH\Source\PlanPHRuntime\GameCore\PlanPH_GameState.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 980. `D:\Release4.6.0\AS\Survive\Plugins\GVoiceSDK\Source\GVoiceSDK\Private\GVoiceSDK.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 981. `D:\Release4.6.0\AS\Survive\Plugins\MMKVUnreal\Source\MMKVUnreal\Private\MMKVObject.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 982. `D:\Release4.6.0\AS\Survive\Plugins\Pandora\Source\Pandora\Private\Components\Scale9Grid.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 983. `D:\Release4.6.0\AS\Survive\Plugins\QDevKit\Source\QDevKit\Private\Android\SystemPermissionHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 984. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\AtlasAttachmentLoader.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 985. `/Script/SpinePlugin`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 986. `D:\Release4.6.0\AS\Survive\Plugins\UnrealAgent\Source\HTTPServer\Private\HttpListener.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 987. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\CustomMeshLoader\Source\CustomMeshLoader\Private\RuntimeSkeletalMeshBuilder.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 988. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanIndexBuffer.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 989. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\AnimNotify\AnimNotify_TimedAkEvent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 990. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\STExtraAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 991. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AvatarDIY\Action\AvatarAction_ApplyDIYPattern.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 992. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\ChipBattleItemHandle.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 993. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_AvatarSlot.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 994. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Chat\ChatComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 995. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\AirAttackLocatorComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 996. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\GeneralSMComponent\Task\GeneralSMTask_SetComponentsCollisionEnabled.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 997. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\LandScapeLODByHeight.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 998. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\STExtraNetBunchQueueSystem.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 999. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\SocialIsland\IslandGameState.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1000. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\IdeaDecal\IdeaDecalManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1001. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Assist\UAERecastNavMesh.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1002. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Component\AIAttributeModifyComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1003. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Component\FlyingCharacterMovement.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1004. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UAESkillPicker_Box.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1005. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Utility\BitMsg.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1006. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Airdrop\VehicleAirdropComponent_WithDamping.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1007. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Wheeled\STExtraVehicleMovementComponent4W.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1008. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\BulletHitInfoUploadComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1009. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\Grenade\ExplosionFinder.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1010. `D:\Release4.6.0\AS\Survive\Source\Basic\Skill\SkillLuaUtils.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1011. `D:\Release4.6.0\AS\Survive\Source\Client\Private\CDNUpdate.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1012. `D:\Release4.6.0\AS\Survive\Source\Client\Private\LuaClassObj.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1013. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\BugReporter.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1014. `/Script/MovieSceneTracks`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1015. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\NativeWidgetHost.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1016. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\PanelWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1017. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\BehaviorTree\BlackboardData.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1018. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\BehaviorTree\BlueprintNodeHelpers.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1019. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AI\Navigation\NavAreas\NavAreaMeta.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1020. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AI\Navigation\NavigationPath.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1021. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimNode_AnimInstanceContainer.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1022. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\GPUSort.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1023. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\ShaderCompiler\ShaderCompiler.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1024. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\StaticMeshBuild.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1025. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\StreamingSM\StreamingManagerStaticMesh.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1026. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\TextureDerivedData.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1027. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ClothingSystemRuntime\Private\ClothingSimulationNv.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1028. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ClothingSystemRuntime\Private\NvCloth\extensions\ClothMeshQuadifier.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1029. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\OpenGLDrv\Private\OpenGLShaders.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1030. `D:/Release4.6.0/AS/Survive/Source/UnrealArchExt/Private/UAEDataTable.Cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1031. `/Script/SurviveLoadingScreen`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1032. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\NamedVar.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1033. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\BlockyPresetItemWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1034. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\Search\BlockySearchResultPanel.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1035. `D:\Release4.6.0\AS\Survive\Plugins\iGShareUE4\Source\iGShareUE4\Private\CustomCognitoCredentialsProvider.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1036. `D:\Release4.6.0\AS\Survive\Plugins\iGShareUE4\Source\iGShareUE4\Private\DeveloperAuthenticationProvider.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1037. `v:/devel/projects/oodle2/core/newlzf_escape_packet.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1038. `/../`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 1039. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\Tweens\TweenFloat.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1040. `/Script/GenericFeatures`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1041. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\CreativeLua\Object\CreativePlayerAPIObject.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1042. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Component\CreativeCustomUIDataComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1043. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\UIParticleSystem2\Source\UIParticleSystem2\Private\ParticleWidget2.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1044. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraDataInterfaceSimpleCounter.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1045. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraDataInterfaceVector2DCurve.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1046. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraRenderer.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1047. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Experimental\GameFeatures\Source\GameFeatures\Private\GameFeaturePluginStateMachine.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1048. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PandoraPickerPlugin\Source\PandoraPickerPlugin\Private\Android/Android_JniCall_PandoraPicker.h`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1049. `D:\Release4.6.0\AS\Survive\Plugins\IGH5CachePlugin\Source\IGH5CachePlugin\Private\IGH5Cache.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1050. `/Script/RuntimeMeshComponent`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1051. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Private\SpineSkeletonDataAsset.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1052. `D:/Release4.6.0/AS/Survive/Plugins/SpinePlugin/Source/SpinePlugin/Public/spine-cpp/include\spine/Vector.h`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1053. `/Script/ACLPlugin`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1054. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Media\ImgMedia\Source\ImgMedia\Private\Player\ImgMediaPlayer.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1055. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\CharacterAnimState\Vehicle\AnimInstanceMotorcyclePassenger.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1056. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\Components\CharacterVehicleAnimListComponentBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1057. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\NPC\Animation\STExtraNPCAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1058. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Anim\LobbyAircraftAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1059. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AvatarDIY\WeaponAvatarDIYComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1060. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\BackpackSurfboardHandle.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1061. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_CloneCharacterMontage.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1062. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\MileStone\EmoteAction_MileStoneBackFly.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1063. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STCharacterCarryBackComp.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1064. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STCharacterMovementComponent_Physics.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1065. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\AirDropComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1066. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\AvatarCapture.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1067. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\PartHitPlayerComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1068. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\TimeTableSplineMoveComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1069. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\FeatureSetCollection.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1070. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\PVE\CustomActor\PVEProjectileBase.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1071. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\FourInOne\FourInOneGameMode.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1072. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Online\STExtraGameSession.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1073. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pickup\PickupManagerComponent.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1074. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Component\NewPathFollowingComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1075. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Security\TimeWatchDogComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1076. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\LoopScrollBase.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1077. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\MapUIMarkBaseWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1078. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Trailer\VehicleTrailerComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1079. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Floating\STExtraFloatingVehicleMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1080. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\TrackedVehicle\TrackedVehicleMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1081. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\TrackedVehicle\VehicleSyncComponentBase.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1082. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleSyncComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1083. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\LaserSeekAndLockRPGBullet.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1084. `D:\Release4.6.0\AS\Survive\Source\Basic\Buff\STBuffCondition.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1085. `D:\Release4.6.0\AS\Survive\Source\Basic\Lua\TableManager.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1086. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\FPathCompression.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1087. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\UAEGameEngine.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1088. `D:\Release4.6.0\AS\Survive\Source\Client\Actor\LobbySceneCaptureActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1089. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\SavedFileUtil.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1090. `D:/Release4.6.0/AS/Survive/Source/ClientNet/Private/IMSDKListenerImp.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1091. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\Mod\BaseMLAIStateInfoCollector.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1092. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\Mod\MercenaryJumpObstacleInfoCollector.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1093. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_HangInAir.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1094. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_PlayMontage.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1095. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SmartBearer\BearerUnit\MainCharacterBearerUnit.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1096. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BlanketVehicle\Animation\BlanketVehicleAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1097. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Camel\Animations\CamelRiderAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1098. `/sdcard/Android/data/com.tencent.ig/files`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1099. `/sdcard/Android/data/com.pubg.krmobile/files/ansi.flag`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1100. `/sdcard/Android/data/com.tencent.igce/files/ansi.flag`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1101. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Internationalization\TextFormatter.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1102. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Internationalization\TextLocalizationResource.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1103. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Serialization\BitReader.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1104. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\Blueprint\BlueprintSupport.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1105. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\Misc\PackageName.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1106. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\LinkerLoad.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1107. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\SavePackage.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1108. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\RHI\Private\AsyncPSOManager.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1109. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\RHI\Private\RHICommandList.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1110. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Input\SMultiLineEditableTextBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1111. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/MobileTranslucentRendering.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1112. `/etc/ssl/ca-bundle.pem`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1113. `/Script/EngineMessages`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1114. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\PakFile\Private\IPlatformFilePak.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1115. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimationStreaming.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1116. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PacketHandlers\StatelessConnectHandlerComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1117. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Particles\ParticleBeamModules.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1118. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\OpenGLDrv\Private\AsyncCompilePSOThread.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1119. `// Uses samplerExternalOES`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 1120. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\OpenGLDrv\Private\ShaderPrecompile.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1121. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\OpenGLDrv\Private\OpenGLVertexDeclaration.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1122. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Online\Voice\Private\VoiceCodecOpus.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1123. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\BlockLuaCorePlugin.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1124. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\LocaleFormatter.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1125. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\Widgets\BlockyMenuItemObjects\BlockyMenuItemObject_Variable.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1126. `/Script/Intl`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1127. `v:/devel/projects/oodle2/core/templates/rrvector.h`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1128. `v:/devel/projects/oodle2/core/lznacompressfast.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1129. `v:\devel\projects\oodle2\core\newlz.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1130. `v:/devel/projects/oodle2/core/newlz_vtable.h`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1131. `v:/devel/projects/oodle2/core/newlzhc_decode_parse_inner.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1132. `v:\devel\projects\oodle2\core\rrlzhlw.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1133. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\SceneCaptureWidgetPlugin\Source\SceneCaptureWidgetPlugin\Private\SceneCaptureWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1134. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Wingman\WingmanAvatarComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1135. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AvatarDIY\Entity\WeaponGunEntity.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1136. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\BackpackAvatarItem.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1137. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_LobbyDanceTogether.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1138. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STExtraSimpleCharacter.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1139. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\DayToNightActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1140. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\DynamicBatchActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1141. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\DynamicLevelGenerator.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1142. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\DamageableComponentBase.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1143. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\DamageDrivenMeshChanger.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1144. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\DynamicOptimizeActorComponents.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1145. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\GeneralSMComponent\Task\GeneralSMTask_SetAkEventSwitch.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1146. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\PVE\CustomComponent\PVEProjectileMovementComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1147. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\GameModeStateActive.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1148. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Mesh\UAESkeletalMeshComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1149. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pickup\GlobalPickupManagerComponent.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1150. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pickup\PickupItemUsefulProxy.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1151. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\ClientInGameReplay.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 1152. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\DeathPlaybackUtils.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 1153. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Security\SecurityLogWeaponCollector.cpp`

Security/anti-cheat-related component by name. It may collect, evaluate, or report integrity/gameplay signals, but the filename alone cannot establish its checks or enforcement behavior.

## 1154. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UAESkillPicker_Fan.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1155. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UTSkillLocationPicker_GroundLoc.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1156. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\PolygonDrawWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1157. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Audio\VehicleAudios.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1158. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\STExtraVehicleUtils.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1159. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\SeekAndLockProjectileComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1160. `D:\Release4.6.0\AS\Survive\Source\Basic\UECommon\Private\UELanguageUtilityMethods.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1161. `D:\Release4.6.0\AS\Survive\Source\Client\BpToolLib\STExtraClientUtils.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1162. `D:\Release4.6.0\AS\Survive\Source\Client\ScriptHelp\ScriptHelperClient.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1163. `D:\Release4.6.0\AS\Survive\Source\Client\WINMSDK\WINSDKFBWebLogin.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1164. `D:/Release4.6.0/AS/Survive/Source/ClientNet/Private/StoreGameHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1165. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Component\CustomDamageEventComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1166. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_ChangeWeaponMaterials.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1167. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_PlayParticleScreenEffect.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1168. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_WeaponAttrModifierForbid.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1169. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffConditions\STBuffCondition_IsKillSomeOne.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1170. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Components\EditorPreviewComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1171. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_AddRandomBuff.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1172. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ApplyRadiusDamage.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1173. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_MoveToRelativeLocation.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1174. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SmartBearer\TextureMerge\AvatarMergeUnit.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1175. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\BoardMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1176. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\GhostBalloon\GhostBalloonMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1177. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\AmphibiousSlidingVehicle\AmphibiousSlidingVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1178. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Components\BioFlyMovementComponentBase.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1179. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Components\VehicleHitBioVHComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1180. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\LandingCreatures\Raptor\RaptorVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1181. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\HoverVehicle\HoveringVehicleMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1182. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ClothingSystemRuntime\Private\NvCloth\CsSolverKernel.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1183. `/Script/ClothingSystemRuntime`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1184. `/Script/UnrealArchExt`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1185. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\Custom\CustomActionImp.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1186. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\LogicAnd.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1187. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\ScriptGen/CodeBuilder.h`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1188. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\Search\BlockySearchResults_GraphWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1189. `D:\Release4.6.0\AS\Survive\Plugins\WWise\Source\AkAudio\Private\AkAreaCheckComponent.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 1190. `/Script/UIParticle`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1191. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Component\CreativeWoWInactiveCheckComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1192. `/Script/Creative`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1193. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraDataInterfaceColorCurve.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1194. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraScriptExecutionContext.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1195. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Experimental\GameFeatures\Source\GameFeatures\Private\GameFeaturesSubsystem.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1196. `/Script/QRCodeUtility`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1197. `D:\Release4.6.0\AS\Survive\Plugins\CosHelper\Source\CosHelper\Private\CosResponse.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1198. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\MainCity\Source\MainCity\Animation\CharLocomotionMCAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1199. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PixUIViewPortWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1200. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdRes\PxResSlot.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1201. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\GameletPuerts\Source\GameletJsEnv\Private\JSLogger.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1202. `/Script/KawaiiPhysics`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1203. `D:\Release4.6.0\AS\Survive\Plugins\Pandora\Source\Pandora\Private\Externals\lua\src\luasocket\usocket.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1204. `D:/Release4.6.0/AS/Survive/Plugins/SpinePlugin/Source/SpinePlugin/Public/spine-cpp/include\spine/Pool.h`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1205. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Media\AndroidMedia\Source\AndroidMedia\Private\Player\AndroidMediaPlayer.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1206. `/Script/LightningComponent`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1207. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AnimNotify\AnimNotify_GameplayTagOperation.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1208. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AnimNotify\AnimNotify_PlayFXEffect.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1209. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AnimNotify\AnimNotify_PlayWeaponParticleEffectEnhanced.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1210. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AnimNotify\AnimNotifyState_AttachMeshAndPlayAnim.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1211. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_CloneRagdoll.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1212. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_LockCameraViewType.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1213. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\MoveBatchSyncManager.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1214. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\SimpleRayProjectile.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1215. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\STBuildingActorBase.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1216. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\DivingComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1217. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\InterpToMovementComponent3.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1218. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\PlayerSlideComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1219. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\DSCommand\GrayPushCommand.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1220. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\PVE\Factory\DecoratorUnitFactory.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1221. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\BattleRoyaleGameMode.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1222. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\SocialIsland\IslandGameMode.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1223. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\State\StatePC_Initial.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1224. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\STExtraPlayerController_Spectator.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1225. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\AIWayPointSystem\AIEvent\AIWayPointEvent_Lua.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1226. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Component\AIShootingOffsetComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1227. `D:\Release4.6.0\AS\UE4181\Engine\Source\..\..\..\Survive\Source\ShadowTrackerExtra\ScreenAppearance/ScreenAppearanceProvider.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1228. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\STExtraGameInstance.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1229. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\ScrollableEditableTextBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1230. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Tank\VehicleAvatarComponentTank.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1231. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Tank\VehicleMovementComponentTank.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1232. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleMusicComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1233. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleStatComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1234. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Wheeled\WheeledVehicleProtectionComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1235. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\LaserSeekAndLockWeapon3DWidget.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1236. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\SeekAndLockCrossHairComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1237. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\SeekAndLockRPGBullet.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1238. `/Game/CSV/VibrateAssetsConfig.VibrateAssetsConfig`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 1239. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\UAESpotDataSerialize.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1240. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTaskNode_CharacterCastNoneTargetSkill.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1241. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\AI\Mercenary\Animation\MercenaryAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1242. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\AI\Zombies\VampireZombieAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1243. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Animation\AnimGraphRuntime\AnimNode_ProceduralWalk.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1244. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Animation\AnimGraphRuntime\BlendNodes\AnimNode_InertializationBlendListBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1245. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Components\CharacterAvoidObstacleComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1246. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Components\MultiLinkActorMoveComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1247. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_CameraAnim.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1248. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_HideMesh.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1249. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_SetViewLimit.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1250. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Transformer\Components\TransformerMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1251. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\UAVVine\VineMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1252. `/sys/devices/system/cpu/cpu%d/cpufreq/%s`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1253. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Containers\String.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1254. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\HAL\ThreadHeartBeat.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1255. `/Docking/Tab_Hovered`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 1256. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ImageWrapper\Private\Formats\PngImageWrapper.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1257. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\RenderCore\Private\RenderResource.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1258. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\Docking\FDockingDragOperation.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1259. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\MultiBox\SToolBarSeparatorBlock.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1260. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Input\SCheckBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1261. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Sockets\Private\BSDSockets\SocketSubsystemBSD.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1262. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/ShaderBaseClasses.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1263. `/Script/UMG`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1264. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\DSPVS\Private\DSPVSQuery.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1265. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AssetRegistry\Private\AssetDataGatherer.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1266. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\EnvironmentQuery\EnvQueryInstanceBlueprintWrapper.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1267. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\MovieSceneCapture\Private\MovieSceneCaptureModule.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1268. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\NetworkReplayStreaming\HttpNetworkReplayStreaming\Private\HttpNetworkReplayStreaming.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 1269. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AnimationAsset.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1270. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Audio.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 1271. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\DemoNetDriver.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1272. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\NetObjectPathNameMapping.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1273. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Particles\ParticleModules_Collision.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1274. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Particles\ParticleSystemRender.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1275. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Particles\ParticleTrail2EmitterInstance.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1276. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\PhysLevel.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1277. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ClothingSystemRuntime\Private\NvCloth\SwFabric.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1278. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\CreateFunction.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1279. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\CustomizeEditableText.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1280. `/etc/entropy`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1281. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\ScriptPlugin\ScriptPlugin\Source\Nula\Private\Nula.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1282. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\TweenFactory\Standard\TweenVectorStandardFactory.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1283. `D:\Release4.6.0\AS\Survive\Plugins\slua_unreal\Source\slua_unreal\Private\LuaNet.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1284. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\LiteComponent\CreativeIntegralMechanismLiteComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1285. `D:\Release4.6.0\AS\Survive\Plugins\resetcore-unreal\ReAutomatic\Source\ReAutomatic\Private\API\AutomaticUIHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1286. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\NiagaraShader\Private\NiagaraShared.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1287. `D:\Release4.6.0\AS\Survive\Plugins\CrashSight\Source\CrashSight\Private\CrashSightAnrMonitor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1288. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\VoiceEngineImpl.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1289. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxLibAsync\PxLibAsyncRun.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1290. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdObject\PxDrawItem\PxDrawItem.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1291. `D:\Release4.6.0\AS\Survive\Source\Client\Widgets\SMaskBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1292. `D:/Release4.6.0/AS/Survive/Source/ClientNet/Private/IMSDKManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1293. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\GlobalConfigActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1294. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\UAEChaCustomAnimListComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1295. `D:\Release4.6.0\AS\Survive\Source\AI\Mercenary\MercenaryAICharacterBase.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1296. `/Script/HiggsBoson`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1297. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Animation\AnimInstances\BioVehicleAbilityAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1298. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Animation\AnimInstances\BioVehiclePlayerAbilityAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1299. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_AddComponent.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1300. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_AttrModifier.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1301. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_PlayMontage_Pose.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1302. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_ReplaceAvatarMaterial.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1303. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_SetMoveable.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1304. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Components\QuadrupedHeadVOComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1305. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ActivityInteractiveReset.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1306. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_PlayMontage_IsArmed.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1307. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_PlayMontageByTable.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1308. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_Vault.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1309. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SmartBearer\SmartBearerManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1310. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SmartBearer\Utils\SmartBearerManagerLuaBridge.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1311. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\Nightwatcher\BatSwarmMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1312. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BallVehicle\STExtraBallMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1313. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\BioSpecialMoves\BioSpecialMove_Sprint.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1314. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Components\BioVehicleMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1315. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BlanketVehicle\BlanketMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1316. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\FloatingCapsuleVehicle\FloatingCapsuleVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1317. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\ReindeerCart\Components\ReindeerTerrainAdaptingComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1318. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Serialization\ArchiveSaveCompressedProxy.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1319. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\UObjectAllocator.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1320. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\MultiBox\MultiBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1321. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Sockets\Private\BSDSockets\SocketsBSD.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1322. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/MobileSceneCaptureRendering.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1323. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/VelocityRendering.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1324. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/PostProcess/PostProcessWeightedSampleSum.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1325. `/Script/Foliage`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1326. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\Border.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1327. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\Viewport.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1328. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\PakFile\Private\UnrealPak.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1329. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\InterpToMovementComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1330. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\SplineMeshComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1331. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\GameUserSettings.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1332. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\HierarchicalInstancedStaticMesh.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1333. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\HUD.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1334. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Level.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1335. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\LevelScriptActor.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1336. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\MatineeUtils.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1337. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SceneView.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1338. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SoundNodeWavePlayer.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1339. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\UserDefinedEnum.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1340. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Component\CreativeTaskComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1341. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\GameMode\GameModeStateFighting_Creative.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1342. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeGameParameterManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1343. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Object\CreativeObjectInterface.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1344. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\MainCity\Source\MainCity\Animation\MainCitySeesawAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1345. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\PlanPH\Source\PlanPHRuntime\CustomActor\PlanPHDoor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1346. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\TPlanGame\Source\TPlanGame\Game\GameMode\XTGameModeStateFightingTeam.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1347. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\TPlanGame\Source\TPlanGame\Game\GameMode\XTGameModeStateReady.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1348. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PixUIBPLibrary.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1349. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdObject\PixUIWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1350. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdObject\PxDrawItem\PxBatchDrawItems.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1351. `D:\Release4.6.0\AS\Survive\Plugins\Pandora\Source\Pandora\Private\LuaExtenders\PLuaHttp.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1352. `D:\Release4.6.0\AS\Survive\Plugins\QDevKit\Source\QDevKit\Private\FilePicker.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1353. `D:\Release4.6.0\AS\Survive\Plugins\QDevKit\Source\QDevKit\Private\FirebaseSDK.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1354. `D:\Release4.6.0\AS\Survive\Plugins\TApm\Source\TApm\Private\TApmSceneMarker.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1355. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\SkeletonData.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1356. `/Script/UITweens`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1357. `D:\Release4.6.0\AS\Survive\Plugins\UnrealAgent\Source\HTTPServer\Private\HttpConnectionResponseWriteContext.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1358. `D:\Release4.6.0\AS\Survive\Plugins\UnrealAgent\Source\HTTPServer\Private\HttpRouter.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1359. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanRenderTarget.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1360. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AnimNotify\AnimNotifyState_EquipItem.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1361. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AnimNotify\AnimNotifyState_TimedAttachMesh.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1362. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\CharacterEffectCfg\CharacterEffect_SpawnActor.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1363. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AvatarDIY\DecalBakingActorMgr.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1364. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\BackpackSnowboardItemHandle.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1365. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\MileStone\EmoteAction_MileStoneBase.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1366. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\SpecialMovement\SpecialMoveBaseObj.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1367. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STCharacterMovementComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1368. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STCharacterRescueOtherComp.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1369. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STExtraCharacter.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1370. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\DeathMatch\ScoreBoardActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1371. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\UAEAvatarDisplayDirector.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1372. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\ActorAttachUIComp.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1373. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\BulletTrackComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1374. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\GeneralSMComponent\Task\GeneralSMTask_HideComponents.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1375. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\GeneralSMComponent\Task\GeneralSMTask_PlayAnimMontage.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1376. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\MovementComponent\ObbyActorMoveComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1377. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\PVE\PointEnterAreaComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1378. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\STExtraGameStateBase.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1379. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\SocialIsland\SocialIslandPlayerState.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1380. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Interface\DamageableInterface.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1381. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\SocialIsland\SIslandInteractEmoteComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1382. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\STTouchSelectComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1383. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\PVS\PVSNetRelevantHelper.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1384. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UAESkillPicker_Base.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1385. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\UMG\SimpleScaleBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1386. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Utility\MeshBatchHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1387. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Utility\SkillUtils.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1388. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Aircraft\AircraftMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1389. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Transform\TransformStates.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1390. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\STExtraVehicleBase_AsMovementBase.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1391. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Tank\UGC\VehicleEffectComponentUGCTank.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1392. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleMotorbikeComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1393. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Wheeled\STExtraWheeledVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1394. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\VN\VNTargetedProjectileActor.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1395. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\NewWeaponTypes.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1396. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\WeaponPostFireState.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1397. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\WeaponState\BowAccumulateEnergyState.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1398. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\GenericPlatform\GenericPlatformMemory.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1399. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\HAL\FileManagerGeneric.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1400. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Internationalization\ICUInternationalization.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1401. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Math\TransformVectorized.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1402. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\Misc\WorldCompositionUtility.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1403. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateCore\Private\Styling\CoreStyle.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1404. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\SToolTip.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1405. `/Script/Slate`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1406. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/RendererScene.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1407. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/PostProcess/PostProcessTonemap.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1408. `/Script/Renderer`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1409. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Online\HTTP\Private\HttpManager.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1410. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\MovieScene\Private\Tests\MovieSceneSegmentCompilerTests.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1411. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\MovieSceneTracks\Private\Sections\MovieSceneSkeletalAnimationSection.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1412. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\InvalidationBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1413. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\MultiLineEditableText.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1414. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\UserWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1415. `/Script/GameplayTags`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1416. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\EnvironmentQuery\Tests\EnvQueryTest_Dot.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1417. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\Perception\AISense_Sight.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1418. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimEncoding.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1419. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1420. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimNotifyState_Trail.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1421. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\ProjectileMovementComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1422. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\LODActor.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1423. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\NetworkObjectList.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1424. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PackageMapClient.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1425. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SkeletalMesh.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1426. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\StreamingSM\StreamingStaticMesh.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1427. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AudioMixer\Private\Components\SynthComponent.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 1428. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\SetVar.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1429. `D:\Release4.6.0\AS\Survive\Source\Development\GMCheat\GMCheatHiggs.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1430. `/Script/Development`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1431. `v:/devel/projects/oodle2/core/lznadecompress.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1432. `v:/devel/projects/oodle2/core/rrlzhlwdecompresssub.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1433. `v:\devel\projects\oodle2\core\rrrans64dual.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1434. `D:\Release4.6.0\AS\Survive\Plugins\OceanPlugin\Source\OceanPlugin\Private\OceanManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1435. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\GameplayCueTranslator.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1436. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeModGameTaskManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1437. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Object\CreativeRuntimePlayerBattleDataObject.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1438. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\PhysXVehicles\Source\PhysXVehicles\Private\TireConfig.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1439. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraFunctionLibrary.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1440. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraParameterStore.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1441. `/Script/NiagaraCore`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1442. `/Script/CustomLayout`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1443. `/Script/CommonUIWidget`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1444. `D:\Release4.6.0\AS\Survive\Plugins\EventTrackEx\Source\EventTrackEx\Private\MovieSceneXTQTETemplate.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1445. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystem\Source\Private\NamedInterfaces.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1446. `/Script/PlanCHRuntime`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1447. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxLibCore\1_0_0\PxKit100View.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1448. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdRes\PxBrush\PxSlateGradientBrush.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1449. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdRes\PxResFileLoad.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1450. `D:\Release4.6.0\AS\Survive\Plugins\QDevKit\Source\QDevKit\Private\FirebaseRemoteConfigImpl.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1451. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Private\SpineSkeletonAnimationComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1452. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Private\SpineSkeletonComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1453. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\RegionAttachment.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1454. `D:\Release4.6.0\AS\Survive\Plugins\WebCameraFeed\Source\WebCameraFeed\Private\WebCameraWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1455. `/Script/MediaCompositing`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1456. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemNull\Source\Private\OnlineSubsystemNull.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1457. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanRHI.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1458. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\Manager\IGameAnimAssetManager.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1459. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\Monster\STExtraMonsterAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1460. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\BackpackUtilsClassical.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1461. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STExtraBaseCharacter_Parachute.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1462. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\SubSystem\LagCompensationSubSystem.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1463. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\DesertStorm.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1464. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\EnvControlActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1465. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\TaskAreaActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1466. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\AirAttackComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1467. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CircleMgrComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1468. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\MovementComponent\STProjectileMovementComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1469. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\PlayerSecurityInfoCollector.cpp`

Security/anti-cheat-related component by name. It may collect, evaluate, or report integrity/gameplay signals, but the filename alone cannot establish its checks or enforcement behavior.

## 1470. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\TargetTrainComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1471. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\PVE\CustomComponent\MonsterRagDollComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1472. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameLua\GameLuaEnv.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1473. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameLua\LuaBudgetScheduler.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1474. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\STExtraDSPush.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1475. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\VehicleUserComponent_TLog.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1476. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Private\TargetKeyOperation.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1477. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Assist\DeliveryConditionDistance.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1478. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\ScriptGameplayStatics.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1479. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\MouseMoveDetector.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1480. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\NormalActorPositionWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1481. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Floating\FloatingTrailerBackwardProtectionComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1482. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\AntiCheat\AntiCheatUtils.cpp`

Security/anti-cheat-related component by name. It may collect, evaluate, or report integrity/gameplay signals, but the filename alone cannot establish its checks or enforcement behavior.

## 1483. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\FillGasComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1484. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\WeaponLaserEffectComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1485. `D:\Release4.6.0\AS\Survive\Source\Basic\Buff\STBuffSystemComponent.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1486. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\IStackModifyAttrInterface.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1487. `D:\Release4.6.0\AS\Survive\Source\Client\Notice\HDmpveNotice.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1488. `D:\Release4.6.0\AS\Survive\Source\Client\Private\HTTPDNS.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1489. `D:\Release4.6.0\AS\Survive\Source\Client\Private\SDKCallbackHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1490. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\ImageDownloadUtil.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1491. `D:\Release4.6.0\AS\Survive\Source\Client\Widgets\UAEVarButton.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1492. `D:/Release4.6.0/AS/Survive/Source/ClientNet/Private/IMSDKHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1493. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\BackpackComponent.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1494. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\DynamicSpotContainerComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1495. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\ItemSpotSceneComponent.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1496. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\UAEChaVehAnimListComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1497. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_Mob_MoveTo.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1498. `D:\Release4.6.0\AS\Survive\Source\AI\SpawnSystem\AESpawnSubsystem.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1499. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Addons.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1500. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\AI\MonsterLOD\FakePlayerLODComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1501. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_ChangeGravityScale.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1502. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_StunGrenade.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1503. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffConditions\STBuffCondition_IsMoveDistance.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1504. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\BoardMoveAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1505. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\FreeWallClimbing\AnimInstance_LocomotionSP.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1506. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Horse\HorseVehicleMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1507. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Containers\LockFreeList.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1508. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\PackageFileSummary.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1509. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\ReferenceChainSearch.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1510. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateCore\Private\Input\HittestGrid.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1511. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\MultiBox\SWidgetBlock.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1512. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ShaderCore\Private\ShaderCore.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1513. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/HWSoftwareOcclusion.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1514. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\DSPVS\Private\DSPVSHandler.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1515. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\JsonUtilities\Private\JsonObjectConverter.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1516. `/Script/AssetRegistry`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1517. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\BehaviorTree\Services\BTService_RunEQS.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1518. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\Perception\AIPerceptionSystem.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1519. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Net\Core\Private\Net\Core\Misc\DDoSDetection.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1520. `/Script/MeshDescription`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1521. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\PakFile\Private\SignedArchiveReader.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1522. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Collision\CollisionProfile.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1523. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\GameState.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1524. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\BodyInstance.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1525. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\Array\ArrayLength.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1526. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Public\BlockyLuaGameInstance.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1527. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\MediaAssets\Private\Assets\MediaPlaylist.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1528. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeSpawnManager.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1529. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\CreativeLua\Object\PlayerAttachedToVehicleEventObject.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1530. `D:\Release4.6.0\AS\Survive\Plugins\UgcLua\Source\UgcLua\Private\UgcLua.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1531. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraDataInterfaceSkeletalMesh.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1532. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraDataInterfaceVectorCurve.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1533. `/Script/NiagaraAnimNotifies`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1534. `D:\Release4.6.0\AS\Survive\Plugins\CustomLayout\Source\CustomLayout\Private\Widget\CustomizePanel.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1535. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\MainCity\Source\MainCity\MainCitySubsystem.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1536. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\PlanPH\Source\PlanPHRuntime\Tools\PlanPHGameplayStatics.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1537. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdGlobalVar.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1538. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdMgr.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1539. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdRes\PxResAsset.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1540. `/Script/PixUIProfiler`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1541. `/Script/GameletJsEnv`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1542. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PandoraPickerPlugin\Source\PandoraPickerPlugin\Private\PImageHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1543. `D:\Release4.6.0\AS\Survive\Plugins\iTOP\Source\iTOP\Private\iTOP.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1544. `/Script/LuaHotReload`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1545. `/Script/QDevKit`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1546. `D:\Release4.6.0\AS\Survive\Plugins\SpawnSystem\Source\SpawnSystem\Private\Strategy\Species\STStrategySpecies_SquadRatio.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1547. `/Script/NiagaraUIRenderer`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1548. `/Script/AndroidPermission`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1549. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\LobbyPawnAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1550. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\DeadBox\DeadBoxAvatarComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1551. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\BackpackUAVItem.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1552. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_MeshAnim.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1553. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\MileStone\EmoteAction_MileStoneRank.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1554. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\LagCompensationComponentBase_ProjectileVertify.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1555. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\MoveAntiCheatComponent.cpp`

Security/anti-cheat-related component by name. It may collect, evaluate, or report integrity/gameplay signals, but the filename alone cannot establish its checks or enforcement behavior.

## 1556. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STCharacterSearchFilter.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1557. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\ItemCheckActorBase.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1558. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\PlaneCharacter.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1559. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\MovementComponent\SplineMoveComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1560. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\PlaneComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1561. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\STScreenAppearanceComponentAdditional.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1562. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\ECS\ECSManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1563. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Effects\STEShootWeaponBulletImpactEffect.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1564. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\BattleRoyaleGameModeBase.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1565. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\GameModeStateFinishedGroup.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1566. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\PetSpectator\STExtraPetSpectatorCharacter.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1567. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\STExtraPlayerController_Parachute.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1568. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UAESkillPicker_InRange.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1569. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\WorldSpaceCanvasPanel.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1570. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Utility\TickControlComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1571. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Airdrop\VehicleAirdropComponent_ConstantSpeed.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1572. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Protection\VehicleProtectionComponentBase.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1573. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\STExtraVehicleAIController.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1574. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\TimeLineVehicle\STExtraAmphibiousVehicleTimeline.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1575. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\Projectile\STProjectileTask.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1576. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\STEShootWeaponProjectComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1577. `D:\Release4.6.0\AS\Survive\Source\Client\Private\ViberateEngine.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1578. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\AI\LuaBTNode\LuaBTServiceBase.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1579. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AnimGraphRuntime\Private\AnimNodes\AnimNode_CopyPoseFromMesh.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1580. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\InputKeySelector.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1581. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\BehaviorTree\BehaviorTreeManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1582. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\EnvironmentQuery\EnvQueryManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1583. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\PakFile\Private\CacheCore.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1584. `/Script/MRMesh`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1585. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Classes\Engine\Texture2DArray.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1586. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimationRuntime.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1587. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimInstanceProxy.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1588. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AudioDecompress.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 1589. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Commandlets\SmokeTestCommandlet.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1590. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\KismetSystemLibrary.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1591. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\LevelActor.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1592. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\ProfilingDebugging\MallocLeakReporter.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1593. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\UnrealClient.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1594. `/Script/Serialization`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1595. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\OpenGLDrv\Private\Android\AndroidOpenGL.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1596. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\OpenGLDrv\Private\Android/AndroidOpenGLPrivate.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1597. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\SaveLoadImplement\JsonSaveLoadImplement.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1598. `D:/Release4.6.0/AS/Survive/Source/Intl/Private/StatManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1599. `v:/devel/projects/oodle2/core/lzb_fast_normal.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1600. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PandoraVideoPlayer\Source\PandoraVideoPlayer\Private\BP_PixVideoLibrary.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1601. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\TweenFactory\Latent\TweenVectorLatentFactory.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1602. `/Script/KantanChartsUMG`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1603. `D:\Release4.6.0\AS\Survive\Plugins\slua_unreal\Source\slua_unreal\Private\LuaPatchRPCComponent.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1604. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\GameState\Component\CreativeGameStateComponent.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1605. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeInGameManagerCenter.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1606. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Utility\CreativeBackpackUtils.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1607. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Utility\CreativeSceneDetectLib.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1608. `/usr/local/share/ugclua/5.4/?.ugclua;/usr/local/share/ugclua/5.4/?/init.ugclua;/usr/local/lib/ugclua/5.4/?.ugclua;/usr/local/lib/ugclua/5.4/?/init.ugclua;./?.ugclua;./?/init.ugclua`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1609. `I:\trunk\DevOps\Survive\DeveloperTools\ExtractPak\base.pak`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 1610. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraRendererMeshes.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1611. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraRendererRibbons.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1612. `D:\Release4.6.0\AS\Survive\Plugins\AWSHelper\Source\AWSHelper\Private\AWSHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1613. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\JoinSessionCallbackProxy.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1614. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystem\Source\Private\OnlineSubsystemImpl.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1615. `/Script/PlanPHRuntime`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1616. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdObject\PxSubLayerWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1617. `D:\Release4.6.0\AS\Survive\Plugins\SpawnSystem\Source\SpawnSystem\Private\Strategy\Timing\STStrategyTiming_Trigger.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1618. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Private\SpineAtlasAsset.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1619. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\MeshAttachment.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1620. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\PointAttachment.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1621. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\SkeletonJson.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1622. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanState.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1623. `/Game/Arts_Player/Characters/Mesh/Male/Head/Mesh/CharacterFakeHeadMesh_Lod.CharacterFakeHeadMesh_Lod`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 1624. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\ClothAvatarUtils.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1625. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Buff\STExtraBuffRandomApplierComponent.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1626. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STCharacterMeshComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1627. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\Conveyor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1628. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\DropItemCurveAnimComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1629. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\MapAlertManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1630. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Effect\EffectWeaponCheckReload.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1631. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\PVE\AreaTrigger.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1632. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Interface\ActorHiddenInterface.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1633. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\BaseTaskComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1634. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\VehicleUserComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1635. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Controller\MobAIControllerBase.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1636. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\DeathPlayCameraShot.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 1637. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\ObservingReplay.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 1638. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\DraggableBubblePanel.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1639. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\UMG\ShearScrollBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1640. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Utility\STGeometryUtils.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1641. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\WeaponLogicBaseComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1642. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\WeaponManagerComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1643. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\WeaponStateBase.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1644. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\BudgetScheduler.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1645. `/proc/self/maps`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1646. `/Game/BluePrints/Generator/Base/BP_VehicleAndTreasureBoxGeneratorComponent.BP_VehicleAndTreasureBoxGeneratorComponent_C`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 1647. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\UAEGameMode.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1648. `/Game/Arts_PlayerBluePrints/Vehicle/UAZ01/VH_UAZ01.VH_UAZ01_C`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 1649. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Service\BTService_WeatherTimeCount.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1650. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_FindWayPointByIDList.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1651. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffConditions\STBuffCondition_IsKeepInState.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1652. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\CustomActor\DynamicSplineRoad.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1653. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_FollowMoveActor.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1654. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ReplaceCharAnim.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1655. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SmartBearer\TextureMerge\AvatarMergeUnitManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1656. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\FlyingArmor\FlyingArmorMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1657. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Serialization\LargeMemoryWriter.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1658. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\Class.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1659. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateCore\Private\Sound\SlateSound.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1660. `/Docking/Tab_Inactive`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 1661. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\MultiBox\SButtonRowBlock.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1662. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Sockets\Private\WaterMark.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1663. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateRHIRenderer\Private\SlateRHIResourceManager.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1664. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\RichTextBlock.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1665. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AssetRegistry\Private\NameTableArchive.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1666. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\EnvironmentQuery\Generators\EnvQueryGenerator_PathingGrid.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1667. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Actor.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1668. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AI\Navigation\NavigationSystem.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1669. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AI\Navigation\RecastNavMeshGenerator.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1670. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\DirectionalLightComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1671. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Particles\ParticleComponents.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1672. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\PhysScene.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1673. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\PhysSubstepTasks.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1674. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PlayerCameraManager.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1675. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Rendering\StaticMeshVertexBuffer.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1676. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Streaming\DynamicAtlasTexture2DStreamIn_IO.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1677. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Streaming\Texture2DStreamIn_IO.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1678. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AudioMixer\Private\AudioMixerBuffer.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 1679. `D:\Release4.6.0\AS\Survive\Plugins\resetcore-unreal\CommonLib\Source\CommonLib\Private\Services\LuaService.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1680. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\BlockyTimerParam.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1681. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\Custom\CustomEvent.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1682. `/Script/BlockyLua`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1683. `D:\Release4.6.0\AS\Survive\Source\Development\GMCheat\GMCheatBackpack.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1684. `D:\Release4.6.0\AS\Survive\Source\Development\GMCheat\GMCheatSkill.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1685. `D:\Release4.6.0\AS\Survive\Plugins\iGShareUE4\Source\iGShareUE4\Private\IGShare.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1686. `D:\Release4.6.0\AS\Survive\Plugins\iGShareUE4\Source\iGShareUE4\Private\ManualS3Uploader.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1687. `v:/devel/projects/oodle2/core/lzacompressfast.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1688. `v:\devel\projects\oodle2\core\lzna.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1689. `v:/devel/projects/oodle2/core/newlz_arrays.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1690. `v:/devel/projects/oodle2/core/newlzhc_decode_parse_outer.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1691. `/Script/TweenMaker`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1692. `/Script/KantanChartsSlate`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1693. `/Script/SGameplayAbilities`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1694. `D:\Release4.6.0\AS\Survive\Plugins\QDevKit\Source\QDevKit\Private\Android\FilePicker.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1695. `D:\Release4.6.0\AS\Survive\Plugins\QDevKit\Source\QDevKit\Private\Android\TouchTransmission.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1696. `D:\Release4.6.0\AS\Survive\Plugins\SpawnSystem\Source\SpawnSystem\Private\Strategy\Timing\STStrategyTiming_Period.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1697. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AnimNotify\AnimNotify_PlayParticleEffectWithCondition.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1698. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AnimNotify\AnimNotifyState_TimedActor.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1699. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Emote\DanceTogetherAvatarComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1700. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AvatarDIY\Lobby\UDIYManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1701. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Buff\STExtraDamageActor.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1702. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\NotifySoundManager.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1703. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STExtraBaseCharacter_WeaponSwitch.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1704. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CanBeScannedComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1705. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\SecuryInfoComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1706. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\STBuildSystemComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1707. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\STPlayerCameraManager.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1708. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Effect\EffectReloadWait.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1709. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\BattlePreloadSubSystem.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1710. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\PVE\Factory\AIPlayerUnitFactory.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1711. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\GameModeDataAsset.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1712. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\SocialIsland\SocialIslandGameMode.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1713. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\PetSpectator\PetSpectatorAvatarComp.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1714. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Pet\PetSpectator\STExtraPetSpectatorAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1715. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\State\StatePC.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1716. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Navigation\ST3DNavigationSystem.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1717. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\SkillPhasePawnStateSettings.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1718. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Utility\STExtraMapFunctionLibrary.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1719. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Respawn\VehicleRespawnComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1720. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleModify\VehicleWeapon\VehicleShootWeapon.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1721. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Wheeled\WheeledVehicleRespawnComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1722. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\BounceExplosionProjectileBullet.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1723. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\ExplosionDecal.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1724. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\ProjectileBulletBase.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1725. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\TriggerEvent\WeaponTriggerEventHandleSkill.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1726. `/Script/ShadowTrackerExtra`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1727. `D:\Release4.6.0\AS\Survive\Source\Basic\Buff\STBuffCheckConditionWrapper.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1728. `D:\Release4.6.0\AS\Survive\Source\Basic\TickOptimization\TickOptimizationSubsystem.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1729. `D:\Release4.6.0\AS\Survive\Source\Client\HotUpdate\HttpQueue.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1730. `D:\Release4.6.0\AS\Survive\Source\Client\UMG\MaskImage.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1731. `D:\Release4.6.0\AS\Survive\Source\Client\Widgets\ScatterPlot.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1732. `/Script/ClientNet`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1733. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\UAEChaParachuteAnimListComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1734. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Decorator\BTDecorator_TargetHasBuff.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1735. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Service\BTService_AdvancedShooting.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1736. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Service\BTService_DetectVehicleRisk.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1737. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_EnemySense.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1738. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffConditions\STBuffCondition_IsKill.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1739. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_CharMoveByPath.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1740. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SmartBearer\Merge\AvatarMerger.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1741. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SmartBearer\Merge\MergedMeshCacheManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1742. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SmartBearer\TextureMerge\MeshMergeUtils.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1743. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Pterosaur\PterosaurVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1744. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Mecha\AnimNotify\AnimNotify_ShakeVehicleCamera.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1745. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Myriapod\STExtraHorseMovementCom.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1746. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\OceanVehicle\OceanVehicleMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1747. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Panda\VehicleProtectionComponent_Ball.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1748. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\PenguinCart\Components\PenguinSnowBallComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1749. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ClothingSystemRuntime\Private\NvCloth\SwClothData.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1750. `D:\Release4.6.0\AS\Survive\Plugins\resetcore-unreal\CommonLib\Source\CommonLib\Private\Utility\LambdaRunnable.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1751. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\Arithmetic.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1752. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\BlockyTimer.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1753. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\Comment.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1754. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Public\BlockyLuaCommandlet.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1755. `D:\Release4.6.0\AS\Survive\Source\Development\GMCheat\GMCheatOther.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1756. `v:/devel/projects/oodle2/core/lzb_vfast.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1757. `/Script/OceanPlugin`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1758. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\TweenFactory\Latent\TweenLinearColorLatentFactory.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1759. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\Tweens\TweenRotator.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1760. `D:\Release4.6.0\AS\Survive\Plugins\KantanCharts\Source\KantanChartsUMG\Private\KantanTimeSeriesPlotBase.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1761. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\Abilities\Tasks\AbilityTask_ApplyRootMotionMoveToActorForce.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1762. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\AbilitySystemGlobals.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1763. `D:\Release4.6.0\AS\Survive\Plugins\slua_unreal\Source\slua_unreal\Private\LuaNetSerialization.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1764. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\2D\Paper2D\Source\Paper2D\Private\PaperTileMapComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1765. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraDataInterfaceCollisionQuery.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1766. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraDataInterfaceTexture.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1767. `/Script/NiagaraShader`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1768. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxExtBpCall\PxExtBpItemMap.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1769. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUICanvas\Private\PixCanvasDrawNanoVgImp.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1770. `/Script/PixUICanvas`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1771. `D:\Release4.6.0\AS\Survive\Plugins\MMKVUnreal\Source\MMKVUnreal\Private\MemoryFile.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1772. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemNull\Source\Private\OnlineLeaderboardInterfaceNull.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1773. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemNull\Source\Private\OnlineSessionInterfaceNull.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1774. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\Trace\Source\TraceDataHandler\Private\DataHandler\TraceDataFileHandler.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1775. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanLayers.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1776. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Activity\ActivityUtils.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1777. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AnimNotify\AnimNotifyState_ChangeMaterialParameter.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1778. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Anim\AvatarPendantAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1779. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_WeaponSwitchShow.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1780. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\MileStone\EmoteAction_MileStone.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1781. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\CharacterCacheSubsystem.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1782. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\SimulateSyncSmoothComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1783. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STCharacterCarryBackComp_SubState.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1784. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STCharacterNearDeathComp.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1785. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STExtraBaseCharacter_Shoulder.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1786. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\AirMissile.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1787. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\GeneralSMComponent\Task\GeneralSMTask_PlayParticleEffect.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1788. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomCondition\CustomCndComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1789. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Effect\EffectWait.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1790. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\PVE\CustomComponent\ItemDropMgrComponent.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1791. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\STExtraNewObjectPool.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1792. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\GameModeState_Training.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1793. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\GameModeStateFinishedTeam.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1794. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Lobby\STExtraLobbyVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1795. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\SubSystem\MonsterLODSubsystem.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1796. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\ClientReplayDataReporter.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 1797. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\DeathPlayback.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 1798. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UTSkillLocationPicker_CrossHair.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1799. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\Map\OBMapUIWidgetBase.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1800. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\Slate\MoveSlider.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1801. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\TrackedVehicle\TrackedVehicleSyncComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1802. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleAvatarProperty.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1803. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\CrossHairComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1804. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\SeekAndLockWeapon3DWidget.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1805. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\STExtraWeaponCommonDataLayer.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1806. `D:/Release4.6.0/AS/Survive/Source/ClientNet/Private/HDmpveSDK.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1807. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_CrowdMoveToOcclusion.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1808. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_SummonActor.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1809. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTaskNode_NewParachuteJumpBase.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1810. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Animation\AnimGraphRuntime\AnimNode_PUBGMLookAt.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1811. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_PlayScreenAppearance.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1812. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_PlayMontage_WeaponState.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1813. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillConditions\UAESkillCondition_FaceToPoint.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1814. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\AnimNodes\AnimNode_SyncBlendSpacePlayer.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1815. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Internationalization\TextLocalizationManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1816. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Stats\StatsJank.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1817. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\LinkerManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1818. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateCore\Private\Fonts\FontCacheCompositeFont.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1819. `/Docking/AppTab_ColorOverlayIcon`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 1820. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\MultiBox\SMenuSeparatorBlock.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1821. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ShaderCore\Private\ShaderParameters.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1822. `/etc/pki/tls/certs/ca-bundle.crt`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1823. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\ReferenceSkeleton.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1824. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\AudioComponent.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 1825. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Timeline.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1826. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\MoviePlayer\Private\DefaultGameMoviePlayer.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1827. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\ExecuteablePreview.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1828. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\Utility\HotfixUtility.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1829. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\While.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1830. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\CustomizeEditableTextBox.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1831. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Public\BlockyEditor.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1832. `D:\Release4.6.0\AS\Survive\Source\Development\GMCheat\GMCheatManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1833. `D:\Release4.6.0\AS\Survive\Source\Development\ImGui\Core\ImGuiWindowManager.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1834. `D:\Release4.6.0\AS\Survive\Plugins\iGShareUE4\Source\iGShareUE4\Private\AWSUploader.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1835. `v:/devel/projects/oodle2/core/lznacompressfast.h`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1836. `v:\devel\projects\oodle2\core\newlz_multiarrays.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1837. `v:\devel\projects\oodle2\core\newlzf.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1838. `v:\devel\projects\oodle2\core\newlz_vtable.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1839. `v:\devel\projects\oodle2\core\newlz_offsets.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1840. `v:/devel/projects/oodle2/core/lzblw_fast.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1841. `v:/devel/projects/oodle2/core/rrvarbitcodes.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1842. `/var/run/egd-pool`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 1843. `/usr/bin/ntlm_auth`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1844. `D:\Release4.6.0\AS\Survive\Plugins\WWise\Source\AkAudio\Private\AkComponent.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 1845. `/Script/OMobileFBPL`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1846. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\Abilities\Tasks\AbilityTask_ApplyRootMotionRadialForce.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1847. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\Abilities\Tasks\AbilityTask_PlayMontageAndWait.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1848. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\GenericFeatures\Source\GenericFeatures\Private\Monster\GenericMonster.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1849. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeAdaptiveSchedulManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1850. `D:\Release4.6.0\AS\Survive\Plugins\AutoRobot\Source\AutoRobot\AutoRobotThread4GM.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1851. `D:\Release4.6.0\AS\Survive\Source\Basic\Lua\SluaTool.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1852. `D:\Release4.6.0\AS\Survive\Source\Client\Private\AsyncTaskCDNDownloader.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1853. `D:\Release4.6.0\AS\Survive\Source\Client\Private\GameBusinessManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1854. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\DataTunnel.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1855. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\GCDolphinUpdater.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1856. `D:\Release4.6.0\AS\Survive\Source\Client\Widgets\UAERichTextBlock.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1857. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\UAEWindowComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1858. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_ConvertActorToRotaion.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1859. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_MoveToSafeArea.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1860. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_PickUpItemAtTombBox.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1861. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_Dot.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1862. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\CommonSubSystem\PickTargetSubsystem.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1863. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Components\TweenAnimComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1864. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_AttachActor.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1865. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\FlowerWing\FlowerWingMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1866. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Spectating\OB\ObserverProbeComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1867. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Mecha\Components\MechaDamageComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1868. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\MegaDrop\STExtraMegaDropVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1869. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\NitroBoost\NitroThrusterAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1870. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\PenguinCart\PenguinSnowBall.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1871. `/proc/meminfo`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1872. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Android\AndroidMisc.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1873. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Internationalization\SyntaxHyphen.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1874. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Misc\OutputDeviceAnsiError.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1875. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Modules\ModuleManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1876. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Analytics\AppStartupTracker\Private\AppStartupTrackerModule.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1877. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\Obj.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1878. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\UObjectArray.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1879. `/Docking/Tab_ColorOverlay`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 1880. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/PostProcess/SceneRenderTargets.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1881. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\MovieScene\Private\Tests\MovieScenePreAnimatedStateTests.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1882. `/Script/MovieScene`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1883. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AnimGraphRuntime\Private\BoneControllers\AnimNode_ModifyBone.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1884. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AnimGraphRuntime\Private\BoneControllers\AnimNode_SkeletalControlBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1885. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\HorizontalBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1886. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\ScrollBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1887. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Slate\SRetainerWidget.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1888. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\ScriptPlugin\ScriptPlugin\Source\Nula\Private\lina.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1889. `D:\Release4.6.0\AS\Survive\Plugins\OceanPlugin\Source\OceanPlugin\Private\BuoyancyForceComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1890. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\GameplayAbilityTypes.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1891. `/Script/Paper2D`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1892. `D:\Release4.6.0\AS\Survive\Plugins\AutoRobot\Source\AutoRobot\AutoRobotThread.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1893. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\PhysXVehicles\Source\PhysXVehicles\Private\WheeledVehicleMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1894. `/Script/PhysXVehicles`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1895. `D:\Release4.6.0\AS\Survive\Plugins\CustomLayout\Source\CustomLayout\Private\Widget\SettingCustomPanel.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1896. `D:\Release4.6.0\AS\Survive\Plugins\AIGCKit\Source\AIGCKit\Private\AIGCKitFunctionLibrary.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1897. `D:\Release4.6.0\AS\Survive\Plugins\EZUMG\Source\EZUMG\Private\Widget\RadialPanel.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1898. `/Script/EZUMG`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1899. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\PartyBeaconHost.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1900. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\PlanPH\Source\PlanPHRuntime\GameCore\PlanPH_GameMode.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1901. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\Gamelet\Source\Private\GameletUtilities.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1902. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxLibAsync\PxLibVmAsyncProxy.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1903. `D:\Release4.6.0\AS\Survive\Plugins\IGH5CachePlugin\Source\IGH5CachePlugin\Private\IGH5CacheCDNManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1904. `D:\Release4.6.0\AS\Survive\Plugins\SpawnSystem\Source\SpawnSystem\Private\STSpawnSubsystem.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1905. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\AnimationState.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1906. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Compression\OodleNetwork\Source\Private\OodleNetworkArchives.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1907. `v:\devel\projects\oodle2\network\oodlestaticlzp.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1908. `v:/devel/projects/oodle2/core\rrvarbitcodes.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1909. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\CharacterEffectCfg\CharacterEffect_CharacterMontage.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1910. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AvatarDIY\Entity\WeaponPendantAvatarEntity.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1911. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_ChangeMesh.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1912. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_CharacterLocation.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1913. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\Interface\BackpackOwnerInterface.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 1914. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BloodPactLink\BloodPactLinkTickComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1915. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STCharacterMovementComponent_Observer.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1916. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CharacterAvatarEntity.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1917. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CharacterComponent\PlayEmoteComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1918. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\Camera\CameraModifier_TransTo.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1919. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\SocialIsland\SIslandInactiveClearComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1920. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\State\StateMachineComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1921. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Component\ActorNavComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1922. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Controller\BasicAIController.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1923. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\MobAdvancedMovement\MobAdvancedMovement.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1924. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UAESkillCondition_HandleItemLimit.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1925. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UAESkillPicker_FanForClient.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1926. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UAESkillPickerFilters.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1927. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\CustomComboBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1928. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\Map\MapUIWidgetBase.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1929. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Amphibious\STExtraAmphibiousVehicle2.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1930. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Floating\SurfBoardComp.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1931. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Hlicopter\STExtraHelicopterVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1932. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Tank\VehicleSyncComponentTank.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1933. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\EntityAntiCheatComponent.cpp`

Security/anti-cheat-related component by name. It may collect, evaluate, or report integrity/gameplay signals, but the filename alone cannot establish its checks or enforcement behavior.

## 1934. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\TriggerEvent\WeaponTriggerEventHandleShoot.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1935. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\HAL\ConsoleManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1936. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\ProfilingDebugging\LoadTimeTracker.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1937. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\Serialization\AsyncLoading.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1938. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\RenderCore\Private\DynamicBufferAllocator.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1939. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Framework\Text\SlateHyperlinkRun.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1940. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Images\SThrobber.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1941. `/Script/MaterialShaderQualitySettings`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1942. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/TranslucentRendering.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1943. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\WidgetSwitcher.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1944. `/Script/LevelSequence`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1945. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimMontage.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1946. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\ChildActorComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1947. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\SceneComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1948. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\PhysicsAsset.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1949. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SoundWave.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 1950. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Subsystems\ParallelWorldSubsystem.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1951. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Texture2DDynamic.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1952. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\UserInterface\Canvas.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1953. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\DoNum.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1954. `v:\devel\projects\oodle2\core\longrangematcher.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1955. `v:\devel\projects\oodle2\core\newlz_arrays_huff.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1956. `/sdcard/Download/dolby/da4mg_debug/da4mg_float32_48khz_714.pcm`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 1957. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\ScriptPlugin\ScriptPlugin\Source\ScriptPlugin\Private\LuaStateWrapper.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1958. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\Abilities\GameplayAbilityTargetActor.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1959. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\GameplayCueManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 1960. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\GenericFeatures\Source\GenericFeatures\Private\Monster\Animation\GenericMonsterAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1961. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativePhysicsManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1962. `D:\Release4.6.0\AS\Survive\Plugins\CreativeLua\Source\CreativeLua\Private\CreativeBridgeLuaVM.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 1963. `/Script/UIParticleSystem2`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1964. `D:\Release4.6.0\AS\Survive\Plugins\COSHttpHelper\Source\COSHttpHelper\Private\COSHttpHelper.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1965. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxExtBpCall\PxExtBpMgr.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1966. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxLibCore\1_0_0\PxKit100Util.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1967. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxLibLoader.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1968. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdRes\PxResMat.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1969. `/Script/PixUI`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 1970. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Private\SpineWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1971. `D:\Release4.6.0\AS\Survive\Plugins\UnrealAgent\Source\HTTPServer\Private\HttpConnection.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 1972. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\NiagaraUIRenderer\Source\NiagaraUIRenderer\Private\NiagaraSystemWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1973. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanUtil.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1974. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanViewport.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 1975. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\CharacterAnimState\Vehicle\AnimInstanceCarPassengerBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1976. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\STExtraAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 1977. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\AvatarAssetUtils.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1978. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AvatarDIY\Action\AvatarAction_ApplyMesh.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1979. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_WeaponReloadShow.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1980. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\LagCompensationComponentBase.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1981. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STExtraBaseCharacter.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1982. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STMonsterMeshComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1983. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\EmergencyCallActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1984. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\Audio\AudioRegion.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 1985. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CharacterAvatarMeshClipComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 1986. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CustomGroundMovementComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1987. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\GameModeBaseComponent.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1988. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\SingleTraining\SingleTrainingGameMode.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1989. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\WarGameMode.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 1990. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Private\GameMode\TeamDeathMatch\Component\ArmsRaceWeaponManagerComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 1991. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Props\AirDropListWrapperActor.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 1992. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\ReplayRecordManager.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 1993. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\WonderfulRecordingCut.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 1994. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UTSkillLocationPicker_IndoorLoc.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 1995. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\STExtraGameplayStatics.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1996. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\ExtendedLoopScrollGrid.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 1997. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Utility\ParticleCacheMgr.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 1998. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\STExtraVehicleAudio.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 1999. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\TrackedVehicle\TrackedVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2000. `D:\Release4.6.0\AS\Survive\Source\Basic\Lua\LuaEventSubsystem.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2001. `D:\Release4.6.0\AS\Survive\Source\Client\Private\AsyncLoadWidgetBlueprint.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2002. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\GMLogShare.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2003. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\VoiceSDKNotifyImpl.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2004. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\Mod\BRBaseStateInfoCollector.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2005. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\Mod\StateInfoCollectorBase.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2006. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Component\AIPerceptionDynamicItemComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2007. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Service\BTService_ClearTrouble.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2008. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\AI\NTFox\NTFoxMovementComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2009. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UTSkillLocationPicker_CrossHairMecha.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2010. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\LifterControlMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2011. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Spectating\SpectatingSubsystem.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2012. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Components\BioVehicleAvoidObstacleComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2013. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BroomVehicle\BroomVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2014. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Myriapod\STExtraMyriapodVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2015. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Myriapod\STExtraMyriapodVehMovementCom.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2016. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\NitroBoost\VehicleNitroBoostComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2017. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Titan\Components\TitanSeatComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2018. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Transformer\Audio\TransformerAudio.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2019. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Android\AndroidProcess.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2020. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Containers\ContainersTest.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2021. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\GenericPlatform\GenericPlatformMisc.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2022. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Layout\SScrollBar.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2023. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SandboxFile\Private\IPlatformFileSandboxWrapper.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2024. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Sockets\Private\BSDIPv6Sockets\SocketsBSDIPv6.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2025. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\EditableText.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2026. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\SizeBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2027. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Slate\UMGDragDropOp.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2028. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Animation\AnimEncoding_PerTrackCompression.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2029. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\LightComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2030. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\NewObjectPool\NewObjectPoolSystem.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2031. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\ScriptPlatformInterface.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2032. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SimpleConstructionScript.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2033. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\VorbisAudioInfo.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2034. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\OpenGLDrv\Private\OpenGLES2.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2035. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\OpenGLDrv\Private\OpenGLTexture.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2036. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\Array\GetArrayElement.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2037. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\BlockyPresetWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2038. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\BlockySelectFromSceneWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2039. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\AndroidDeviceProfileSelector\Source\AndroidDeviceProfileSelector\Private\AndroidDeviceProfileSelector.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2040. `v:/devel/projects/oodle2/core/lzadecompresssub.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2041. `D:\Release4.6.0\AS\Survive\Plugins\Pandora\Source\Pandora\Private\PLog.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2042. `D:\Release4.6.0\AS\Survive\Plugins\Pandora\Source\Pandora\Private\ZComponents\RichText\PRichText.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2043. `/Script/TApm`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2044. `/Game/Arts_Player/Characters/Mesh/Male/Head/Mesh/CharacterFakeHeadMesh.CharacterFakeHeadMesh`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 2045. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\AnimLODSubsystem.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2046. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\ExtendAnimLists\SimpleAnimListBaseComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2047. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\STExtraVehicleAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2048. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Vehicle\VehicleContainerAvatarComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2049. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\Observe\BackpackObserverRepActor.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 2050. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Buff\STExtraNewBuffApplierComponent.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2051. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\SimpleLagCompensationComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2052. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STCharacterSearchOtherComp.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2053. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\CirleAreaVolume.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2054. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\HolePerformanceTriggerMgr.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2055. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\STExtraGrenadeBase.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2056. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CharacterAvatarComponent2.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2057. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\LevelDynamicComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2058. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\MissileFlyingAnimationComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2059. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\ProduceDropItemComponent.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 2060. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\ServerSwitchComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2061. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\ActorGirdGenerator\GridGeneratorFactory_Normal.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2062. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\BRReadyStateGroupComponent.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 2063. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\State\StatePC_InExPlane.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2064. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\State\StatePC_ParachuteOpen.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2065. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Private\Trigger\Item\SpotLocSceneComponent.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 2066. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Props\PickUpWrapperActor.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 2067. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Public\AI\Controller\NewFakePlayerAIController.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2068. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\AutoScroll\AutoScrollTextBlock.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2069. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\ScreenMarkManager.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2070. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Effect\VehicleMatEffects.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2071. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\VehicleBackpackComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2072. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Wheeled\STExtraVehicleMovementComponent4W_Replication.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2073. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\VN\VNPainCausingVolComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2074. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\ShootWeaponEntity.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2075. `D:\Release4.6.0\AS\Survive\Source\Basic\Lua\LuaAsyncTasksSubsystem.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2076. `D:\Release4.6.0\AS\Survive\Source\Basic\Lua\LuaEventBridge.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2077. `D:\Release4.6.0\AS\Survive\Source\Client\BpToolLib\BusinessHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2078. `D:\Release4.6.0\AS\Survive\Source\Client\Private\CentauriManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2079. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\PandoraV2Helper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2080. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Decorator\BTDecorator_HasOccludeBuildActor.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2081. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Animation\AnimGraphRuntime\AnimNode_AdvanceBlendSpacePlayer.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2082. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\CustomAnimInstances\VehicleParachuteAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2083. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_PlayAvatarAction.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2084. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_PredictProjectilePath.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2085. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillConditions\UAESkillCondition_RotatorAngle.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2086. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\NinjaRush\NinjaRushObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2087. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\ODMGear\ODMGearMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2088. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\SpiderSwing\SpiderSwingSyncComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2089. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Spectating\OB\Widget\OBModePositionWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2090. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BlanketVehicle\Components\BlanketDanceComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2091. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Titan\Animations\TitanAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2092. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ClothingSystemRuntime\Private\NvCloth\SwCloth.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2093. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Android\AndroidLocalNotification\Private\AndroidLocalNotification.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2094. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\BlockyGraphData.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2095. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\DefineFunction.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2096. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\CustomizeMultiLineEditableTextBox.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2097. `v:\devel\projects\oodle2\core\oodlelzcompressors.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2098. `/etc/localtime`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2099. `/Script/PandoraVideoPlayer`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2100. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\TweenManagerComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2101. `/Script/AnimationBudgetAllocator`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2102. `D:\Release4.6.0\AS\Survive\Plugins\slua_unreal\Source\slua_unreal\Private\LuaState.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2103. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeGridLevelsManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2104. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativePoolManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2105. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Object\CreativeGameObject.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2106. `D:\Release4.6.0\AS\Survive\Plugins\CosHelper\Source\CosHelper\Private\CosHelper.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2107. `/Script/CosHelper`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2108. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\OnlineBeacon.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 2109. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\PartyBeaconState.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 2110. `/Script/TPlanGame`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2111. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdObject\PxCustomDelegate.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2112. `/Script/GameplayTagEvent`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2113. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\Sequence.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2114. `D:\Release4.6.0\AS\Survive\Plugins\SpinePlugin\Source\SpinePlugin\Public\spine-cpp\src\spine\SkeletonBinary.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2115. `/Script/AndroidMediaFactory`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2116. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanDevice.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 2117. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanPipelineState.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 2118. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\EmergencyCallParabagAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2119. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\Manager\AnimLayerStack.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2120. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AnimNotify\AnimNotifyState_TimedAudio.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2121. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\CharacterEffectCfg\CharacterEffectCfgBase.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2122. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Buff\NGCondition_IsEquipSkillProp.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2123. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\ExtendChars\STExtraSimpleCharacterBase.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2124. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\SpecialMovement\DivingMoveObj.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2125. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\STExtraBaseCharacter_Spectator.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2126. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\AirDropBoxActor.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2127. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\CameraModifier_SmartPhotographer.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2128. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\SequenceEventActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2129. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\CharacterComponent\DecoyComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2130. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\GeneralSMComponent\Task\GeneralSMTask_SetSMState.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2131. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\ShowVehicleComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2132. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\STExtraSimpleCharacterPhysics.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2133. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Effect\Effect.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2134. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Effect\EffectRefreshWeapon.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2135. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\GameModeStateFightingWar.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 2136. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Private\GameMode\TeamDeathMatch\BRGameModeStateFighting_DeathMatch.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 2137. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\CompletePlayback.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 2138. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\ReplayRecorders\ReplayRecorder.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 2139. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Replay\STExtraDemoNetDriver.cpp`

Replay/recording subsystem. Likely captures, stores, synchronizes, or plays back gameplay events or session data.

## 2140. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Security\Weapon\VehicleWeaponACComp.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2141. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\CustomScrollBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2142. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\Map\MiniMapUI.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2143. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\SLineChart.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2144. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\WeakGuidWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2145. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Component\Airdrop\WheeledVehicleAirdropComponent_ConstantSpeed.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2146. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Wheeled\STExtraVehicleMovementComponent4W_Drift.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2147. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\Grenade\EliteProjectile.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2148. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\Grenade\PredictLineComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2149. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\NormalProjectileComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2150. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\TriggerEvent\WeaponTriggerEventHandleEnergyBow.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2151. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\WeaponStateManager.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2152. `D:/Release4.6.0/AS/Survive/Source/ClientNet/Private/HDmpveNet.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 2153. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\Mod\MLAINearbyDoorInfoCollector.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2154. `D:\Release4.6.0\AS\Survive\Source\AI\Private\AI.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2155. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Service\BTService_TurnAround.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2156. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_FindWayPoint.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2157. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTaskNode_ParachuteJumpV3.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2158. `D:\Release4.6.0\AS\Survive\Source\Security\HiggsBoson\Private\GlueHiaCamo.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2159. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Animation\AnimGraphRuntime\AnimNode_GroundIK.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2160. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_EnterState.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2161. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffConditions\STBuffCondition_ItemOperation.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2162. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffConditions\STBuffCondition_PlayerState.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2163. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\CustomActor\BuildingMeshArray.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2164. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ActivityInteractiveStarted.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2165. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_SetMeshNeedUpdateEveryFrame.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2166. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\FlyingCloudMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2167. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Camel\CamelMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2168. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\CatapultMachine\STExtraCatapultMachineVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2169. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\ReindeerCart\ReindeerBioVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2170. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Scorpion\ScorpionVehicleMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2171. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Tiger\Components\TigerVehicleMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2172. `/Game/Mod/EvoBase/BluePrints/Actor/BP_UAESkillSequenceActor.BP_UAESkillSequenceActor_C`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 2173. `/sdcard/Android/data/com.vng.pubgmobile/files`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2174. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Internationalization\Internationalization.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2175. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Misc\UProjectInfo.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2176. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\CoreNet.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 2177. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\RHI\Private\GPUProfiler.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 2178. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\RHI\Private\RHIPreRotation.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 2179. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Input\SButton.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2180. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Input\SInputKeySelector.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2181. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Slate\Private\Widgets\Views\STableViewBase.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2182. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/LightGridInjection.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 2183. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/PixelProjectedReflectionRendering.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 2184. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\MovieSceneTracks\Private\Evaluation\MovieSceneAudioTemplate.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2185. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Slate\SWorldWidgetScreenLayer.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2186. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Analytics\AnalyticsET\Private\AnalyticsET.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2187. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\ActorParallelWorld.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2188. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\AI\Navigation\RecastNavMeshDataChunk.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2189. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\MeshComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2190. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\DelayObserveNetConnection.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 2191. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\EngineService.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2192. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Materials\MeshMaterialShader.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2193. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Particles\ParticleModules.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2194. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PhysicsEngine\PhysicalAnimationComponent.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2195. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SparseVolumeTexture\SparseVolumeTextureStreamingManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2196. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\World.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2197. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AudioMixer\Private\AudioMixerSource.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2198. `D:/Release4.6.0/AS/Survive/Source/UnrealArchExt/Private/UAEWidgetContainer.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2199. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\ScriptGen\Lua\LuaBackend.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2200. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\String\StringAppend.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2201. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLua\Private\BlockyStringWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2202. `D:\Release4.6.0\AS\Survive\Source\Development\Private\CloudGMHandle.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2203. `v:\devel\projects\oodle2\core\rrcompressutil.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2204. `D:\Release4.6.0\AS\Survive\Plugins\WWise\Source\AkAudio\Private\AkComponentCallbackManager.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2205. `/sdcard/Download/dolby/da4mg_debug/da4mg_float32_48khz_stereo.pcm`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2206. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\TweenFactory\Standard\TweenVector2DStandardFactory.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2207. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\Tweens\TweenVector.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2208. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\PhotonDestructible\Source\PhotonDestructible\Private\PhotonDestructibleSurface\PhotonDestructibleSurfaceComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2209. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\Abilities\Tasks\AbilityTask_WaitGameplayEffectApplied.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2210. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\AttributeSet.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2211. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\GameplayPrediction.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2212. `D:\Release4.6.0\AS\Survive\Source\Basic\Buff\STBuffEvent.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2213. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\BPClassManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2214. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\ItemContainer.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2215. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\ScreenshotMaker.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2216. `D:/Release4.6.0/AS/Survive/Source/ClientNet/Private/HDmpveConnectorObserver.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2217. `D:\Release4.6.0\AS\Survive\Source\Gameplay\Private\UAEHouseActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2218. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\TeammateMLAIControllerComponent.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2219. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Decorator\BTDecorator_HasStaticOccludePos.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2220. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Decorator\BTDecorator_IsInSafetyCircle.cpp`

Security/anti-cheat-related component by name. It may collect, evaluate, or report integrity/gameplay signals, but the filename alone cannot establish its checks or enforcement behavior.

## 2221. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Service\BTService_ChooseTeammate.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2222. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTaskNode_EquipOrUnWeapon.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2223. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_AddRemoveMapMarkForSelfPawn.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2224. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffConditions\STBuffCondition_IsRescueOther.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2225. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\VehicleActions\STBuffAction_VehicleTriggerFastStart.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2226. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\GeneralNode\Action\GNAction_CharacterPlayMontage.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2227. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\GeneralNode\Action\GNAction_PlayWeaponMontage.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2228. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\RegionOverlap\RegionOverlapComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2229. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ChangeMaterial.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2230. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_LockCameraViewType.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2231. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_Scale.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2232. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ScaleCapsule.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2233. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_SwitchCameraMode.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2234. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\CreateIceRoad\CreateRoadMoveAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2235. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\FreeWallClimbing\FreeWallClimbingComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2236. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\PenguinRocket\PenguinRocketMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2237. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\AnimNodes\AnimNode_SyncSequencePlayer.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2238. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Components\BioBaseFlyComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2239. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Horse\HorseVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2240. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Mecha\Components\MechaMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2241. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Mecha\MechaAimCircle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2242. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\PenguinCart\Components\PenguinCartMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2243. `/sdcard/Android/data/com.tencent.iglitece/files/ansi.flag`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2244. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Async\TaskGraph.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2245. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\GenericPlatform\GenericPlatformTime.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2246. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Misc\CoreGlobals.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2247. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\Internationalization\PackageLocalizationManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2248. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\CoreRedirects.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2249. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateCore\Private\Fonts\FontCache.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2250. `D:\Release4.6.0\AS\Survive\Source\Development\GMCheat\GMCheatWeapon.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2251. `v:/devel/projects/oodle2/core/lznib_vfast.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2252. `v:/devel/projects/oodle2/core/templates/rrnew.h`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2253. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\TweenFactory\Latent\TweenFloatLatentFactory.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2254. `/Script/KantanChartsDatasource`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2255. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\Abilities\Tasks\AbilityTask_ApplyRootMotionConstantForce.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2256. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\Abilities\Tasks\AbilityTask_ApplyRootMotionMoveToForce.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2257. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\GameplayCueSet.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2258. `D:\Release4.6.0\AS\Survive\Plugins\slua_unreal\Source\slua_unreal\Private\LuaOverrider.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2259. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Manager\CreativeSceneQueryManager.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2260. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Object\CreativeEditorObject.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2261. `/Script/ClusterReplication`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2262. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\FX\Niagara\Source\Niagara\Private\NiagaraGPUInstanceCountManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2263. `D:\Release4.6.0\AS\Survive\Plugins\CustomLayout\Source\CustomLayout\Private\CustomLayoutSubsystem.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2264. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\MainCity\Source\MainCity\GameMode\MainCityPlayerState.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2265. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\FindTurnBasedMatchCallbackProxy.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 2266. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystem\Source\Private\OnlineSubsystemModule.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 2267. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxLibProxy.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2268. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdObject\PxObjectProxy\PxRenderImp.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2269. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdRes\PxResImg.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2270. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixQjs\Source\PixQjs\Public\quickjs-dynamic\quickjs_dylib.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2271. `/Script/PandoraPickerPlugin`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2272. `D:\Release4.6.0\AS\Survive\Plugins\GameplayTagEvent\Source\GameplayTagEvent\Private\UAEGameplayTagTypes.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2273. `D:\Release4.6.0\AS\Survive\Plugins\GeneralNode\Source\GeneralNode\Private\GNNode.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2274. `/Script/Pandora`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2275. `/Script/ImgMedia`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2276. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\AndroidDeviceProfileSelector\Source\AndroidDeviceProfileSelectorRuntime\Private\AndroidDeviceProfileSelectorRuntimeModule.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2277. `/system/lib/libhoudini.so`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2278. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\AndroidPermission\Source\AndroidPermission\Private\AndroidPermissionFunctionLibrary.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2279. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanCommandBuffer.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 2280. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\VulkanRHI\Private\VulkanPendingState.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 2281. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Animation\WeaponAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2282. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Actor\ModelActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2283. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\CharacterEffectCfg\ChareterEffect_ChangeWeaponShow.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2284. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\Custom\Custom_PatternNum.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2285. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Avatar\SlotAvatarComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2286. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\AvatarDIY\EffectCfg\WeaponEffect_SetMuzzleEffectByDataAsset.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2287. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_CameraSequence.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 2288. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_CharacterWeaponMontage.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2289. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\BackPack\EmoteAction\EmoteAction_SpawnStaticMesh.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2290. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Character\BaseFPPComponent.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2291. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomActor\SkillRayActor.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2292. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\AvatarEntity.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2293. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\SpectatorComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2294. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\CustomComponent\STExtraPhotonDestructibleSurfaceComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2295. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Game\PVE\Spawner\FakePlayerSpeciesGenerator.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2296. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\FourInOne\FourInOneGameModeTeam.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 2297. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\GameMode\GameModeStateFightingGroup.cpp`

Game-mode/session-state component. Likely defines rules, phases, match flow, or state shared by participants.

## 2298. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\Camera\CameraModifier_Blend.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2299. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Player\SingleBackpackComp.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2300. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Skill\UTSkillLocationPickerFilters.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2301. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Subsystem\LuaReplicateClassRegSubsystem.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2302. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\UI\Widget\NavigatorPannelUAEUserWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2303. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Floating\STExtraFloatingVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2304. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Parachuting\ParachutingVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2305. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Wheeled\STExtraVehicleMovementComponent4W_AntiCheat.cpp`

Security/anti-cheat-related component by name. It may collect, evaluate, or report integrity/gameplay signals, but the filename alone cannot establish its checks or enforcement behavior.

## 2306. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Vehicle\Wheeled\WheeledVehicleBalanceComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2307. `D:\Release4.6.0\AS\Survive\Source\ShadowTrackerExtra\Weapons\EnergyAccumulateShootComponent.cpp`

Weapon/projectile subsystem. Likely handles weapon state, firing, projectiles, hit effects, ammunition, or related gameplay logic.

## 2308. `D:\Release4.6.0\AS\Survive\Source\AI\MLAI\Mod\MPStateInfoCollector.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2309. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Service\BTService_ChooseEnemy.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2310. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_MoveToOcclusion.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2311. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Animation\AnimGraphRuntime\AnimNode_ProceduralWalkSafety.cpp`

Security/anti-cheat-related component by name. It may collect, evaluate, or report integrity/gameplay signals, but the filename alone cannot establish its checks or enforcement behavior.

## 2312. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffEvent\STBuffEvent_RescueOther.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2313. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ActivityInteractiveFinished.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2314. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_DestroyActor.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2315. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_FindLocation.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2316. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_LaunchToxicGrnd.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2317. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_MoveToBlackboardLocation.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2318. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_PlayMontage_Pose_IsArmed.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2319. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_ShowSkillPrompt.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2320. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SmartBearer\Merge\CustomSkeletalMeshMerge.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2321. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SpecialMove\NinjaMove\NinjaMoveObj.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2322. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\Animation\BioVehicleAnimInstanceBase.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2323. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Myriapod\STExtraMyriapodVehMovementCom_Observer.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2324. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\OceanVehicle\Animation\RaysFishAnimInstance.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2325. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Internationalization\StringTableCore.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2326. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Tests\Misc\TripleBufferTest.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2327. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ApplicationCore\Private\Android\AndroidApplication.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2328. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\Serialization\BulkData.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2329. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\LazyObjectPtr.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2330. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\LinkerSave.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2331. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\PropertyArray.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2332. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateCore\Private\Logging\EventLogger.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2333. `/Docking/ShowTabwellButton_Normal`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 2334. `/Docking/AppTab_Inactive`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 2335. `/Docking/OuterDockingIndicator`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 2336. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateCore\Private\Widgets\SWindow.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2337. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\HeadMountedDisplay\Private\HeadMountedDisplayFunctionLibrary.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2338. `D:/Release4.6.0/AS/UE4181/Engine/Source/Runtime/Renderer/Private/PostProcess/RenderTargetPool.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 2339. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Landscape\Private\LandscapeCollision.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2340. `/Script/Landscape`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2341. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Online\HTTP\Private\HttpTests.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 2342. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\SlateRHIRenderer\Private\Slate3DRenderer.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2343. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\MultiLineEditableTextBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2344. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\NamedSlot.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2345. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Navmesh\Private\DetourTileCache\DetourTileCacheBuilder.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2346. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AIModule\Private\BehaviorTree\Decorators\BTDecorator_CheckGameplayTagsOnActor.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2347. `/Script/AIModule`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2348. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\MRMesh\Private\MRMeshComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2349. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Camera\CameraPhotography.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2350. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\DynamicAtlasTexture2D.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2351. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\LevelStreaming.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2352. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\LocalPlayer.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2353. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\ModelRender.cpp`

Graphics/rendering subsystem. Likely manages rendering resources, GPU commands, presentation, or graphics API integration.

## 2354. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Pawn.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2355. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SoundClass.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2356. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\TimerManagerTests.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2357. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\VoiceChannel.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2358. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Android\AudioMixerAndroid\Private\AudioMixerPlatformAndroid.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2359. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private/BlockBase.h`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2360. `D:\Release4.6.0\AS\Survive\Plugins\BlockyLua\Source\BlockyLuaCore\Private\ForEach.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2361. `D:\Release4.6.0\AS\Survive\Source\Development\GMCheat\GMCheatLevel.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2362. `v:\devel\projects\oodle2\core\lza.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2363. `v:/devel/projects/oodle2/core/rrarenaallocator.h`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2364. `v:\devel\projects\oodle2\core\rrlzh_lzhlw_shared.cpp`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2365. `D:\Release4.6.0\AS\Survive\Plugins\TweenMaker\Source\TweenMaker\Private\TweenManagerActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2366. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\Abilities\GameplayAbility.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2367. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\Abilities\Tasks\AbilityTask.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2368. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\GameplayAbilities\Source\GameplayAbilities\Private\AbilitySystemComponent_Abilities.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2369. `D:\Release4.6.0\AS\Survive\Plugins\slua_unreal\Source\slua_unreal\Private\Log.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2370. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\GenericFeatures\Source\GenericFeatures\Private\Monster\Animation\GenericMonsterAnimShareParamsComp.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2371. `/Script/UgcLua`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2372. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsys`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 2373. `D:\Release4.6.0\AS\Survive\Source\Basic\Private\UAENetActor.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 2374. `D:\Release4.6.0\AS\Survive\Source\Client\Tools\VoiceSDKInterface.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2375. `D:\Release4.6.0\AS\Survive\Source\Client\UMG\DragDropTextBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2376. `/Game/Mod/EvoBase/BluePrints/Actor/BP_CharacterLevelSequenceActor.BP_CharacterLevelSequenceActor_C`

An Unreal asset/UI resource path. It identifies a packaged content asset or interface resource; the exact behavior requires inspecting that asset.

## 2377. `D:\Release4.6.0\AS\Survive\Source\AI\Private\Task\BTTask_RotateToTarget.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2378. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffActions\STBuffAction_HighLightEffect.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2379. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Buffs\BuffConditions\STBuffCondition_IsOnWater.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2380. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_LaunchMove.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2381. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_PostEventAtLoc.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2382. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillActions\UAESkillAction_SetMaterialParameterValueWithAvatarSlot.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2383. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Skills\SkillConditions\UAESkillCondition_CheckActivityActor.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2384. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\SmartBearer\TextureMerge\TextureMergeUtils.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2385. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\BioVehicles\BioVehicleBase.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2386. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Drone\DroneVehicle.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2387. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\MTLB\AnimInstanceMTLB.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2388. `D:\Release4.6.0\AS\Survive\Source\Addons\Addons\Vehicles\Titan\Components\TitanMovementComponent.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2389. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Android\AndroidMemory.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2390. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Misc\CoreMisc.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2391. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Core\Private\Serialization\Csv\CsvParserTests.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2392. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\ApplicationCore\Private\Android\AndroidErrorOutputDevice.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2393. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\CoreUObject\Private\UObject\UObjectHash.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2394. `/Script/InputCore`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2395. `/Script/SlateCore`

An Unreal Engine reflected script/package identifier. It names a runtime module or asset namespace, not a standalone source file.

## 2396. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UtilityShaders\Private\ClearQuad.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2397. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AnimGraphRuntime\Private\BoneControllers\AnimNode_AnimDynamics.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2398. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\AnimGraphRuntime\Private\BoneControllers\AnimNode_QuadrupedTerrainAdapting.cpp`

Animation system component. Likely controls animation instances, state transitions, montages, pose data, or animation-related events.

## 2399. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\CheckBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2400. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\CircularThrobber.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2401. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\EditableTextBox.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2402. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\UMG\Private\Components\StaticMeshWidget.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2403. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Collision\WorldCollision.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2404. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\MovementComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2405. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Components\ReflectionCaptureComponent.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2406. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\DSPrecomputedVisibilityData.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2407. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\Materials\MaterialInstance.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2408. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\ObjectLibrary.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2409. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\PersistentObjectManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2410. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\SCS_Node.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2411. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\StreamableManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2412. `D:\Release4.6.0\AS\UE4181\Engine\Source\Runtime\Engine\Private\UserInterface\PlayerInput.cpp`

Player/character subsystem. Likely manages character state, movement, controller interaction, replication, or player-facing behavior.

## 2413. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\GenericFeatures\Source\GenericFeatures\Private\Component\BehaviorControlComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2414. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\GenericFeatures\Source\GenericFeatures\Private\Monster\GenericMonsterBase.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2415. `D:\Release4.6.0\AS\Survive\Plugins\SkillEditor\Source\Skill\SkillLua\UTSkillAction_Lua.cpp`

Lua scripting integration. Likely exposes engine/game APIs to scripts, manages script state, scheduling, callbacks, or Lua-related data.

## 2416. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\Private\Object\CreativeModeStaticMeshBatchActor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2417. `D:\Release4.6.0\AS\Survive\Plugins\Creative\Source\Creative\CustomAsset\CustomAudio\Tool\CustomAudioWemTool.cpp`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2418. `D:\Release4.6.0\AS\Survive\Plugins\AutoRobot\Source\AutoRobot\AutoRobotInputProcessor.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2419. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Online\OnlineSubsystemUtils\Source\OnlineSubsystemUtils\Private\OnlineBeaconHost.cpp`

Networking/online subsystem. Likely handles connections, sessions, transport, replication, requests, or online-service integration.

## 2420. `D:\Release4.6.0\AS\Survive\Plugins\GameFeatures\TPlanGame\Source\TPlanGame\Game\BackPack\BackpackTPlanUtils.cpp`

Inventory/item subsystem. Likely manages pickups, item state, equipment, storage, or item-related UI.

## 2421. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdCore\PxExtBpCall\PxExtBpItemArray.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2422. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdObject.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2423. `D:\Release4.6.0\AS\Survive\Plugins\GameletSDK\PixUI\Source\PixUI\Private\PxMdObject\PixUIScriptVM.cpp`

User-interface component. Likely implements a widget, layout, input interaction, or UI rendering behavior.

## 2424. `D:\Release4.6.0\AS\Survive\Plugins\IGH5CachePlugin\Source\IGH5CachePlugin\Private\IGH5CachePlugin.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2425. `D:\Release4.6.0\AS\Survive\Plugins\MetaperfSupport\Source\MetaperfSupport\Private\MetaperfSession.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2426. `D:\Release4.6.0\AS\Survive\Plugins\MMKVUnreal\Source\MMKVUnreal\Private\MMKV.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2427. `/usr/local/lib/lua/5.3/?.so;/usr/local/lib/lua/5.3/loadall.so;./?.so`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2428. `D:\Release4.6.0\AS\Survive\Plugins\RuntimeMeshComponent\Source\RuntimeMeshComponent\Private\RuntimeMeshComponent.cpp`

A source-file path retained in the binary, probably from build/debug metadata or diagnostic strings. The filename suggests its subsystem; it is not the source code itself and does not prove that the file is present on the device.

## 2429. `v:/devel/projects/oodle2/network/arith_o0.inl`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2430. `D:\Release4.6.0\AS\UE4181\Engine\Plugins\Runtime\CustomMeshLoader\Source\CustomMeshLoader\Private\SModelReader.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2431. `//&(*,`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2432. `/^q/`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2433. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\serialization\Xml\SnRepXCoreSerializer.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2434. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\pvd\src\PxPvdImpl.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2435. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXVehicle\src\VehicleUtilTelemetry.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2436. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\foundation\include/PsSync.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2437. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\PhysX\src\buffering/ScbCloth.h`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2438. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\cloth\NpCloth.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2439. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SimulationController\src\ScScene.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2440. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelAABB\src\BpBroadPhaseSap.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2441. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\ExtFixedJoint.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2442. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\serialization\SnSerializationRegistry.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2443. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\serialization\Xml\SnXmlSerialization.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2444. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\serialization\Binary\SnBinarySerialization.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2445. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\convex\ConvexHullBuilder.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2446. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\Common\src\CmCollection.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2447. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\pvd\src\PxProfileEventImpl.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2448. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevel\common\src\pipeline\PxcNpContactPrepShared.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2449. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\foundation\include/PsThread.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2450. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\pvd\src\PxPvdObjectModelMetaData.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2451. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXVehicle\src\PxVehicleDrive4W.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2452. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXVehicle\src\PxVehicleTireFriction.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2453. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\foundation\include/PsHashInternals.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2454. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelDynamics\src\DyArticulationHelper.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2455. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\ExtFixedJoint.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2456. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\ExtPrismaticJoint.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2457. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\foundation\src\unix\PsUnixMutex.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2458. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXVehicle\src\PxVehicleNoDrive.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2459. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXVehicle\src\PxVehicleDriveNW.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2460. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpActorTemplate.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2461. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SceneQuery\src\SqSceneQueryManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2462. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\compiler\cmake\Android\..\..\..\..\src\foundation\include/PsHashInternals.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2463. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\GeomUtils\src/GuGeometryUnion.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2464. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\PhysXExtensions\src\serialization\Xml/SnXmlVisitorWriter.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2465. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\mesh\GuMeshQuery.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2466. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXVehicle\src\PxVehicleSerialization.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2467. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpBatchQuery.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2468. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevel\software\src\PxsCCD.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2469. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\mesh\GrbTriangleMeshCooking.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2470. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\convex\ConvexPolygonsBuilder.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2471. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\foundation\src\unix\PsUnixThread.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2472. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\particles\NpParticleBaseTemplate.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2473. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SimulationController\src\ScContactReportBuffer.h`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2474. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevel\software\src\PxsContext.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2475. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevel\software\src\PxsDefaultMemoryManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2476. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\pvd\src\PxPvdProfileZoneClient.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2477. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpRigidActorTemplate.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2478. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\PhysX\src\buffering/ScbParticleSystem.h`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2479. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\LowLevel\software\include/PxsDefaultMemoryManager.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2480. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\ExtExtensions.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2481. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\pvd\src\PxPvdDefaultSocketTransport.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2482. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\foundation\include/PsMutex.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2483. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpArticulation.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2484. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SimulationController\src\ScArticulationSim.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2485. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelAABB\src\BpSimpleAABBManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2486. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\Common\src/CmTmpMem.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2487. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\LowLevelDynamics\include/DyThresholdTable.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2488. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\ExtPrismaticJoint.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2489. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpRigidDynamic.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2490. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\Common\src/CmFlushPool.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2491. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpShape.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2492. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\buffering\ScbScene.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2493. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\LowLevel\software\include/PxsCCD.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2494. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\compiler\cmake\Android\..\..\..\..\src\foundation\include/PsArray.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2495. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpArticulationLink.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2496. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\Common\src/CmBitMap.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2497. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelParticles\src\PtContextCpu.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2498. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\foundation\include/PsSList.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2499. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SimulationController\src\cloth\ScClothSim.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2500. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\ExtD6Joint.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2501. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\GuBounds.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2502. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SceneQuery\src\SqExtendedBucketPruner.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2503. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelAABB\src\BpBroadPhase.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2504. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\ExtDefaultStreams.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2505. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\mesh\GuMidphaseInterface.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2506. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\mesh\GuRTree.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2507. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\pvd\src\PxPvdDefaultFileTransport.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2508. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\pvd\src\PxPvdDataStream.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2509. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\foundation\include/PsPool.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2510. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelParticles\src\PtParticleData.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2511. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelAABB\src\BpBroadPhaseSapAux.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2512. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelDynamics\src\DyConstraintPartition.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2513. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\foundation\src\PsFoundation.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2514. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpFactory.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2515. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\foundation\include/PsSort.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2516. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\ExtRigidBodyExt.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2517. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\serialization\SnSerialization.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2518. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpSerializerAdapter.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2519. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SimulationController\src\ScNPhaseCore.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2520. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\convex\ConvexHullLib.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2521. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\GuRaycastTests.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2522. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\convex\GuBigConvexData.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2523. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevel\common\src\pipeline\PxcNpMemBlockPool.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2524. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\Common\src/CmPriorityQueue.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2525. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelCloth\src\Allocator.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2526. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\Quantizer.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2527. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\convex\GuConvexMesh.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2528. `F:\SpatialEngine\SpatialAudio\Resonance\resoance-audio\resonance_audio/node/node.h`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2529. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpShapeManager.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2530. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpVolumeCache.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2531. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\cloth\NpClothFabric.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2532. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SimulationController\src\ScConstraintSim.cpp`

Artificial-intelligence or NPC subsystem. Likely supports behavior trees, navigation, perception, decisions, or non-player entities.

## 2533. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\LowLevel\common\include\utils/PxcThreadCoherentCache.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2534. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelAABB\src\BpBroadPhaseMBP.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2535. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SimulationController\src\particles\ScParticleSystemSim.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2536. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpPhysicsInsertionCallback.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2537. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelDynamics\src\DySolverControl.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2538. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\mesh\RTreeCooking.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2539. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\PhysX\src/NpActorTemplate.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2540. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SceneQuery\src\SqBucketPruner.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2541. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SimulationController\src\ScElementSim.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2542. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\ExtRevoluteJoint.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2543. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\serialization\Binary\SnBinaryDeserialization.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2544. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\Cooking.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2545. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\CookingUtils.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2546. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\mesh\GuBV4Build.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2547. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\mesh\GuBV32.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2548. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\GeomUtils\src\mesh/GuMidphaseInterface.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2549. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelParticles\src\PtSpatialHash.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2550. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\Common\src/CmPreallocatingPool.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2551. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\ExtRevoluteJoint.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2552. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\mesh\GuTriangleMesh.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2553. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\sweep\GuSweepCapsuleBox.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2554. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXVehicle\src\PxVehicleWheels.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2555. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpScene.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2556. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SceneQuery\src\SqPruningStructure.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2557. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SimulationController\src\cloth\ScClothCore.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2558. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\MeshCleaner.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2559. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\EdgeList.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2560. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelParticles\src\PtParticleSystemSimCpu.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2561. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\serialization\Xml\SnXmlVisitorReader.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2562. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\convex\InflationConvexHullLib.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2563. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\GuMeshFactory.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2564. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\pvd\src\PxPvdObjectModelInternalTypes.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2565. `F:\SpatialEngine\SpatialAudio\Resonance\resoance-audio\resonance_audio\dsp\biquad_filter.cc`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2566. `F:\SpatialEngine\SpatialAudio\Resonance\resoance-audio\resonance_audio\ambisonics\ambisonic_binaural_decoder.cc`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2567. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\foundation\include/PsArray.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2568. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\PhysX\src\buffering/ScbScene.h`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2569. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\convex\ConvexMeshBuilder.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2570. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\GuSweepTests.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2571. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SceneQuery\src\SqPruningPool.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2572. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SimulationController\src\ScSimulationController.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2573. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SimulationController\src\cloth\ScClothFabricCore.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2574. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\GuOverlapTests.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2575. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\GeomUtils\src\mesh\GuBV4.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2576. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXVehicle\src\PxVehicleSDK.cpp`

Vehicle or movement subsystem. Likely implements vehicle state, movement, seats, physics, presentation, or related gameplay behavior.

## 2577. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpRigidBodyTemplate.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2578. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpRigidStatic.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2579. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpSceneQueries.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2580. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\PhysX\src\particles/NpParticleFluidReadData.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2581. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SceneQuery\src\SqAABBPruner.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2582. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelDynamics\src\DyDynamics.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2583. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\convex\ConvexHullUtils.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2584. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXCooking\src\convex\QuickHullConvexHullLib.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2585. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\buffering\ScbShape.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2586. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelParticles\src\PtCollision.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2587. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\SimulationController\src\ScBodyCore.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2588. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelCloth\src\SwSolver.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2589. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\LowLevelDynamics\include/DyContext.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2590. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\ExtSphericalJoint.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2591. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysXExtensions\src\serialization\Xml\SnXmlMemoryPool.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2592. `F:\SpatialEngine\SpatialAudio\Resonance\resoance-audio\resonance_audio\dsp\partitioned_fft_filter.cc`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2593. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\GeomUtils\src\mesh/GuMeshData.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2594. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\Common\src\CmRadixSortBuffered.cpp`

Gameplay ability/status-effect subsystem. Likely implements skills, ability phases, buffs, triggers, or temporary gameplay modifiers.

## 2595. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\foundation\src\unix\PsUnixSocket.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2596. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PxShared\src\pvd\src\PxPvdFoundation.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2597. `F:\SpatialEngine\SpatialAudio\Resonance\resoance-audio\resonance_audio\utils\lockless_task_queue.cc`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2598. `F:\SpatialEngine\SpatialAudio\Resonance\resoance-audio\resonance_audio\dsp\sh_hrir_creator.cc`

Audio/voice subsystem. Likely manages sound playback, audio components, voice communication, or audio middleware.

## 2599. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpPhysics.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2600. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\PhysX\src\NpMaterialManager.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2601. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelDynamics\src\DySolverControlPF.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2602. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\LowLevelParticles\src\PtDynamics.cpp`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2603. `I:\dev_engine\DevOps\UE4181\Engine\Source\ThirdParty\PhysX\PhysX_3.4\Source\compiler\cmake\Android\..\..\..\LowLevel\common\include\utils/PxcScratchAllocator.h`

Unreal Engine runtime or plugin source-path string. It identifies an engine subsystem; the exact function is suggested by the directory and filename but cannot be proven from this path alone.

## 2604. `/./f/`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2605. `/"/&/*0`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2606. `/B/F/J/N/R/V/Z/^/b0`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2607. `/z/~/`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2608. `/'/)/A/E/K/M/Q/W/o/u/}/`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2609. `/H/I/J/K/L/Y`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2610. `/p/q/r/s/`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2611. `/(/)/`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2612. `//A!`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2613. `/usr/local/share/lua/5.3/?.lua;/usr/local/share/lua/5.3/?/init.lua;/usr/local/lib/lua/5.3/?.lua;/usr/local/lib/lua/5.3/?/init.lua;./?.lua;./?/init.lua`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2614. `/usr/local/lib/lua/5.3/?.so;/usr/local/lib/lua/5.3/loadall.so;./?.so`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2615. `/./66`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2616. `/ /!/"/#/$/%/&/'/(/)/*/+/,/-/.///0/1/2/3/4/5/6/7/8/9/:/;/</=/>/?/@/A/B/C/D/E/F/G/H/I/J/K/L/M/N/O/P/Q/R/S/T/U/V/W/X/Y/Z/[/\/]/^/_/\`/a/b/c/d/e/f/g/h/i/j/k/l/m/n/o/p/q/r/s/t/u/v/w/x/y/z/{/|/}/~/`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2617. `R:\Sg|p5rL`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2618. `/v]p/w]q/`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2619. `/.](//])/ ]*/!]+/"],/#]-/$]./%]//&] /']!/8]"/9]#/:]$/;]%/<]&/=]'/>]8/?]9/0]:/1];/2]</3]=/4]>/5]?/6]0/`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2620. `////`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2621. `R:/)`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2622. `R:/)`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2623. `/i68/`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2624. `j:\!77`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2625. `/7X!/7x`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2626. `/7X!/7x`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2627. `/7X!/7x`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2628. `b:\;`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2629. `o:\;`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2630. `n:\<`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2631. `W:\;`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2632. `V:\<`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2633. `T:\;`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2634. `D:\<`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2635. `C:\(`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2636. `D:\<`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2637. `B:\h`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2638. `D:\;`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2639. `B:\;`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2640. `C:\<`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2641. `A:\<`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2642. `A:\<`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2643. `A:\<`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2644. `w:\ +`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2645. `w:\ +`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2646. `w:\`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2647. `t:\`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2648. `t:\`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2649. `v:\`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2650. `t:\`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2651. `t:\`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2652. `v:\`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2653. `v:\`

A runtime or build-environment filesystem path embedded in the binary. Its presence may support file access, configuration, diagnostics, or library functionality; it does not prove the path is accessed.

## 2654. `/9A)/`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2655. `t:/_`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

## 2656. `Y:/<_`

An extracted string or identifier. Its role is context-dependent; inspect nearby references and cross-references before assigning behavior.

---

## Recommended analysis workflow

1. Group identical strings and retain their occurrence counts and file offsets.
2. Resolve source-path strings to their nearest subsystem/module and nearby strings.
3. Cross-reference security-related names with callers, imports, logging strings, and control-flow.
4. Separate confirmed facts (disassembly/runtime evidence) from name-based hypotheses.
5. Do not treat a source path or anti-cheat-related name as proof of a working feature or a vulnerability.
