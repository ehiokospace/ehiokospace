<svg
  xmlns="http://www.w3.org/2000/svg"
  width="850"
  height="70"
  viewBox="0 0 850 70"
>
  <style>
    @font-face {
      font-family: "Departure Mono";
      src: url("https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/main/assets/DepartureMono-Regular.woff2")
        format("woff2");
    }

    .text {
      font-family: "Departure Mono", monospace;
      font-size: 33px;
      fill: #ffffff;
      letter-spacing: 1px;
    }

    .reveal {
      animation: typing 6s steps(34, end) infinite;
    }

    .cursor {
      animation:
        cursorMove 6s steps(34, end) infinite,
        blink 0.8s step-end infinite;
    }

    @keyframes typing {
      0% {
        width: 0;
      }

      40% {
        width: 720px;
      }

      65% {
        width: 720px;
      }

      95% {
        width: 0;
      }

      100% {
        width: 0;
      }
    }

    @keyframes cursorMove {
      0% {
        transform: translateX(0);
      }

      40% {
        transform: translateX(690px);
      }

      65% {
        transform: translateX(690px);
      }

      95% {
        transform: translateX(0);
      }

      100% {
        transform: translateX(0);
      }
    }

    @keyframes blink {
      50% {
        opacity: 0;
      }
    }
  </style>

  <defs>
    <clipPath id="typing-mask">
      <rect
        class="reveal"
        x="0"
        y="0"
        width="0"
        height="70"
      />
    </clipPath>
  </defs>

  <g clip-path="url(#typing-mask)">
    <text
      class="text"
      x="0"
      y="45"
    >
      hello i'm ehi
    </text>
  </g>

  <rect
    class="cursor"
    x="0"
    y="16"
    width="3"
    height="33"
    fill="#ffffff"
  />
</svg>
