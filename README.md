# eFootball 2027 PC Offline MyClub Mod

## 中文

吹雪可萝卡菲特制作的 Windows PC 离线 MyClub 养成模组，包含球员签约、培养和比赛奖励。部分页面目前仅提供中文。

### 首次安装

1. 在 Steam 安装国际版 eFootball（App ID `1665460`），并登录 Steam。这个小包需要原版游戏文件，制作时使用的 Steam Build ID 是 `25359256`。如果 Steam 游戏版本已变化，请使用与本体匹配的模组版本。预留能同时容纳原版、独立副本和解压临时文件的磁盘空间。
2. 在 Steam 库中找到 eFootball 的本地文件，使用干净的原版目录作为复制来源。如首次安装前还未进入原版，可以先从 Steam 启动原版，让游戏内实时更新完成并进入主菜单，再正常退出。
3. 在 Steam 库目录之外新建安装目录，例如 `D:\efootball`。把原版游戏目录内的内容复制到 `D:\efootball\game`，使 `cpk`、`eFootball` 等目录直属于 `game`。
4. 从 [Releases](https://github.com/light23335/efootball2027-pc-offline-myclub-mod/releases) 下载主包的四个分卷 `efootball2027-pc-offline-myclub-v1-20261118-base.7z.001` 至 `.004`，放在同一文件夹。用 7-Zip 打开 `.001` 并解压。把解压后 `发布` 文件夹里的内容合并到 `D:\efootball`，替换目标副本中的同名文件。最后，`启动养成版游戏.exe` 应和 `game` 文件夹位于同一级。
5. 下载 [Releases](https://github.com/light23335/efootball2027-pc-offline-myclub-mod/releases) 中的 `efootball2027-pc-offline-myclub-v1-20261119-cumulative-update.7z`，解压后也把包内 `发布` 文件夹里的内容合并到同一个安装目录。
6. 保持 Steam 登录，从养成版安装目录双击 `启动养成版游戏.exe`。随包的 `使用说明.html` 提供游戏内功能说明。

### 更新与排查

- 已安装 2026 年 11 月 18 日 V1 的玩家，可以在退出游戏后直接应用 11 月 19 日累计升级包。更新前备份养成版的 `data\gateway` 和 `data\client\Documents`，其中 `data\gateway\my-team.sqlite3` 保存 MyClub 养成数据。
- Steam 库里的原版和养成版副本分开管理。把模组和升级文件应用到养成版目录，Steam 的游戏文件验证用于 Steam 库里的原版。
- 如果游戏提示无法访问服务器，可先用 Steam 启动原版，等游戏内实时更新完成并进入主菜单，再退出并重开养成版。问题持续时，查看养成版目录下的 `data\gateway\growth-startup.log` 和 `data\gateway\growth.log`。

## English

A Windows PC offline MyClub progression mod by 吹雪可萝卡菲特, featuring player signings, squad development, and match rewards. Some pages are currently available only in Chinese.

### First-time installation

1. Install the international Steam edition of eFootball (App ID `1665460`) and sign in to Steam. The base mod archive requires the original game files. It was prepared against Steam Build ID `25359256`. If your Steam game version differs, use a matching mod release. Allow room for the Steam installation, a separate copy, and temporary extraction files.
2. Locate the original game files from your Steam Library and use a clean installation as the source. If you have yet to launch the original game, you can launch it from Steam, let the in-game Live Update finish, reach the main menu, and exit normally.
3. Create an installation folder outside your Steam Library, for example `D:\efootball`. Copy the contents of the original game folder into `D:\efootball\game`. Folders such as `cpk` and `eFootball` should sit directly inside `game`.
4. Download the four base volumes from [Releases](https://github.com/light23335/efootball2027-pc-offline-myclub-mod/releases), from `efootball2027-pc-offline-myclub-v1-20261118-base.7z.001` through `.004`. Keep all four in one folder, open `.001` with 7-Zip, and extract it. Merge the contents of the extracted `发布` folder into `D:\efootball` and replace matching files in that copy. The `启动养成版游戏.exe` launcher should sit alongside the `game` folder.
5. Download `efootball2027-pc-offline-myclub-v1-20261119-cumulative-update.7z` from [Releases](https://github.com/light23335/efootball2027-pc-offline-myclub-mod/releases). Extract it and merge the contents of its `发布` folder into the same mod installation.
6. Keep Steam signed in and double-click `启动养成版游戏.exe` in your mod installation. The package includes `使用说明.html` with further information about its features.

### Updates and troubleshooting

- If you already installed the November 18, 2026 V1 base, close the game and apply the November 19 cumulative update directly. Back up the mod's `data\gateway` and `data\client\Documents` folders first. MyClub progression is stored in `data\gateway\my-team.sqlite3`.
- Keep the Steam installation and the mod installation separate. Apply mod files and updates to your mod installation. Use Steam's file verification on the original Steam installation.
- If the game reports that it cannot reach the server, launch the original from Steam, let the in-game Live Update complete, reach the main menu, then exit and relaunch the mod. If the issue persists, check `data\gateway\growth-startup.log` and `data\gateway\growth.log` in the mod installation.
