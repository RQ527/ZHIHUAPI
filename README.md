# 声明

以下所有 API 均由 知乎（Zhihu.Inc） 提供，本人采取非正常手段获取。获取与共享之行为或有侵犯知乎权益的嫌疑。若被告知需停止共享与使用，本人会及时删除此页面与整个项目。
请您暸解相关情况，并遵守知乎协议。

# API 说明

- 知乎日报的消息以 JSON 格式输出
- 网址中 `api` 后数字代表 API 版本，过高或过低均会得到错误信息
- 以下所有 API 使用的 HTTP Method 均为 `GET`
- 所有的链接均使用 `HTTPS`

### 最新消息

- URL: `https://news-at.zhihu.com/api/4/news/latest`

- 响应实例：

  ```json
    {
      "date": "20230425",
      "stories": [
          {
              "image_hue": "0xb39168",
              "title": "昆虫为什么要进化出蛹这种不利于生存的形态？",
              "url": "https://daily.zhihu.com/story/9760754",
              "hint": "法小喵 · 4 分钟阅读",
              "ga_prefix": "042507",
              "images": [
                  "https://picx.zhimg.com/v2-4e93be3339e9994d42de8855b947ea2b.jpg?source=8673f162"
              ],
              "type": 0,
              "id": 9760754
          },
          {
              "image_hue": "0x6b8099",
              "title": "如果汉字失传了，释读它的难度有多大？",
              "url": "https://daily.zhihu.com/story/9760759",
              "hint": "黄鼠狼精Morrica · 1 分钟阅读",
              "ga_prefix": "042507",
              "images": [
                  "https://pica.zhimg.com/v2-099f912c8550c34c34218bab4b2fae61.jpg?source=8673f162"
              ],
              "type": 0,
              "id": 9760759
          },
          {
              "image_hue": "0x4d5b22",
              "title": "博物馆中令你最震惊的一件文物是什么？",
              "url": "https://daily.zhihu.com/story/9760767",
              "hint": "王盛 · 1 分钟阅读",
              "ga_prefix": "042507",
              "images": [
                  "https://pica.zhimg.com/v2-48a37db57d2ee7cf5ece74a380602471.jpg?source=8673f162"
              ],
              "type": 0,
              "id": 9760767
          },
          {
              "image_hue": "0xb3a57d",
              "title": "前电脑时代的建筑图纸是什么样的？是怎么画成的？",
              "url": "https://daily.zhihu.com/story/9760775",
              "hint": "知乎用户 · 3 分钟阅读",
              "ga_prefix": "042507",
              "images": [
                  "https://picx.zhimg.com/v2-80c3d23a94bb839ecf703ea42eb6f464.jpg?source=8673f162"
              ],
              "type": 0,
              "id": 9760775
          },
          {
              "image_hue": "0x64818f",
              "title": "在你所处的领域中，有哪些想象已经变成了现实？",
              "url": "https://daily.zhihu.com/story/9760778",
              "hint": "极萨学院冷哲 · 5 分钟阅读",
              "ga_prefix": "042507",
              "images": [
                  "https://pic1.zhimg.com/v2-17dc46b57e9520a85e8da8a36614ca46.jpg?source=8673f162"
              ],
              "type": 0,
              "id": 9760778
          },
          {
              "image_hue": "0xb3aa7d",
              "title": "瞎扯 · 如何正确地吐槽",
              "url": "https://daily.zhihu.com/story/9760785",
              "hint": "VOL.3090",
              "ga_prefix": "042506",
              "images": [
                  "https://pic1.zhimg.com/v2-33e239053063d36376a5bc603e005d38.jpg?source=8673f162"
              ],
              "type": 0,
              "id": 9760785
          }
      ],
      "top_stories": [
          {
              "image_hue": "0x935755",
              "hint": "作者 / 今夕何夕",
              "url": "https://daily.zhihu.com/story/9760718",
              "image": "https://picx.zhimg.com/v2-5e21ac17e9c4266261e28282433de0b2.jpg?source=8673f162",
              "title": "请问在中国历史上，洛阳和长安各自作为首都的利弊有哪些？",
              "ga_prefix": "042107",
              "type": 0,
              "id": 9760718
          },
          {
              "image_hue": "0xb39168",
              "hint": "作者 / 法小喵",
              "url": "https://daily.zhihu.com/story/9760754",
              "image": "https://picx.zhimg.com/v2-03914594de86953ffe60b7017fb6e650.jpg?source=8673f162",
              "title": "昆虫为什么要进化出蛹这种不利于生存的形态？",
              "ga_prefix": "042507",
              "type": 0,
              "id": 9760754
          },
          {
              "image_hue": "0x2e3022",
              "hint": "作者 / 思思安",
              "url": "https://daily.zhihu.com/story/9759918",
              "image": "https://picx.zhimg.com/v2-bd0852aec02e17f8caa2facf9194d201.jpg?source=8673f162",
              "title": "《甄嬛传》里的淳儿到底是真的单纯还是有心计藏得深？",
              "ga_prefix": "042407",
              "type": 0,
              "id": 9759918
          },
          {
              "image_hue": "0x22291d",
              "hint": "作者 / 十四花生",
              "url": "https://daily.zhihu.com/story/9760727",
              "image": "https://picx.zhimg.com/v2-cf32f0c2bfe8ed0c98ecc24b46dfd797.jpg?source=8673f162",
              "title": "小事 · 你经历过的最有趣的事是什么呀？",
              "ga_prefix": "042307",
              "type": 0,
              "id": 9760727
          },
          {
              "image_hue": "0xb39a7d",
              "hint": "作者 / 高远",
              "url": "https://daily.zhihu.com/story/9760715",
              "image": "https://pica.zhimg.com/v2-a8896eb09b82cff7daf05d44fdbd0b04.jpg?source=8673f162",
              "title": "小事 · 你遇过的最温暖的瞬间是什么？",
              "ga_prefix": "042207",
              "type": 0,
              "id": 9760715
          }
      ]
  }
  ```

