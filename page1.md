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
        <h2>你比較喜歡一個人待著還是和他人在一起？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">獨自待著  
            <label> <input type="radio" name="question1" value="1" onclick="setSliderValue(1, 1)"> 1 </label>
            <label> <input type="radio" name="question1" value="2" onclick="setSliderValue(1, 2)"> 2 </label>
            <label> <input type="radio" name="question1" value="3" onclick="setSliderValue(1, 3)"> 3 </label>
            <label> <input type="radio" name="question1" value="4" onclick="setSliderValue(1, 4)"> 4 </label>
            <label> <input type="radio" name="question1" value="5" onclick="setSliderValue(1, 5)"> 5 </label>
            <label> <input type="radio" name="question1" value="6" onclick="setSliderValue(1, 6)"> 6 </label>
            <label> <input type="radio" name="question1" value="7" onclick="setSliderValue(1, 7)"> 7 </label>
            <type value="5-7">他人一起 
        </div>
        </div>
        <h2>你是偏向大局思考還是注重細節的人？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">注重細節  
            <label> <input type="radio" name="question2" value="1" onclick="setSliderValue(2, 1)"> 1 </label>
            <label> <input type="radio" name="question2" value="2" onclick="setSliderValue(2, 2)"> 2 </label>
            <label> <input type="radio" name="question2" value="3" onclick="setSliderValue(2, 3)"> 3 </label>
            <label> <input type="radio" name="question2" value="4" onclick="setSliderValue(2, 4)"> 4 </label>
            <label> <input type="radio" name="question2" value="5" onclick="setSliderValue(2, 5)"> 5 </label>
            <label> <input type="radio" name="question2" value="6" onclick="setSliderValue(2, 6)"> 6 </label>
            <label> <input type="radio" name="question2" value="7" onclick="setSliderValue(2, 7)"> 7 </label>
            <type value="5-7">偏向大局
        </div>
        </div>
        <h2>你是以邏輯或情感為基礎做決定的人？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">邏輯為重  
            <label> <input type="radio" name="question3" value="1" onclick="setSliderValue(3, 1)"> 1 </label>
            <label> <input type="radio" name="question3" value="2" onclick="setSliderValue(3, 2)"> 2 </label>
            <label> <input type="radio" name="question3" value="3" onclick="setSliderValue(3, 3)"> 3 </label>
            <label> <input type="radio" name="question3" value="4" onclick="setSliderValue(3, 4)"> 4 </label>
            <label> <input type="radio" name="question3" value="5" onclick="setSliderValue(3, 5)"> 5 </label>
            <label> <input type="radio" name="question3" value="6" onclick="setSliderValue(3, 6)"> 6 </label>
            <label> <input type="radio" name="question3" value="7" onclick="setSliderValue(3, 7)"> 7 </label>
            <type value="5-7">情感基礎 
        </div>
        </div>
        <h2>你比較喜歡自行安排你的一天或是跟著他人的計畫走呢？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">他人計畫 
            <label> <input type="radio" name="question4" value="1" onclick="setSliderValue(4, 1)"> 1 </label>
            <label> <input type="radio" name="question4" value="2" onclick="setSliderValue(4, 2)"> 2 </label>
            <label> <input type="radio" name="question4" value="3" onclick="setSliderValue(4, 3)"> 3 </label>
            <label> <input type="radio" name="question4" value="4" onclick="setSliderValue(4, 4)"> 4 </label>
            <label> <input type="radio" name="question4" value="5" onclick="setSliderValue(4, 5)"> 5 </label>
            <label> <input type="radio" name="question4" value="6" onclick="setSliderValue(4, 6)"> 6 </label>
            <label> <input type="radio" name="question4" value="7" onclick="setSliderValue(4, 7)"> 7 </label>
            <type value="5-7">自己安排
        </div>
        </div>
        <h2>你是會遵守規則和法規的人還是喜歡挑戰它們？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">遵守規則 
            <label> <input type="radio" name="question5" value="1" onclick="setSliderValue(5, 1)"> 1 </label>
            <label> <input type="radio" name="question5" value="2" onclick="setSliderValue(5, 2)"> 2 </label>
            <label> <input type="radio" name="question5" value="3" onclick="setSliderValue(5, 3)"> 3 </label>
            <label> <input type="radio" name="question5" value="4" onclick="setSliderValue(5, 4)"> 4 </label>
            <label> <input type="radio" name="question5" value="5" onclick="setSliderValue(5, 5)"> 5 </label>
            <label> <input type="radio" name="question5" value="6" onclick="setSliderValue(5, 6)"> 6 </label>
            <label> <input type="radio" name="question5" value="7" onclick="setSliderValue(5, 7)"> 7 </label>
            <type value="5-7">挑戰規則 
        </div>
        </div>
        <h2>你比較喜歡有條理、有計畫的環境還是比較自由、沒有明確結構的環境？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">條理環境  
            <label> <input type="radio" name="question6" value="1" onclick="setSliderValue(6, 1)"> 1 </label>
            <label> <input type="radio" name="question6" value="2" onclick="setSliderValue(6, 2)"> 2 </label>
            <label> <input type="radio" name="question6" value="3" onclick="setSliderValue(6, 3)"> 3 </label>
            <label> <input type="radio" name="question6" value="4" onclick="setSliderValue(6, 4)"> 4 </label>
            <label> <input type="radio" name="question6" value="5" onclick="setSliderValue(6, 5)"> 5 </label>
            <label> <input type="radio" name="question6" value="6" onclick="setSliderValue(6, 6)"> 6 </label>
            <label> <input type="radio" name="question6" value="7" onclick="setSliderValue(6, 7)"> 7 </label>
            <type value="5-7">沒有明確 
        </div>
        </div>
        <h2>你是喜歡獨立工作還是喜歡跟團隊一起合作的人？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">獨立工作  
            <label> <input type="radio" name="question7" value="1" onclick="setSliderValue(7, 1)"> 1 </label>
            <label> <input type="radio" name="question7" value="2" onclick="setSliderValue(7, 2)"> 2 </label>
            <label> <input type="radio" name="question7" value="3" onclick="setSliderValue(7, 3)"> 3 </label>
            <label> <input type="radio" name="question7" value="4" onclick="setSliderValue(7, 4)"> 4 </label>
            <label> <input type="radio" name="question7" value="5" onclick="setSliderValue(7, 5)"> 5 </label>
            <label> <input type="radio" name="question7" value="6" onclick="setSliderValue(7, 6)"> 6 </label>
            <label> <input type="radio" name="question7" value="7" onclick="setSliderValue(7, 7)"> 7 </label>
            <type value="5-7">團隊合作 
        </div>
        </div>
        <h2>你比較喜歡生活有規律、有重複的事情還是喜歡多樣化、變化多端的生活？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">重複事情  
            <label> <input type="radio" name="question8" value="1" onclick="setSliderValue(8, 1)"> 1 </label>
            <label> <input type="radio" name="question8" value="2" onclick="setSliderValue(8, 2)"> 2 </label>
            <label> <input type="radio" name="question8" value="3" onclick="setSliderValue(8, 3)"> 3 </label>
            <label> <input type="radio" name="question8" value="4" onclick="setSliderValue(8, 4)"> 4 </label>
            <label> <input type="radio" name="question8" value="5" onclick="setSliderValue(8, 5)"> 5 </label>
            <label> <input type="radio" name="question8" value="6" onclick="setSliderValue(8, 6)"> 6 </label>
            <label> <input type="radio" name="question8" value="7" onclick="setSliderValue(8, 7)"> 7 </label>
            <type value="5-7">多變生活
        </div>
        </div>
        <h2>你喜歡和與你相似或不同的人一起共處嗎？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">自身相似
            <label> <input type="radio" name="question9" value="1" onclick="setSliderValue(9, 1)"> 1 </label>
            <label> <input type="radio" name="question9" value="2" onclick="setSliderValue(9, 2)"> 2 </label>
            <label> <input type="radio" name="question9" value="3" onclick="setSliderValue(9, 3)"> 3 </label>
            <label> <input type="radio" name="question9" value="4" onclick="setSliderValue(9, 4)"> 4 </label>
            <label> <input type="radio" name="question9" value="5" onclick="setSliderValue(9, 5)"> 5 </label>
            <label> <input type="radio" name="question9" value="6" onclick="setSliderValue(9, 6)"> 6 </label>
            <label> <input type="radio" name="question9" value="7" onclick="setSliderValue(9, 7)"> 7 </label>
            <type value="5-7">自身不同 </br>
        </div>
        </div>
        <h2>你比較關注當下還是未來?</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">當下  
            <label> <input type="radio" name="question10" value="1" onclick="setSliderValue(10, 1)"> 1 </label>
            <label> <input type="radio" name="question10" value="2" onclick="setSliderValue(10, 2)"> 2 </label>
            <label> <input type="radio" name="question10" value="3" onclick="setSliderValue(10, 3)"> 3 </label>
            <label> <input type="radio" name="question10" value="4" onclick="setSliderValue(10, 4)"> 4 </label>
            <label> <input type="radio" name="question10" value="5" onclick="setSliderValue(10, 5)"> 5 </label>
            <label> <input type="radio" name="question10" value="6" onclick="setSliderValue(10, 6)"> 6 </label>
            <label> <input type="radio" name="question10" value="7" onclick="setSliderValue(10, 7)"> 7 </label>
            <type value="5-7">未來 
        </div>
        </div>
        <h2>你喜歡探索新的想法和概念，還是喜歡堅持已知的事物？</h2>
        <div class="container">
        <div class="slider">
            <type value="1-3">堅持已知   
             <label > <input type="radio" name="question11" value="1" onclick="setSliderValue(11, 1)"> 1 </label>
            <label> <input type="radio" name="question11" value="2" onclick="setSliderValue(11, 2)"> 2 </label>
            <label> <input type="radio" name="question11" value="3" onclick="setSliderValue(11, 3)"> 3 </label>
            <label> <input type="radio" name="question11" value="4" onclick="setSliderValue(11, 4)"> 4 </label>
            <label> <input type="radio" name="question11" value="5" onclick="setSliderValue(11, 5)"> 5 </label>
            <label> <input type="radio" name="question11" value="6" onclick="setSliderValue(11, 6)"> 6 </label>
            <label> <input type="radio" name="question11" value="7" onclick="setSliderValue(11, 7)"> 7 </label>
            <type value="5-7">探索新知
        </div>
        </div>
        <h2>你比較喜歡口頭或書面表達你的想法和感受？</h2>
           <div class="container">
           <div class="slider">
            <type value="1-3">書面表達 
            <label> <input type="radio" name="question12" value="1" onclick="setSliderValue(12, 1)"> 1 </label>
            <label> <input type="radio" name="question12" value="2" onclick="setSliderValue(12, 2)"> 2 </label>
            <label> <input type="radio" name="question12" value="3" onclick="setSliderValue(12, 3)"> 3 </label>
            <label> <input type="radio" name="question12" value="4" onclick="setSliderValue(12, 4)"> 4 </label>
            <label> <input type="radio" name="question12" value="5" onclick="setSliderValue(12, 5)"> 5 </label>
            <label> <input type="radio" name="question12" value="6" onclick="setSliderValue(12, 6)"> 6 </label>
            <label> <input type="radio" name="question12" value="7" onclick="setSliderValue(12, 7)"> 7 </label>
            <type value="5-7">口頭表達  
        </div>
        </div>
         
    </div>

<div class="container">
<div class="button">
    <br> 
    <button class="styled-button" onclick="navigateToNextPage()">下一頁</button>
  <script>
    function navigateToNextPage() {
      // 使用 window.location.href 將網頁導航至下一頁的 URL
      window.location.href = "MBTI-page2.html";
    }
  </script>
</div>
</div>
</body>

<script>
    // 儲存題目的回答值
    var answers = {}; 
    function setSliderValue(questionNumber, value) {
      answers[questionNumber] = value;
    }
    function navigateToNextPage() {
      // 將回答值作為查詢參數附加到下一頁的 URL 上
      var queryString = Object.entries(answers).map(([questionNumber, value]) => `${questionNumber}=${value}`).join('&');
      window.location.href = `MBTI-page2.html?${queryString}`;
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
  font-size: 2.8rem;
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
</style>

</html>
