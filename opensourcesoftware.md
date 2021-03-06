# 인기있는 오픈소스 소프트웨어

---

지금까지 오픈소스의 정의, 역사, 장단점, 라이선스에 대하여 알아보았다. 여기에서는 대표적인 오픈소스 소프트웨어에 대해서 알아볼 것이다. 현재 2018년을 기준으로 각 분야별 인기있는 소프트웨어에 대하여 설명한다. 여기에선  빅데이터, 소프트웨어 개발, 머신러닝, 총 세가지 분야로 나누어서 소개 할 예정이다.

---

### 빅데이터

![](/assets/apache spark.jpg)

**아파치 스파크\(Apache Spark\)**

멋진 소프트웨어가 많이 등장했지만 아파치 스파크는 여전히 데이터 애널리틱스 세계의 중심이다. 분산 컴퓨팅, 데이터 과학, 또는 머신러닝하려면 아파치 스파크로 시작하라. 2월 아파치 스파크 2.3이 출시되면서 스파크는 구조화 스트리밍 API를 지속적으로 개발하고 통합하고 개선했다. 아울러 쿠버네티스 스케줄러가 새롭게 추가되어 이 컨테이너 플랫폼 상에서 스파크를 직접 실행하기가 더욱 쉬워졌다. 전반적으로, 현재의 스파크 버전은 다듬어지고 조율되고 크롬 도금까지 입힌 느낌이다.

![](/assets/apachepulsar.jpg)  
**아파치 펄사\(Apache Pulsar\)**  
아파치 펄사는 야후가 개발했고 현재 아파치 프로젝트로 육성 중이다. 아파치 카프카가 여러 해 동안 차지했던 메시징의 왕좌를 노리고 있다. 여러 상황에서 아파치 카프카보다 더 빠른 입출력과 더 낮은 지연시간의 가능성을 제시하고, 개발자가 카프카에서 펄사로 비교적 손쉽게 전환할 수 있는 호환성 API를 갖추었다. 그러나 아파치 펄사의 최대의 장점은 아파치 카프카보다 훨씬 더 간소하고 견고한 운용 기능들을 제공한다는 점일 것이다. 관측성, 원거리 복제, 멀티 테넌시 문제의 처리 측면에서 특히 그렇다. 거대한 아파치 카프카 클러스터를 운영하며 힘겨워했던 기업이라면 아파치 펄사로 한숨 돌릴 수 있을 것이다.

![](/assets/jupyter.jpg)  
**주피터랩\(JupyterLab\)**  
주피터랩은 데이터 과학자라면 누구나 선호했던 유서 깊은 웹 기반 노트북 서버인 주피터\(Jupyter\)의 차세대 버전이다. 완성까지 3년이 걸린 주피터랩은 노트북 개념을 완전히 일신했다. 드래그 앤 드롭에 의한 셀 정리, 탭 노트북, 마크다운 편집의 라이브 프리뷰가 가능하고, 깃허브 같은 다른 서비스와의 통합을 용이하게 하는 개량된 확장 프로그램 시스템을 갖추었다. 2018년 말쯤이면 안정적인 1.0 릴리즈가 나올 것으로 예상되고, 2019년에 접어들면 데이터 과학은 좀 더 진화할 것이다.

![](/assets/knime.jpg)  
**KNIME 애널리틱스 플랫폼\(KNIME Analytics Platform\)**  
KNIME 애널리틱스 플랫폼은 데이터 과학 애플리케이션 및 서비스를 생성하는 오픈소스 소프트웨어이다. 비주얼 워크플로우를 생성하기 위한 드래그 앤 드롭 방식의 그래픽 인터페이스를 갖추었고, R 및 파이썬에 의한 스크립팅, 머신러닝, 아파치 스파크로의 커넥터를 지원한다. KNIME는 워크플로우에서 노드로 쓰일 수 있는 약 2,000개의 모듈을 가지고 있다. KNIME의 상용 버전도 있다. 여기에는 생산성을 증대하고 협업을 지원하는 확장 프로그램이 추가된다. 그렇다고 해서, 오픈소스 KNIME 애널리틱스 플랫폼에 인위적 제한이 있는 것은 아니고, 수억 줄에 이르는 프로젝트도 처리할 수 있다.

### 소프트웨어 개발

