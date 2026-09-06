# kawpolmoney/smartstore-images

사심콜렉트 상품 이미지. jsDelivr 로 서빙.

- `main/<상품코드>.jpg` 대표이미지(누끼)
- `set/<상품코드>_<수량>.jpg` 묶음 세트컷 (ESM)
- `extra/<상품코드>/n.jpg` 추가이미지
- `detail/<상품코드>/` 상세이미지 재호스팅분
- `spec/<상품코드>.jpg` 스펙카드 · `common/` 공통

갱신: `node src/pipeline/git-upload.js`
