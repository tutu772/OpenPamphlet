### GPL형 라이선스

GPL형 라이선스에는 GPL 2.0,  GPL 3.0, LGPL 2.1, LGPL 3.0, AGPL 3.0 등이 포함되며 대부분 FSF에서 주도하여 만든 것 이다. 카피레프트 조항과 소스코드 제공 의무를 가진다는 점에서 BSD와 비교 된다.

**2-1 GPL 2.0**   
GPL 2.0으로 배포되는 오픈소스는 i\) 각 복제본에 적절한 저작권 표시와 보증책임이  
없음을 명시하고, ii\) GPL 라이선스를 언급하는 고지사항과 보증책임 관련 고지사항을  
원본 그대로 유지하고, iii\) 소프트웨어를 양도받는 모든 이들에게 소프트웨어와 함께 GPL  
라이선스 사본을 제공하고, iv\) 파일을 수정한 경우 수정했다는 사실과 날짜를 파일에  
명기해야 한다. 그리고 v\) 원본저작물과 파생저작물\(derivative work\)을 GPL 2.0에 의해  
배포해야 하며, vi\) 원본저작물 및 파생저작물에 대한 소스코드를 제공하거나, 요청 시  
제공하겠다는 약정서를 제공해야 한다. 여기서 i\) ~ iv\)의 의무사항은 Apache 라이선스와  
동일하거나 유사한 내용이지만, v\) 및 vi\)의 의무사항은 BSD형의 라이선스에서는 찾아볼  
수 없는 내용이다.

**2-2 GPL 3.0**
GPL 3.0은 GPL 2.0이 배포되고 난 이후 오픈소스 환경을 둘러싼 다양한 변화들을  
수용하여 만든 라이선스이다. GPL 3.0의 의무사항으로는 i\) 각 복제본에 저작권 고지와  
보증책임이 없음을 명시할 것, ii\) GPL 3.0의 조건 및 제7조의 조건에 관한 내용을 있는  
그대로 유지할 것, iii\) 소프트웨어를 양도받는 모든 이들에게 소프트웨어와 함께 GPL  
라이선스 사본을 제공할 것, iv\) 소프트웨어를 수정했을 경우 수정사실 및 일시를 명시할  
것, v\) 원본저작물과 그에 기반한 저작물\(Work based on the program\)을 GPL 3.0에 의해  
배포할 것, vi\) 원본저작물 및 그에 기반한 저작물\(Work based on the program\)에 대한  
소스코드를 제공하거나, 요청 시 제공하겠다는 약정서를 제공할 것, vii\) 사용자 제품\(user  
product\)에 대한 인증키 등 설치정보\(installation information\)를 제공할 것, viii\) 차별적인  
특허라이선스 계약을 체결하지 말 것 등의 내용이 포함되어 있다.  
i\) ~ vi\) 의 내용은 GPL 2.0의 내용과 같거나 내용을 더욱 명확히 하는 것이었지만, vii\) 및  
viii\)의 내용은 GPL 3.0에 처음으로 포함된 내용으로 많은 논란을 불러일으켰다.

**\[참고\] Tivoization과 설치정보의 제공**
미국의 TiVo 라는 회사는 케이블방송 또는 위성방송 등의 방송프로그램을 하드디스크에  
녹화하거나, 경우에 따라서는 개인 PC나 DVD 등에 저장할 수 있도록 하는 DVR\(digital  
video recorder\)제품을 시장에 출시하여 성공하였다. 한편 해당 제품에는 리눅스 커널  
등 GPL 소프트웨어가 포함되어 있었기 때문에 TiVo는 GPL 2.0의 규정에 따라 관련  
소스코드를 이용자들에게 제공하였다. 그런데 이용자들이 해당 소스코드를 수정하여 다시  
TiVo의 제품에 포팅하였으나 정상적으로 작동하지 않았다. 이는 TiVo사가 이용자들이  
해당 제품을 수정하여 사용하는 것을 허용하지 않았기 때문이다. 이와 같은 TiVo의  
정책에 대해 스톨만은 TiVo가 GPL을 악용하고 있다고 주장하였다. GPL의 근본 목적은  
이용자들이 해당 소프트웨어를 자유롭게 수정하여 사용할 수 있도록 하는 것임에도  
불구하고 Tivo는 이를 막고 있다는 것이다. 스톨만은 이와 같은 GPL의 남용행위를  
Tivoization이라고 이름 짓고, 이를 방지하기 위해 GPL 3.0에 다음과 같은 규정을  
마련하였다.

