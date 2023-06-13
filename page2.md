# 111421047
<!DOCTYPE html>
<html>
<head>
    <title>MBTI人格測試</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>

<body>
    <h1>MBTI人格測試</h1>
    <div id="questionnaire">
        <h2>你是比較衝動還是比較謹慎、深思熟慮的人？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">深思熟慮  
            <label> <input type="radio" name="question13" value="1" onclick="setSliderValue(13, 1)"> 1 </label>
            <label> <input type="radio" name="question13" value="2" onclick="setSliderValue(13, 2)"> 2 </label>
            <label> <input type="radio" name="question13" value="3" onclick="setSliderValue(13, 3)"> 3 </label>
            <label> <input type="radio" name="question13" value="4" onclick="setSliderValue(13, 4)"> 4 </label>
            <label> <input type="radio" name="question13" value="5" onclick="setSliderValue(13, 5)"> 5 </label>
            <label> <input type="radio" name="question13" value="6" onclick="setSliderValue(13, 6)"> 6 </label>
            <label> <input type="radio" name="question13" value="7" onclick="setSliderValue(13, 7)"> 7 </label>
            <type value="5-7">衝動 
        </div>
        </div>
        <h2>你比較喜歡在團體中帶領或是跟隨他人的領導？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">跟隨他人 
            <label> <input type="radio" name="question14" value="1" onclick="setSliderValue(14, 1)"> 1 </label>
            <label> <input type="radio" name="question14" value="2" onclick="setSliderValue(14, 2)"> 2 </label>
            <label> <input type="radio" name="question14" value="3" onclick="setSliderValue(14, 3)"> 3 </label>
            <label> <input type="radio" name="question14" value="4" onclick="setSliderValue(14, 4)"> 4 </label>
            <label> <input type="radio" name="question14" value="5" onclick="setSliderValue(14, 5)"> 5 </label>
            <label> <input type="radio" name="question14" value="6" onclick="setSliderValue(14, 6)"> 6 </label>
            <label> <input type="radio" name="question14" value="7" onclick="setSliderValue(14, 7)"> 7 </label>
            <type value="5-7">帶領別人 
        </div>
        </div>
        <h2>社交互動對你是增加能量還是消耗能量？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">消耗能量  
            <label> <input type="radio" name="question15" value="1" onclick="setSliderValue(15, 1)"> 1 </label>
            <label> <input type="radio" name="question15" value="2" onclick="setSliderValue(15, 2)"> 2 </label>
            <label> <input type="radio" name="question15" value="3" onclick="setSliderValue(15, 3)"> 3 </label>
            <label> <input type="radio" name="question15" value="4" onclick="setSliderValue(15, 4)"> 4 </label>
            <label> <input type="radio" name="question15" value="5" onclick="setSliderValue(15, 5)"> 5 </label>
            <label> <input type="radio" name="question15" value="6" onclick="setSliderValue(15, 6)"> 6 </label>
            <label> <input type="radio" name="question15" value="7" onclick="setSliderValue(15, 7)"> 7 </label>
            <type value="5-7">增加能量 
        </div>
        </div>
        <h2>當面對新的挑戰時，你喜歡探索不同的可能性還是依循過去經驗和已知事實?</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">過去經驗
            <label> <input type="radio" name="question16" value="1" onclick="setSliderValue(16, 1)"> 1 </label>
            <label> <input type="radio" name="question16" value="2" onclick="setSliderValue(16, 2)"> 2 </label>
            <label> <input type="radio" name="question16" value="3" onclick="setSliderValue(16, 3)"> 3 </label>
            <label> <input type="radio" name="question16" value="4" onclick="setSliderValue(16, 4)"> 4 </label>
            <label> <input type="radio" name="question16" value="5" onclick="setSliderValue(16, 5)"> 5 </label>
            <label> <input type="radio" name="question16" value="6" onclick="setSliderValue(16, 6)"> 6 </label>
            <label> <input type="radio" name="question16" value="7" onclick="setSliderValue(16, 7)"> 7 </label>
            <type value="5-7">不同可能性 
        </div>
        </div>
        <h2>當面對工作或任務時，你喜歡提前計劃還是保持彈性？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">提前計劃  
            <label> <input type="radio" name="question17" value="1" onclick="setSliderValue(17, 1)"> 1 </label>
            <label> <input type="radio" name="question17" value="2" onclick="setSliderValue(17, 2)"> 2 </label>
            <label> <input type="radio" name="question17" value="3" onclick="setSliderValue(17, 3)"> 3 </label>
            <label> <input type="radio" name="question17" value="4" onclick="setSliderValue(17, 4)"> 4 </label>
            <label> <input type="radio" name="question17" value="5" onclick="setSliderValue(17, 5)"> 5 </label>
            <label> <input type="radio" name="question17" value="6" onclick="setSliderValue(17, 6)"> 6 </label>
            <label> <input type="radio" name="question17" value="7" onclick="setSliderValue(17, 7)"> 7 </label>
            <type value="5-7">保持彈性
        </div>
        </div>
        <h2>當你面臨壓力或煩惱時，你喜歡與他人討論還是獨自思考解決問題？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">獨自思考 
            <label> <input type="radio" name="question18" value="1" onclick="setSliderValue(18, 1)"> 1 </label>
            <label> <input type="radio" name="question18" value="2" onclick="setSliderValue(18, 2)"> 2 </label>
            <label> <input type="radio" name="question18" value="3" onclick="setSliderValue(18, 3)"> 3 </label>
            <label> <input type="radio" name="question18" value="4" onclick="setSliderValue(18, 4)"> 4 </label>
            <label> <input type="radio" name="question18" value="5" onclick="setSliderValue(18, 5)"> 5 </label>
            <label> <input type="radio" name="question18" value="6" onclick="setSliderValue(18, 6)"> 6 </label>
            <label> <input type="radio" name="question18" value="7" onclick="setSliderValue(18, 7)"> 7 </label>
            <type value="5-7">與他人討論 
        </div>
        </div>
        <h2>在工作時，你喜歡以達到整體目標為目標還是喜歡處理每個細節？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">處理細節  
            <label> <input type="radio" name="question19" value="1" onclick="setSliderValue(19, 1)"> 1 </label>
            <label> <input type="radio" name="question19" value="2" onclick="setSliderValue(19, 2)"> 2 </label>
            <label> <input type="radio" name="question19" value="3" onclick="setSliderValue(19, 3)"> 3 </label>
            <label> <input type="radio" name="question19" value="4" onclick="setSliderValue(19, 4)"> 4 </label>
            <label> <input type="radio" name="question19" value="5" onclick="setSliderValue(19, 5)"> 5 </label>
            <label> <input type="radio" name="question19" value="6" onclick="setSliderValue(19, 6)"> 6 </label>
            <label> <input type="radio" name="question19" value="7" onclick="setSliderValue(19, 7)"> 7 </label>
            <type value="5-7">達到目標 
        </div>
        </div>
        <h2>您是否對新的、未知的事物充滿好奇心，並且願意嘗試新的方法和想法？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">是  
            <label> <input type="radio" name="question20" value="1" onclick="setSliderValue(20, 1)"> 1 </label>
            <label> <input type="radio" name="question20" value="2" onclick="setSliderValue(20, 2)"> 2 </label>
            <label> <input type="radio" name="question20" value="3" onclick="setSliderValue(20, 3)"> 3 </label>
            <label> <input type="radio" name="question20" value="4" onclick="setSliderValue(20, 4)"> 4 </label>
            <label> <input type="radio" name="question20" value="5" onclick="setSliderValue(20, 5)"> 5 </label>
            <label> <input type="radio" name="question20" value="6" onclick="setSliderValue(20, 6)"> 6 </label>
            <label> <input type="radio" name="question20" value="7" onclick="setSliderValue(20, 7)"> 7 </label>
            <type value="5-7">否
        </div>
        </div>
        <h2>在與他人互動時，你是先思考後說話，還是直接表達自己的想法和感受？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">先思考後說話  
            <label> <input type="radio" name="question21" value="1" onclick="setSliderValue(21, 1)"> 1 </label>
            <label> <input type="radio" name="question21" value="2" onclick="setSliderValue(21, 2)"> 2 </label>
            <label> <input type="radio" name="question21" value="3" onclick="setSliderValue(21, 3)"> 3 </label>
            <label> <input type="radio" name="question21" value="4" onclick="setSliderValue(21, 4)"> 4 </label>
            <label> <input type="radio" name="question21" value="5" onclick="setSliderValue(21, 5)"> 5 </label>
            <label> <input type="radio" name="question21" value="6" onclick="setSliderValue(21, 6)"> 6 </label>
            <label> <input type="radio" name="question21" value="7" onclick="setSliderValue(21, 7)"> 7 </label>
            <type value="5-7">直接表達
        </div>
        </div>
        <h2>您是喜歡保持冷靜和理性，並在壓力下保持客觀的態度的人嗎？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">是  
              <label> <input type="radio" name="question22" value="1" onclick="setSliderValue(22, 1)"> 1 </label>
              <label> <input type="radio" name="question22" value="2" onclick="setSliderValue(22, 2)"> 2 </label>
              <label> <input type="radio" name="question22" value="3" onclick="setSliderValue(22, 3)"> 3 </label>
              <label> <input type="radio" name="question22" value="4" onclick="setSliderValue(22, 4)"> 4 </label>
              <label> <input type="radio" name="question22" value="5" onclick="setSliderValue(22, 5)"> 5 </label>
              <label> <input type="radio" name="question22" value="6" onclick="setSliderValue(22, 6)"> 6 </label>
              <label> <input type="radio" name="question22" value="7" onclick="setSliderValue(22, 7)"> 7 </label>
            <type value="5-7">否 
        </div>
        </div>
    </div>
