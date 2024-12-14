<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <style>
        *{
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            color: #575656;
        }
        div.interactive{
            width: 640px;
           height: 1200px;
            border-radius: 94px;
            background-color: #f5f5f5;
            padding:10px;
        }
        h1{
            font-size: 40px;
            margin:30px; 
            margin-top:40px;
        }
        h2{
            font-weight: normal;
            font-size: 30px;
            margin-top:-20px;
        }
        div.question{
            width:240px;
            height:300px;
            background-color:#CECECE;
            border-radius: 60px;
            margin: auto;
            padding: 20px;    
            margin-inline: 15px;   
            margin-bottom: 20px;   
            display:inline-block;
            float: left;
            align-content: center;

        }
        button{
            border: 0px;
        }
        button.ans{
            width:220px;
            height: 90px;
           border-radius: 10px;
           background-color: #F5F5F5;
           align-content: center;
           display:inline-block;
           float:right;
           margin: 10px;

        }
        p{
            font-size: 30px;
            display:block ;
        }

        button.cir{
            width: 90px;
            height: 90px;
            border-radius: 90px;
            align-content: inline-block;
            float:inherit;
            margin-left:20px;
        }
        div.play{
            align-content: center;
            width: 20px;
            margin:15px;
            height:auto;
            margin-top: 15px;
        }
        .cir:hover{
            opacity:0.75;
        }
        .ans:hover{
            background-color: rgba(228, 228, 228, 0.945);
        }
        .aud{
            
        }
       #q1{
        .cir{ 
            background-color: #9C6BFF;}
        }
        #q2{
        .cir{ 
            background-color: #F58027;}
        }
        #q3{
        .cir{ 
            background-color: #D82FC1;}
        }
        #q4{
        .cir{ 
            background-color: #4867FF;}
        }
       span{
          font-size: 22px;
          font-weight: bold;
          line-height: 22px;
         }
     @media screen and (max-width: 540px) {
        div.interactive{
            width: 480px;   
            height:1800px;
        }
        div.question{
                display:inline-block;
                width: 300px;
                align-items: center;
                align-content: center;
                margin-inline: 80px;
            }
        button.cir{
            margin-inline-start: 40px;
        }
        button.ans{
            width:290px;
            margin: 10px;
         }
         }
    </style>