- 分析：

  - `date` : 日期

  - stories: 当日新闻

    - `image_hue`:图像色彩，用不到可以不管

    - `title` : 新闻标题
    - `url`:文章内容的url，可以用webview直接加载内容
    - `hint`:作者和预计的阅读时间，用在标题下面示意
    - `images` : 图像地址（官方 API 使用数组形式。目前暂未有使用多张图片的情形出现，曾见无 `images` 属性的情况，请在使用中注意 ）
    - `ga_prefix` : 供 Google Analytics 使用，用不到不管
    - `type` : 作用未知
    - `id` : 文章的id

  - `top_stories` : 界面顶部的Banner图（请注意区分此处的 `image` 属性与 `stories` 中的 `images` 属性，其他参数无异。）

### 过往消息

- URL: `https://news-at.zhihu.com/api/4/news/before/20230425`

- 若果需要查询 4月24号的消息，`before` 后的数字应为 20230425

- 知乎日报的生日为 2013 年 5 月 19 日，若 `before` 后数字小于 `20130520` ，只会接收到空消息

- 输入的今日之后的日期仍然获得今日内容，但是格式不同于最新消息的 JSON 格式

- 响应实例：

  ```json
   {
      "date": "20230424",
      "stories": [
          {
              "image_hue": "0x2e3022",
              "title": "《甄嬛传》里的淳儿到底是真的单纯还是有心计藏得深？",
              "url": "https://daily.zhihu.com/story/9759918",
              "hint": "思思安 · 8 分钟阅读",
              "ga_prefix": "042407",
              "images": [
                  "https://picx.zhimg.com/v2-41a7ccd9640b5bf56cf0a5077e4d0baa.jpg?source=8673f162"
              ],
              "type": 0,
              "id": 9759918
          },
          {
              "image_hue": "0xb39979",
              "title": "怎么看待国内很多时候将越南语和泰语归入汉藏语系？",
              "url": "https://daily.zhihu.com/story/9759864",
              "hint": "知乎用户 · 2 分钟阅读",
              "ga_prefix": "042407",
              "images": [
                  "https://pica.zhimg.com/v2-74e308eb00598a42c979ac033aaec602.jpg?source=8673f162"
              ],
              "type": 0,
              "id": 9759864
          },
          {
              "image_hue": "0xb38f7d",
              "title": "古代诗词是如何被记录并传播开来的？",
              "url": "https://daily.zhihu.com/story/9759872",
              "hint": "豆子 · 2 分钟阅读",
              "ga_prefix": "042407",
              "images": [
                  "https://picx.zhimg.com/v2-3c73d8a7d3ca99d5afc715be6ca5f437.jpg?source=8673f162"
              ],
              "type": 0,
              "id": 9759872
          },
          {
              "image_hue": "0x636363",
              "title": "历史上中国死了那么多人都土葬，为什么没感觉有那么多坟墓？",
              "url": "https://daily.zhihu.com/story/9759880",
              "hint": "郁练级 · 3 分钟阅读",
              "ga_prefix": "042407",
              "images": [
                  "https://picx.zhimg.com/v2-2185b708171b5178d1597bffd00b142c.jpg?source=8673f162"
              ],
              "type": 0,
              "id": 9759880
          },
          {
              "image_hue": "0x14130c",
              "title": "如果从远古开始温度一直适宜，人类有可能进化成不穿衣服的生物群体吗？",
              "url": "https://daily.zhihu.com/story/9760886",
              "hint": "赵泠 · 1 分钟阅读",
              "ga_prefix": "042407",
              "images": [
                  "https://pic1.zhimg.com/v2-75d18581cd391e6f32635e5ae8b63d8c.jpg?source=8673f162"
              ],
              "type": 0,
              "id": 9760886
          },
          {
              "image_hue": "0x293625",
              "title": "瞎扯 · 如何正确地吐槽",
              "url": "https://daily.zhihu.com/story/9759884",
              "hint": "VOL.3089",
              "ga_prefix": "042406",
              "images": [
                  "https://pic1.zhimg.com/v2-3f42af35cf6c9335d7eba6b50d2efe1c.jpg?source=8673f162"
              ],
              "type": 0,
              "id": 9759884
          }
      ]
  }
  ```

