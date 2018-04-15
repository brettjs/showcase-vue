<template>
  <header>
    <span id="logo">
      <svg id="scalableSiteLogo" xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 527.71 579.51">

        <switch>
          <g>
            <g>
              <path id="swoosh" d="M552.11,277.77c-45.23-76.22-92.07-59-160.65-61.41,32-22.31,50.81-29.38,72.54-63.45C557,4,276.12,89.84,187.63,153.1S115,238,174.13,196.6c80.4-56.5,240.07-108.7,255.74-89.65s-6.95,34.9-19,48.93c-53.68,59-111.73,77.3-166.5,96.86-39.65,14.16-49.14,52.92,1.2,28.21C437.7,168.39,712.6,306.09,339.61,518.82c-177.48,93.26-256.45,61.48-268,39.28C28.63,438.08,201,396.55,201,396.55S73.34,417.91,50.72,491C-22.36,774.07,704.87,505.77,552.11,277.77Z" transform="translate(-45.55 -33.44)" />
            </g>

            <g>
              <path id="stalk" d="M344.43,197.54s0-17-1.44-23.69-25.92-6.33-29.11-3.79c-7.63,6.09-6,18-6.36,28.78-0.23,6.5-8.56,224.46-8.19,233.84,0.59,15.26,8.64,32.64,24.6,32.84,17.45,0.21,12.91-19.64,15.57-31.54C341.7,424.19,344.43,197.54,344.43,197.54Z" transform="translate(-45.55 -33.44)"/>
            </g>

            <g>
              <path id="top-tick" d="M339.83,33.83c-16.78-3-17.94,11.68-20.7,25.28-2.18,10.74-2.57,45-2.57,45l1.18,9.16c0.85,6.89,24.64,8.56,27.07-6.72,0,0,6.46-63.86,7.69-67.74S339.83,33.83,339.83,33.83Z" transform="translate(-45.55 -33.44)"/>
            </g>
          </g>

          <foreignObject>
            <p>Fallback image</p>
            <img src="images/logo-b3-grey.png" >
          </foreignObject>
        </switch>

      </svg>
    </span>
    <h1>{{t 'meta.author'}}</h1>
    <h2 class="desktop-only">{{t 'meta.role'}}</h2>

    <ul class="nav nav-pills pull-right">
      <li>
        <a href="mailto:contact@brettslone.com">
          <span class="non-mobile">{{t 'main.contact'}}</span>
          <span class="mobile-only glyphicon glyphicon-comment"></span>
        </a>
      </li>
      <li>
        <a href="/dl/brettSloneResume.pdf">
          <span class="non-mobile">{{t 'main.resume'}}</span>
          <span class="mobile-only glyphicon glyphicon-paperclip"></span>
        </a>
      </li>
    </ul>
  </header>
</template>
