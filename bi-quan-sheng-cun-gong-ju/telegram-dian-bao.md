# Telegram电报

> 电报是加密世界最常用的即时聊天软件，大陆需要科学上网方可使用。

## 只能用手机号码注册

* 国外：手机号不用实名制，相对安全。
* 国内：通过 Google Voice 注册电报，也可以绕开私聊限制。

## 注册使用

### **下载登录**

请进入 [Telegram Apps 的官方下载页面](https://telegram.org/apps)，选择对应的平台，下载，安装，注册。

自由开放的 Telegram 在各平台都有数十种客户端，各有哪些优缺点，又该如何选择呢？请查阅 [Telegram 客户端版本比较](https://tlgr.tw/)，但我不推荐使用第三方电报客户端，安全没有保证。

### **🐼 汉化界面**

既然已经出来混了（突破网络墙），首选使用英文版的 Telegram（突破语言墙），好像加起来也没几个单词。要是一点英文底子都没有：

1. [点此安装官方简体中文语言包](https://t.me/setlanguage/zh-hans-beta)
2. 选择 `CHANGE`（更改）
3. 即可把界面语言替换为简体中文

截至 2020 年 11 月 01 日，翻译已完成 95% 了，但不妨碍日常使用。

### **🔒 账号设置**

2020 年 7 月 26 日新增视频头像（[Profile Videos](https://telegram.org/blog/profile-videos-people-nearby-and-more#profile-videos)）功能。

### **👤 设置用户名**

你可以在 `Setting`（设置）里面填写一个 `Username`（用户名）。设置后，别人能够在不知道你的电话号码的情况下，通过用户名找到你。

* 用户名可以随时更改或删除（用户名为空）。
* 用户名不区分大小写（TingTalk = tingtalk），但 Telegram 会记住的大小写偏好。

**侵权**

* [如果一个骗子假装是你](https://telegram.org/faq#q-what-if-someone-is-pretending-to-be-me)，联系 [@notoscam](https://t.me/notoscam)。
* 针对品牌方，[用户名被占用怎么办？](https://telegram.org/faq#q-what-do-i-do-if-my-username-is-taken)把你在 Facebook、Twitter 或 Instagram 的用户名（两个平台以上）发给 [@username\_bot](https://t.me/username\_bot)。
* 如果你看到表情包（sticker sets）、频道（channels）或机器人（bots）侵犯了你的版权，请提交投诉到 [dmca@telegram.org](mailto:dmca@telegram.org)

**联系人**

* 添加和删除联系人（Contacts）都是单向操作，双方的通讯录都是独立的（你中有我，我中可能没有你），也没有通知。
* 点击左侧菜单栏 > `Contacts`（联系人）> `Find People Nearby`（寻找附近的人）。
* [转发消息时，长按联系人 / 群组 / 频道可多选。](https://telegram.org/blog#multi-sharing-from-other-apps)

### **💢 解除私聊限制**

自由的土壤吸引了比特币、社工库、NSFW 等灰色产业到电报野蛮生长，因为这些国产老鼠屎对电报的滥用，导致使用中国大陆的手机号码（+86）注册 Telegram 后，私聊 Ta 人时，可能会提示 `Sorry, you can only send messages to mutual contacts at the momet.`（对不起，你现在只能发送私信给双向联系人。），这表明此账号被判定为 Spam（垃圾信息）账号了。

如何解除私聊限制：在 Telegram 搜索 [@SpamBot](https://t.me/SpamBot)，点击 `START`，然后依次回复以下话术（仅供参考）：

1. But I can’t message non-contacts.
2. No, I’ll never do any of this.
3. I can’t chat with non-contacts.

大概半小时之后，即可解除禁言。

另外，若用户在 24 小时内访问超过 200 个群组或频道的链接（点击打开就算访问，不需要加入），就会被打入冷宫 24 小时。禁闭期间，无法通过链接访问新的群组或频道（点击链接一直转圈而无法访问）。

### **🙈 隐藏手机号码**

1. `Setting`（设置）
2. `Privacy and Security`（隐私和安全）
3. `Phone number`（手机号码）
4. `Who can see my phone number`（谁可以看到我的手机号码：`Nobody` 不允许任何人）

对隐私有要求，或者彻底解除 +86 开头的手机号码的私聊限制，可以把手机号码换绑到非中国区的手机号码，例如 Google Voice：

1. [注册 Google 账号](https://tingtalk.me/google-account/)。
2. 在 Google 或淘宝上搜索关键词 `Google Voice` 或 `GV` ，购买别人注册下来的号码。
3. 转移到自己的 Google 账号上。

以及：

* 添加陌生人到通讯录，记得取消勾选 `Share my phone number`。
* 开启 SIM（手机卡）密码（PIN 码），纵使别人捡到你的手机（卡），也不能启用 SIM，也就不能收到登录验证码。

### **✌️** [**两步验证**](https://telegram.org/blog/sessions-and-2-step-verification#two-step-verification)

1. `Setting`（设置）
2. `Privacy and Security`（隐私和安全）
3. `Two-step verification`（两步验证：添加密码提示和 ❗️ 安全邮箱 ❗️）

以后登录时，输入验证码后，还要输入密码。

* 安全密码：请勿使用纯数字密码，可使用开源的 [KeePass](https://keepass.info/) 生成高强度密码。
* 电子邮箱：Gmail 或者 Outlook，尽量不用国内的邮箱。

### **🎭** [**匿名转发**](https://telegram.org/blog/unsend-privacy-emoji#anonymous-forwarding)

1. `Setting`（设置）
2. `Privacy and Security`（隐私和安全）
3. `Forwarded messages: Nobody`（引用转发来源：不允许任何人）

启用此设置后，转发你的消息将无法指向（链接）回你的帐户，只会在 `From ***`（`来自***`）字段中显示一个无法点击的昵称（非用户名）。而昵称不是唯一的，所以通过这种方式，将没有证据证明某条消息是你发送的（无法溯源）。

### **💥 删除账户**

* **主动删除**：[不想使用此账号](https://telegram.org/faq#q-how-do-i-delete-my-account)，可 [永久删除账户（Delete Account）](https://my.telegram.org/auth?to=delete)
* **自动删除**：电报自带账户自毁机制（[Account Self-Destruction](https://telegram.org/blog/android-2-0#account-self-destruction)）
  * `Setting`（设置）
  * `Privacy and Security`（隐私和安全）
  * `Delete my account if away for 1 month/3 months/6 months/1 year` （删除我的帐户若离线时间达 1 个月 / 3 个月 / 6 个月 / 1 年）

**为什么要给账户设置自毁机制**

* Telegram 作为一个免费的非商业软件，没有任何收入来源，为了节约服务器的存储空间，Telegram 会自动删除长时间不上线的用户。再说了，Telegram 也不需要你的私人数据。
* 如果不慎丢失了 SIM（手机卡），此前未开启 SIM 卡的 PIN 码（强烈建议开启）和 Telegram 账户的两步验证，新的「主人」就能把你的 Telegram 账号占为己有。但是假如你设置了 1 个月不上线就销户，坏人在第 32 天捡到你的手机，不过此时你的 Telegram 账号已经不存在了。

### **💬 对话界面**

Telegram 有一个非常人性化的特性：**记忆浏览进度**，打开对话界面会自动跳转到未读消息 `Unread Messages`（The app restores your previous scroll position when you switch back to a chat）或者上次的未读位置。纵使重新安装 Telegram，没看完的消息，状态依旧是未读的。

### **✏️ 消息发送前**

打上句号之前，检查一遍内容是否有误，虽然 Telegram 支持无限期的（撤回）修改。

### **↩️ 引用消息**

**手机**

* 左滑 [Reply](https://telegram.org/tour/groups#replies) 消息。
* 长按，在弹出的界面中选择 Reply。

**电脑**

* 左键双击消息的空白处，例如时间附近。
* 右击消息，在弹出的菜单中选择 Reply。

点击引用的消息，就会向上滚动到原始消息（[If you tap on the quote, the app scrolls up to the original message](https://telegram.org/blog/replies-mentions-hashtags#replies)）。

假设从 `Unread Messages` 开始浏览动态（已发布 120 条 Post），遇到新消息引用了旧消息，例如庭说频道的第 100 条消息[https://t.me/tingtalk/100](https://t.me/tingtalk/100) 引用第 56 条消息[https://t.me/tingtalk/56，点击引用的消息，即可定位到第](https://t.me/tingtalk/56%EF%BC%8C%E7%82%B9%E5%87%BB%E5%BC%95%E7%94%A8%E7%9A%84%E6%B6%88%E6%81%AF%EF%BC%8C%E5%8D%B3%E5%8F%AF%E5%AE%9A%E4%BD%8D%E5%88%B0%E7%AC%AC) 56 条消息。如何回到第 100 条消息，点击右下角的 🔽 就会回到第 100 条消息，而不是回到最新的消息（shows an arrow button to go back to the previous location. This makes navigating conversations in groups easy even if you’ve been away for a while）。这是一个非常动人的细节，深深地被 Telegram 折服。

## **📝 文本格式化**

学会插入超文本链接，避免冗长的 URL 霸屏（简短的网址例外），是一种网络美德。

#### **Desktop（桌面端）**

1. 在编辑区输入文本。
2. 左键选择想要格式化的文本。
3. 右击 > `Formatting`（格式选项）。

| Formatting                                                                                     | Shortcut for Windows |
| ---------------------------------------------------------------------------------------------- | -------------------- |
| Bold（加粗 ）                                                                                      | Ctrl + B             |
| Italic（斜体）                                                                                     | Ctrl + I             |
| Underline（下划线）                                                                                 | Ctrl + U             |
| Strikethrough（删除线）                                                                             | Ctrl + Shift + X     |
| Monospace（等宽）                                                                                  | Ctrl + Shift + M     |
| [https://tingtalk.me/（超链接）](https://tingtalk.me/%EF%BC%88%E8%B6%85%E9%93%BE%E6%8E%A5%EF%BC%89) | Ctrl + K             |
| Plain text（纯文本）                                                                                | Ctrl + Shift + N     |

#### **Android（安卓）**

1. 在编辑区输入文本。
2. 长按选择想要格式化的文本。
3. 轻触界面右上角的三个点（顶栏右侧，大概在通知栏电量 🔋 的下方。非常刁钻的一个位置，我花了好几天才找到），即可看到文本格式化选项。

#### **iOS（iPhone & iPad）**

1. 在编辑区输入文本。
2. 长按选择想要格式化的文本，会弹出一些文字操作的选项。
3. 轻触 `BIU`（或许藏在 ▶️ 后面），即可看到文本格式化选项。

如果觉得以上格式化文本的方法太麻烦，打乱了输入节奏，可在任意聊天框输入 [@bold](https://telegram.me/bold)，接着使用 [Markdown](https://tingtalk.me/markdown/) 编辑消息（最多输入 256 字符），最后选择 `Custom markdown`。

## **#️⃣ 主题标签**

任何以 `#` 开头的词组，以标点符号或空格结尾的词组（[hashtags](https://telegram.org/blog/replies-mentions-hashtags#hashtags)）都可以被点击搜索，也相当于用标签给消息分组。

康德说过：`#自由 不是让你想做什么就做什么，自由是教你不想做什么，就可以不做什么。`

消息发出后，`#自由` 就会变成一个可点击搜索的状态。

## **🌅 发送原图**

先选择想要发送的图片（不止于 9 张）：

* Android：点击弹出窗口右上角的三个点，`Send without compression`
* iOS、macOS 和 Windows：`Send as a file`

请注意：

* 原图不会压缩图片，但是会暴露文件名。
* Telegram 会记住你的操作习惯，下次发送图片时不必再次勾选原图选项。

## **📡 消息发送时**

手机上长按（电脑上右击）消息发送键：

* `Send without sound`（静音发送消息）：纵使对方在睡觉，你的 urgent idea 也不会搅人春梦，简直就是为健忘的人而设计。
* `Scheduled Message`（[定时发送](https://telegram.org/blog/scheduled-reminders-themes)）
  * 发送日程消息时，对方并不知道你使用了定时发送。
  * 在 [Saved Messages](https://telegram.org/blog/albums-saved-messages#saved-messages)（我的收藏）也可以发送定时消息作为提醒（Set a reminder）。
  * `Send when * comes online`（[当对方上线时发送](https://telegram.org/blog#send-when-online)）：这样就可以排在对方聊天列表的前面（Put you right at the top of their chat list.）。

接收者可屏蔽联系人 / 群组 / 频道的消息通知（[Mute Notifications](https://telegram.org/blog/shared-files#mute-notifications)）：

* 1 个小时
* 4 个小时
* 18 个小时
* 3 天
* 永久静音

## **🔙 消息发送后**

点击消息，选择 `Pin`，即可在频道、群组或私聊界面中置顶多个消息（[Multiple Pinned Messages](https://telegram.org/blog/pinned-messages-locations-playlists#multiple-pinned-messages)）。

## **✔️ 消息状态**

消息的读取状态（回执）分为两种

* One check（✔️）：发送成功。在微信，有些消息没发送出去，只对你可见，也不会有发送失败的感叹号 ❗。这是对用户赤裸裸的欺骗 。
* Two checks（✔️✔️）：消息已阅。瞥见状态栏弹出来的消息，不会产生已读标记。因此，一直显示单勾，不代表对方没看到信息。

## **✏️ 消息更正**

在 Telegram，说出去的话不会像泼出去的水收不回来，任何时候，你都可以重新编辑（[Edit your messages after posting](https://telegram.org/blog/edit)），包括文字、图片和视频，所以：

* 文字出现 typos，不用删除，多久之前发的消息都能随时更正（Edit）。
* 图片忘记打马赛克，但因为有图片说明（配文），懒得撤回重输，可以当场抹除敏感信息，当场换图片（[Replace Media](https://telegram.org/blog/unread-replace-2x#replace-media-and-add-captions)）。
* 视频发错了，善后方式与图片同理。
* 图片换视频，视频换图片，Why not?

如何替换图片或视频？长按或右击消息，选择 `Edit`：

* 通用法：点击笔头图标 ✏️，弹出资源窗口，选择正确的图片和视频即可替换。
* 桌面端：复制正确的图片和视频，回到 Telegram，粘贴即可替换。

## **👇 长按消息**

* 消息可以无限期撤回（[Delete Messages](https://telegram.org/faq#q-can-i-delete-my-messages)）：删除信息时，勾选 `Also delete for***`，聊天记录就可以双向删除。
* 选择部分消息（[Select Parts of Messages](https://telegram.org/blog/verifiable-apps-and-more#select-parts-of-messages)）：长按 2 次消息，可选择部分文字，而不是复制全文（Copy Selected Text）。

## **🗣️ 语音消息**

* 支持 2 倍速播放（[2X playback](https://telegram.org/blog/unread-replace-2x#double-time-playback-for-voice-and-video-messages)）。
* 可调节语音消息的进度（不必从头开始播放）。
* [记忆播放位置](https://telegram.org/blog/verifiable-apps-and-more#podcast-and-audiobook-support)：超过 20 分钟的音频文件，Telegram 会帮你记住最后的播放位置，以便中断后再次收听（Telegram apps will remember your last position when resuming playback of audio files longer than 20 minutes.）。

此外，在 Telegram 上进行语音通话（打电话），需要在翻墙服务端/客户端开启 UDP 转发。

## **🙈 生动表情**

**Emoji（绘文字）**

按关键字搜索表情（[Search emoji by keyword](https://telegram.org/blog/unsend-privacy-emoji#emoji-search-and-gifs)）：在消息框输入关键词，就会弹出相关的 Emoji。

* [能触发 Emoji 的英文关键词合集](https://translations.telegram.org/en/emoji)
* [能触发 Emoji 的简体中文关键词合集](https://translations.telegram.org/zh-hans/emoji)

如何在句中（mid-message）快捷添加 Emoji？语法是 `:（英文半角冒号）` + `关键词`。例如输入 I am `:happy`，就会弹出开心相关的 Emoji，这样就不用从 Emoji 面板挑选 Emoji 了。

**Stickers（表情包）**

在聊天窗口输入 [@sticker](https://t.me/sticker) + Emoji，可以检索**所有**与 Emoji 相关表情包，例如 `@sticker 👍`。

部分 Emoji 支持动态播放（Animated Emoji）：在任意聊天窗口发送 1 个 [非礼勿视猿](https://zh.wikipedia.org/zh/%E4%B8%89%E7%8C%BF) 🙈（[See-No-Evil Monkey](https://emojipedia.org/see-no-evil-monkey/)），再动 Ta 试试，可爱吧！查看更多被 Telegram 赋予「生命」的动态 Emoji，请参阅 [Telegram Animated Emoji List](https://tingtalk.me/telegram-animated-emoji/)。

📤 **如何导出电报上的表情包**

1. 选择一个 Sticker to GIF Converter，例如 [@tgstogifbot](https://t.me/tgstogifbot) 或 [@Sticker2GIFBot](https://t.me/Sticker2GIFBot)（后一个 Bot 可下载整套表情包）
2. 发送 Stickers，Bots 就会把 Telegram 上 tgs 格式的表情包转换为 gif 格式

🗜️ **在限制多多的微信 App 上，小于 1 MB 的 GIF 图片才会自动播放。如何压缩：**

1. 打开 [图贴式](https://www.tutieshi.com/compress/)（网站），选择 GIF 压缩
2. 宽度设置为 `240`，压缩质量 70（默认）
3. 选择或拖拽一个或多个 GIF 到压缩窗口，`开始压缩`
4. 压缩完成后，（推荐使用 [IDM](https://tingtalk.me/windows/#%E4%B8%8B%E8%BD%BD%E5%B7%A5%E5%85%B7)）`打包下载`

此时某些表情包可能大于 1 MB，需要再压一次：

* 方法一：修改 [图贴式](https://www.tutieshi.com/compress/) 的压缩质量等级（压得太狠会失真）
* 方法二：使用 [docsmall](https://docsmall.com/gif-compress)（网站）或者 [图压](https://tuya.xinxiao.tech/)（软件）二次压缩

为什么不用 Photoshop 压缩 GIF？因为会产生毛糙的白边。

两外，推荐一个可以批量修改图片尺寸的网站：[iLoveIMG](https://www.iloveimg.com/zh-cn/resize-image)

## **📊** [**投票功能**](https://telegram.org/blog/polls-2-0-vmq)

**发起人**

* 支持：匿名投票（Anonymous Voting）、多选（Multiple Answers）、答题模式（ [Quiz Mode](https://telegram.org/blog#quiz-mode)）。
* 不支持：修改发出的 Poll。

**投票者 / 答题者**

* 不满意长按或右击投票（Poll）可以撤回投票（Retract vote）。

## **🖥️ 电脑版技巧**

* **快速多选**：在对话界面的空白位置，按着鼠标左键不放，即可多选信息，然后选择转发或者删除。
* **链接直达**：按住 `Ctrl` 再点击 URL，直接打开链接，不必弹窗确认（Open this link? CANCEL / OPEN）。

## **📖 通用技巧**

## **🌐 互联开放**

公开（Public）的频道或群组，是可以被搜索引擎索引（The contents of public channels can be seen on the Web without a Telegram account and are indexed by search engines.），并且不注册 Telegram 账号也看到公开频道或群组中的内容，方法就是在 Permanent link（永久链接）中加一个 `s`，例如 [t.me/s/tingtalk](https://t.me/s/tingtalk)，即可在浏览器中查阅庭说频道。

一个用户最多可创建 10 个公开用户名（public usernames），包括公开的频道和群组。

## **🔍 搜索秘技**

去哪里找钟意的频道（Channel），群组（Group）和机器人（Bot）呢？

☝️ 在 Telegram 内直接搜索关键词，但中文搜索识别较差。例如，「庭说」的频道是[https://t.me/tingtalk](https://t.me/tingtalk)

* 搜索英文 `@tingtalk`（`t.me/` 后面的字符就是 ID），可以准确识别
* 搜索中文 `庭说`，可能无法识别

✌️ 配合一些 [Google 搜索技巧](https://tingtalk.me/search-tips/)，在 [Google](https://www.google.com/search?q=site:tingtalk.me) 上搜索：

* 关键词 + site:t.me，例如：`海贼王 OR one piece site:t.me`
* 关键词 + telegram 及其俗称，例如：`Rick and Morty telegram OR 电报 OR TG`

这也再次证明了 Telegram 的内容是可以被 Google 等搜索引擎抓取的。反观国内的互联网江湖，各自割据，搞得网民苦不堪言。就拿微信来说，你不能在 Google 或者百度搜到公众号文章，这也是庭说另开一个独立博客的原因。

👌 Telegram 频道搜索引擎（非官方）：[sssoou.com](http://www.sssoou.com/)。帮助大家搜 Telegram 频道里的资源，不用因为 Telegram 对中文支持不好，而找不到想要的资源。

## **☁️ 多端同步**

Telegram 可以在多个设备上**同时**使用。以下是我的设备列表：

* 2 台 Windows 电脑（开机自启）
* 1 部 Android 手机
* 1 部 iPhone 手机
* 1 个 [网页端](https://web.telegram.org/)
* ……

并且具备以下优势：

* 登录过的设备，下次登录时，不必再次扫描二维码或者输入密码。
* 云草稿（[Cloud drafts](https://telegram.org/blog/drafts)）：除了消息可在各个平台同步之外，连未完成编辑的消息（草稿）都可以跨设备同步。Now you can start typing on your phone, then continue on your computer – right where you left off.
* 与 WhatsApp 不同的是，手机下线 Telegram 后，其他设备的 Telegram 并不会退出。

允许传送最大 2000 MiB 的文件，简直就是绝佳的「文件传输助手」：

* 把 [Saved Messages](https://telegram.org/blog/albums-saved-messages#saved-messages)（收藏夹）当作是 [GTD](https://tingtalk.me/gtd) 中 Inbox。并且每条保存的消息都有一个 ▶️ 按钮，可以将你带到最初发布消息的位置。
* 建立多个私人频道，分类存放你的信息和资讯。你甚至可以在 Telegram 上传本地音乐或者录音到自己的频道，建立自己的云端音乐播放库和播客（Podcast）。

## **📁 对话列表**

在对话列表长按某个对话：

* **删除对话（Delete chat）**：勾选 `Also delete for ***`，即可同时删除双方所有的聊天记录。
  * 不用经过对方同意。如果你的朋友遭遇不测，你可以及时清除消息来保护自己和对方。
  * 反之，需要保留证据时，请及时截图或（在桌面端）导出聊天记录。
* **归档对话（**[**Archive chat**](https://telegram.org/blog/folders#archived-chats)**）**：把不常用的群组和频道放到归档文件夹中，精简对话列表，[Everything in its place](https://telegram.org/blog/archive-and-new-design#everything-in-its-place)。
  * 在移动端的对话列表里，从顶部往下拉，即可看到「已归档对话」，[长按可标记全部归档对话为已读状态](https://telegram.org/blog#mark-archive-as-read)。
  * 当未设置静音的存档对话收到通知时，它将从归档列表中返回到聊天列表中。
*

## **🔴 关闭通知**

1. `Settings`（设置）> `Notifications and Sounds`（通知和声音）。
2. `Badge Counter`（未读消息数量显示）：取消 `Include Muted Chats`（包含已关闭通知的对话）

如此设置，只有未静音的对话（私聊 / 群组 / 频道）来消息了，才会收到「小红点」。

## **🧹 清除缓存**

此举只是暂时释放存储空间，因为媒体文件都会保留在 Telegram 云端，若需要可以再次下载，例如翻看历史消息的时候。

1. `Settings`（设置）
2. `Data and Storage`（数据和存储）
3. `Storage Usage`（存储使用情况）
4. `Clear Telegram Cache`（清理缓存）

## **🗃️** [**导出数据**](https://telegram.org/blog/export-and-more)

⚠️此功能需在 [Telegram 电脑版](https://desktop.telegram.org/) 上运行。

聊天历史会被存储在 Telegram 云端，但是也可以导出部分（或全部）聊天记录到电脑上离线回味，而且排版还是原来的样子。

1. 打开 Telegram Desktop
2. 选择某个对话
3. 点击对话界面右上角的设置（三个点 …）
4. 导出聊天记录（Export chat history）

你也可以导出 Telegram 的所有数据。对，是所有，不仅仅是聊天记录，还有账号信息：

1. 打开 Telegram Desktop
2. 依次点击 `Settings` > `Advanced` > `Export Telegram data`
3. 选择要导出的数据类型

## **🤐** [**私密聊天**](https://telegram.org/faq#secret-chats)

**Cloud Chats**（默认聊天模式）

`客户端` –`服务器` / `服务器` – `客户端`

信息存储在 Telegram Cloud 中进行加密，这使云消息既安全又可以立即从任何设备访问，即使丢失了设备。所以你不需要将所有的信息历史记录存储在手机上，当你需要的时候，你可以随时在 Telegram 下载（缓存）旧的信息和媒体，这为你节省了大量的磁盘空间和内存。

**Secret Chats**（不支持在 Windows 和 Web 上发起）

`客户端` – `客户端`

聊天记录不能云备份，因为私人数据没有经过 Telegram 的同步服务器，所以没有任何人可以破解，包含 Telegram 团队本身。

> 关联阅读：为什么电报的端到端加密不是默认的？

* 只能通过原始设备访问历史消息，如果退出并再次登录，将失去所有的秘密聊天记录。
* 可设置阅后即焚（self-destruct）计时器，自动销毁消息或媒体文件（只适用于计时器设置后发送的消息，对早期的信息没有影响）。
* 不能转发消息。
* 不能编辑已发送的消息。
* Android 设备不能截屏；iOS 设备可以截屏 ，但对方截屏时你会收到通知。不过，只建议与你信任的人分享敏感信息。 毕竟，对方可以用另外一台设备给屏幕拍照。
* 删除发送方的消息，接收方那边也会强制删除。