<audio id="q1mustango" src="q1mustango.wav"></audio>
<audio id="q1real" src="q1real.wav"></audio>
<audio id="q2real" src="q2real.wav"></audio>
<audio id="q2suno" src="q2suno.wav"></audio>
<audio id="q3real" src="q3real.wav"></audio>
<audio id="q3mgm" src="q3mgm.wav"></audio>
<audio id="q4mldm" src="q4mldm.wav"></audio>
<audio id="q4real" src="q4real.wav"></audio>
<div class="interactive">
    <h1>
        Can you tell which music is AI?
    </h1>
    <h2>Play the two audio samples<br> and decide which clip sounds AI-generated</h2>
    <div class="question" id="q1">
            <button class="cir" id="q1aud1" >
                <div id="play1" class="play">
                    <svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 80.001 80">
                        <path id="play1" data-name="Subtraction 1" d="M-729.95-300.26a16.6,16.6,0,0,1-5.658-.989,15.55,15.55,0,0,1-4.806-2.762,12.488,12.488,0,0,1-4.586-9.6v-53.3a12.488,12.488,0,0,1,4.587-9.6,15.552,15.552,0,0,1,4.806-2.762,16.6,16.6,0,0,1,5.658-.99,16.439,16.439,0,0,1,7.711,1.926l49.956,26.648A13,13,0,0,1-665-340.26a13,13,0,0,1-7.283,11.426l-49.956,26.648A16.441,16.441,0,0,1-729.95-300.26Zm11.464-50.259V-318h9.229v-42.95h-5.6a38.872,38.872,0,0,1-5.772,3.6,38.632,38.632,0,0,1-6.8,2.7v7.793a17.991,17.991,0,0,0,2.49-.483,19.992,19.992,0,0,0,2.432-.821,18.637,18.637,0,0,0,2.211-1.084,11.1,11.1,0,0,0,1.8-1.273Z" transform="translate(745 380.26)" fill="#FFFFFF" opacity="0.75"/>
                      </svg>                      
                </div>
            </button>
            <button class="cir" id="q1aud2">
                <div class="play">
                <svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 80.001 80">
                    <path id="Subtraction_1" data-name="Subtraction 1" d="M-729.95-300.26a16.6,16.6,0,0,1-5.658-.989,15.55,15.55,0,0,1-4.806-2.762,12.488,12.488,0,0,1-4.586-9.6v-53.3a12.488,12.488,0,0,1,4.587-9.6,15.552,15.552,0,0,1,4.806-2.762,16.6,16.6,0,0,1,5.658-.99,16.439,16.439,0,0,1,7.711,1.926l49.956,26.648A13,13,0,0,1-665-340.26a13,13,0,0,1-7.283,11.426l-49.956,26.648A16.441,16.441,0,0,1-729.95-300.26Zm11.141-53.072a6.8,6.8,0,0,1,4.658,1.377,5.235,5.235,0,0,1,1.524,4.072,7.175,7.175,0,0,1-.469,2.592,9.121,9.121,0,0,1-1.421,2.4,18.521,18.521,0,0,1-2.344,2.388c-.93.8-2.019,1.649-3.237,2.519-1.169.838-2.416,1.789-3.706,2.827a23.79,23.79,0,0,0-3.589,3.6,19.315,19.315,0,0,0-2.724,4.6,14.8,14.8,0,0,0-1.084,5.786V-318h27.949v-7.676h-17.812a3.226,3.226,0,0,1,.586-1.729,10.61,10.61,0,0,1,1.581-1.86,25.842,25.842,0,0,1,2.3-1.933c.853-.642,1.765-1.308,2.71-1.977,1.381-.953,2.731-1.954,4.013-2.974a21.639,21.639,0,0,0,3.414-3.384,15.884,15.884,0,0,0,2.372-4.1,13.984,13.984,0,0,0,.894-5.157,12.761,12.761,0,0,0-.922-4.936,10.239,10.239,0,0,0-2.681-3.765,12.181,12.181,0,0,0-4.291-2.388,18.364,18.364,0,0,0-5.728-.834,22.362,22.362,0,0,0-12.363,3.545v8.144A15.713,15.713,0,0,1-718.808-353.332Z" transform="translate(745 380.26)" fill="#FFFFFF" opacity="0.75"/>
                  </svg>    
                </div>              
            </button>    
        <button class="q1 ans right" id="q1a1" onclick="questionOne()">
            <span class="q1a1">Sample 1</span>
        </button>
        <button class="q1 ans wrong" id="q1a2" onclick="questionOne()">
            <span class="q1a2">Sample 2</span>
        </button>
    </div>
    <div class="question" id="q2">
        <button class="cir" id="q2aud1">
            <div id="play1" class="play">
                <svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 80.001 80">
                    <path id="play1" data-name="Subtraction 1" d="M-729.95-300.26a16.6,16.6,0,0,1-5.658-.989,15.55,15.55,0,0,1-4.806-2.762,12.488,12.488,0,0,1-4.586-9.6v-53.3a12.488,12.488,0,0,1,4.587-9.6,15.552,15.552,0,0,1,4.806-2.762,16.6,16.6,0,0,1,5.658-.99,16.439,16.439,0,0,1,7.711,1.926l49.956,26.648A13,13,0,0,1-665-340.26a13,13,0,0,1-7.283,11.426l-49.956,26.648A16.441,16.441,0,0,1-729.95-300.26Zm11.464-50.259V-318h9.229v-42.95h-5.6a38.872,38.872,0,0,1-5.772,3.6,38.632,38.632,0,0,1-6.8,2.7v7.793a17.991,17.991,0,0,0,2.49-.483,19.992,19.992,0,0,0,2.432-.821,18.637,18.637,0,0,0,2.211-1.084,11.1,11.1,0,0,0,1.8-1.273Z" transform="translate(745 380.26)" fill="#FFFFFF" opacity="0.75"/>
                  </svg>                      
            </div>
        </button>
        <button class="cir" id="q2aud2">
            <div class="play">
            <svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 80.001 80">
                <path id="Subtraction_1" data-name="Subtraction 1" d="M-729.95-300.26a16.6,16.6,0,0,1-5.658-.989,15.55,15.55,0,0,1-4.806-2.762,12.488,12.488,0,0,1-4.586-9.6v-53.3a12.488,12.488,0,0,1,4.587-9.6,15.552,15.552,0,0,1,4.806-2.762,16.6,16.6,0,0,1,5.658-.99,16.439,16.439,0,0,1,7.711,1.926l49.956,26.648A13,13,0,0,1-665-340.26a13,13,0,0,1-7.283,11.426l-49.956,26.648A16.441,16.441,0,0,1-729.95-300.26Zm11.141-53.072a6.8,6.8,0,0,1,4.658,1.377,5.235,5.235,0,0,1,1.524,4.072,7.175,7.175,0,0,1-.469,2.592,9.121,9.121,0,0,1-1.421,2.4,18.521,18.521,0,0,1-2.344,2.388c-.93.8-2.019,1.649-3.237,2.519-1.169.838-2.416,1.789-3.706,2.827a23.79,23.79,0,0,0-3.589,3.6,19.315,19.315,0,0,0-2.724,4.6,14.8,14.8,0,0,0-1.084,5.786V-318h27.949v-7.676h-17.812a3.226,3.226,0,0,1,.586-1.729,10.61,10.61,0,0,1,1.581-1.86,25.842,25.842,0,0,1,2.3-1.933c.853-.642,1.765-1.308,2.71-1.977,1.381-.953,2.731-1.954,4.013-2.974a21.639,21.639,0,0,0,3.414-3.384,15.884,15.884,0,0,0,2.372-4.1,13.984,13.984,0,0,0,.894-5.157,12.761,12.761,0,0,0-.922-4.936,10.239,10.239,0,0,0-2.681-3.765,12.181,12.181,0,0,0-4.291-2.388,18.364,18.364,0,0,0-5.728-.834,22.362,22.362,0,0,0-12.363,3.545v8.144A15.713,15.713,0,0,1-718.808-353.332Z" transform="translate(745 380.26)" fill="#FFFFFF" opacity="0.75"/>
              </svg>    
            </div>              
        </button>    
    <button class="ans" id="q2a1" onclick="questionTwo()">
        <span class="q2a1">Sample 1</span>
    </button>
    <button class="ans" id="q2a2" onclick="questionTwo()">
        <span class="q2a2">Sample 2</span>
    </button>
