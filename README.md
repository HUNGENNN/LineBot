# 定義字典
words_dict = {
    "你今天來這裡的原因是什麼？": "我感到工作和個人責任讓我不堪重負。",
    "你最近的感覺如何？": "我大多數時候感到焦慮和壓力很大。",
    "你能描述一下你目前的心情嗎？": "我經常感到悲傷和沮喪。",
    "你最近經歷過什麼重大生活變化嗎？": "是的，我最近搬到了一個新城市工作。",
    "你通常如何應對壓力？": "我通常會試圖通過愛好或鍛煉來分散注意力，但這並不總是有效。",
    "你有可以依靠的支持系統嗎？": "我有幾個可以談心的親密朋友和家人。",
    "你喜歡做哪些活動？": "我喜歡閱讀、遠足和畫畫。",
    "你有注意到你的睡眠模式有變化嗎？": "是的，我最近一直很難入睡和保持睡眠。",
    "你對這次心理輔導有什麼目標？": "我希望學會更好地管理壓力，並提高我的整體幸福感。",
    "apple": "蘋果",
    "banana": "香蕉",
    "cat": "貓",
    "dog": "狗",
    "elephant": "大象",
    "flower": "花",
    "guitar": "吉他",
    "house": "房子",
    "ice": "冰",
    "jacket": "夾克"
}

# 使用者輸入英文單字


Q = input("請輸入英文單字：").lower()
if Q == 'quit':
    break
A=words_dict[Q]
print("答案:",A )
