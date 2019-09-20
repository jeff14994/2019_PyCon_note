## Pycon -201920 -Day1
## 1. [Keynote 林守德] R0 (我在R1 看直播)

*  RNN -> recurrent neural network  
	* output是下一個的input -> 連續性的資料 encode（記住前面的資訊）
		* 1. vanilla forward
		* 2. LSTM -> forget gates
		* 3. GRU -> LSTM 簡化版 (Gated Recurrent Unit)

* 用途：
	* 1. Language Modeling  
 	* 2. Classification/Regression Tasks   
	* 3. Sequence to sequence(Seq2seq) -> NMT(Neural machine transition)
		* e.g. 小冰寫詩 -> How? -> Encoder/decoder
#### How to design encoder?
*  先轉成向量
*  Components of Seq2seq:
	* encoder  
	* decoder  

* Evaluation:
	* Perplexity  
	* Rouge
#### Seq2seq Model Implicit Control Signals
* Research questions:
	* Can a seq2seq **understand** the <strong>meanings</strong> ?  
		* Goal: learn to control length
			* length  	
			* Rhyme  
			* POS

* **Performance**: Accuracy: 80-90%  
	* THE RESULTS ARE SURPRISING!!!  
	* Why? What is the model behavior?  
	* What we have found?
		* Finding:
			* 3: the existence of counting down
	* How did we **find** the Responsiblity of those neurons
	* How to verify? -> disable those neurons -> and see if the performance drops -> if yes -> THAT IS THE RESPONSIBLE NEURONS!!!
## 
## 2. [驢車 (Donkey Car)，一個基於 Raspberry Pi 與機器學習的自走車專案介紹sosorry] R1
* Raspberry Pi 官方經銷商
* Agenda
	* What is Donkey car ?
		* 硬體
		* 架構
	* 引入機器學習
	* Hack Donkey car
	* Resources
* Creator of Donkey Car:
	* Will Roscoe (software)
	* Adam (Hardware)
* Hardware
	* RC car
	* RPi
	* Python
	* Neural Network
* Goal:
	* Drive itself
* 動力系統架構：
	* ESC 用來控制motor轉速（油門）
	* I2C
	* PWM 訊號
* 控制理論：
	* Percepion:
		* Take pictures
		* get user input
	* Planning
		* Get model prediction
	* Control
		* Update servo
		* Update motor
	* Data collection
		* Save data (檔案類型)
			* .jpg
			* .json
			* Train data in Colab
* 實際運作
	* 建立車道：
	* 使用browser 控制
	* 搜集訓練資料 -> 使用CNN訓練model -> colab訓練資料
	* 清理資料

* Hack donkey car:
	* Duckiebot 
	* fix actuator.py
## 
## 3. [How to Transform Research Oriented Code into Machine Learning APIs with Python Tetsuya Jesse Hirata] R0
* Research oriented code 
* APIs are composed of three elements
##
## 4. [Click Click Boom! Bombs Over Our Mind! KunYu Chen] R2
* Goal: to join VirusTotal
	* Zip bomb 
	* Mitigation 
* Create own zip bumb
	* zipfile
* Request a CVE 
* [BPO](https://bugs.python.org)
* [CVE](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-9674)
##
## 5. [Py車達人 Malo] R0
* CANBus: Controller Area Network
	* 兩條線傳輸資料
	* 通訊協議：J1929
* BeagleBone 上的CANBus 通訊
	* CAN interface: socketCAN 方式 [控制器區域網路](https://www.wikiwand.com/zh-tw/控制器區域網路)