</div>
<div class="question" id="q3">
    <button class="cir" id="q3aud1">
        <div id="play1" class="play">
            <svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 80.001 80">
                <path id="play1" data-name="Subtraction 1" d="M-729.95-300.26a16.6,16.6,0,0,1-5.658-.989,15.55,15.55,0,0,1-4.806-2.762,12.488,12.488,0,0,1-4.586-9.6v-53.3a12.488,12.488,0,0,1,4.587-9.6,15.552,15.552,0,0,1,4.806-2.762,16.6,16.6,0,0,1,5.658-.99,16.439,16.439,0,0,1,7.711,1.926l49.956,26.648A13,13,0,0,1-665-340.26a13,13,0,0,1-7.283,11.426l-49.956,26.648A16.441,16.441,0,0,1-729.95-300.26Zm11.464-50.259V-318h9.229v-42.95h-5.6a38.872,38.872,0,0,1-5.772,3.6,38.632,38.632,0,0,1-6.8,2.7v7.793a17.991,17.991,0,0,0,2.49-.483,19.992,19.992,0,0,0,2.432-.821,18.637,18.637,0,0,0,2.211-1.084,11.1,11.1,0,0,0,1.8-1.273Z" transform="translate(745 380.26)" fill="#FFFFFF" opacity="0.75"/>
              </svg>                      
        </div>
    </button>
    <button class="cir" id="q3aud2">
        <div class="play">
        <svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 80.001 80">
            <path id="Subtraction_1" data-name="Subtraction 1" d="M-729.95-300.26a16.6,16.6,0,0,1-5.658-.989,15.55,15.55,0,0,1-4.806-2.762,12.488,12.488,0,0,1-4.586-9.6v-53.3a12.488,12.488,0,0,1,4.587-9.6,15.552,15.552,0,0,1,4.806-2.762,16.6,16.6,0,0,1,5.658-.99,16.439,16.439,0,0,1,7.711,1.926l49.956,26.648A13,13,0,0,1-665-340.26a13,13,0,0,1-7.283,11.426l-49.956,26.648A16.441,16.441,0,0,1-729.95-300.26Zm11.141-53.072a6.8,6.8,0,0,1,4.658,1.377,5.235,5.235,0,0,1,1.524,4.072,7.175,7.175,0,0,1-.469,2.592,9.121,9.121,0,0,1-1.421,2.4,18.521,18.521,0,0,1-2.344,2.388c-.93.8-2.019,1.649-3.237,2.519-1.169.838-2.416,1.789-3.706,2.827a23.79,23.79,0,0,0-3.589,3.6,19.315,19.315,0,0,0-2.724,4.6,14.8,14.8,0,0,0-1.084,5.786V-318h27.949v-7.676h-17.812a3.226,3.226,0,0,1,.586-1.729,10.61,10.61,0,0,1,1.581-1.86,25.842,25.842,0,0,1,2.3-1.933c.853-.642,1.765-1.308,2.71-1.977,1.381-.953,2.731-1.954,4.013-2.974a21.639,21.639,0,0,0,3.414-3.384,15.884,15.884,0,0,0,2.372-4.1,13.984,13.984,0,0,0,.894-5.157,12.761,12.761,0,0,0-.922-4.936,10.239,10.239,0,0,0-2.681-3.765,12.181,12.181,0,0,0-4.291-2.388,18.364,18.364,0,0,0-5.728-.834,22.362,22.362,0,0,0-12.363,3.545v8.144A15.713,15.713,0,0,1-718.808-353.332Z" transform="translate(745 380.26)" fill="#FFFFFF" opacity="0.75"/>
          </svg>    
        </div>              
    </button>    
