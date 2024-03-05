<svg fill='none' viewBox='0 0 800 400' width='800' height='400' xmlns='http://www.w3.org/2000/svg'>
	<foreignObject width='100%' height='100%'>
		<div xmlns='http://www.w3.org/1999/xhtml' style='height: 100%'>
      <link rel="preconnect" href="https://fonts.gstatic.com"></link>
      <link href="https://fonts.googleapis.com/css2?family=Dosis" rel="stylesheet"></link>
			<style>
        .text {
          --positionX: .025em;
          --positionY: .025em;
          --spread: .15em;
          --gh-background-light: #ffffff;
          --gh-text-light: #24292e;
          --gh-background-dark: #0d1117;
          --gh-text-dark: #c9d1d9;
          display: flex;
					flex-direction: column;
					align-items: center;
					justify-content: center;
					margin: 0;
					width: 100%;
          height: 100%;
        }

        h1, h2 {
          font-display: swap;
					font-family:
            'Dosis',
						system-ui,
						-apple-system,
						'Segoe UI',
						Roboto,
						Helvetica,
						Arial,
						sans-serif,
						'Apple Color Emoji',
						'Segoe UI Emoji';
          text-transform: uppercase;
          line-height: 1;
          margin: 0;
          padding: 0;
          text-align: center;
        }

        h1 {
          font-size: clamp(6rem, calc(4vw + 4vh), 7.5rem);
          font-weight: bold;
          margin-bottom: 1rem;
        }

        h2 {
          font-size: clamp(3rem, calc(2vw + 2vh), 4rem);
          font-weight: bold;
        }

        @keyframes pulse {
          0%, 100% {
            text-shadow:
              calc(1 * var(--positionX)) calc(1 * var(--positionY)) calc(1 * var(--spread)) yellow,
              calc(1.5 * var(--positionX)) calc(1.5 * var(--positionY)) calc(2 * var(--spread)) magenta,
              calc(2 * var(--positionX)) calc(2 * var(--positionY)) calc(3 * var(--spread)) cyan
            ;
          }
          
          25% {
            text-shadow:
              calc(-1 * var(--positionX)) calc(1 * var(--positionY)) calc(1 * var(--spread)) yellow,
              calc(-1.5 * var(--positionX)) calc(1.5 * var(--positionY)) calc(2 * var(--spread)) magenta,
              calc(-2 * var(--positionX)) calc(2 * var(--positionY)) calc(3 * var(--spread)) cyan
            ;
          }
          
          50% {
            text-shadow:
              calc(-1 * var(--positionX)) calc(-1 * var(--positionY)) calc(1 * var(--spread)) yellow,
              calc(-1.5 * var(--positionX)) calc(-1.5 * var(--positionY)) calc(2 * var(--spread)) magenta,
              calc(-2 * var(--positionX)) calc(-2 * var(--positionY)) calc(3 * var(--spread)) cyan
            ;
          }
          
          75% {
            text-shadow:
              calc(1 * var(--positionX)) calc(-1 * var(--positionY)) calc(1 * var(--spread)) yellow,
              calc(1.5 * var(--positionX)) calc(-1.5 * var(--positionY)) calc(2 * var(--spread)) magenta,
              calc(2 * var(--positionX)) calc(-2 * var(--positionY)) calc(3 * var(--spread)) cyan
            ;
          }          
        }

        .text {
          background: var(--gh-background-light);
          color: var(--gh-background-light);
        }

        h1, h2 {
          animation: pulse 2s cubic-bezier(.20,.40,.80,.60) infinite;
        }

        h2 {
          animation-direction: reverse;
          animation-duration: 2.5s;
        }

        @media (prefers-color-scheme: dark) {
          .text {
            background: var(--gh-background-dark);
            color: var(--gh-background-dark);
          }
        }

        @media (prefers-reduced-motion) {
          .text {
            --positionX: .25em;
            --positionY: .25em;
            --spread: .5em;
            text-shadow:
              var(--positionX) var(--positionY) calc(1 * var(--spread)) yellow,
              var(--positionX) var(--positionY) calc(2 * var(--spread)) magenta,
              var(--positionX) var(--positionY) calc(3 * var(--spread)) cyan
            ;
          }

          h1, h2 {
            animation: unset;
          }
        }
			</style>
			<div class='text'>
        <h1 data-text="Jihui("Todd") Tan">Jihui("Todd") Tan</h1>
        <h2 data-text="A Dude">A Dude</h2>
        <!-- TODO: write a blog post about this and make this link to it-->
			</div>
    </div>

	</foreignObject>
</svg>
