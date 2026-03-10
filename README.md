## openclaw-windows-backup Windows本地部署Openclaw的备份脚本

### 使用方式：
将back.md复制到本地，修改默认配置包括：

$backupRoot = "D:\WorkSpace\backup"  备份输出的目录地址

$workspaceSource = "D:\WorkSpace"   Workspace所在目录地址（这个可以在Openclaw的config配置文件中看到）

$openclawSource = "C:\Users\devops\.openclaw"  OpenClaw 配置所在目录地址（默认是C:\Users\用户名\.openclaw）

然后改文件后缀为.ps1格式，右键以PowerShell运行，然后就可以在备份输出的目录地址看到备份内容

### 主要备份内容

<img width="557" height="493" alt="image" src="https://github.com/user-attachments/assets/bce51a17-5b6a-4263-b8a9-6f1df2f213e7" />

### 备份展示

<img width="510" height="125" alt="image" src="https://github.com/user-attachments/assets/c4020bef-e81c-4d80-8b31-118481730bdb" />

千万不要将备份内容（包含config和.env）公开或者提交到Github公共仓库！！！
