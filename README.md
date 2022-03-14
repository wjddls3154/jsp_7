# jsp_7 : 문자와 숫자를 이용한 예시

![image](https://user-images.githubusercontent.com/37132897/158110662-d36e096a-c8c1-4c30-abfb-b8710120a001.png)


      // 변수
      
      var txt = "paullab CEO jik";
      
      var num = 10;
      
      // 문자(txt) 사용 예시

      document.write(txt.length); // txt 의 길이, 공백까지 합쳐서, 15의 수가 나온다.

      document.write("<br>");

      document.write(txt.indexOf("CEO")); // 인덱스 8번째 부터 CEO 가 시작해서, 값이 8이 나온다.

      document.write("<br>");

      document.write(txt.slice(0, 7)); // 인덱스 0번부터 7번 전까지의 값, paullab 이 나온다.

      document.write("<br>");

      document.write(txt.replace("CEO", "CTO")); // CEO 라는 글자를, CTO 로 대체해준다.

      document.write("<br>");

      document.write(txt.toUpperCase()); // txt 값이, 모두 대문자로 변경된다.

      document.write("<br>");

      document.write(txt.toLowerCase()); // txt 값이, 모두 소문자로 변경된다.

      document.write("<br>");


      // 숫자(num) 사용 예시
      document.write(num.toFixed(6)); // 소수점 6자리가 뒤에 붙게 해줘라.

      document.write("<br>");

      document.write(num.toString()); // 숫자를, string 형으로 변환을 해줘라

      document.write("<br>");

      document.write(Math.PI); // PI = 3.14

      document.write("<br>");

      document.write(Math.max(10, 20, 30)); // 주어진 값 중 최대값 구하기

      document.write("<br>");

      document.write(Math.min(10, 20, 30)); // 주어진 값 중, 최소값 구하기

      document.write("<br>");

      document.write(Math.random() * 10); // 랜덤한 수

      document.write("<br>");
