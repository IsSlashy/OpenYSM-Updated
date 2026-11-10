# Yes Steve Model — unofficial Fabric ports

**[Companion model catalog](https://github.com/IsSlashy/Yes-Steve-Model-Repo) · [Model installation and compatibility](https://github.com/IsSlashy/Yes-Steve-Model-Repo/blob/main/COMPATIBILITY.md) · [Tested model ZIP](https://github.com/IsSlashy/Yes-Steve-Model-Repo/archive/1749b46467acea11694891c01ede24914b22dc6c.zip)**

English · Français · 简体中文 · 日本語

| Minecraft | Fabric JAR / Release | Sources |
| --- | --- | --- |
| 26.1 / 26.1.1 / 26.1.2 | [fabric-26.1.x-alpha.1](https://github.com/IsSlashy/OpenYSM-Updated/releases/tag/fabric-26.1.x-alpha.1) | [codex/fabric-26.1-port](https://github.com/IsSlashy/OpenYSM-Updated/tree/codex/fabric-26.1-port) |
| 26.2 | [fabric-26.2-alpha.4](https://github.com/IsSlashy/OpenYSM-Updated/releases/tag/fabric-26.2-alpha.4) | [codex/fabric-26.2-port](https://github.com/IsSlashy/OpenYSM-Updated/tree/codex/fabric-26.2-port) |
| 26.3 | [fabric-26.3-alpha.2](https://github.com/IsSlashy/OpenYSM-Updated/releases/tag/fabric-26.3-alpha.2) | [codex/fabric-26.3-port](https://github.com/IsSlashy/OpenYSM-Updated/tree/codex/fabric-26.3-port) |


## English

Choose the JAR for your exact Minecraft version from the table and install the same file on the server and every client. Releases contain English, French, Simplified Chinese and Japanese instructions, including the verified Windows Java options. Get the original models from the [companion catalog](https://github.com/IsSlashy/Yes-Steve-Model-Repo); model files are unchanged across these ports. This fork's `main` keeps the upstream source snapshot; the current port sources are on the version branches linked above. These are unofficial experimental alpha releases; each Release and port document states its test scope and limits.

## Français

Choisis le JAR de ta version exacte de Minecraft dans le tableau et installe le même fichier sur le serveur et chaque client. Les Releases contiennent les instructions en anglais, français, chinois simplifié et japonais, avec les paramètres Java Windows vérifiés. Les modèles d'origine sont dans le [catalogue associé](https://github.com/IsSlashy/Yes-Steve-Model-Repo) ; leurs fichiers restent inchangés entre ces portages. La branche `main` conserve le code amont ; les sources des portages sont dans les branches de versions liées ci-dessus. Ces Releases sont des alphas expérimentales non officielles ; leurs notes et documents précisent les tests et les limites.

## 简体中文

请从上表选择与 Minecraft 确切版本对应的 JAR，并在服务器和每个客户端安装同一个文件。Release 提供英语、法语、简体中文和日语说明，以及已验证的 Windows Java 参数。原始模型位于[配套模型仓库](https://github.com/IsSlashy/Yes-Steve-Model-Repo)，这些移植版本无需修改模型文件。本仓库的 `main` 保留上游源码快照，当前移植源码请查看上表链接的版本分支。这些是非官方实验性 Alpha 版本，测试范围与限制见各 Release 及移植说明。

## 日本語

表から Minecraft の正確なバージョンに対応する JAR を選び、サーバーとすべてのクライアントに同じファイルを導入してください。Release には英語・フランス語・簡体字中国語・日本語の手順と、検証済みの Windows Java 設定があります。元のモデルは[対応モデルカタログ](https://github.com/IsSlashy/Yes-Steve-Model-Repo)にあり、各移植版のためにモデルファイルを変更する必要はありません。このフォークの `main` は上流ソースのスナップショットを保持し、現在の移植ソースは表のバージョン別ブランチにあります。非公式・実験用アルファ版のため、検証範囲と制限は各 Release および移植ドキュメントを参照してください。

---

## Archived upstream README — main source snapshot

上游项目已迁移至 https://github.com/OpenYSMDev/OpenYSM

增加了对高版本ysm加密模型的加载能力
---

<div align="center">
  <img src="images/banner2.png" alt="logo"/>
  <h1>OpenYSM-Updated</h1>
  <p>OpenYSM 的 fabric 高版本移植</p>
</div>

___

## 注意
### 该项目仅作为高版本移植可行性验证，_**对可用性没有任何保证，使用过程中可能会出现大量bug**_，如果发现问题请提交 issue。
### 目前仅确保了可以进入单人世界并且正常渲染模型，多人游戏及服务器相关功能暂未测试，如果发现问题请提交 issue。

## 版本支持

| 版本      | 支持状态                                        |
|---------|---------------------------------------------|
| 1.20.1  | ✅ (原生)                                      |
| 1.21.1  | ✅ (见 commit history)                        |
| 1.21.4  | ✅ (见 commit history, 有的类忘了交了可能无法编译，从后面的提交里找 |
| 1.21.8  | ✅ (见 commit history)                        |
| 1.21.9  | ✅ (见 commit history)                        |
| 1.21.10 | ✅ (见 commit history)                        |
| 1.21.11 | ✅                                           |
| 26.1.x  | ❌ Architectury 没更新                          |

## 已知问题
ModelPreviewRenderer 中的动画暂未适配, 会出现问题 (sleep, ride 等动画)
