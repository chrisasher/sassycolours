<h1>SassyColours</h1>

<p>Sassy colours is an easy way to automatically create beautiful colour schemes in Sass. Just follow the usage below</p>

// step 1 include _sassycolours scss
@import 'partials/sassycolours';

// rule options are:
// 'mono' (default - monochromatic)
// 'compound'
// 'complement' (complementary)
// 'split' (split complementary)
// 'triad'
// 'triad2'
// 'analog' (analogous)
// 'analog2' (analogous)

// there is a third boolean (true/false) option for grayscale, by default it is false.

// Just Call
$colour: sassycolours(#e86ea4, 'analog');

// then set the list items to a colour variable you will remember
$colour-1: nth($colour, 1);
$colour-2: nth($colour, 2);
$colour-3: nth($colour, 3);
$colour-4: nth($colour, 4);
$colour-5: nth($colour, 5);