<button class="ans" id="q3a1" onclick="questionThree()">
    <span class="q3a1">Sample 1</span>
</button>
<button class="ans" id="q3a2" onclick="questionThree()">
    <span class="q3a2">Sample 2</span>
</button>
</div>
<div class="question" id="q4">
    <button class="cir" id="q4aud1">
        <div id="play1" class="play">
            <svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 80.001 80">
                <path id="play1" data-name="Subtraction 1" d="M-729.95-300.26a16.6,16.6,0,0,1-5.658-.989,15.55,15.55,0,0,1-4.806-2.762,12.488,12.488,0,0,1-4.586-9.6v-53.3a12.488,12.488,0,0,1,4.587-9.6,15.552,15.552,0,0,1,4.806-2.762,16.6,16.6,0,0,1,5.658-.99,16.439,16.439,0,0,1,7.711,1.926l49.956,26.648A13,13,0,0,1-665-340.26a13,13,0,0,1-7.283,11.426l-49.956,26.648A16.441,16.441,0,0,1-729.95-300.26Zm11.464-50.259V-318h9.229v-42.95h-5.6a38.872,38.872,0,0,1-5.772,3.6,38.632,38.632,0,0,1-6.8,2.7v7.793a17.991,17.991,0,0,0,2.49-.483,19.992,19.992,0,0,0,2.432-.821,18.637,18.637,0,0,0,2.211-1.084,11.1,11.1,0,0,0,1.8-1.273Z" transform="translate(745 380.26)" fill="#FFFFFF" opacity="0.75"/>
              </svg>                      
        </div>
    </button>
    <button class="cir" id="q4aud2">
        <div class="play">
        <svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 80.001 80">
            <path id="Subtraction_1" data-name="Subtraction 1" d="M-729.95-300.26a16.6,16.6,0,0,1-5.658-.989,15.55,15.55,0,0,1-4.806-2.762,12.488,12.488,0,0,1-4.586-9.6v-53.3a12.488,12.488,0,0,1,4.587-9.6,15.552,15.552,0,0,1,4.806-2.762,16.6,16.6,0,0,1,5.658-.99,16.439,16.439,0,0,1,7.711,1.926l49.956,26.648A13,13,0,0,1-665-340.26a13,13,0,0,1-7.283,11.426l-49.956,26.648A16.441,16.441,0,0,1-729.95-300.26Zm11.141-53.072a6.8,6.8,0,0,1,4.658,1.377,5.235,5.235,0,0,1,1.524,4.072,7.175,7.175,0,0,1-.469,2.592,9.121,9.121,0,0,1-1.421,2.4,18.521,18.521,0,0,1-2.344,2.388c-.93.8-2.019,1.649-3.237,2.519-1.169.838-2.416,1.789-3.706,2.827a23.79,23.79,0,0,0-3.589,3.6,19.315,19.315,0,0,0-2.724,4.6,14.8,14.8,0,0,0-1.084,5.786V-318h27.949v-7.676h-17.812a3.226,3.226,0,0,1,.586-1.729,10.61,10.61,0,0,1,1.581-1.86,25.842,25.842,0,0,1,2.3-1.933c.853-.642,1.765-1.308,2.71-1.977,1.381-.953,2.731-1.954,4.013-2.974a21.639,21.639,0,0,0,3.414-3.384,15.884,15.884,0,0,0,2.372-4.1,13.984,13.984,0,0,0,.894-5.157,12.761,12.761,0,0,0-.922-4.936,10.239,10.239,0,0,0-2.681-3.765,12.181,12.181,0,0,0-4.291-2.388,18.364,18.364,0,0,0-5.728-.834,22.362,22.362,0,0,0-12.363,3.545v8.144A15.713,15.713,0,0,1-718.808-353.332Z" transform="translate(745 380.26)" fill="#FFFFFF" opacity="0.75"/>
          </svg>    
        </div>              
    </button>    