![](/assets/truffle.jpg)  
**트러플 프레임워크\(Truffle Framework\)**  
스마트 계약은 적절한 툴이 없을 때 개발하기가 매우 복잡하고 진행 속도도 더디다. 다행히도 트러플 프레임워크는 스마트 계약을 개발 및 테스트해 이더리움\(Ethereum\) 블록체인에 배치하기 위한 트러플\(Truffle\), 가니쉬\(Ganache\), 드리즐\(Drizzle\) 등 일련의 툴을 제공한다. 트러플 CLI는 구성 가능한 다양한 템플릿을 사용해 스마트 계약 프로젝트를 스스로 수행하고 배치할 수 있도록 도와주며, 이후에 구동하고 가니쉬가 제공하는 로컬 이더리움 블록체인에 대해 테스트할 수 있다. 리덕스\(Redux\) 스토어와의 인터랙션만큼 계약 인터랙션을 간소화하는 자바스크립트 라이브러리인 드리즐을 사용해 새롭게 배치된 계약과 인터랙션하는 UI를 구축한다. 이더리움을 개발할 계획이라면 트러플이 정답이다.

![](/assets/blockstack.jpg)  
**블록스택\(Blockstack\)**  
이더리움에 관한 성능 및 스케일링 소식을 지속적으로 구독하지 않고 블록체인 기반의 DApp를 작성할 수 있다면 얼마나 좋을까? 비트코인 블록체인에서 앱을 개발하기 위해 개발된 일련의 애플리케이션 개발 툴인 블록스택\(Blockstack\)에 주목하자. 블록스택에서의 앱 개발 역학은 표준 웹사이트 개발과 유사하기 때문에 많은 개발 원칙을 모방할 수 있다. 하지만 일반적으로 유사성은 거기까지이다. 사용자는 비트코인 블록체인에서 전사되고 자신이 제어하는 하나의 분산 ID를 사용해 어느 블록스택 앱에서나 인증한다. 문서, 채팅 이력, 팟캐스트 구독 등의 애플리케이션 데이터는 앱 개발자의 저장소에 저장되지 않는다. 대신에 모든 애플리케이션 데이터를 개발자가 액세스 및 제어할 수 없는 자신이 선택한 개인용 저장소에 보관한다. 블록스택을 이용한 개발을 시작하고 자신의 행위가 지속적으로 모니터링되지 않는 기분을 느껴보자.

![](/assets/visualstudiocode.jpg)  
**비주얼 스튜디오 코드\(Visual Studio Code\)**  
비주얼 스튜디오 코드를 간소화된 IDE나 강화된 텍스트 편집기라고 말하기 어렵다. 어쨌든 모든 개발자의 가려운 곳을 시원하게 긁어주고 있는 것으로 보인다. 초기에는 프론트 엔드 개발에 치중했지만 언어 지원이 확대되어 루비\(Ruby\), 고\(Go\), C/C++, 파이썬도 포함되었다. 인텔리센스\(IntelliSense\), 린팅\(linting\), 깃\(Git\) 통합 등의 기능 외에 비주얼 스튜디오 코드는 풍부한 커뮤니티 개발 확장기능 생태계도 지원한다. 풍부한 기능, 교차 플랫폼 지원, 누구나 확장기능을 개발할 수 있는 역량 때문에 많은 개발자가 좋아한다. 심지어 보수적인 빔\(Vim\) 사용자도 뛰어들고 있다.

![](/assets/dotnetcore.jpg)  
**닷넷 코어\(.Net Core\)**  
닷넷 코어의 가능성은 그 이름에서 알 수 있듯이, 닷넷 API의 기본으로 간소화된 하위 세트이다. 닷넷 코어는 플랫폼을 초월하는 방식으로 폭넓은 참여를 바탕으로 오픈소스 프로젝트를 통해 필요한 것만 제공한다. 닷넷 코어의 매력은 간결함과 유연함에 있으며, 필요에 따라 간소화하거나 확장할 수 있다. 닷넷 코어 2에서 지원되는 윈도우 호환성 팩은 닷넷 프레임워크와의 완전한 호환성을 추가한다\(2만 개 이상의 API\). 닷넷 코어 2 역시 더 나은 성능과 독립\(self-contained\) 애플리케이션 퍼블리싱을 위한 더 적응성이 좋은 닷넷 JIT\(just-in-time\) 컴파일러 사용을 도입하여 앱을 필요한 런타임의 자체 버전과 묶을 수 있다.

