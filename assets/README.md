# assets 폴더

여기에 그림 파일을 넣습니다. **인터넷 없이도 돌아가야 하므로 외부 주소를 쓰지 않습니다.**

| 파일명 | 용도 | 권장 크기 |
|---|---|---|
| `gnmc_logo.png` | 경남수학문화관 로고 (왼쪽 위 흰 박스 안) | 높이 200px 이상, 투명 배경 |

> `gnmc_logo.png` 가 없으면 로고 박스는 **자동으로 숨겨집니다**(`onerror` 처리).
> 로고 원본을 이 폴더에 `gnmc_logo.png` 이름으로 올리기만 하면 바로 나타납니다.

무당벌레·배경·메달은 그림 파일 없이 **CSS로 직접 그렸기 때문에** 추가 에셋이 필요 없습니다.
폰트도 외부 링크를 쓰지 않습니다. 주아체(Jua)를 쓰려면 서브셋한 폰트 파일을 이 폴더에 넣고
`index.html` 의 `<style>` 맨 위에 아래를 추가하세요.

```css
@font-face {
  font-family: 'Jua Web';
  src: url('assets/Jua-subset.woff2') format('woff2');
  font-display: swap;
}
```
