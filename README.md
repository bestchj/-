<!DOCTYPE html>

<html>

<title>상대경로와 절대경로에 대한 이해</title>

<body>

 

<h1>The img element</h1>

  

<!--html파일과 같은 폴더 안에 있어야 이미지가 보여집니다. -->

<img src="smiley.gif" alt="Smiley face" width="42" height="42">

  

<p>상대경로</p>

  <a href="../smiley.gif" download>

      <img src="../smiley.gif" alt="Smiley face" width="42" height="42">

  </a>

 

<p>절대경로</p>

<!--github의 개인 URL로 테스트 해보세요 -->

 <img src="https://dbeod.github.io/web1/smiley.gif">

 

 

</body>

</html>