![](/assets/rust.jpg)  
**러스트\(Rust\)**  
이제 러스트가 C와 C++를 초월한 다음 단계라는 이야기는 귀에 못이 박히게 들었을 것이다. 그래도 해야 한다. 러스트 프로그램은 기기 본연의 속도로 구동하며 그 어느 때보다도 방대한 서드파티 라이브러리 생태계에 의존하고 안전 및 무결성을 우선시한다. 러스트는 미래 지향적이고 실용적이다. 동시 실행, 수집, 메모리 안전, 재사용 가능한 모듈 등의 현대적인 개념과 함께 여러 프로그래밍 스타일\(명령식, 기능, 객체 지향\)을 지원한다. 그리고 러스트는 웹어셈블리\(WebAssembly\)로의 컴파일링 기본 지원부터 러스트 버전들 사이에서 마이그레이션할 때 새로운 언어 기능을 더욱 잘 활용할 수 있도록 코드를 자동으로 재작성하는 러스트픽스\(rustfix\) 등의 툴까지 다양한 언어 본연의 개발자 유틸리티를 보유하고 있다.

### 딥 러닝

![](/assets/tensorflow.jpg)  
**텐서플로우\(TensorFlow\)**  
보편화된 딥러닝용 신경망 프레임워크는 5차례의 버전 업그레이드가 이루어지면서 더 쉽고 강력해졌다. 주요 신기능 및 개선으로는 데이터 소스인 구글 클라우드 빅테이블의 통합, 향상된 tf.kera 모듈, 모바일 기기에 최적화된 모델 생성, 개선된 데이터 로딩 및 텍스트 처리, GPU 메모리로의 데이터 프리페칭, 개선된 구글 클라우드 TPU 사용 성능, 즉시 실행\(eager execution\) 모드의 전적인 지원 상태로의 격상 등이 있다. 즉시 실행은 그래프를 구축한 후 실행하는 것보다 더 이해하기 쉬운 명령형 프로그래밍 스타일을 제공한다.

![](/assets/keras.jpg)  
**케라스\(Keras\)**  
케라스는 심층 신경망 프레임워크를 가능한 한 단순화시켰다. 계층당 1줄의 파이썬 코드, 그리고 순차 모델을 이용하며 모델을 컴파일하고 훈련시키는 데 각각 1회의 호출이면 충분하다. 함수형 API를 통해 임의 토폴로지\(arbitrary topologies\) 역시 지원한다. 텐서플로우, 테아노, CNTK2를 백엔드로 이용하고, 이에 의해 GPU를 원활하게 지원한다\(그리고 텐서플로우를 이용한 구글 클라우드 상의 TPU\). 케라스는 훈련 시 넘피 배열\(Numpy arrays\)을 입력으로 이용하지만, 파이썬 제너레이터 인터페이스를 통해 다른 포맷도 지원할 수 있다. 클라우드 서비스로부터 모바일 기기에 이르기까지 다채로운 배치 옵션을 제공한다.

![](/assets/Pytorch.jpg)  
**파이토치\(PyTorch\)**  
파이토치는 파이썬을 스크립트 언어로 이용하는 고급 심층 신경망이고, 진화된 토치 C/CUDA 백엔드를 이용한다. 카페2\(Caffe2\)의 프로덕션 기능들 역시 파이토치 프로젝트에 통합되었다. 파이토치는 다이내믹 신경망을 특징으로 하고, 이는 네트워크 토폴로지 자체가 훈련 중의 이터레이션에 따라 변할 수 있다는 의미이다. 정적 네트워크보다 디버깅이 더 수월하고 이터레이션이 더 빠른 다이내믹 네트워크를 위해 파이토치 프로그램은 프로그램 실행 중에 그래프를 생성한다. 그 후 백프로퍼게이션\(backpropagation\)이 동적으로 생성된 그래프를 이용하면서 그라디언트\(gradients\)를 저장된 텐서 상태로부터 자동으로 계산한다. 파이토치는 성숙한 토치 프레임워크 상에서 구축되었으므로 이미 강력한 신경망 계층, 최적화 알고리즘, 손실 함수를 보유하고 있다.

![](/assets/Fastai.jpg)  
**Fast.ai**  
Fast.ai는 딥러닝 MOOC일뿐 아니라 파이토치 상에 구축된 딥러닝 라이브러리이기도 하다. Fast.ai 프레임워크는 모델을 구축하고 훈련시키기 위한 일관되고 확고한 래퍼\(wrappers\)를 제공하고, 아울러 딥러닝 모델을 훈련시키는 최첨단 기법을 일부 통합시키기도 했다\(순환 학습 속도 및 NLP 문제 분야에 대한 전이 학습 기법 등\). 다시 말해 Fast.ai는 캐글 대회 및 실제 프로덕션 애플리케이션을 위한 모델을 구축하는데 유용하다. 무엇보다, 이는 아마 딥러닝 세계로 들어가는 가장 쉬운 길일 것이다.