GPL 코드를 특정한 사용자 제품\(User Product\)에 포함하거나 혹은 그와 함께 배포하는  
경우에는 해당 소스에 설치 정보\(Installation Information\)를 함께 제공해야 한다.  
이때 ‘사용자 제품\(User Product\)’이란 통상적인 소비자 제품이나 집안에서 쓰일  
목적으로 설계되었거나 판매되는 제품을 말하며, ‘설치 정보\(Installation Information\)’란  
소프트웨어를 수정하여 해당 제품에 설치하고 실행하는 데 필요한 방법\(methods\),  
절차\(procedures\), 인증키\(authorization keys\) 혹은 여타 정보 모두를 의미한다. 다만  
소프트웨어가 ROM에 설치된 경우처럼, 해당 제품의 제조업체나 여타 제3자도 수정된  
코드를 제품에 설치할 수 없는 경우에는 설치정보를 제공하지 않아도 된다. 또한,  
사용자가 설치하거나 수정한 저작물 및 해당 제품에 대한 지원서비스나 보증, 업데이트를  
계속해서 제공할 필요는 없다. 그리고 사용자의 수정으로 인해 네트워크의 작동에  
실질적이고 부정적인 영향을 끼치거나, 네트워크를 통한 통신 규칙 및 프로토콜을  
위반하는 경우에는 네트워크에 대한 접속을 거부할 수 있다.

**2-3 LGPL**
LGPL은 주로 라이브러리에 사용하기 위해 FSF가 GPL과는 별도로 만든 라이선스이다.  
라이브러리에 GPL 라이선스를 적용하게 되면 응용프로그램까지 GPL로 배포해야 하므로  
사용자는 해당 라이브러리의 사용을 꺼리게 된다. FSF는 GPL의 내용을 약간 수정하여  
라이브러리 자체를 수정한 경우에는 카피레프트 조항을 적용하지만, 해당 라이브러리를  
이용한 응용프로그램은 카피레프트 조항을 적용하지 않고 소스코드 제공 의무도 없는  
형태로 LGPL 라이선스를 만들었다.  
LGPL의 의무사항은 i\) 각 복제본에 적절한 저작권 안내와 보증책임이 없음을 명시할 것,  
ii\) LGPL 라이선스를 언급하는 안내 사항과 보증책임 관련 고지사항을 원본 그대로 유지할  
것, iii\) 소프트웨어를 양도받는 모든 이들에게 소프트웨어와 함께 LGPL 라이선스 사본을  
제공할 것, iv\) 라이브러리 형태로의 수정을 허용하며, 만약 수정한 경우 수정사실과  
날짜를 파일에 명기할 것, iv\) 원본저작물과 파생저작물을 LGPL 또는 GPL에 의해 배포할  
것, v\) 원본저작물 및 파생저작물에 대한 소스코드를 제공하거나, 요청 시 제공하겠다는  
약정서를 제공할 것, vi\) 응용프로그램을 배포할 경우, LGPL 라이브러리를 사용하고  
있다는 사실을 명시할 것, vii\) 사용자가 라이브러리를 수정해도 응용프로그램을 사용할  
수 있도록 \(예를 들어 응용프로그램의 오브젝트 코드를 제공하거나, 해당 라이브러리의  
형태를 공유 라이브러리 방식 등을 이용하여\) 허용할 것 등이다. i\) ~ v\)의 내용은 GPL  
2.0과 동일하거나 유사하지만, vi\) ~ vii\)은 LGPL에 특유한 내용이다.

**\[프로젝트 사례\] GNU C Library**  
LGPL로 배포되는 대표적인 프로젝트는 GNU C Library 또는 glibc이다. glibc는 GNU  
프로젝트에서 배포되는 C 표준 라이브러리이다. 1980년대부터 FSF에서 만들어 배포하기  
시작했는데, 1990년대 초반 리눅스 커널 개발자들이 glibc에서 분기\(fork\)된 별도의 Linux libc 프로젝트를 진행하였다. 그런데, FSF에서 1997년 POSIX 표준에 가깝고 다양한 기능을  
추가한 glibc 2.0을 배포하자 리눅스 커널 개발자들은 별도의 프로젝트를 포기하고 FSF의  
glibc에 합류하였다. 다만, glibc의 크기, 속도 등에 만족하지 못하는 오픈소스 개발자들을  
중심으로 지금도 별도의 프로젝트들이 진행되고 있다. 예를 들면, 안드로이드 플랫폼에서  
사용되는 Bionic\(BSD\)이 대표적이며, 이밖에 dietlibc\(GPL\), eglibc\(LGPL\), uClibc\(LGPL\),  
Newlib20\), Klibc\(GPL\) 등이 있다.