<button class="ans" id="q4a1" onclick="questionFour()">
    <span class="q4a1">Sample 1</span>
</button>
<button class="ans" id="q4a2" onclick="questionFour()">
    <span class="q4a2">Sample 2</span>
</button>
</div>
<p> Adapted from an open-source dataset created by Luca Comanducci, Paolo Bestagini, and Stefano Tubaro.</p>
</div>
</body>
<script>

    const q1aud1 = document.getElementById("q1aud1");
    const q1mustango = document.getElementById("q1mustango");

   q1aud1.addEventListener("click", () => {
    if (q1mustango.paused) {
   q1mustango.play();
    } else {
    q1mustango.pause();
  }
});
    const q1aud2 = document.getElementById("q1aud2");
    const q1real = document.getElementById("q1real");

   q1aud2.addEventListener("click", () => {
    if (q1real.paused) {
   q1real.play();
    } else {
    q1real.pause();
  }
});
    const q2aud1 = document.getElementById("q2aud1");
    const q2real = document.getElementById("q2real");

   q2aud1.addEventListener("click", () => {
    if (q2real.paused) {
   q2real.play();
    } else {
    q2real.pause();
  }
});
const q2aud2 = document.getElementById("q2aud2");
    const q2suno = document.getElementById("q2suno");

   q2aud2.addEventListener("click", () => {
    if (q2suno.paused) {
   q2suno.play();
    } else {
    q2suno.pause();
  }
});
const q3aud1 = document.getElementById("q3aud1");
const q3real = document.getElementById("q3real");

   q3aud1.addEventListener("click", () => {
    if (q3real.paused) {
   q3real.play();
    } else {
    q3real.pause();
}});
const q3aud2 = document.getElementById("q3aud2");
const q3mgm = document.getElementById("q3mgm");

   q3aud2.addEventListener("click", () => {
    if (q3mgm.paused) {
   q3mgm.play();
    } else {
    q3mgm.pause();
  }
});
const q4aud1 = document.getElementById("q4aud1");
const q4mldm = document.getElementById("q4mldm");

   q4aud1.addEventListener("click", () => {
    if (q4mldm.paused) {
   q4mldm.play();
    } else {
    q4mldm.pause();
  }
});
const q4aud2 = document.getElementById("q4aud2");
const q4real = document.getElementById("q4rea.");
   q4aud2.addEventListener("click", () => {
    if (q4real.paused) {
   q4real.play();
    } else {
    q4real.pause();
  }
});
    function questionOne() {
    document.getElementById("q1a1").style.backgroundColor = "#78FFA1";
    document.querySelector("span.q1a1").innerHTML = "Sample 1:<br>Generated with Mustango";
    document.getElementById("q1a2").style.backgroundColor ="#FF7448";
    document.querySelector("span.q1a2").innerHTML = "Sample 2: Non-AI";
     }
     function questionTwo() {
    document.getElementById("q2a1").style.backgroundColor = "#FF7448";
    document.querySelector("span.q2a1").innerHTML = "Sample 1: Non-AI";
    document.getElementById("q2a2").style.backgroundColor ="#78FFA1";
    document.querySelector("span.q2a2").innerHTML = "Sample 2:<br>Generated with Suno V3";
     }
     function questionThree() {
    document.getElementById("q3a1").style.backgroundColor = "#FF7448";
    document.querySelector("span.q3a1").innerHTML = "Sample 1: Non-AI";
    document.getElementById("q3a2").style.backgroundColor ="#78FFA1";
    document.querySelector("span.q3a2").innerHTML = "Sample 2:<br>Generated with MusicGen";
     }
     function questionFour() {
    document.getElementById("q4a1").style.backgroundColor = "#78FFA1";
    document.querySelector("span.q4a1").innerHTML = "Sample 1:<br>Generated with MusicLDM";
    document.getElementById("q4a2").style.backgroundColor ="#FF7448";
    document.querySelector("span.q4a2").innerHTML = "Sample 2: Non-AI";
     }
   
</script>
</html>

