# sushi-lucky
# 🍣 e sushi 店内即时互动抽奖系统 (In-Store Lucky Draw System)

这是一个专为美国 Mount Prospect 门店设计的“实体扭蛋互动 + 线上邮箱收集”的营销系统。结合了门店自助餐（All-You-Can-Eat）的商业模式，旨在通过极低的维护成本和最低的顾客操作门槛，为门店无感积累本地食客的有效电子邮箱（Email List）。

## 🌐 线上活动网址
* **活动访问链接：** [www.e-sushimountprospect.com/lucky]([http://www.e-sushimountprospect.com/lucky](暂时是https://professormin.github.io/sushi-lucky/lucky/))

---

## 🛠️ 店内运营闭环动线 (The 4-Step Customer Journey)

1. **线下投币（即时满足）：**
   顾客在结账时，满足消费条件后，店员递上一枚专属代币（Token）。顾客离店前可在机械扭蛋机处抽取一个精美且物美价廉的实体周边（如：高质感钥匙扣、精美开瓶器）。
2. **小卡引导（双重诱惑）：**
   扭蛋内含有一张设计直观的规则卡片，印有独立的 4 位幸运码和专属二维码，引导顾客扫码参与“大师手作价值$100店长特色双人餐”的阳光普照奖抽奖。
3. **极速扫码（最小努力）：**
   顾客使用手机相机扫码秒级拉开本网页。输入卡片上的 4 位幸运码，并借助手机自带的 Autofill 自动填充功能，点击一下即可秒速提交邮箱。
4. **邮件锁死（二次复购）：**
   提交成功后，系统自动发送一封欢迎邮件至顾客邮箱，内附一张“**下次到店可兑换的免费手作饮品或精美周边礼品一袋（Free Handcrafted Drink or Gift Bag）**”的核销券，完美锁定顾客的下一次到店消费，且不干扰自助餐原本的厨房出餐流水。

---

## 📂 仓库文件说明

* `/lucky/index.html` — 抽奖系统前端核心单页代码（采用黑底、鎏金、中国红的现代轻奢工业风视觉设计）。
* `logo.png` — 门店专属的锦鲤 Logo 图片（已进行视觉优化，确保整体精致透气，无任何多余寿司元素遮挡锦鲤眼睛）。

---

## ⚠️ 运营合规及避坑指南 (Compliance & Fine Print)

为完全规避美国各州复杂的博彩法律风险（Sweepstakes/Lottery Laws），本活动严格执行以下合规设计：
1. **控制奖项总额：** 线上大奖设定为店内自营的“大师手作 $100 店长特色双人餐 (Master-crafted $100 Chef's Special Dinner for Two)”，总价值低，属于极具吸引力且绝对合规的日常促销（Standard Promotional Contest）。
2. **免费参与（No Purchase Necessary）：** 网页底部已预留官方规则小字，符合美国各州基础的市场准入营销免责条款。
3. **数据管理建议：** 后续对接 Klaviyo 或 Mailchimp 时，需确保默认勾选发送“合规推广邮件”同意书（Marketing Opt-in）。
