
<svg width="800" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <clipPath id="roundedBg">
      <rect x="0" y="0" width="800" height="220" rx="14"/>
    </clipPath>
  </defs>

  <g clip-path="url(#roundedBg)">
    <rect width="800" height="220" fill="#0d1117"/>

    <!-- Matrix-style falling code characters -->
    <g font-family="Consolas, Menlo, monospace" font-size="14" fill="#3fb950">
      <text x="60" y="0" opacity="0">01
        <animate attributeName="y" values="-20;240" dur="3.2s" begin="0s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.8;1" dur="3.2s" begin="0s" repeatCount="indefinite"/>
      </text>
      <text x="160" y="0" opacity="0">{ }
        <animate attributeName="y" values="-20;240" dur="3.6s" begin="1s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.8;1" dur="3.6s" begin="1s" repeatCount="indefinite"/>
      </text>
      <text x="300" y="0" opacity="0">λ
        <animate attributeName="y" values="-20;240" dur="3s" begin="1.8s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.8;1" dur="3s" begin="1.8s" repeatCount="indefinite"/>
      </text>
      <text x="450" y="0" opacity="0">&#9729;
        <animate attributeName="y" values="-20;240" dur="3.4s" begin="0.5s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.8;1" dur="3.4s" begin="0.5s" repeatCount="indefinite"/>
      </text>
      <text x="580" y="0" opacity="0">10
        <animate attributeName="y" values="-20;240" dur="3.1s" begin="1.3s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.8;1" dur="3.1s" begin="1.3s" repeatCount="indefinite"/>
      </text>
      <text x="710" y="0" opacity="0">/&gt;
        <animate attributeName="y" values="-20;240" dur="3.5s" begin="0.8s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.8;1" dur="3.5s" begin="0.8s" repeatCount="indefinite"/>
      </text>
    </g>

    <!-- Name -->
    <text x="400" y="85" text-anchor="middle" font-family="Segoe UI, Arial, sans-serif" font-size="34" font-weight="600" fill="#ffffff">
      Rawan Azzam
    </text>

    <!-- Subtitle -->
    <text x="400" y="112" text-anchor="middle" font-family="Consolas, Menlo, monospace" font-size="14" fill="#3fb950">
      building the cloud, line by line
    </text>

    <!-- Flutter logo -->
    <g transform="translate(300,150)">
      <animateTransform attributeName="transform" type="translate" values="300,150; 300,142; 300,150" dur="2.4s" repeatCount="indefinite" additive="sum"/>
      <path fill="#54C5F8" d="M14.6 2 3.6 13l3.4 3.4L21.4 2Zm0 9.4L7.9 18l3.4 3.4h3.3l7-7h-7Zm-3.3 3.4-3.6 3.6H21v-3.6Z" transform="scale(1.3)"/>
      <text x="16" y="42" text-anchor="middle" font-family="Segoe UI, Arial, sans-serif" font-size="11" fill="#8b949e">Flutter</text>
    </g>

    <!-- WordPress logo -->
    <g transform="translate(392,150)">
      <animateTransform attributeName="transform" type="translate" values="392,150; 392,142; 392,150" dur="2.4s" begin="0.4s" repeatCount="indefinite" additive="sum"/>
      <circle cx="16" cy="16" r="14" fill="#21759B"/>
      <path fill="#fff" d="M6 16a10 10 0 0 0 5.6 9L8 12.3A9.9 9.9 0 0 0 6 16Zm17.2-.5c0-1-.35-1.6-.65-2.1-.4-.65-.77-1.2-.77-1.85 0-.7.55-1.4 1.3-1.4h.1A10 10 0 0 0 16 6a10 10 0 0 0-8.4 4.55h.35c.8 0 2-.1 2-.1.4 0 .47.6.05.65 0 0-.4.05-.87.07l2.75 8.2 1.66-4.97-1.18-3.23c-.4-.02-.78-.07-.78-.07-.4-.03-.36-.65.05-.65 0 0 1.25.1 2 .1.78 0 2-.1 2-.1.4 0 .47.6.05.65 0 0-.4.05-.87.07l2.73 8.13.76-2.53c.33-1.05.58-1.8.58-2.45Z"/>
      <path fill="#fff" d="M16.2 17.7l-2.15 6.24c.64.19 1.3.29 2 .29.83 0 1.62-.13 2.36-.37l-.06-.1-2.15-6.06ZM24.6 16.5a7.5 7.5 0 0 1 .07 1.05c0 1.04-.2 2.2-.78 3.66l-3.15 9.1a10 10 0 0 0 3.86-13.81Z" transform="scale(0.7) translate(6,3)"/>
      <text x="16" y="42" text-anchor="middle" font-family="Segoe UI, Arial, sans-serif" font-size="11" fill="#8b949e">WordPress</text>
    </g>

    <!-- AWS logo -->
    <g transform="translate(484,150)">
      <animateTransform attributeName="transform" type="translate" values="484,150; 484,142; 484,150" dur="2.4s" begin="0.8s" repeatCount="indefinite" additive="sum"/>
      <rect x="2" y="4" width="28" height="20" rx="2.5" fill="#252F3E"/>
      <path fill="#FF9900" d="M6.5 17.5c3.2 2.3 8 2.5 11.3.2.2-.15.4.1.2.25-3 2.7-8.4 2.9-11.75.35-.2-.15 0-.35.25-.15Zm-.9-1c.2-.2.45-.2.55 0 2.7-1.4 6-1.4 8.9-.2.2.1.05.35-.15.25-2.6-.9-5.5-.85-8 .35-.2.1-.45 0-1.3-.4Z"/>
      <rect x="12" y="9" width="8" height="7" rx="1" fill="#FF9900"/>
      <text x="16" y="42" text-anchor="middle" font-family="Segoe UI, Arial, sans-serif" font-size="11" fill="#8b949e">AWS</text>
    </g>

  </g>
</svg>
