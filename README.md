# netflixMockDesign
*{
  margin: 0;

}
body{
  background-color: black;
}
.mainWrap {
  position: relative;
  background-color: black;
  height: 100vh;
}

.mainWrap:before {
  content: ' ';
  display: block;
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  opacity: 0.5;
  background-image: url(netflixBackground.jpg);
  background-repeat: no-repeat;
  background-position: left;
  background-size: cover;
}

.wrapContent {
  position: relative;
  height: 100%;
}

nav{
  width: 100%;
  height: 75px;
}