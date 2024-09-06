
# ABCD Market 

**[뱃지나 프로젝트에 관한 이미지들이 이 위치에 들어가면 좋습니다]**  
One Paragraph of project description goes here / 프로젝트의 전반적인 내용에 대한 요약을 여기에 적습니다


## ⚙ Organization

|    역할   |           Name           | 
|  :-----: | :----------------------: | 
|    팀장   | <center> 노민철  </center> |
|    팀원   | <center> **이원영** </center> | 
|    팀원   | <center> 이종남  </center> |
|    팀원   | <center> 한재영  </center> |

### Packages / 사용한 패키지

```
  get: ^4.6.6
  sqflite: ^2.3.3+1
  path: ^1.9.0
  image_picker: ^1.1.2
  get_storage: ^2.1.1
  syncfusion_flutter_charts: ^26.2.11
  tab_indicator_styler: ^2.0.0
  table_calendar: ^3.1.2
```

## Running the tests / 테스트의 실행

어떻게 테스트가 이 시스템에서 돌아가는지에 대한 설명을 합니다

### ABC Market Clone 코딩

```
소비자는 앱을 통해 수령할 지점과 상품을 결정하여 구매
구매한 신발은 해당 지점에서 키오스크를 통해 수령
신발들의 판매 현황을 보는 관리자 페이지 구현
```

## Built With 
* [노민철]((https://github.com/nnmmnn15))
  - 키오스크 구현, 현황 웹 페이지 구현, 로직 수정,
    
  View
 
  View Model
  - /purchase_handler/queryPurchasedetail(),
  - /purchase_handler/queryPurchasedetail(),


* [이원영](https://github.com/Leewonyooung)
  - 탭바를 활용한 앱의 전체적인 ui, 신발 전체 리스트, 검색 페이지 및 내 정보 페이지
 
  View

  View Model
  - /purchase_handler/insertPurchase(),
  - /shoes_market_app/lib/vm/transport_handler.dart
  - /shoes_market_app/lib/vm/product_handler.dart
 
    
* [이종남](https://github.com/LeeJongNam7)
  - 현황 웹페이지 구현, 앱 주문 상세 페이지 구현

  View
  - /
  View Model
  - /
  - 
* [한재영](https://github.com/hanjaeng)
   - 앱 로그인, 구매내역 페이지, customer_handler 구현
     
   View Model
   - /shoes_market_app/lib/vm/customer_handler.dart
 
   View
   - /shoes_market_app/lib/view/login.dart
   - /shoes_market_app/lib/view/order.dart