- 格式与前同，恕不再赘述

###  新闻额外信息

- URL: `https://news-at.zhihu.com/api/4/story-extra/9759884`

- 9759884为对应文章的id，在上述接口中获取，获取对应新闻的额外信息，如评论数量，所获的『赞』的数量。

- 响应实例：

  ```json
  {
      "long_comments": 0,
      "popularity": 64,
      "short_comments": 13,
      "comments": 13
  }
  ```

- 分析：

  - `long_comments` : 长评论总数
  - `popularity` : 点赞总数
  - `short_comments` : 短评论总数
  - `comments` : 评论总数

### 新闻对应长评论查看

- URL: `https://news-at.zhihu.com/api/4/story/8997528/long-comments`

- 8997528为文章id，在 `https://news-at.zhihu.com/api/4/story/8997528/long-comments` 中将 8997528 替换为对应的 `id`，得到长评论 JSON 格式的内容

- 响应实例：

  ```json
  {
      "comments": [
          {
              "author": "andy小陆",
              "content": "《小仙有毒》里，温家的入室弟子考题有一年是“硕鼠”。温家大伯温吞海当年应试的毒方是采尽天下至甜至香之物，密炼熬成一碗甜羹，无毒且馥郁甘甜。但人一旦饮下此羹，尝到了那绝世甜香，之后哪怕是喝蜂蜜也会觉得腥臭苦涩无比，止不住的呕吐，从此世上可食之物就只剩一个味道：苦，最终竟把人活活饿死！正应了考题“硕鼠”。。",
              "avatar": "https://picx.zhimg.com/4953f864a_l.jpg?source=8673f162",
              "time": 1479737963,
              "id": 27279755,
              "likes": 9
          },
          {
              "author": "级你个长",
              "content": "孟婆汤从设定上看是洗去人的，哦不，鬼的晶体记忆，保留程序记忆（不然喝完碗都拿不住路都不会走）下意识记忆等非晶体记忆。假设真的保留了下意识记忆，那么给一只喝过孟婆汤5分钟的鬼一碗孟婆汤，和一碗好喝的汤（具体什么汤根据被试的饮食文化来定），让他立刻做出选择哪碗汤好喝。在30个不同被试身上做了以上测验后，再找另外30个被试，让他在水和孟婆汤之间做出选择。最后再找另外30个被试，让他在孟婆汤和难喝的汤之间做选择。考虑到被试作为鬼已经没有任何物质需要，其实被试想找多少都可以。\n现在问题是：\n1.外国的鬼会不会来，来多少，多的话要对应他们做准备。\n2.鬼差是否愿意我们这样做，毕竟冥府鬼流量大，我们在那里摆个摊拦住鬼会降低鬼流速度。\n3.最关键的问题，怎么下去，去了怎么回来。",
              "avatar": "https://pic1.zhimg.com/01d9e29ae2ff6c4f973a5a7c7b93a73b_l.jpg?source=8673f162",
              "time": 1479730471,
              "id": 27278908,
              "likes": 12
          },
          {
              "author": "还是个宝宝",
              "content": "他娘的    敢情我现在是个愚蠢的凡人都是因为不小心喝了孟婆的汤！死老太婆泡过的汤打死我也不想再喝了！\n喝一次变成傻子！六亲不认！\n喝两次沦为智障！玩物丧志！\n喝三次彻底反动！万劫不复！\n这汤堪比毒药！这汤胜似砒霜！这汤简直万恶之源！",
              "avatar": "https://picx.zhimg.com/96f7af72906a361333d259abc818be7b_l.jpg?source=8673f162",
              "time": 1479709874,
              "id": 27276499,
              "likes": 3
          },
          {
              "author": "-是刘宗铭吧",
              "content": "“路过的人儿呐，渴了累了就喝口汤吧”\n“你是孟婆对吗？”\n“是的，怎么？不愿意忘记那些苦与累吗？”\n“只是不愿意忘记那些爱的人与事”\n“你若真爱着那些人与事，又怎么会忘记呢？”\n“可大家都说喝了您的汤，就会忘记所有事情了”\n“那他们又是如何记得会忘记的呢？”\n“……”\n“喝一口吧”\n“咕咚咕咚……”\n“味道如何？喜欢吗”\n“我以为是苦的呢”\n“还记得吗？”\n“忘了”\n“忘了就好”\n\n“我是不是在哪里见过这个女生？”\n“你脸怎么红了？”\n“哈 我也不知道，你们认识那个女孩子吗”",
              "avatar": "https://pic1.zhimg.com/ddb29358f18c8e2ec806d63bcb98d7a4_l.jpg?source=8673f162",
              "time": 1479708864,
              "id": 27276366,
              "likes": 15
          },
          {
              "author": "巨型黑娃儿",
              "content": "也不算逻辑问题。其实小时候刚刚听说这个玩意的时候我也奇怪了很久，既然喝了就什么都忘了，那怎么还会有人知道这玩意呢？其实各种神话传说都这样，凡人谁真的见过呢？怎么就能知道那些故事？非要有个解释的话，只能说总有些神啊仙啊妖啊怪的把这些东西传出来。所以即使你喝了孟婆汤什么都忘了，当你来到这个世上，你还是会知道这个玩意，因此说“忘了”的意思是遵照孟婆汤的设定，每个鬼都必须喝，所以你我众生是一定喝了的，但是怎么喝的味道怎样是肯定不会记得了。开脑洞总得有个背设，没背设也就玩不了脑洞游戏了。",
              "avatar": "https://picx.zhimg.com/4131a3385c748c9e2d02ab80e29a0c52_l.jpg?source=8673f162",
              "time": 1479706360,
              "reply_to": {
                  "content": "第二个机灵抖的还是有逻辑问题，不该说忘了，应该说没喝过啊我也不知道",
                  "status": 0,
                  "id": 27275308,
                  "author": "2233155495"
              },
              "id": 27276057,
              "likes": 3
          },
          {
              "author": "坑灰易冷",
              "content": "谁说孟婆一定是给你做喝的“汤”的——孟婆怎么就不能是开浴池的呢？话说人到了孟婆这里都得扒光衣服泡个热水澡，代表涤荡尘埃、抛却尘世间的一切牵挂。然后洗美了烫舒服了一不留神就喝了口洗澡水——顿时大脑一片空白，迷迷糊糊把所有衣服连带全部盘缠（川资）都忘在了孟婆那里，所以日久天长那个地方就叫“忘川”……编不下去了。",
              "avatar": "https://picx.zhimg.com/01d9e29ae2ff6c4f973a5a7c7b93a73b_l.jpg?source=8673f162",
              "time": 1479704382,
              "id": 27275789,
              "likes": 26
          }
      ]
  }
  ```

