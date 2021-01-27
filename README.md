# GitHub Clone Coding

## 깃허브 클론 코딩

---

GitHub 메인 화면을 clone conding 한 것 입니다.

> 해당 프로젝트는 HTML / CSS / Vanilla JS 로만 작성 되었습니다.

- 768px 이하 일 때 nav 및 input 태그 모두 반응형

- 모바일 사이즈에서 nav 바의 메뉴 버튼 활성/비활성 가능

- Google Map API 사용

```css
<script>
    function initMap() {
        const myLatLng = {
            lat: 37.782293,
            lng: -122.391240
        }
        const map = new google.maps.Map(
            document.getElementById('map'),
            {
                center: myLatLng,
                scrollwheel: false,
                zoom: 18
            }
        );
        const marker = new google.maps.Marker({
            position: myLatLng,
            map: map,
            title: 'GitHub'
        });
    }
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCTQIlxBn5AfKGvsfJiormAE1esN3fcCkg&callback=initMap" async defer></script>
```

### 768px 이하 (태블릿, 모바일)

![github3](https://user-images.githubusercontent.com/60214107/105949272-c6748380-60af-11eb-94d6-286c9bd73a46.PNG)
![github4](https://user-images.githubusercontent.com/60214107/105949276-c7a5b080-60af-11eb-9c6e-b92d44a93a16.PNG)
![github2](https://user-images.githubusercontent.com/60214107/105949440-09cef200-60b0-11eb-9480-60763737033a.PNG)
![github7](https://user-images.githubusercontent.com/60214107/105949839-bad58c80-60b0-11eb-8474-fcf73e4668ae.PNG)

### 768px ~ 1024px (모니터)

![github1](https://user-images.githubusercontent.com/60214107/105949278-c83e4700-60af-11eb-9377-08da79fe3ac1.PNG)
![github5](https://user-images.githubusercontent.com/60214107/105949609-4995d980-60b0-11eb-9737-60e733be149b.PNG)
![github6](https://user-images.githubusercontent.com/60214107/105949613-4b5f9d00-60b0-11eb-801b-98c55eb53c58.PNG)

> 해당 프로젝트는 **패스트캠퍼스 전웅재 강사님** 의 미니 프로젝트를 클론 코딩한 것입니다.

> 구글맵 인증도 **패스크 캠퍼스 전웅재 강사님** 의 인증 코드를 사용하였습니다.