</body>
  <script>
    function navigateToPreviousPage() {
      // 使用 window.location.href 將網頁導航至上一頁的 URL
      window.location.href = "MBTI-page1 copy.html";
    }
  </script>
  </div>
</div>
  <script>
    function navigateToNextPage() {
      // 使用 window.location.href 將網頁導航至下一頁的 URL
      window.location.href = "MBTI-page3.html";
    }
  </script>
  </div>
</div>
<div class="button-container">
  <br>
  <button class="styled-button" onclick="navigateToPreviousPage()">上一頁</button>
  <button class="styled-button" onclick="calculateResult()">計算結果</button>
</div>

<script>
  function calculateResult() {
    var queryString = window.location.search;
    var urlParams = new URLSearchParams(queryString);
    var total1 = 0;
    var total2 = 0;
    var total3 = 0;
    var total4 = 0;

    // 計算各個維度的總數
    for (var [questionNumber, value] of urlParams.entries()) {
      value = parseInt(value);
      if ([1, 7, 9, 12, 14, 15, 18, 21].includes(parseInt(questionNumber))) {
        total1 += value;
      }
      if ([2, 5, 6, 9, 10, 13, 20, 21].includes(parseInt(questionNumber))) {
        total2 += value;
      }
      if ([3, 4, 6, 11, 16, 17, 19, 22].includes(parseInt(questionNumber))) {
        total3 += value;
      }
      if ([3, 4, 5, 6, 8, 11, 16, 17].includes(parseInt(questionNumber))) {
        total4 += value;
      }
    }

    // 根據總數計算 MBTI 結果
    var result = "";
    if (total1 <= 28) {
      result += "I";
    } else {
      result += "E";
    }
    if (total2 <= 28) {
      result += "S";
    } else {
      result += "N";
    }
    if (total3 <= 28) {
      result += "T";
    } else {
      result += "F";
    }
    if (total4 <= 28) {
      result += "J";
    } else {
      result += "P";
    }

    // 將結果傳遞到下一頁
    window.location.href = `MBTI-page3.html?result=${result}`;
  }
