<!-- Pixel-style animated headline -->
<picture>
  <img alt="Welcome to my portfolio - pixel animation" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="880" height="140" viewBox="0 0 880 140" preserveAspectRatio="xMidYMid meet">
    <rect width="100%" height="100%" fill="white"/>
    <defs>
      <!-- make the text chunkier to get a pixel/blocky look -->
      <filter id="pixelate">
        <feMorphology in="SourceGraphic" operator="dilate" radius="1"/>
      </filter>

      <style type="text/css"><![CDATA[
        text { 
          font-family: "Courier New", "Courier", monospace;
          font-weight: 700;
          font-size: 36px;
          letter-spacing: 6px;
          shape-rendering: crispEdges;
          paint-order: stroke fill markers;
          fill: #000000;
        }
        .cursor {
          fill: #000000;
        }
      ]]></style>
    </defs>

    <!-- Centering group -->
    <g transform="translate(40,80)">
      <!-- The phrase is split into individual tspans so we can animate each character -->
      <text filter="url(#pixelate)">
        <!-- We'll keep exact casing: "Welcome to my portfolio" -->
        <!-- Each <tspan> corresponds to one character; animation 'begin' staggers them for typing effect -->
        <tspan opacity="0">
          W
          <animate attributeName="opacity" from="0" to="1" begin="0s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          e
          <animate attributeName="opacity" from="0" to="1" begin="0.06s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          l
          <animate attributeName="opacity" from="0" to="1" begin="0.12s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          c
          <animate attributeName="opacity" from="0" to="1" begin="0.18s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          o
          <animate attributeName="opacity" from="0" to="1" begin="0.24s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          m
          <animate attributeName="opacity" from="0" to="1" begin="0.30s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          e
          <animate attributeName="opacity" from="0" to="1" begin="0.36s" dur="0.12s" fill="freeze"/>
        </tspan>

        <!-- space -->
        <tspan dx="8" opacity="0">
          &#160;
          <animate attributeName="opacity" from="0" to="1" begin="0.42s" dur="0.12s" fill="freeze"/>
        </tspan>

        <tspan opacity="0">
          t
          <animate attributeName="opacity" from="0" to="1" begin="0.48s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          o
          <animate attributeName="opacity" from="0" to="1" begin="0.54s" dur="0.12s" fill="freeze"/>
        </tspan>

        <!-- space -->
        <tspan dx="8" opacity="0">
          &#160;
          <animate attributeName="opacity" from="0" to="1" begin="0.60s" dur="0.12s" fill="freeze"/>
        </tspan>

        <tspan opacity="0">
          m
          <animate attributeName="opacity" from="0" to="1" begin="0.66s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          y
          <animate attributeName="opacity" from="0" to="1" begin="0.72s" dur="0.12s" fill="freeze"/>
        </tspan>

        <!-- space -->
        <tspan dx="8" opacity="0">
          &#160;
          <animate attributeName="opacity" from="0" to="1" begin="0.78s" dur="0.12s" fill="freeze"/>
        </tspan>

        <tspan opacity="0">
          p
          <animate attributeName="opacity" from="0" to="1" begin="0.84s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          o
          <animate attributeName="opacity" from="0" to="1" begin="0.90s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          r
          <animate attributeName="opacity" from="0" to="1" begin="0.96s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          t
          <animate attributeName="opacity" from="0" to="1" begin="1.02s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          f
          <animate attributeName="opacity" from="0" to="1" begin="1.08s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          o
          <animate attributeName="opacity" from="0" to="1" begin="1.14s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          l
          <animate attributeName="opacity" from="0" to="1" begin="1.20s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          i
          <animate attributeName="opacity" from="0" to="1" begin="1.26s" dur="0.12s" fill="freeze"/>
        </tspan>
        <tspan opacity="0">
          o
          <animate attributeName="opacity" from="0" to="1" begin="1.32s" dur="0.12s" fill="freeze"/>
        </tspan>
      </text>

      <!-- blinking cursor: a small pixel-block rectangle after the text -->
      <!-- the cursor's x is tuned visually — tweak translateX if you change font-size/letter-spacing -->
      <g transform="translate(640, -30)">
        <rect class="cursor" x="0" y="0" width="10" height="26" rx="0" ry="0" opacity="1">
          <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite" begin="1.44s"/>
        </rect>
      </g>
    </g>
  </svg>' />
</picture>
