/*
to fit in forumotion limit, replace
cour1 -> gks_1
cour2 -> gks_2
cour3 -> gks_3
cour4 -> gks_4
cour5 -> gks_5
cour6 -> gks_6
cour7 -> gks_7
*/
@media screen and (min-device-width: 1000px) { 


  @import url('https://fonts.googleapis.com/css?family=Nova+Mono');
  
  .cour4 {
    text-shadow:  1px 1px #aeaeae, 
                  2px 2px #aeaeae, 
                  3px 3px #aeaeae;
    font-size: 35px;
    color: black;
  }
  
  .cour1 {
    width: 550px;
    height: 300px;
    padding: 0px;
    margin: 0px;
    display: table;
    background-color: black;
  }
  
  .cour2 {
    width: 50px;
    height: 300px;
    display: table-cell;
    position: relative;
    
    transition: width 1s;
    -webkit-transition: width 1s;
  }
   .cour25 {
    max-width: 100%;
    height: auto;
    background-image: url('https://i.imgur.com/jlYCmpm.jpg?1');
    background-position: center;
    background-repeat: no-repeat;
    background-color: black;
  }
  .cour24 {
    max-width: 100%;
    height: auto;
    background-image: url('https://i.imgur.com/Hq8VqMT.jpg?1');
    background-position: center;
    background-repeat: no-repeat;
    background-color: black;
  }
  .cour23 {
    max-width: 100%;
    height: auto;
    background-image: url('https://i.imgur.com/ST6s9ht.jpg?1');
    background-position: center;
    background-repeat: no-repeat;
    background-color: black;
  }
  .cour22 {
    max-width: 100%;
    height: auto;
    background-image: url('https://i.imgur.com/jlYCmpm.jpg?1');
    background-position: center;
    background-repeat: no-repeat;
    background-color: black;
  }
  .cour21 {
    max-width: 100%;
    height: auto;
    background-image: url('https://i.imgur.com/iUYeqxE.jpg?1');
    background-position: center;
    background-repeat: no-repeat;
    background-color: black;
  }
  
  .cour1:not(:hover) > .cour21 {
    width: 400px;
  }
  
  .cour2:hover {
    width: 400px;
  }
  
  
  
  .cour5 {
    position: absolute;
    height: 200px;
    width: 150px;
    top: 50px;
    left: 10px;
    
    opacity: 0;
    transition: opacity 1s;
  }
  .cour51 {
    left: 200px;
  }
  .cour52 {
  }
  .cour53 {
    height: 50px;
    top: 5px;
  }
  .cour54 {
    height: 50px;
    top: 220px;
  }
  .cour2:hover > .cour5:not(:hover), .cour2:hover > a > .cour5:not(:hover) {
    opacity: .4;
  }
  .cour5:hover {
    opacity: 1;
  }
  .cour1:not(:hover) > .cour21 > .cour5 {
    opacity: .4
  }
  
  
  .cour7 {
    width: 75px;
    margin-left: auto;
    margin-right: auto;
    position: relative;
    top: 50%;
    transform: translateY(-50%);
    text-align: center;
    
    font-size: 20;
    font-family: 'Nova Mono', monospace;
    
    color: white;
      text-shadow: -1px -1px 0 #000,
                   1px -1px 0 #000,
                   -1px 1px 0 #000,
                   1px 1px 0 #000;
  }
  
  .cour6 {
    background-color: #00ffcc;
    transition: background-color 1s, opacity 1s;
    
    -moz-border-radius: 100px / 50px;
    -webkit-border-radius: 100px / 50px;
    border-radius: 150px / 50px;
  }
  .cour6:hover {
    background-color: #00ffcc;
  }
  
  
  
  .cour3 {
    position: absolute;
    bottom: 3px;
    right: 3px;
    
    
    white-space: nowrap;
    
    
    transform-origin: bottom right;
    -webkit-transform-origin: bottom right;
    -moz-transform-origin: bottom right;
    -o-transform-origin: bottom right;
    -ms-transform-origin: bottom right;
    
    transform: rotate(-90deg) translateX(100%);
    -webkit-transform: rotate(-90deg) translateX(100%);
    -moz-transform: rotate(-90deg) translateX(100%);
    -o-transform: rotate(-90deg) translateX(100%);
    -ms-transform: rotate(-90deg) translateX(100%);
  }
  .cour2:hover > .cour3 {
    animation: courrotateBack .5s ease-in-out 1;
    animation-fill-mode: forwards;
    
    -webkit-animation: courrotateBack .5s ease-in-out 1;
    -webkit-animation-fill-mode: forwards;
    
    -moz-animation: courrotateBack .5s ease-in-out 1;
    -moz-animation-fill-mode: forwards;
    
    -o-animation: courrotateBack .5s ease-in-out 1;
    -o-animation-fill-mode: forwards;
    
    -ms-animation: courrotateBack .5s ease-in-out 1;
    -ms-animation-fill-mode: forwards;
  }
  
  @keyframes courrotateBack {	100% { transform: rotate(0deg) translateX(0%) translateY(0%); } }
  @-webkit-keyframes courrotateBack {	100% { -webkit-transform: rotate(0deg) translateX(0%) translateY(0%); } }
  @-moz-keyframes courrotateBack {	100% { -moz-transform: rotate(0deg) translateX(0%) translateY(0%); } }
  @-o-keyframes courrotateBack {	100% { -o-transform: rotate(0deg) translateX(0%) translateY(0%); } }
  @-ms-keyframes courrotateBack {	100% { -ms-transform: rotate(0deg) translateX(0%) translateY(0%); } }
  
}

@media screen and (max-device-width: 999px) {
  .cour1::before {
    content: "Signature super simplified due to the possibility of this being a mobile device! Sorry it's ugly now!"
  }
}
