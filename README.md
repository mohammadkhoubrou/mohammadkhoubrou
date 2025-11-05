<div align="center">
  <!-- Clickable neon text linking to your profile -->
  <a href="https://github.com/YOUR_USERNAME" target="_blank" rel="noopener noreferrer" aria-label="Visit my GitHub profile">
    <svg width="760" height="140" viewBox="0 0 760 140" xmlns="http://www.w3.org/2000/svg" role="img" aria-labelledby="titleDesc">
      <title id="titleDesc">Neon GitHub link — YOUR_USERNAME</title>

      <defs>
        <!-- base blurred glow -->
        <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
          <feGaussianBlur stdDeviation="6" result="b"/>
          <feMerge>
            <feMergeNode in="b"/>
            <feMergeNode in="b"/>
            <feMergeNode in="SourceGraphic"/>
          </feMerge>
        </filter>

        <!-- intense outer glow for flicker -->
        <filter id="glow-strong" x="-60%" y="-60%" width="220%" height="220%">
          <feGaussianBlur stdDeviation="10" result="b2"/>
          <feMerge>
            <feMergeNode in="b2"/>
            <feMergeNode in="b2"/>
            <feMergeNode in="b2"/>
            <feMergeNode in="SourceGraphic"/>
          </feMerge>
        </filter>
      </defs>

      <!-- background rectangle (transparent) keeps layout stable -->
      <rect width="100%" height="100%" fill="transparent"/>

      <!-- blurred glow layer (animated subtle pulse) -->
      <text x="50%" y="55%" text-anchor="middle" font-family="Segoe UI, Roboto, Arial, sans-serif"
            font-weight="700" font-size="56" fill="#00ffea" filter="url(#glow)" style="letter-spacing:3px;">
        YOUR_USERNAME
        <animate attributeName="opacity" values="0.75;1;0.8;1;0.75" dur="3s" repeatCount="indefinite"/>
      </text>

      <!-- stronger glow layer that flickers -->
      <text x="50%" y="55%" text-anchor="middle" font-family="Segoe UI, Roboto, Arial, sans-serif"
            font-weight="700" font-size="56" fill="#39ff14" filter="url(#glow-strong)" style="letter-spacing:3px;">
        YOUR_USERNAME
        <!-- flicker pattern -->
        <animate attributeName="opacity"
                 values="1;0.6;1;0.2;1;0.9;1"
                 keyTimes="0;0.12;0.25;0.4;0.6;0.85;1"
                 dur="2.8s"
                 repeatCount="indefinite"/>
      </text>

      <!-- sharp front text -->
      <text x="50%" y="55%" text-anchor="middle" font-family="Segoe UI, Roboto, Arial, sans-serif"
            font-weight="700" font-size="56" fill="#eaff00" style="letter-spacing:3px;">
        YOUR_USERNAME
        <!-- slow color shimmer -->
        <animate attributeName="fill" values="#eaff00;#ffd400;#eaff00" dur="5s" repeatCount="indefinite"/>
      </text>
    </svg>
  </a>
</div>