- 分析：

  - `comments`: 长评论列表，形式为数组（请注意，其长度可能为 0）
    - `author` : 评论作者
    - `content` : 评论的内容
    - `avatar` : 用户头像图片的地址
    - `time` : 评论时间
    - `id` : 评论的id
    - `likes` : 评论所获『赞』的数量
    - reply_to: 所回复的消息
      - `content` : 原消息的内容
      - `status` : 消息状态，0为正常，非0为已被删除
      - `id` : 被回复者的唯一标识符
      - `author` : 被回复者
      - `err_msg`: 错误消息，仅当`status`非0时出现

### 新闻对应短评论查看

- URL: `https://news-at.zhihu.com/api/4/story/4232852/short-comments`

- 4232852为新闻id，在 `https://news-at.zhihu.com/api/4/story/4232852/short-comments` 中将 4232852替换为对应的 `id`，得到短评论 JSON 格式的内容

- 响应实例：

  ```json
  {
      "comments": [
          {
              "author": "每一天都在混水摸鱼",
              "content": "钱会让它变的好吃",
              "avatar": "https://picx.zhimg.com/0ecf2216c2612b04592126adc16affa2_l.jpg?source=8673f162",
              "time": 1413987020,
              "id": 556780,
              "likes": 0
          },
          {
              "author": "TuoTuo的亲爹",
              "content": "第一次也是吃了牛肉…吃完以后，人家很客气的问我还需要么…我也很客气地再来了一盒鸡肉的。。。。可惜后来专门坐那个航班，居然换成茄子饭了?",
              "avatar": "https://picx.zhimg.com/8949bb2f30ed5789857accd489644234_l.jpg?source=8673f162",
              "time": 1413859600,
              "reply_to": {
                  "content": "我每次都不假思索选了牛肉，然后就深深的后悔没有试过一次鸡肉，到下一次又情不自禁选了牛肉，周而复始循环往复-_-#",
                  "status": 0,
                  "id": 551969,
                  "author": "怒放的腋毛"
              },
              "id": 552762,
              "likes": 0
          },
          {
              "author": "怒放的腋毛",
              "content": "我每次都不假思索选了牛肉，然后就深深的后悔没有试过一次鸡肉，到下一次又情不自禁选了牛肉，周而复始循环往复-_-#",
              "avatar": "https://picx.zhimg.com/f91c41e78_l.jpg?source=8673f162",
              "time": 1413820952,
              "reply_to": {
                  "content": "其实吃南航的牛肉饭和鸡肉饭还是蛮好吃的，屌丝表示只坐经济舱",
                  "status": 0,
                  "id": 548570,
                  "author": "TuoTuo的亲爹"
              },
              "id": 551969,
              "likes": 0
          },
          {
              "author": "乎乎胖胖的",
              "content": "吃过最差的是埃塞航空，11个小时的飞行时间，又不能不吃，就把里面一颗颗的青豆挑来吃了。其次是香港航空飞台北的航班，蛋炒饭，饭那个硬啊，一颗一颗挑鸡蛋末吃?",
              "avatar": "https://picx.zhimg.com/9a82cc6bed3ee0fac29216139a4d06a1_l.jpg?source=8673f162",
              "time": 1413803690,
              "id": 551237,
              "likes": 0
          },
          {
              "author": "大年三十儿",
              "content": "最难吃的我也吃两份。。土豪我们做【哔~~】友吧！",
              "avatar": "https://picx.zhimg.com/5be0e0451d50ed55ec33b9b42b6eb56d_l.jpg?source=8673f162",
              "time": 1413790772,
              "id": 550793,
              "likes": 0
          },
          {
              "author": "三查落落落",
              "content": "诶其实我觉得全部的飞机餐都挺好吃的诶(◐‿◑)﻿是我口味比较奇妙吗",
              "avatar": "https://pica.zhimg.com/a26e65e1267b1b193842e567b77e917f_l.jpg?source=8673f162",
              "time": 1413788056,
              "reply_to": {
                  "content": "居然还有人觉得达美的飞机餐好吃。。。 觉得达美是飞美国吃过最烂的之一。。。 跟大韩 全日空 国泰完全没法比。。。ˊ_>ˋ",
                  "status": 0,
                  "id": 545714,
                  "author": "喵要回家卖喵粮"
              },
              "id": 550718,
              "likes": 0
          },
          {
              "author": "小葱拌兔子",
              "content": "经济舱的东西真的是难吃得要死- -从澳洲飞国内不管是哪家都一样难吃，想要好吃还得坐头等舱_(:3」∠)_",
              "avatar": "https://picx.zhimg.com/5fe7f9449_l.jpg?source=8673f162",
              "time": 1413769524,
              "id": 550037,
              "likes": 0
          },
          {
              "author": "海涛小伙纸",
              "content": "晕飞机的表示十几个小时的国际也吃不下，这下看到不好吃就放心了",
              "avatar": "https://picx.zhimg.com/25d0f02d088929197e34bce35a0c3385_l.jpg?source=8673f162",
              "time": 1413751677,
              "id": 549573,
              "likes": 0
          },
          {
              "author": "管阿洁洁小慧慧",
              "content": "ANA的日式飞机餐是我吃过的最好吃的飞机餐！特别是今年秋冬的新菜单！",
              "avatar": "https://picx.zhimg.com/698b68678e2c1ed150e652883c1c1b8a_l.jpg?source=8673f162",
              "time": 1413742603,
              "id": 549528,
              "likes": 0
          },
          {
              "author": "风雨超人",
              "content": "好不好吃也得看航空公司的。",
              "avatar": "https://pica.zhimg.com/103a0b392_l.jpg?source=8673f162",
              "time": 1413732001,
              "id": 549273,
              "likes": 0
          },
          {
              "author": "cm_LiMei",
              "content": "生活在小农村，十几年前飞机还是非常昂贵的交通工具。爸爸每次出差都不舍得吃飞机上的食品，把那些小食品揣在包里带回来给我们。当时的飞机餐就算只是一包花生都觉得很好吃。",
              "avatar": "https://picx.zhimg.com/b06b47c725e00e6d144c8c783dc46876_l.jpg?source=8673f162",
              "time": 1413727167,
              "id": 549136,
              "likes": 0
          },
          {
              "author": "Rilakkunan",
              "content": "灰机餐很好吃的，乃们不要黑它～",
              "avatar": "https://picx.zhimg.com/c54324cd37bdafc461ed821371d2852f_l.jpg?source=8673f162",
              "time": 1413715348,
              "id": 548830,
              "likes": 0
          },
          {
              "author": "TuoTuo的亲爹",
              "content": "其实吃南航的牛肉饭和鸡肉饭还是蛮好吃的，屌丝表示只坐经济舱",
              "avatar": "https://picx.zhimg.com/8949bb2f30ed5789857accd489644234_l.jpg?source=8673f162",
              "time": 1413704442,
              "id": 548570,
              "likes": 1
          },
          {
              "author": "四月小曦",
              "content": "我觉得维珍航空的飞机餐还不错，至少有哈根达斯的冰淇淋。。。",
              "avatar": "https://picx.zhimg.com/7f9c7feb84168cb499d93e498ab342d9_l.jpg?source=8673f162",
              "time": 1413697656,
              "id": 548325,
              "likes": 0
          },
          {
              "author": "sunshine",
              "content": "小时候长辈做了飞机总是给我拿回来飞机上发的小袋椒盐花生，那时觉得那个简直是最美味的东西",
              "avatar": "https://picx.zhimg.com/81b4506bb2163c47602695cca4d37ee5_l.jpg?source=8673f162",
              "time": 1413695931,
              "id": 548252,
              "likes": 0
          },
          {
              "author": "一边按快门一边等待逆袭",
              "content": "居然看到图片里面有骨头，我想问问吃的哪家飞机餐。。。",
              "avatar": "https://pica.zhimg.com/290172b4c_l.jpg?source=8673f162",
              "time": 1413665436,
              "id": 547265,
              "likes": 0
          },
          {
              "author": "毛绒绒的小爪子",
              "content": "澳航qantas，飞机餐不好吃可以问空姐要开杯乐，开杯乐无限量全程供应。",
              "avatar": "https://pic1.zhimg.com/22b3e5a55_l.jpg?source=8673f162",
              "time": 1413662394,
              "id": 547254,
              "likes": 0
          },
          {
              "author": "Merenguesly",
              "content": "我觉得川航的还不错，还有特色辣酱",
              "avatar": "https://picx.zhimg.com/91e66703e_l.jpg?source=8673f162",
              "time": 1413652667,
              "id": 547162,
              "likes": 0
          },
          {
              "author": "鱼仔饼里的鲸鱼呢",
              "content": "读者上有一篇基本差不多内容 甚至大段内容一样的文章",
              "avatar": "https://pica.zhimg.com/5a3eb03b369f51703143f146e8859b50_l.jpg?source=8673f162",
              "time": 1413650284,
              "id": 547112,
              "likes": 0
          },
          {
              "author": "HazelQ_",
              "content": "第一个答主那么认真的讲解了半天，最后来了一句觉得国航的餐食不错，我瞬间就开始怀疑人生了有木有啊！",
              "avatar": "https://pica.zhimg.com/88b7cc43e8d512a7f955afcb8cb0594c_l.jpg?source=8673f162",
              "time": 1413649236,
              "id": 547091,
              "likes": 0
          }
      ]
  }
  ```

- 格式与前同，恕不再赘述
