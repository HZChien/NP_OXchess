github: https://github.com/HZChien/NP_OXchess
1.	
	輸入make以編譯
2.
	以./server 開啟伺服端程式 預設IP位置為127.0.0.1
	以./client <IP address> 開啟客戶端連結

3.
	client連結成功後, 輸入自己的名字
	輸入後按下Enter, 之後有數種功能可使用,輸入

	1 <Name>
		rename, 可將自己改名為<Name>
		名稱不可與他人同名, 相同會出現提示並無法更改
	
	2 
		list, 不須參數, 直接列出線上所有人
		且以idle表示目前閒置, 可接受邀請
		無法邀請將會顯示該玩家目前與誰進行遊戲
	
	3 <Name>
		invite, 邀請名字為<Name>的玩家進行OX旗遊戲
		無法邀請自己, 不在線上的人, 正在遊玩的人
		正在遊玩時也無法邀請他人
		邀請他人後可任意繼續邀請其他人
		但是只有最後一位受邀者可回覆

	5 Y <Name>
		accept, 接受<Name>的邀請,接受後便開始遊戲
	
	5 N <Name>
		refuse, 拒絕<Name>的邀請,拒絕後雙方都會收到通知

	-0 -1...-8
	OX棋輪到自己時, 輸入-0~-8來決定將棋下在何處
	順序非自己時無法下棋, 遊戲開始前或結束後無法下棋

	help
	呼叫指令說明

	logout
	登出伺服器

