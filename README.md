<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&family=Young+Serif&display=swap"
      rel="stylesheet"
    />

    <link rel="stylesheet" href="style.css" type="text/css" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./assets/images/favicon-32x32.png"
    />

    <title>Frontend Mentor | Recipe page</title>

    <!-- 
    - White: hsl(0, 0%, 100%)

    - Stone 100: hsl(30, 54%, 90%)
    - Stone 150: hsl(30, 18%, 87%)
    - Stone 600: hsl(30, 10%, 34%)
    - Stone 900: hsl(24, 5%, 18%)

    - Brown 800: hsl(14, 45%, 36%)

    - Rose 800: hsl(332, 51%, 32%)
    - Rose 50: hsl(330, 100%, 98%)
    -->
    <style>
      .young-serif-regular {
        font-family: "Young Serif", serif;
        font-weight: 400;
        font-style: normal;
        font-optical-sizing: auto;
      }
      .text-outfit {
        font-family: "Outfit", sans-serif;
        font-optical-sizing: auto;
        font-weight: 400;
        font-style: normal;
        font-size: 16px;
      }
      .fontColorStone {
        color: hsl(30, 10%, 34%);
      }
      .flex {
        display: flex;

      }
      .fontColorBrown {
        color: hsl(14, 45%, 36%);
      }
      .fontColorRose {
        color: hsl(332, 51%, 32%);
      }
      .box-prep {
        background-color: hsl(330, 100%, 98%);
        border-radius: 15px;
      }
      .attribution {
        font-size: 11px;
        text-align: center;
      }
      .attribution a {
        color: hsl(228, 45%, 44%);
      }
      .responsive {
        max-width: 100%;
        height: auto;
      }
      .headingPadding {
        padding-left: 25px;
        padding-top: 15px;
      }
      .h2padding {
        padding-left: 18px;
        padding-top: 15px;
      }
      .padMobile {
        padding-left: 40px;
        padding-right: 40px;
      }
      .padList {
        padding-left: 50px;
      }
      .padElelist {
        padding-left: 12px;
        padding-bottom: 8px;
      }
      .padTD {
        padding-right: 16px;
      }
      .centerText {
        text-align: center;
      }
      .padEleListLast {
        padding-bottom: 25px;
      }
      .center {
        margin-left: auto;
        margin-right: auto;
      }
      @media (min-width: 769px){
        .bg {
          background-color: hsl(30, 54%, 90%);
        }

        .whiteBox {
          background-color: white;
          width: 700px;
          height: 500px;
          border: none;
          border-radius: 15px;
          display: flex;
          flex-direction: column;
          align-self: center;
          margin-top: 40px;
        }

        .toFit{
          height: 100%;
        }

        .imgScale{
          height: 90%;
          width: 90%;
          margin: 30px 0px 0px 30px;
          border-radius:4%;
        }
        
        .alignHeading{
          padding-left:0px;
        }

        .eleLeft{
          text-align:left;
        }
        
      }
    </style>
  </head>
  <body class="bg flex">
    <section class="whiteBox">
      <div class="toFit">
        <img
          src="assets\images\image-omelette.jpeg"
          alt="food"
          class="responsive imgScale"
        />
      </div>
      <div class="padMobile toFit">
        <p class="young-serif-regular" style="font-size: 34px">
          Simple Omelette Recipe
        </p>
        <p class="text-outfit fontColorStone">
          An easy and quick dish, perfect for any meal. This classic omelette
          combines beaten eggs cooked to perfection, optionally filled with your
          choice of cheese, vegetables, or meats.
        </p>

        <div class="box-prep toFit">
          <h2
            class="fontColorRose headingPadding text-outfit"
            style="font-weight: bold; font-size: 20px"
          >
            Preparation time
          </h2>
          <ul class="text-outfit fontColorStone padList">
            <li class="padElelist"><b>Total: </b>Approximately 10 minutes</li>
            <li class="padElelist"><b>Preparation:</b> 5 minutes</li>
            <li class="padElelist padEleListLast"><b>Cooking: </b>5 minutes</li>
          </ul>
        </div>
        <div>
          <h2 class="fontColorBrown h2padding">Ingredients</h2>
          <ul class="text-outfit fontColorStone">
            <li class="padElelist">2-3 large eggs</li>
            <li class="padElelist">Salt, to taste</li>
            <li class="padElelist">Pepper, to taste</li>
            <li class="padElelist">1 tablespoon of butter or oil</li>
            <li class="padElelist">
              Optional fillings: cheese, diced vegetables, cooked meats, herbs
            </li>
          </ul>
        </div>
        <hr />
        <div>
          <h2 class="fontColorBrown h2padding">Instructions</h2>
          <ol class="text-outfit fontColorStone">
            <li class="padElelist">
              <b>Beat the eggs: </b> In a bowl, beat the eggs with a pinch of
              salt and pepper until they are well mixed. You can add a
              tablespoon of water or milk for a fluffier texture.
            </li>
            <li class="padElelist">
              <b>Heat the pan: </b> Place a non-stick frying pan over medium
              heat and add butter or oil.
            </li>
            <li class="padElelist">
              <b>Cook the omelette: </b> Once the butter is melted and bubbling,
              pour in the eggs. Tilt the pan to ensure the eggs evenly coat the
              surface.
            </li>
            <li class="padElelist">
              <b>Add fillings (optional):</b> When the eggs begin to set at the
              edges but are still slightly runny in the middle, sprinkle your
              chosen fillings over one half of the omelette.
            </li>
            <li class="padElelist">
              <b>Fold and serve:</b> As the omelette continues to cook,
              carefully lift one edge and fold it over the fillings. Let it cook
              for another minute, then slide it onto a plate.
            </li>
            <li class="padElelist">
              <b>Enjoy:</b> Serve hot, with additional salt and pepper if
              needed.
            </li>
          </ol>
        </div>
        <hr />
        <div>
          <h2 class="fontColorBrown h2padding alignHeading">Nutrition</h2>
          <p class="fontColorStone">
            The table below shows nutritional values per serving without the
            additional fillings.
          </p>
          <table class="center" style="margin-bottom: 30px;">
            <tr>
              <td class="fontColorStone centerText padTD relativeTD">Calories</td>
              <td class="fontColorBrown relativeTDsecond">277kcal</td>
            </tr>
            <tr>
              <td class="fontColorStone centerText padTD relativeTD">Carbs</td>
              <td class="fontColorBrown relativeTDsecond">0g</td>
            </tr>
            <tr>
              <td class="fontColorStone centerText padTD relativeTD">Protein</td>
              <td class="fontColorBrown relativeTDsecond">20g</td>
            </tr>
            <tr>
              <td class="fontColorStone centerText padTD relativeTD">Fat</td>
              <td class="fontColorBrown relativeTDsecond">22g</td>
            </tr>
          </table>
        </div>
      </div>
    </section>

   <footer style="text-align: center; padding: 3rem;">
    <hr>
     <div class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by <a href="#">felipedvieira</a>.
  </footer>
  </body>
</html>
