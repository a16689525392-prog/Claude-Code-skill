# claude-ceshi
claude 测试项目仓库

## 项目简介

这是一个用来测试 Claude Code 自定义 skill 的仓库，目前收录了一个中文恋爱军师 skill：**狗头军师（进攻版）**。

它专门帮你在追求阶段往前推进：分析聊天记录或截图，判断对方信号的冷热，找出卡在哪一步，再按进攻时间表给出可以直接发送的话术和下一步安排。遇到"这句怎么回""怎么约出来""什么时候表白"这类问题，它会先给一条能直接复制的回复，再说明什么时候发、对方不同反应时怎么接。

- **开箱即用**：只有一个 `SKILL.md`，没有外部依赖。克隆仓库后启动 Claude Code 就能用。
- **强度可调**：有稳健、进攻、满攻三个档位，随时可以说"再猛一点"或"收一点"。
- **有底线**：对方明确拒绝、让你别联系或拉黑时，立即停止。

## Skills

### 狗头军师（进攻版）

路径：`.claude/skills/goutoujunshi/SKILL.md`

恋爱军师 skill：分析聊天记录、暧昧、邀约、约会、表白、确认关系等场景，按进攻时间表给出可直接发送的话术和推进方案。

**使用方式**

- Claude Code：在本仓库目录中启动 Claude Code，`.claude/skills/` 下的 skill 会自动加载；也可以输入 `/goutoujunshi` 直接调用。
- 其他项目：把 `.claude/skills/goutoujunshi/` 整个文件夹复制到目标项目的 `.claude/skills/` 下，或复制到 `~/.claude/skills/` 作为个人 skill。
- Claude 应用：把 `goutoujunshi` 文件夹打包成 zip，在应用设置的 Skills 页面上传。

**来源与许可**

改编自 [shengjidaguai-china/goutoujunshi](https://github.com/shengjidaguai-china/goutoujunshi)，原项目采用 MIT 许可，原许可证见 `.claude/skills/goutoujunshi/LICENSE`。
