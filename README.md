# pradusha.github.io-occ-exam
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./assets/images/favicon-32x32.png"
    />
    <link rel="stylesheet" href="styles.css" />

    <title>Frontend Mentor | Results summary component</title>
  </head>
  <body>
    <!--begin main page>-->
    <main class="main-page">
      <!--begin main card-->
      <div class="card">
        <!--begin card left-->
        <div class="card-left">
          <h1>Your Result</h1>
          <div class="circle-box">
            <h2 class="circle-header">76</h2>
            <p class="circle-text">of 100</p>
          </div>
          <div class="card-left-bottom">
            <p class="card-left-text">Great</p>
            <p class="card-left-paragraph">
              You scored higher than 65% of the people who have taken these
              tests.
            </p>
          </div>
        </div>
        <!--end card left-->
        <!--begin card right-->
        <div class="card-right">
          <div class="card-right-header-box">
            <h2 class="card-right-header">Summary</h2>
          </div>
          <div class="stats-container">
            <div class="stats-box1">
              <div class="stats-left">
                <img
                  class="stats-image"
                  src="images/icon-reaction.svg"
                  alt="reaction image"
                />
                <p class="stats-title">Reaction</p>
              </div>
              <div class="stats-right">
                <p class="stats-results">
                  80 <span class="stats-span">/ 100</span>
                </p>
              </div>
            </div>
            <div class="stats-box2">
              <div class="stats-left">
                <img
                  class="stats-image"
                  src="images/icon-memory.svg"
                  alt="reaction image"
                />
                <p class="stats-title2">Memory</p>
              </div>
              <div class="stats-right">
                <p class="stats-results">
                  92 <span class="stats-span">/ 100</span>
                </p>
              </div>
            </div>
            <div class="stats-box3">
              <div class="stats-left">
                <img
                  class="stats-image"
                  src="images/icon-verbal.svg"
                  alt="verbal image"
                />
                <p class="stats-title3">Verbal</p>
              </div>
              <div class="stats-right">
                <p class="stats-results">
                  61 <span class="stats-span">/ 100</span>
                </p>
              </div>
            </div>
            <div class="stats-box4">
              <div class="stats-left">
                <img
                  class="stats-image"
                  src="images/icon-visual.svg"
                  alt="visual image"
                />
                <p class="stats-title4">Visual</p>
              </div>
              <div class="stats-right">
                <p class="stats-results">
                  72 <span class="stats-span">/ 100</span>
                </p>
              </div>
            </div>
          </div>
          <button>Continue</button>
        </div>
        <!--end card right-->
      </div>
      <!--end main card-->
    </main>
    <!--end main page-->
  </body>
</html>
