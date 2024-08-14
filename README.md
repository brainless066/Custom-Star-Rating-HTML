# Custom-Star-Rating-HTML
<style>
  .starsRating {
    /* Reset common inherited styles to their default values */
    all: unset;
    /* Unset all inherited styles */
    /* Reapply the styles you want to keep */
    position: relative;
    float: left;
    font-size: 10pt;
    height: 1em;
    line-height: 1em;
    /* Set other specific properties to default if needed */
    display: inline-block;
    /* Ensures it's inline element if 
	<p> or 
		<div> styles are block-level */
    white-space: nowrap;
  }

  .starsRating:before {
    content: "\2606\2606\2606\2606\2606";
    float: left;
    z-index: 1;
  }

  .starsRating .percent {
    position: absolute;
    left: 0;
    float: left;
    overflow: hidden;
    z-index: -1;
  }

  .starsRating .percent:after {
    content: "\2605\2605\2605\2605\2605";
    color: rgb(255, 200, 0);
  }

  li {
    display: table;
  }
</style>
<ul>
  <li>
    <div class="starsRating">
      <div class="percent" style="width: 50%;">&#8203;</div>
    </div>
  </li>
</ul>
<ul>
  <li>
    <div class="starsRating">
      <div class="percent" style="width:  0%;"></div>
    </div>
  </li>
  <li>
    <div class="starsRating">
      <div class="percent" style="width: 10%;"></div>
    </div>
  </li>
  <li>
    <div class="starsRating">
      <div class="percent" style="width: 20%;"></div>
    </div>
  </li>
  <li>
    <div class="starsRating">
      <div class="percent" style="width: 30%;"></div>
    </div>
  </li>
  <li>
    <div class="starsRating">
      <div class="percent" style="width: 40%;"></div>
    </div>
  </li>
  <li>
    <div class="starsRating">
      <div class="percent" style="width: 50%;"></div>
    </div>
  </li>
  <li>
    <div class="starsRating">
      <div class="percent" style="width: 60%;"></div>
    </div>
  </li>
  <li>
    <div class="starsRating">
      <div class="percent" style="width: 70%;"></div>
    </div>
  </li>
  <li>
    <div class="starsRating">
      <div class="percent" style="width: 80%;"></div>
    </div>
  </li>
  <li>
    <div class="starsRating">
      <div class="percent" style="width: 90%;"></div>
    </div>
  </li>
  <li>
    <div class="starsRating">
      <div class="percent" style="width: 100%;"></div>
    </div>
  </li>
</ul>
