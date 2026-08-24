# hey, i'm shanrou 👋

computer science student @ central south university  
🤔 currently:
> turning random ideas into things that actually run.

# 🦖 Welcome to my little corner of the internet

<div align="center">

<svg width="900" height="330" viewBox="0 0 900 330"
     xmlns="http://www.w3.org/2000/svg">

  <defs>

    <!-- Dark jungle-ish background -->
    <linearGradient id="bg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#07100c"/>
      <stop offset="65%" stop-color="#0d1711"/>
      <stop offset="100%" stop-color="#020504"/>
    </linearGradient>

    <!-- Dinosaur skin -->
    <linearGradient id="skin" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#536b42"/>
      <stop offset="45%" stop-color="#344b32"/>
      <stop offset="100%" stop-color="#17251b"/>
    </linearGradient>

    <!-- Dark skin -->
    <linearGradient id="skinDark" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#263a28"/>
      <stop offset="100%" stop-color="#0d170f"/>
    </linearGradient>

    <!-- Mouth -->
    <linearGradient id="mouth" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#260d0d"/>
      <stop offset="100%" stop-color="#080303"/>
    </linearGradient>

    <!-- Slight cinematic glow -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="2"/>
    </filter>

    <!-- Animation -->
    <style>
      .trex {
        animation: chase 1.4s steps(4) infinite;
        transform-origin: 430px 180px;
      }

      @keyframes chase {
        0%   { transform: translateX(0px) translateY(0px); }
        25%  { transform: translateX(-5px) translateY(2px); }
        50%  { transform: translateX(2px) translateY(-2px); }
        75%  { transform: translateX(-3px) translateY(1px); }
        100% { transform: translateX(0px) translateY(0px); }
      }

      .jaw {
        animation: jaw 1.4s steps(2) infinite;
        transform-origin: 420px 215px;
      }

      @keyframes jaw {
        0%, 100% { transform: rotate(0deg); }
        50% { transform: rotate(2deg); }
      }

      .eye {
        animation: blink 3.5s steps(2) infinite;
      }

      @keyframes blink {
        0%, 92%, 100% { opacity: 1; }
        94%, 97% { opacity: 0.1; }
      }
    </style>

  </defs>


  <!-- ================================================= -->
  <!-- BACKGROUND -->
  <!-- ================================================= -->

  <rect width="900" height="330" fill="url(#bg)"/>

  <!-- cinematic black bars -->

  <rect x="0" y="0" width="900" height="28" fill="#000"/>
  <rect x="0" y="302" width="900" height="28" fill="#000"/>


  <!-- distant jungle -->

  <g opacity="0.35">

    <path fill="#142319"
      d="
      M0 270
      L45 220
      L65 245
      L90 205
      L120 245
      L150 195
      L180 245
      L215 210
      L245 255
      L280 215
      L310 250
      L345 200
      L380 250
      L420 215
      L460 250
      L500 205
      L540 250
      L580 220
      L620 255
      L660 205
      L700 250
      L740 215
      L780 255
      L820 205
      L860 245
      L900 215
      L900 330
      L0 330 Z"/>

  </g>


  <!-- mist -->

  <g opacity="0.08">

    <rect x="0" y="225" width="900" height="18" fill="#d6e5d0"/>

    <rect x="100" y="250" width="600" height="10" fill="#d6e5d0"/>

  </g>


  <!-- ================================================= -->
  <!-- T-REX -->
  <!-- ================================================= -->

  <g class="trex">


    <!-- ============================= -->
    <!-- BODY / BACK -->
    <!-- ============================= -->

    <path
      fill="url(#skinDark)"
      d="
      M120 250

      C155 220 190 195 230 178

      C275 160 320 150 360 153

      C410 155 455 175 490 198

      C535 226 590 238 655 232

      L735 220

      L805 210

      L845 220

      L795 236

      L735 248

      L670 260

      L600 268

      L520 270

      L430 268

      L340 270

      L250 276

      L170 280

      Z"/>


    <!-- dorsal ridge -->

    <path
      fill="#6a8151"
      d="
      M170 208
      L190 188
      L205 197
      L225 176
      L240 188
      L260 170
      L275 181
      L300 164
      L315 177
      L340 163
      L355 177
      L380 168
      L400 184
      L430 180
      L460 198
      L490 204
      L450 218
      L390 211
      L320 207
      L250 214
      L200 225
      Z"/>


    <!-- ============================= -->
    <!-- NECK -->
    <!-- ============================= -->

    <path
      fill="url(#skin)"
      d="
      M250 205

      C255 165 275 130 305 105

      C330 83 360 72 395 73

      C430 74 460 91 475 116

      C490 142 486 170 470 193

      L445 225

      L390 235

      L325 225

      L275 220

      Z"/>


    <!-- neck shadow -->

    <path
      fill="#18271b"
      d="
      M285 195
      C300 155 325 125 355 105
      C385 86 415 92 435 110
      C405 120 380 140 365 170
      C350 198 350 218 365 232
      L320 225
      L285 215
      Z"/>


    <!-- ============================= -->
    <!-- HUGE T-REX HEAD -->
    <!-- ============================= -->

    <path
      fill="url(#skin)"
      d="
      M210 90

      C220 62 250 48 285 44

      C325 38 365 45 398 58

      C430 70 452 88 465 108

      L520 118

      L575 125

      L625 140

      L640 158

      L615 174

      L560 178

      L510 185

      L470 195

      L425 188

      L390 175

      L345 160

      L300 148

      L255 132

      L220 115

      L202 101

      Z"/>


    <!-- skull top plane -->

    <path
      fill="#60784a"
      d="
      M225 87
      C250 60 290 52 325 55
      C360 58 395 72 420 91
      L390 105
      L345 95
      L300 100
      L260 110
      L220 104
      Z"/>


    <!-- ============================= -->
    <!-- BROW -->
    <!-- ============================= -->

    <path
      fill="#19291c"
      d="
      M275 90
      L310 72
      L355 75
      L390 88
      L405 104
      L375 111
      L335 101
      L295 108
      L265 103
      Z"/>


    <!-- ============================= -->
    <!-- EYE -->
    <!-- ============================= -->

    <g class="eye">

      <rect x="326" y="88" width="16" height="12"
            fill="#0a0b08"/>

      <rect x="330" y="90" width="8" height="8"
            fill="#d6b52c"/>

      <rect x="334" y="90" width="4" height="8"
            fill="#050505"/>

      <rect x="330" y="90" width="2" height="2"
            fill="#fff3a0"/>

    </g>


    <!-- ============================= -->
    <!-- SNOUT -->
    <!-- ============================= -->

    <path
      fill="#40573a"
      d="
      M390 112
      L445 111
      L500 121
      L555 132
      L615 145
      L625 158
      L590 166
      L540 162
      L490 157
      L445 151
      L405 143
      Z"/>


    <!-- snout scales -->

    <g fill="#70835a" opacity="0.6">

      <rect x="425" y="119" width="8" height="6"/>
      <rect x="455" y="125" width="7" height="5"/>
      <rect x="480" y="129" width="9" height="6"/>
      <rect x="515" y="136" width="8" height="5"/>
      <rect x="545" y="141" width="7" height="5"/>

    </g>


    <!-- nostril -->

    <rect x="500" y="126"
          width="14" height="8"
          fill="#101610"/>

    <rect x="503" y="126"
          width="5" height="3"
          fill="#778765"/>


    <!-- ============================= -->
    <!-- OPEN MOUTH -->
    <!-- ============================= -->

    <path
      fill="url(#mouth)"
      d="
      M390 145

      L445 151
      L500 160
      L555 165
      L610 166

      L625 174

      L595 187
      L545 190
      L495 188
      L450 182
      L410 171

      L375 157

      Z"/>


    <!-- upper gum -->

    <path
      fill="#6e3430"
      d="
      M392 148
      L440 154
      L490 163
      L540 168
      L600 169
      L590 177
      L540 177
      L490 172
      L445 165
      L405 158
      Z"/>


    <!-- ============================= -->
    <!-- TEETH -->
    <!-- ============================= -->

    <g fill="#e8dfbc">

      <!-- upper teeth -->

      <path d="M420 156 L432 158 L427 177 L418 164 Z"/>
      <path d="M445 160 L457 162 L452 183 L443 167 Z"/>
      <path d="M470 164 L483 166 L477 187 L468 170 Z"/>
      <path d="M498 168 L511 169 L505 188 L496 174 Z"/>
      <path d="M527 170 L539 171 L534 189 L525 175 Z"/>
      <path d="M555 171 L568 171 L564 187 L554 176 Z"/>
      <path d="M582 170 L594 170 L591 183 L582 175 Z"/>

    </g>


    <!-- tongue -->

    <path
      fill="#7d3e3b"
      d="
      M420 180
      C455 176 490 180 520 184
      C495 192 462 194 435 190
      Z"/>


    <path
      fill="#a75b52"
      d="
      M445 183
      C470 181 492 184 507 186
      C485 188 465 188 445 186
      Z"/>


    <!-- ============================= -->
    <!-- LOWER JAW -->
    <!-- ============================= -->

    <path
      fill="#263a29"
      d="
      M405 180

      L450 191
      L500 198
      L555 200
      L605 193

      L590 210
      L545 220
      L490 218
      L440 208
      L405 195

      Z"/>


    <!-- lower jaw highlight -->

    <path
      fill="#506643"
      d="
      M430 196
      L480 205
      L535 208
      L575 201
      L560 210
      L515 214
      L470 207
      L435 202
      Z"/>


    <!-- ============================= -->
    <!-- LITTLE ARMS -->
    <!-- ============================= -->

    <path
      fill="#263b29"
      d="
      M345 190
      C325 205 310 220 298 234
      L310 239
      L328 227
      L340 214
      L355 205
      Z"/>

    <path
      fill="#506643"
      d="
      M300 233
      L282 242
      L288 248
      L304 242
      L319 237
      Z"/>


    <!-- claws -->

    <path
      fill="#c2b88d"
      d="
      M282 242 L273 247 L286 246 Z
      M291 244 L282 251 L296 247 Z
      M300 242 L294 250 L307 244 Z"/>


    <!-- ============================= -->
    <!-- LEG / RUNNING SILHOUETTE -->
    <!-- ============================= -->

    <path
      fill="#18271b"
      d="
      M535 220
      L570 220
      L585 250
      L570 272
      L550 272
      L560 253
      L545 242
      Z"/>


    <path
      fill="#2c422e"
      d="
      M565 269
      L545 274
      L520 276
      L510 282
      L530 283
      L555 280
      L575 276
      Z"/>


    <!-- ============================= -->
    <!-- TAIL -->
    <!-- ============================= -->

    <path
      fill="#18271b"
      d="
      M570 245

      C630 240 680 230 725 215
      C770 200 810 188 855 190

      L900 200
      L900 225

      C850 218 810 220 765 232

      C700 250 640 270 575 275

      Z"/>


    <!-- tail highlight -->

    <path
      fill="#344b32"
      d="
      M620 246
      C690 232 755 208 820 201
      L865 201
      C810 210 755 230 700 246
      C665 256 635 262 605 266
      Z"/>


  </g>


  <!-- ================================================= -->
  <!-- FOREGROUND DUST -->
  <!-- ================================================= -->

  <g fill="#77836d" opacity="0.35">

    <rect x="80" y="278" width="7" height="7"/>
    <rect x="110" y="270" width="4" height="4"/>
    <rect x="145" y="288" width="8" height="5"/>
    <rect x="190" y="275" width="5" height="5"/>
    <rect x="230" y="290" width="9" height="4"/>
    <rect x="690" y="275" width="6" height="6"/>
    <rect x="750" y="268" width="4" height="4"/>
    <rect x="820" y="280" width="8" height="5"/>

  </g>


  <!-- cinematic corner vignette -->

  <rect x="0" y="28" width="900" height="274"
        fill="none"
        stroke="#000"
        stroke-width="35"
        opacity="0.35"/>

</svg>

</div>
