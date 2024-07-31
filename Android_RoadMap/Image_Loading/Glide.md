# Glide - Image_Loading

<br>

* 가장 인기가 있는 이미지 로딩 라이브러리 중 하나임
* 해당 라이브러리는 다른 라이브러리들과 다르게 지원을 하는 기능들이 압도적으로 많음
* Animated GIF 지원, placeholders, transformations, caching, 및 리소스 재사용과 같은 유용한 기능이 있음
* 해당 라이브러리의 주된 목적은 다양한 종류의 이미지를 가져와 이미지 목록을 가능한 부드럽고 빠르게 스크롤을 할 수 있게 하는 것임
* 하지만 원격 이미지를 가져오고, 이미지 크기 조정, 표시를 해야하는 경우들에서 효과적일 수 있음
* 성능적으로는 두 가지 핵심적인 측면이 있는데 이미지를 디코딩 할 수 있는 속도, 이미지를 디코딩하는 동안 발생하는 끊김 현상의 양임
* 해당 라이브러리는 안드로이드에서 위과 같은 이미지 로딩이 가능한 빠르고, 원할하게 진행되도록 여러 단계를 따르게 됨
  * 스마트하고 자동화된 다운샘플링 및 캐싱으로 저장 오버헤드와 디코딩 시간을 최소함
  * 바이트 배열 및 비트맵과 같은 리소스를 적극적으로 재사용하면 비용이 많이 드는 가비지 수집 및 힙 조각화가 최소화 됨
  * 심층적인 라이프사이클 통합을 통해 활성 프래그먼트와 액티비티에 대한 요청만 우선순위가 지정됨
  * 애플리케이션이 백그라운드에서 종료되는 것을 방지하기 위해 필요할 때 리소스를 해제함