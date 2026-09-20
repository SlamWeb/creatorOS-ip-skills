# IP Skills 首版

- 范围：PageSeries/PageSpec → 每页最终生图Prompt。上游内容Skill负责教学，下游IP Skill负责角色、视觉语言与知识关系的视觉表达。本轮不修改CreatorOS绑定逻辑、不安装全局Skill、不生图。
- 新增xiaobai/SKILL.md和用户提供的合并角色图assets/character.png；同图包含标准形象与动作，不另建expressions.png，不创建尚无设定的小黑。
- 保留用户的9:16、正文知识图优先、三类页面、干净角落及十项Prompt输出要求；补充相对路径、实际附参考图与上游文案交接规则。
- 验收：Skill格式、引用路径、原图与副本哈希一致、图片可解码；检查Git diff后commit/push。格式验证不等于生图一致性验证。
- 结果：quick_validate.py通过；参考图副本已实际打开检查，源/目标SHA256均为2C519B331AF3CA6BB268AEB27CD9C2C5B5B888680D585FFC21A773477B3C6121，原样未编辑。没有生图或跨页效果试跑。
