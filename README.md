<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <title>맛집 소개</title>
  <style>
    body { font-family: sans-serif; margin: 0; background: #fafafa; }
    header { background: #ffcb6b; padding: 20px; text-align: center; font-weight: bold; font-size: 20px; }
    .container { padding: 20px; max-width: 900px; margin: auto; }
    .store-card { background: white; border-radius: 10px; padding: 15px; margin-bottom: 15px; border: 1px solid #ddd; display: flex; gap: 15px; }
    .img-box { width: 80px; height: 80px; background: #eee; border-radius: 10px; display: flex; align-items: center; justify-content: center; font-size: 40px;}
    .title { font-size: 1.1rem; font-weight: bold; margin-bottom: 5px; }
    .desc { font-size: 0.9rem; color: #444; }
  </style>
</head>
<body>

  <header>🍽️ 한양대 ERICA 근처 맛집 추천</header>

  <div class="container">

    <!-- 맛집 카드 1 -->
    <div class="store-card">
      <div class="img-box">🍜</div>
      <div>
        <div class="title">가게 이름 1</div>
        <div class="desc">이 가게의 간단한 설명이 들어갑니다.</div>
      </div>
    </div>

    <!-- 맛집 카드 2 -->
    <div class="store-card">
      <div class="img-box">🍖</div>
      <div>
        <div class="title">가게 이름 2</div>
        <div class="desc">이 가게의 간단한 설명이 들어갑니다.</div>
      </div>
    </div>

  </div>

</body>
</html>