**2-4 Affero GPL**
BSD, Apache, GPL, LGPL, MPL, EPL 등 대다수의 오픈소스 라이선스들은 해당  
소프트웨어를 복제하여 ‘배포\(distribute\)’할 때 지켜야 하는 다양한 요구사항들을 규정하고  
있다. 이를 반대로 해석하면 해당 소프트웨어를 배포하지 않고 기업이 해당 오픈소스를  
내부적으로만 사용하거나 네트워크 서버 형태로 이용하고 있는 경우에는 라이선스에 따른  
의무사항들이 거의 없다는 점이다.  
오픈소스 라이선스의 이러한 한계에 대해 비판적인 견해를 가지고 있던 Affero  
프로젝트24\)는 기존의 GPL 라이선스를 변경하여 네트워크 서버에 의해 서비스를 제공하는  
경우에도 카피레프트 조항과 소스코드 제공 의무가 적용되도록 하였다. Affero GPL의  
의무사항은 GPL과 기본적으로 동일하다. 다만, 그 적용의 범위가 단순한 ‘배포’를 넘어서 네트워크 서버 형태로 소프트웨어를 이용하는 경우에도 적용된다는 점에 차이가 있다.   
대표적으로 CPAL과 APSL이 Affero GPL류 에 속한다.

**2-5 GPL Exceptions**  
여러 오픈소스 프로젝트들은 해당 프로젝트는 GPL로 배포되길 바라면서 이를 활용하여  
동작하는 프로그램들은 GPL의 copyleft 조항에서 자유로울 수 있도록, GPL 2.0의 2조를  
다소 완화한 조건으로 배포할 수 있도록 허락해주는 exception을 추가하기도 한다. 이는  
추가적인 제한 사항을 주는 것이 아니므로 GPL과도 호환된다.

**Bison Exception**  
Bison은 GNU 파서 생성기로, 정의된 문법을 처리하고 해석하여 C 코드로 만들어주는  
도구다. Bison의 주요 결과물\(Bison parser implementation file\)은 상당 부분 Bison의  
소스코드를 그대로 복사하여 skeleton 코드를 포함하게 된다. 일반적인 GPL이라면 이  
skeleton 코드에도 GPL이 적용되어야 하고, 이에 따라 bison 결과물인 C 파일과 이를  
사용하는 프로그램 모두 GPL이 적용되어, 사용자들이 bison 사용을 부담스러워할 수  
있다.  
이에 Bison에 예외 조항을 추가하여 Bison이 생성하는 소스코드에 대해서는 GPL 적용이  
되지 않도록 예외를 추가하였다.  
소스코드 내 GPL 라이선스 설명 아래 다음과 같은 문구가 있으면 Bison exception이  
적용되는 파일로 볼 수 있다.

**Classpath exception**  
GNU Classpath25\) 프로젝트는 자바 언어의 가상머신 및 컴파일러에서 사용되는 핵심  
클래스 라이브러리를 자유 소프트웨어로 대체하기 위한 프로젝트이다. 이를 널리 사용할  
수 있도록, GNU Classpath 등 Classpath exception이 적용된 수정하지 않은 core class  
library를 link하여 생성한 program은 GPL의 영향을 받지 않는다. 예를 들면, OpenJDK  
프로젝트에서 가상머신 자체는 GPL 2.0으로 배포하고, Class library와 가상머신 내의  
Public API로 노출되는 부분은 Classpath exception으로 배포하고 있다.  

**Autoconf exception **
GNU Autoconf26\)는 M4 매크로의 확장 패키지로, 소스코드 패키지들의 환경을 설정하는  
쉘 스크립트를 자동으로 생성한다. Autoconf는 GPL로 배포되며, configure.ac의 시스템  
정보를 입력받아, Autoconf의 일부분과 결합, configure 스크립트를 생성한다.  
이에 해당 configure 내에 autoconf의 일부가 포함될 수밖에 없음에도 해당 configure는  
GPL의 파생저작물이 되지 않도록 예외를 적용해주는 것이 autoconf exception이다.

| 라이선스의 특징 및 의무사항 | GPL 2.0 | GPL 3.0 | LGPL | AGPL 3.0 |
| :--- | :--- | :--- | :--- | :--- |
| 복제 배포 수정의 권한부여 | O | O | O | O |
| 배포시 라이선스 사본 첨부 | O | O | O | O |
| 저작권고지사항 또는Attribution고지사항 유지 | O | O | O | O |
| 배포시 소스코드 제공의무\(Reciprocity\)와 범위 | derivative work | work baseon theprogram | derivative work | derivative work |
| 조합 저작물\(Larger Work\)작성 및 타 라이선스 배포 허용 |  |  | O |  |
| 수정시 수정내용 고지 | O | O | O | O |
| 명시적 특허라이선스의 부여 |  | O |  | O |
| 라이선시가 특허소송 제기시 라이선스 종료 |  | O |  | O |
| 이름,상표,상호에 대한 사용제한 |  |  |  |  |
| 보증의 부인 | O | O | O | O |
| 책임의 제한 | O | O | O | O |