</script>

<style>
body {
  color: midnightblue;
  text-align: center;
  background-image: url("2.png");
  background-repeat: repeat;
   background-position: center;
   }
h1 {
  color: darkblue;
  text-shadow: 4.0px 4.1px 5.5px rgba(0, 0, 0, 0.5);
  text-align: center;
  font-size: 2.5rem;
}

h2 {
  text-align: center;
  font-size: 1.8rem;
}

type  {
  font-size: 1.4rem;
}

.container .slider {
  text-align: center;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  vertical-align: middle;
}

.button {
  text-align: center;
}

.container .slider input[type="radio"][value="1"] {
  transform: scale(2.5);
}
.container .slider input[type="radio"][value="2"] {
  transform: scale(2.0);
}
.container .slider input[type="radio"][value="3"] {
  transform: scale(1.6);
}
.container .slider input[type="radio"][value="4"] {
  transform: scale(1.2);
}
.container .slider input[type="radio"][value="5"] {
  transform: scale(1.6);
}
.container .slider input[type="radio"][value="6"] {
  transform: scale(2.0);
}
.container .slider input[type="radio"][value="7"] {
  transform: scale(2.5);
}
.container .slider label {
  font-size: 0px;
}
.container .slider input[type="radio"] {
  text-align: center; 
  margin-bottom: -2px;
  margin-right: 22px;
  margin-left: 22px; 
}
.styled-button {
   font-size: 15px;
   padding: 8px 15px;
    background-color:#8b4513c0;
    border: none;
    color: #ffffff;
     border-radius: 5px;
    } 
    .button-container {
        margin-top: 10px;
        display: flex;
        justify-content: center;
        margin-top: 10px;
    }
    .button-container button {
        margin-right: 10px;
    }

</style>

</html>
