# 부호와 조합(Morse code)

-   최초의 전신 (telegraph) 시스템
-   미국의 “아티스트” 새뮤얼 모스가 발명
-   짧은 전류 (・) 와 긴 전류( - ) 를 조합, 알파벳과 숫자를 표기
-   최초의 실험: 1843년 워싱턴 DC부터 Baltimore까지 불과 몇 분 만에 전송
-   최초의 메시지: “신이 하신 일“ (“What hath God wrought!”)

<img src="moss map.png" alt="drawing" width="700" height= "500px"/>
_전산 시스템 이전에 Washington DC 부터 Baltimore까지 걸리는 시간_

# Pre-morse telegraph

<img src="pre morse.png" alt="drawing" width="700" height= "500px"/>
_같은 시대 (1800s), 모스 이전의 전산 시스템, 5개의 나침반, 느림_

# Key Takeaway

-   모스부호는 "2진" (Binary) 부호
-   표현(조합)할 수 있는 총부호의 수 2<sup>n</sup>

| 점과 선의 수 | 부호의 수     |
| ------------ | ------------- |
| 1            | 2<sup>2</sup> |
| 2            | 2<sup>3</sup> |
| 3            | 2<sup>4</sup> |
| 4            | 2<sup>5</sup> |
| 5            | 2<sup>6</sup> |
| 6            | 2<sup>7</sup> |

<p style="font-size: 20px; ">= 입력<sup>횟수</sup></p>

<p style="font-size: 20px; ">즉, 주사위는 = 6<sup>n</sup></p>

-   알파벳은 26개, 즉 2<sup>5</sup> 로 다 커버가 된다.
-   숫자는 2<sup>6</sup> 을 사용한다

<img src="final tree.png" alt="drawing" width="700" height= "500px"/>
