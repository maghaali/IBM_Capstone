<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />

<title>report</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>



<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook-f:before,
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-feed:before,
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before,
.fa-gratipay:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper-pp:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-resistance:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
div.traceback-wrapper pre.traceback {
  max-height: 600px;
  overflow: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 5px;
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
[dir="rtl"] #ipython_notebook {
  margin-right: 10px;
  margin-left: 0;
}
[dir="rtl"] #ipython_notebook.pull-left {
  float: right !important;
  float: right;
}
.flex-spacer {
  flex: 1;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#kernel_logo_widget {
  margin: 0 10px;
}
span#login_widget {
  float: right;
}
[dir="rtl"] span#login_widget {
  float: left;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
.modal-header {
  cursor: move;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
[dir="rtl"] .center-nav form.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] .center-nav .navbar-text {
  float: right;
}
[dir="rtl"] .navbar-inner {
  text-align: right;
}
[dir="rtl"] div.text-left {
  text-align: right;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
  opacity: 0;
  z-index: 2;
}
.alternate_upload .btn-xs > input.fileinput {
  margin: -1px -5px;
}
.alternate_upload .btn-upload {
  position: relative;
  height: 22px;
}
::-webkit-file-upload-button {
  cursor: pointer;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
[dir="rtl"] ul#tabs.nav-tabs > li {
  float: right;
}
[dir="rtl"] ul#tabs.nav.nav-tabs {
  padding-right: 0;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons .pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .list_toolbar .col-sm-4,
[dir="rtl"] .list_toolbar .col-sm-8 {
  float: right;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: text-bottom;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
[dir="rtl"] .list_item > div input {
  margin-right: 0;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_modified {
  margin-right: 7px;
  margin-left: 7px;
}
[dir="rtl"] .item_modified.pull-right {
  float: left !important;
  float: left;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
[dir="rtl"] .item_buttons.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .item_buttons .kernel-name {
  margin-left: 7px;
  float: right;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
.sort_button {
  display: inline-block;
  padding-left: 7px;
}
[dir="rtl"] .sort_button.pull-right {
  float: left !important;
  float: left;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
[dir="rtl"] #button-select-all.btn {
  float: right ;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
  margin-top: 2px;
  height: 16px;
}
[dir="rtl"] #select-all.pull-left {
  float: right !important;
  float: right;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
#new-menu .dropdown-header {
  font-size: 10px;
  border-bottom: 1px solid #e5e5e5;
  padding: 0 0 3px;
  margin: -3px 20px 0;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.move-button {
  display: none;
}
.download-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
.CodeMirror-dialog {
  background-color: #fff;
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI escape sequences */
/* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
.ansi-black-fg {
  color: #3E424D;
}
.ansi-black-bg {
  background-color: #3E424D;
}
.ansi-black-intense-fg {
  color: #282C36;
}
.ansi-black-intense-bg {
  background-color: #282C36;
}
.ansi-red-fg {
  color: #E75C58;
}
.ansi-red-bg {
  background-color: #E75C58;
}
.ansi-red-intense-fg {
  color: #B22B31;
}
.ansi-red-intense-bg {
  background-color: #B22B31;
}
.ansi-green-fg {
  color: #00A250;
}
.ansi-green-bg {
  background-color: #00A250;
}
.ansi-green-intense-fg {
  color: #007427;
}
.ansi-green-intense-bg {
  background-color: #007427;
}
.ansi-yellow-fg {
  color: #DDB62B;
}
.ansi-yellow-bg {
  background-color: #DDB62B;
}
.ansi-yellow-intense-fg {
  color: #B27D12;
}
.ansi-yellow-intense-bg {
  background-color: #B27D12;
}
.ansi-blue-fg {
  color: #208FFB;
}
.ansi-blue-bg {
  background-color: #208FFB;
}
.ansi-blue-intense-fg {
  color: #0065CA;
}
.ansi-blue-intense-bg {
  background-color: #0065CA;
}
.ansi-magenta-fg {
  color: #D160C4;
}
.ansi-magenta-bg {
  background-color: #D160C4;
}
.ansi-magenta-intense-fg {
  color: #A03196;
}
.ansi-magenta-intense-bg {
  background-color: #A03196;
}
.ansi-cyan-fg {
  color: #60C6C8;
}
.ansi-cyan-bg {
  background-color: #60C6C8;
}
.ansi-cyan-intense-fg {
  color: #258F8F;
}
.ansi-cyan-intense-bg {
  background-color: #258F8F;
}
.ansi-white-fg {
  color: #C5C1B4;
}
.ansi-white-bg {
  background-color: #C5C1B4;
}
.ansi-white-intense-fg {
  color: #A1A6B2;
}
.ansi-white-intense-bg {
  background-color: #A1A6B2;
}
.ansi-default-inverse-fg {
  color: #FFFFFF;
}
.ansi-default-inverse-bg {
  background-color: #000000;
}
.ansi-bold {
  font-weight: bold;
}
.ansi-underline {
  text-decoration: underline;
}
/* The following styles are deprecated an will be removed in a future version */
.ansibold {
  font-weight: bold;
}
.ansi-inverse {
  outline: 0.5px dotted;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  position: relative;
  overflow: visible;
}
div.cell:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: transparent;
}
div.cell.jupyter-soft-selected {
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected,
div.cell.selected.jupyter-soft-selected {
  border-color: #ababab;
}
div.cell.selected:before,
div.cell.selected.jupyter-soft-selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #42A5F5;
}
@media print {
  div.cell.selected,
  div.cell.selected.jupyter-soft-selected {
    border-color: transparent;
  }
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
}
.edit_mode div.cell.selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #66BB6A;
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
  padding: 0.4em 0;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
  padding: 0 0.4em;
  border: 0;
  border-radius: 0;
}
.CodeMirror-cursor {
  border-left: 1.4px solid black;
}
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .CodeMirror-cursor {
    border-left: 2px solid black;
  }
}
@media screen and (min-width: 4320px) {
  .CodeMirror-cursor {
    border-left: 4px solid black;
  }
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
div.output_area .mglyph > img {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 1px 0 1px 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul:not(.list-inline),
.rendered_html ol:not(.list-inline) {
  padding-left: 2em;
}
.rendered_html ul {
  list-style: disc;
}
.rendered_html ul ul {
  list-style: square;
  margin-top: 0;
}
.rendered_html ul ul ul {
  list-style: circle;
}
.rendered_html ol {
  list-style: decimal;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin-top: 0;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
  padding: 0px;
  background-color: #fff;
}
.rendered_html code {
  background-color: #eff0f1;
}
.rendered_html p code {
  padding: 1px 5px;
}
.rendered_html pre code {
  background-color: #fff;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  color: #000;
  font-size: 100%;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: none;
  border-collapse: collapse;
  border-spacing: 0;
  color: black;
  font-size: 12px;
  table-layout: fixed;
}
.rendered_html thead {
  border-bottom: 1px solid black;
  vertical-align: bottom;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html tbody tr:nth-child(odd) {
  background: #f5f5f5;
}
.rendered_html tbody tr:hover {
  background: rgba(66, 165, 245, 0.2);
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
.rendered_html .alert {
  margin-bottom: initial;
}
.rendered_html * + .alert {
  margin-top: 1em;
}
[dir="rtl"] .rendered_html p {
  text-align: right;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.rendered .rendered_html tr,
.text_cell.rendered .rendered_html th,
.text_cell.rendered .rendered_html td {
  max-width: none;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.text_cell .dropzone .input_area {
  border: 2px dashed #bababa;
  margin: -1px;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
.jupyter-keybindings {
  padding: 1px;
  line-height: 24px;
  border-bottom: 1px solid gray;
}
.jupyter-keybindings input {
  margin: 0;
  padding: 0;
  border: none;
}
.jupyter-keybindings i {
  padding: 6px;
}
.well code {
  background-color: #ffffff;
  border-color: #ababab;
  border-width: 1px;
  border-style: solid;
  padding: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.tags_button_container {
  width: 100%;
  display: flex;
}
.tag-container {
  display: flex;
  flex-direction: row;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
}
.tag-container > * {
  margin: 0 4px;
}
.remove-tag-btn {
  margin-left: 4px;
}
.tags-input {
  display: flex;
}
.cell-tag:last-child:after {
  content: "";
  position: absolute;
  right: 0;
  width: 40px;
  height: 100%;
  /* Fade to background color of cell toolbar */
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
}
.tags-input > * {
  margin-left: 4px;
}
.cell-tag,
.tags-input input,
.tags-input button {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  box-shadow: none;
  width: inherit;
  font-size: inherit;
  height: 22px;
  line-height: 22px;
  padding: 0px 4px;
  display: inline-block;
}
.cell-tag:focus,
.tags-input input:focus,
.tags-input button:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.cell-tag::-moz-placeholder,
.tags-input input::-moz-placeholder,
.tags-input button::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.cell-tag:-ms-input-placeholder,
.tags-input input:-ms-input-placeholder,
.tags-input button:-ms-input-placeholder {
  color: #999;
}
.cell-tag::-webkit-input-placeholder,
.tags-input input::-webkit-input-placeholder,
.tags-input button::-webkit-input-placeholder {
  color: #999;
}
.cell-tag::-ms-expand,
.tags-input input::-ms-expand,
.tags-input button::-ms-expand {
  border: 0;
  background-color: transparent;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
.cell-tag[readonly],
.tags-input input[readonly],
.tags-input button[readonly],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  background-color: #eeeeee;
  opacity: 1;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  cursor: not-allowed;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button {
  height: auto;
}
select.cell-tag,
select.tags-input input,
select.tags-input button {
  height: 30px;
  line-height: 30px;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button,
select[multiple].cell-tag,
select[multiple].tags-input input,
select[multiple].tags-input button {
  height: auto;
}
.cell-tag,
.tags-input button {
  padding: 0px 4px;
}
.cell-tag {
  background-color: #fff;
  white-space: nowrap;
}
.tags-input input[type=text]:focus {
  outline: none;
  box-shadow: none;
  border-color: #ccc;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
[dir="rtl"] #kernel_logo_widget {
  float: left !important;
  float: left;
}
.modal .modal-body .move-path {
  display: flex;
  flex-direction: row;
  justify-content: space;
  align-items: center;
}
.modal .modal-body .move-path .server-root {
  padding-right: 20px;
}
.modal .modal-body .move-path .path-input {
  flex: 1;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
[dir="rtl"] #menubar .navbar-toggle {
  float: right;
}
[dir="rtl"] #menubar .navbar-collapse {
  clear: right;
}
[dir="rtl"] #menubar .navbar-nav {
  float: right;
}
[dir="rtl"] #menubar .nav {
  padding-right: 0px;
}
[dir="rtl"] #menubar .navbar-nav > li {
  float: right;
}
[dir="rtl"] #menubar .navbar-right {
  float: left !important;
}
[dir="rtl"] ul.dropdown-menu {
  text-align: right;
  left: auto;
}
[dir="rtl"] ul#new-menu.dropdown-menu {
  right: auto;
  left: 0;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
[dir="rtl"] i.menu-icon.pull-right {
  float: left !important;
  float: left;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
[dir="rtl"] ul#help_menu li a {
  padding-left: 2.2em;
}
[dir="rtl"] ul#help_menu li a i {
  margin-right: 0;
  margin-left: -1.2em;
}
[dir="rtl"] ul#help_menu li a i.pull-right {
  float: left !important;
  float: left;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
[dir="rtl"] .dropdown-submenu > .dropdown-menu {
  right: 100%;
  margin-right: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
[dir="rtl"] .dropdown-submenu > a:after {
  float: left;
  content: "\f0d9";
  margin-right: 0;
  margin-left: -10px;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
[dir="rtl"] #notification_area {
  float: left !important;
  float: left;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] .indicator_area {
  float: left !important;
  float: left;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
[dir="rtl"] #kernel_indicator {
  float: left !important;
  float: left;
  border-left: 0;
  border-right: 1px solid;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] #modal_indicator {
  float: left !important;
  float: left;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  height: 30px;
  margin-top: 4px;
  display: flex;
  justify-content: flex-start;
  align-items: baseline;
  width: 50%;
  flex: 1;
}
span.save_widget span.filename {
  height: 100%;
  line-height: 1em;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
[dir="rtl"] span.save_widget.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] span.save_widget span.filename {
  margin-left: 0;
  margin-right: 16px;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
  white-space: nowrap;
  padding: 0 5px;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
    padding: 0 0 0 5px;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
.toolbar-btn-label {
  margin-left: 6px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
[dir="rtl"] .btn-group > .btn,
.btn-group-vertical > .btn {
  float: right;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
[dir="rtl"] ul.typeahead-list i {
  margin-left: 0;
  margin-right: -10px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
ul.typeahead-list  > li > a.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .typeahead-list {
  text-align: right;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  min-width: 20px;
  color: transparent;
}
[dir="rtl"] .no-shortcut.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .command-shortcut.pull-right {
  float: left !important;
  float: left;
}
.command-shortcut:before {
  content: "(command mode)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
[dir="rtl"] .edit-shortcut.pull-right {
  float: left !important;
  float: left;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
[dir="ltr"] #find-and-replace .input-group-btn + .form-control {
  border-left: none;
}
[dir="rtl"] #find-and-replace .input-group-btn + .form-control {
  border-right: none;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Final-project-of-the-IBM-Data-Science-Professional-Certificate">Final project of the <strong><em>IBM Data Science Professional Certificate</em></strong><a class="anchor-link" href="#Final-project-of-the-IBM-Data-Science-Professional-Certificate">&#182;</a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h5 id="Title:-City-guide-of-Vancouver,-BC,-Canada"><strong>Title</strong>: <em>City guide of Vancouver, BC, Canada</em><a class="anchor-link" href="#Title:-City-guide-of-Vancouver,-BC,-Canada">&#182;</a></h5><h5 id="Description:-The-best-hotels,-restaurants-and-urban-places-in-&quot;Vancouver,-BC,-Canada&quot;-that-are-close-to-the-public-transportation-system,-such-as-buses-or-subways,-to-help-tourists-have-a-better-and-cheaper-experience."><strong>Description</strong>: <em>The best hotels, restaurants and urban places in "Vancouver, BC, Canada" that are close to the public transportation system, such as buses or subways, to help tourists have a better and cheaper experience.</em><a class="anchor-link" href="#Description:-The-best-hotels,-restaurants-and-urban-places-in-&quot;Vancouver,-BC,-Canada&quot;-that-are-close-to-the-public-transportation-system,-such-as-buses-or-subways,-to-help-tourists-have-a-better-and-cheaper-experience.">&#182;</a></h5><h5 id="Steps:"><strong>Steps</strong>:<a class="anchor-link" href="#Steps:">&#182;</a></h5><ul>
<li>##### Sign up for Foursquare developer account, to be able to use Foursquare's API</li>
<li>##### Retrieve information of urban places, hotels, restaurants, bus stops and metro stations with sequentially names as urban_jo, hotel_jo, rest_jo, bus_jo, metro_jo (Note that they are json files)</li>
<li>##### Based on their id value retrieve rating of places and filter to have best ones (over 7)</li>
<li>##### Cleansing data</li>
<li>##### Retrieve Latitude, Longitude, user rate, name, type of each title and put them into pandas DataFrame with sequentially names as urban_df, hotel_df, rest_df, bus_df, metro_df</li>
<li>##### Last step is visualizing our data on map with Folium Library</li>
</ul>
<h5 id="Question:-How-it-can-help-tourist?"><strong>Question</strong>: <em>How it can help tourist?</em><a class="anchor-link" href="#Question:-How-it-can-help-tourist?">&#182;</a></h5><ul>
<li>##### This report will create an object of best hotels, restaurants, urban places and available metro and bus stations on map with exact location so tourist can make a good plan for his/her travel to Vancouver which plac he/she want to stay at and diversity of hugh rank urban places to go and visit them</li>
</ul>
<h5 id="Reporter-github:--https://github.com/spacelover92"><strong>Reporter github</strong>:  <em><a href="https://github.com/spacelover92">https://github.com/spacelover92</a></em><a class="anchor-link" href="#Reporter-github:--https://github.com/spacelover92">&#182;</a></h5>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="1.-Import-necessary-Libraries">1. Import necessary Libraries<a class="anchor-link" href="#1.-Import-necessary-Libraries">&#182;</a></h3>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[1]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">requests</span> <span class="c1"># library to handle requests</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span> <span class="c1"># library for data analsysis</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span> <span class="c1"># library to handle data in a vectorized manner</span>
<span class="kn">import</span> <span class="nn">random</span> <span class="c1"># library for random number generation</span>

<span class="c1"># libraries for displaying images</span>
<span class="kn">from</span> <span class="nn">IPython.display</span> <span class="kn">import</span> <span class="n">Image</span> 
<span class="kn">from</span> <span class="nn">IPython.core.display</span> <span class="kn">import</span> <span class="n">HTML</span> 
    
<span class="c1"># tranforming json file into a pandas dataframe library</span>
<span class="kn">from</span> <span class="nn">pandas.io.json</span> <span class="kn">import</span> <span class="n">json_normalize</span>

<span class="kn">import</span> <span class="nn">folium</span> <span class="c1"># plotting library</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="In-this-part-of-notebook-we're-going-to-create-a-dataframe-of-all-high-rank-(over-7)-hotels-of-&quot;Vancouver,-BC,-Canada&quot;">In this part of notebook we're going to create a dataframe of all high rank (over 7) hotels of "Vancouver, BC, Canada"<a class="anchor-link" href="#In-this-part-of-notebook-we're-going-to-create-a-dataframe-of-all-high-rank-(over-7)-hotels-of-&quot;Vancouver,-BC,-Canada&quot;">&#182;</a></h4><h4 id="Final-result-will-save-into-&quot;hotel_df.csv&quot;-file">Final result will save into "hotel_df.csv" file<a class="anchor-link" href="#Final-result-will-save-into-&quot;hotel_df.csv&quot;-file">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="2.-Set-credentials-from-Foursquare-developer-website">2. Set credentials from Foursquare developer website<a class="anchor-link" href="#2.-Set-credentials-from-Foursquare-developer-website">&#182;</a></h3>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">CLIENT_ID</span> <span class="o">=</span> <span class="s1">&#39;&#39;</span>   <span class="c1"># put your client id</span>
<span class="n">CLIENT_SECRET</span> <span class="o">=</span> <span class="s1">&#39;&#39;</span>  <span class="c1"># put your client isecretd</span>
<span class="n">VERSION</span> <span class="o">=</span> <span class="s1">&#39;20201025&#39;</span>  <span class="c1"># set version #for example 20201025 means October 25, 2020</span>
<span class="n">LIMIT</span> <span class="o">=</span> <span class="mi">50</span> <span class="c1"># Number of requests</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="Note:-Since-we-are-going-to-explore-all-hotels-of-Vancouver-so-I-used-near-but-if-you-want-to-find-neighborhoods-of-specific-location-instead-of-near-you-must-use-ll-which-stands-for-latitude-and-longtitude-of-that-place">Note: Since we are going to explore all hotels of Vancouver so I used <em>near</em> but if you want to find neighborhoods of specific location instead of <em>near</em> you must use <em>ll</em> which stands for latitude and longtitude of that place<a class="anchor-link" href="#Note:-Since-we-are-going-to-explore-all-hotels-of-Vancouver-so-I-used-near-but-if-you-want-to-find-neighborhoods-of-specific-location-instead-of-near-you-must-use-ll-which-stands-for-latitude-and-longtitude-of-that-place">&#182;</a></h4><h4 id="Note:-search_quesry-is-used-which-specific-keywork-in-this-case-I-used-Hotel-to-find-all-hotels">Note: search_quesry is used which specific keywork in this case I used <em>Hotel</em> to find all hotels<a class="anchor-link" href="#Note:-search_quesry-is-used-which-specific-keywork-in-this-case-I-used-Hotel-to-find-all-hotels">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">NEAR</span> <span class="o">=</span> <span class="s1">&#39;Vancouver,BC,Canada&#39;</span>
<span class="n">search_query</span> <span class="o">=</span> <span class="s1">&#39;Hotel&#39;</span> 
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="3.-Define-the-corresponding-URL">3. Define the corresponding URL<a class="anchor-link" href="#3.-Define-the-corresponding-URL">&#182;</a></h4><h5 id="Now,-it's-time-to-create-our-url-based-on-documentation-of-Foursquare-API">Now, it's time to create our <em>url</em> based on documentation of Foursquare API<a class="anchor-link" href="#Now,-it's-time-to-create-our-url-based-on-documentation-of-Foursquare-API">&#182;</a></h5>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[4]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://api.foursquare.com/v2/venues/search?client_id=</span><span class="si">{}</span><span class="s1">&amp;client_secret=</span><span class="si">{}</span><span class="s1">&amp;near=</span><span class="si">{}</span><span class="s1">&amp;v=</span><span class="si">{}</span><span class="s1">&amp;query=</span><span class="si">{}</span><span class="s1">&amp;limit=</span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">CLIENT_ID</span><span class="p">,</span> 
                                                                                                                         <span class="n">CLIENT_SECRET</span><span class="p">,</span> 
                                                                                                                         <span class="n">NEAR</span><span class="p">,</span> 
                                                                                                                         <span class="n">VERSION</span><span class="p">,</span> 
                                                                                                                         <span class="n">search_query</span><span class="p">,</span>  
                                                                                                                         <span class="n">LIMIT</span><span class="p">)</span>
<span class="n">url</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[4]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&#39;https://api.foursquare.com/v2/venues/search?client_id=M0NI1LWGR33KCW3MNT1E3MTJIV1RT0W2VVCLFFFRNTUNKEYL&amp;client_secret=51ULMM5KM3ABRORQ45Z545UWQFJLRCGSPXUTABRIVDELSPHH&amp;near=Vancouver,BC,Canada&amp;v=20201025&amp;query=Hotel&amp;limit=50&#39;</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="4.-Send-the-GET-Request-and-examine-the-hotel_jo">4. Send the GET Request and examine the hotel_jo<a class="anchor-link" href="#4.-Send-the-GET-Request-and-examine-the-hotel_jo">&#182;</a></h4><h5 id="With-line-below-we-are-going-to-retrieve-our-data-and-save-it-as-a-json-file-in-hotel_jo">With line below we are going to retrieve our data and save it as a json file in hotel_jo<a class="anchor-link" href="#With-line-below-we-are-going-to-retrieve-our-data-and-save-it-as-a-json-file-in-hotel_jo">&#182;</a></h5>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[6]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">hotel_jo</span> <span class="o">=</span> <span class="n">requests</span><span class="o">.</span><span class="n">get</span><span class="p">(</span><span class="n">url</span><span class="p">)</span><span class="o">.</span><span class="n">json</span><span class="p">()</span>
<span class="n">hotel_jo</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[6]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>{&#39;meta&#39;: {&#39;code&#39;: 200, &#39;requestId&#39;: &#39;5f94f9719d7cfa6c1bb4e777&#39;},
 &#39;response&#39;: {&#39;venues&#39;: [{&#39;id&#39;: &#39;4aa738def964a520594c20e3&#39;,
    &#39;name&#39;: &#39;Opus Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;322 Davie St.&#39;,
     &#39;crossStreet&#39;: &#39;at Hamilton St.&#39;,
     &#39;lat&#39;: 49.274654423320435,
     &#39;lng&#39;: -123.12233189716328,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.274654423320435,
       &#39;lng&#39;: -123.12233189716328}],
     &#39;postalCode&#39;: &#39;V6B 5Z6&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;322 Davie St. (at Hamilton St.)&#39;,
      &#39;Vancouver BC V6B 5Z6&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4bd09a421f89ce723fb967ea&#39;,
    &#39;name&#39;: &#39;The Sylvia Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1154 Gilford St&#39;,
     &#39;lat&#39;: 49.288784,
     &#39;lng&#39;: -123.142615,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.288784,
       &#39;lng&#39;: -123.142615}],
     &#39;postalCode&#39;: &#39;V6G 2P6&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1154 Gilford St&#39;,
      &#39;Vancouver BC V6G 2P6&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4b0ae864f964a520d72923e3&#39;,
    &#39;name&#39;: &#39;Executive Hotel Vintage Park&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1379 Howe St.&#39;,
     &#39;crossStreet&#39;: &#39;at Pacific St.&#39;,
     &#39;lat&#39;: 49.27591745566755,
     &#39;lng&#39;: -123.1303168826212,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.27591745566755,
       &#39;lng&#39;: -123.1303168826212}],
     &#39;postalCode&#39;: &#39;V6Z 2R5&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1379 Howe St. (at Pacific St.)&#39;,
      &#39;Vancouver BC V6Z 2R5&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4ee7d0330aaf40cac3cd958b&#39;,
    &#39;name&#39;: &#39;Executive Plaza Hotel&#39;,
    &#39;location&#39;: {&#39;lat&#39;: 49.26336582709051,
     &#39;lng&#39;: -123.13461542129517,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.26336582709051,
       &#39;lng&#39;: -123.13461542129517}],
     &#39;postalCode&#39;: &#39;V6H 1H2&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;Vancouver BC V6H 1H2&#39;, &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4ba56584f964a520150339e3&#39;,
    &#39;name&#39;: &#39;Best Western Plus Uptown Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;205 Kingsway&#39;,
     &#39;lat&#39;: 49.26176997209943,
     &#39;lng&#39;: -123.09808201270062,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.26176997209943,
       &#39;lng&#39;: -123.09808201270062}],
     &#39;postalCode&#39;: &#39;V5T 3J5&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;205 Kingsway&#39;, &#39;Vancouver BC V5T 3J5&#39;, &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4d188bfcbb64224b4108c865&#39;,
    &#39;name&#39;: &#39;City Centre Motor Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;2111 Main St.&#39;,
     &#39;crossStreet&#39;: &#39;at 6th Ave.&#39;,
     &#39;lat&#39;: 49.265615514386646,
     &#39;lng&#39;: -123.10127506393786,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.265615514386646,
       &#39;lng&#39;: -123.10127506393786}],
     &#39;postalCode&#39;: &#39;V5T 3C6&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;2111 Main St. (at 6th Ave.)&#39;,
      &#39;Vancouver BC V5T 3C6&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fb931735&#39;,
      &#39;name&#39;: &#39;Motel&#39;,
      &#39;pluralName&#39;: &#39;Motels&#39;,
      &#39;shortName&#39;: &#39;Motel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4bd5c5589649ce7223a6511d&#39;,
    &#39;name&#39;: &#39;Holiday Inn Hotel &amp; Suites Vancouver Downtown&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1110 Howe Street&#39;,
     &#39;lat&#39;: 49.2785379,
     &#39;lng&#39;: -123.1256485,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.2785379,
       &#39;lng&#39;: -123.1256485}],
     &#39;postalCode&#39;: &#39;V6Z 1R2&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1110 Howe Street&#39;,
      &#39;Vancouver BC V6Z 1R2&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4af0f4e4f964a5204ae021e3&#39;,
    &#39;name&#39;: &#39;The Fairmont Hotel Vancouver&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;900 West Georgia Street&#39;,
     &#39;crossStreet&#39;: &#39;btwn Burrard &amp; Hornby&#39;,
     &#39;lat&#39;: 49.283805486323196,
     &#39;lng&#39;: -123.120944,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.283805486323196,
       &#39;lng&#39;: -123.120944}],
     &#39;postalCode&#39;: &#39;V6C 2W6&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;900 West Georgia Street (btwn Burrard &amp; Hornby)&#39;,
      &#39;Vancouver BC V6C 2W6&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4d5ec8ce29ef236ae0cb9059&#39;,
    &#39;name&#39;: &#39;Rosewood Hotel Georgia&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;801 W Georgia St&#39;,
     &#39;crossStreet&#39;: &#39;at Howe St&#39;,
     &#39;lat&#39;: 49.28342914255638,
     &#39;lng&#39;: -123.1189107326352,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.28342914255638,
       &#39;lng&#39;: -123.1189107326352}],
     &#39;postalCode&#39;: &#39;V6C 1P7&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;801 W Georgia St (at Howe St)&#39;,
      &#39;Vancouver BC V6C 1P7&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;37012938&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4aab4f20f964a520615920e3&#39;,
    &#39;name&#39;: &#39;Century Plaza Hotel &amp; Spa&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1015 Burrard St&#39;,
     &#39;crossStreet&#39;: &#39;@ Nelson St&#39;,
     &#39;lat&#39;: 49.28065690166794,
     &#39;lng&#39;: -123.12684048007954,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.28065690166794,
       &#39;lng&#39;: -123.12684048007954}],
     &#39;postalCode&#39;: &#39;V6Z 1Y5&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1015 Burrard St (@ Nelson St)&#39;,
      &#39;Vancouver BC V6Z 1Y5&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4b9b2307f964a5206df535e3&#39;,
    &#39;name&#39;: &#39;Best Western Plus Chateau Granville Hotel &amp; Suites &amp; Conference Ctr.&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1100 Granville St&#39;,
     &#39;crossStreet&#39;: &#39;at Helmcken St.&#39;,
     &#39;lat&#39;: 49.277823,
     &#39;lng&#39;: -123.12463,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.277823,
       &#39;lng&#39;: -123.12463}],
     &#39;postalCode&#39;: &#39;V6Z 2B6&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1100 Granville St (at Helmcken St.)&#39;,
      &#39;Vancouver BC V6Z 2B6&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;36728873&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4aa74575f964a5208f4c20e3&#39;,
    &#39;name&#39;: &#39;Sutton Place Hotel Vancouver&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;845 Burrard Street&#39;,
     &#39;crossStreet&#39;: &#39;btwn Smithe St &amp; Robson St&#39;,
     &#39;lat&#39;: 49.28264004904225,
     &#39;lng&#39;: -123.12387529266849,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.28264004904225,
       &#39;lng&#39;: -123.12387529266849}],
     &#39;postalCode&#39;: &#39;V6Z 2K6&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;845 Burrard Street (btwn Smithe St &amp; Robson St)&#39;,
      &#39;Vancouver BC V6Z 2K6&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;584836110&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4a8e147cf964a520fc1120e3&#39;,
    &#39;name&#39;: &#39;Sandman Hotel Vancouver City Centre&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;180 W. Georgia Street&#39;,
     &#39;crossStreet&#39;: &#39;Cambie St&#39;,
     &#39;lat&#39;: 49.27923800244187,
     &#39;lng&#39;: -123.112841119878,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.27923800244187,
       &#39;lng&#39;: -123.112841119878}],
     &#39;postalCode&#39;: &#39;V6B 4P4&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;180 W. Georgia Street (Cambie St)&#39;,
      &#39;Vancouver BC V6B 4P4&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4b806d95f964a5206e7130e3&#39;,
    &#39;name&#39;: &#39;Riviera on Robson Suites Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1431 Robson St&#39;,
     &#39;lat&#39;: 49.28835687769901,
     &#39;lng&#39;: -123.13020061543632,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.28835687769901,
       &#39;lng&#39;: -123.13020061543632}],
     &#39;postalCode&#39;: &#39;V6G 1C3&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1431 Robson St&#39;, &#39;Vancouver BC V6G 1C3&#39;, &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4aab548ef964a520725920e3&#39;,
    &#39;name&#39;: &#39;Hotel LeSoleil&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;567 Hornby Street&#39;,
     &#39;crossStreet&#39;: &#39;btn W Pender and Dunsmuir&#39;,
     &#39;lat&#39;: 49.285332091018624,
     &#39;lng&#39;: -123.11811069694004,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.285332091018624,
       &#39;lng&#39;: -123.11811069694004}],
     &#39;postalCode&#39;: &#39;V6C 2E8&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;567 Hornby Street (btn W Pender and Dunsmuir)&#39;,
      &#39;Vancouver BC V6C 2E8&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4aab4ce8f964a5205a5920e3&#39;,
    &#39;name&#39;: &#39;Vancouver Marriott Pinnacle Downtown Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1128 West Hastings Street&#39;,
     &#39;lat&#39;: 49.28778960562971,
     &#39;lng&#39;: -123.12036466521064,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.28778960562971,
       &#39;lng&#39;: -123.12036466521064}],
     &#39;postalCode&#39;: &#39;V6E 4R5&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1128 West Hastings Street&#39;,
      &#39;Vancouver BC V6E 4R5&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;129932557&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4abe5a61f964a520ec8c20e3&#39;,
    &#39;name&#39;: &#39;Four Seasons Hotel Vancouver&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;791 West Georgia Street&#39;,
     &#39;lat&#39;: 49.283210306080946,
     &#39;lng&#39;: -123.1184071919454,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.283210306080946,
       &#39;lng&#39;: -123.1184071919454}],
     &#39;postalCode&#39;: &#39;V6C 2T4&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;791 West Georgia Street&#39;,
      &#39;Vancouver BC V6C 2T4&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4acd3910f964a5207dcb20e3&#39;,
    &#39;name&#39;: &#39;Shangri-La Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1128 West Georgia St.&#39;,
     &#39;crossStreet&#39;: &#39;Thurlow&#39;,
     &#39;lat&#39;: 49.28593423238485,
     &#39;lng&#39;: -123.12408050709615,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.28593423238485,
       &#39;lng&#39;: -123.12408050709615}],
     &#39;postalCode&#39;: &#39;V6E 0A8&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1128 West Georgia St. (Thurlow)&#39;,
      &#39;Vancouver BC V6E 0A8&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4b7cf5e1f964a52066aa2fe3&#39;,
    &#39;name&#39;: &#39;Hotel at the Waldorf&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1489 E Hastings St&#39;,
     &#39;crossStreet&#39;: &#39;btwn Commercial &amp; Clark&#39;,
     &#39;lat&#39;: 49.28145565110179,
     &#39;lng&#39;: -123.07463277709543,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.28145565110179,
       &#39;lng&#39;: -123.07463277709543}],
     &#39;postalCode&#39;: &#39;V5L 1S4&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1489 E Hastings St (btwn Commercial &amp; Clark)&#39;,
      &#39;Vancouver BC V5L 1S4&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;86415534&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4b99e544f964a5201f9635e3&#39;,
    &#39;name&#39;: &#39;Georgian Court Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;773 Beatty St&#39;,
     &#39;crossStreet&#39;: &#39;btw Robson St. and Georgia St.&#39;,
     &#39;lat&#39;: 49.278236627377424,
     &#39;lng&#39;: -123.11348480489346,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.278236627377424,
       &#39;lng&#39;: -123.11348480489346}],
     &#39;postalCode&#39;: &#39;V6B 2M4&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;773 Beatty St (btw Robson St. and Georgia St.)&#39;,
      &#39;Vancouver BC V6B 2M4&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;47719517&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4aab560af964a520785920e3&#39;,
    &#39;name&#39;: &#39;Metropolitan Hotel Vancouver&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;645 Howe Street&#39;,
     &#39;lat&#39;: 49.2841801,
     &#39;lng&#39;: -123.1184303,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.2841801,
       &#39;lng&#39;: -123.1184303}],
     &#39;postalCode&#39;: &#39;V6C 2Y9&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;645 Howe Street&#39;,
      &#39;Vancouver BC V6C 2Y9&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4af2380af964a520aae621e3&#39;,
    &#39;name&#39;: &#39;YWCA Hotel/Residence&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;733 Beatty St.&#39;,
     &#39;crossStreet&#39;: &#39;Off Robson St.&#39;,
     &#39;lat&#39;: 49.27841416220364,
     &#39;lng&#39;: -123.11276964174914,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.27841416220364,
       &#39;lng&#39;: -123.11276964174914}],
     &#39;postalCode&#39;: &#39;V6B 4P4&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;733 Beatty St. (Off Robson St.)&#39;,
      &#39;Vancouver BC V6B 4P4&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;45901530&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4ba7ce4ef964a520fbb439e3&#39;,
    &#39;name&#39;: &#39;Vancouver Airport Marriott Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;7571 Westminster Highway&#39;,
     &#39;lat&#39;: 49.17056189669989,
     &#39;lng&#39;: -123.14062854509757,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.17056189669989,
       &#39;lng&#39;: -123.14062854509757}],
     &#39;postalCode&#39;: &#39;V6X 1A3&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Richmond&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;7571 Westminster Highway&#39;,
      &#39;Richmond BC V6X 1A3&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;129932558&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;51c2302d498e6c1fcae32130&#39;,
    &#39;name&#39;: &#39;Trump International Hotel &amp; Tower® Vancouver&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1161 W Georgia St&#39;,
     &#39;crossStreet&#39;: &#39;Bute Street&#39;,
     &#39;lat&#39;: 49.2865695,
     &#39;lng&#39;: -123.1244027,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.2865695,
       &#39;lng&#39;: -123.1244027}],
     &#39;postalCode&#39;: &#39;V6E 0C6&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1161 W Georgia St (Bute Street)&#39;,
      &#39;Vancouver BC V6E 0C6&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4ad5f692f964a520350421e3&#39;,
    &#39;name&#39;: &#39;Coast Coal Harbour Vancouver Hotel by APA&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1180 West Hastings&#39;,
     &#39;crossStreet&#39;: &#39;Hastings &amp; Bute&#39;,
     &#39;lat&#39;: 49.288401,
     &#39;lng&#39;: -123.122343,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.288401,
       &#39;lng&#39;: -123.122343}],
     &#39;postalCode&#39;: &#39;V6E 4R5&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1180 West Hastings (Hastings &amp; Bute)&#39;,
      &#39;Vancouver BC V6E 4R5&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;512550599&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4ca0679019e4236abef06089&#39;,
    &#39;name&#39;: &#39;Greenbrier Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1393 Robson Street&#39;,
     &#39;lat&#39;: 49.287912665171234,
     &#39;lng&#39;: -123.12960045288793,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.287912665171234,
       &#39;lng&#39;: -123.12960045288793}],
     &#39;postalCode&#39;: &#39;V6E 1C3&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1393 Robson Street&#39;,
      &#39;Vancouver BC V6E 1C3&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;85501752&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;580cdb3dd67cd129a2200731&#39;,
    &#39;name&#39;: &#39;Health Club at Sheraton Vancouver Wall Center Hotel&#39;,
    &#39;location&#39;: {&#39;lat&#39;: 49.280777,
     &#39;lng&#39;: -123.125984,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.280777,
       &#39;lng&#39;: -123.125984}],
     &#39;postalCode&#39;: &#39;V6Z 2R9&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;Vancouver BC V6Z 2R9&#39;, &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d175941735&#39;,
      &#39;name&#39;: &#39;Gym / Fitness Center&#39;,
      &#39;pluralName&#39;: &#39;Gyms or Fitness Centers&#39;,
      &#39;shortName&#39;: &#39;Gym / Fitness&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/building/gym_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4dc5f785887717c880324075&#39;,
    &#39;name&#39;: &#39;St. Clair Hotel - Hostel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;577 Richards St.&#39;,
     &#39;crossStreet&#39;: &#39;btwn W Hastings &amp; Dunsmuir&#39;,
     &#39;lat&#39;: 49.2827361940718,
     &#39;lng&#39;: -123.11442132599076,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.2827361940718,
       &#39;lng&#39;: -123.11442132599076}],
     &#39;postalCode&#39;: &#39;V6B 2Z5&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;577 Richards St. (btwn W Hastings &amp; Dunsmuir)&#39;,
      &#39;Vancouver BC V6B 2Z5&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4aeca6c6f964a520eec921e3&#39;,
    &#39;name&#39;: &#39;The Kingston Hotel Bed and Breakfast&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;757 Richards Street&#39;,
     &#39;crossStreet&#39;: &#39;Between Robson + Georgia&#39;,
     &#39;lat&#39;: 49.28072220584647,
     &#39;lng&#39;: -123.11718508887402,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.28072220584647,
       &#39;lng&#39;: -123.11718508887402}],
     &#39;postalCode&#39;: &#39;V6B 3A6&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;757 Richards Street (Between Robson + Georgia)&#39;,
      &#39;Vancouver BC V6B 3A6&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4bd09a3f1f89ce723bb967ea&#39;,
    &#39;name&#39;: &#39;Victorian Hotel Vancouver&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;514 Homer St Vancouver BC Canada&#39;,
     &#39;crossStreet&#39;: &#39;Pender&#39;,
     &#39;lat&#39;: 49.28251724902659,
     &#39;lng&#39;: -123.11214421109624,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.28251724902659,
       &#39;lng&#39;: -123.11214421109624}],
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;514 Homer St Vancouver BC Canada (Pender)&#39;,
      &#39;Vancouver BC&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4f66afede4b0bf1013f09271&#39;,
    &#39;name&#39;: &#39;1606 @ Century Plaza Hotel &amp; Spa&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1015 Burrard St.&#39;,
     &#39;crossStreet&#39;: &#39;Nelson St.&#39;,
     &#39;lat&#39;: 49.2810869018745,
     &#39;lng&#39;: -123.12706678675399,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.2810869018745,
       &#39;lng&#39;: -123.12706678675399}],
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1015 Burrard St. (Nelson St.)&#39;,
      &#39;Vancouver BC&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;533caeaa11d29c2479d8b64e&#39;,
    &#39;name&#39;: &#39;Burrard Hotel&#39;,
    &#39;location&#39;: {&#39;lat&#39;: 49.27988051110661,
     &#39;lng&#39;: -123.12732844239103,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.27988051110661,
       &#39;lng&#39;: -123.12732844239103}],
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;neighborhood&#39;: &#39;Financial District&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;Vancouver BC&#39;, &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4b7f88cbf964a520613330e3&#39;,
    &#39;name&#39;: &#39;West Hotel Bar&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;488 Carrall St&#39;,
     &#39;lat&#39;: 49.280578314366295,
     &#39;lng&#39;: -123.10430193695167,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.280578314366295,
       &#39;lng&#39;: -123.10430193695167}],
     &#39;postalCode&#39;: &#39;V6B 2J7&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;488 Carrall St&#39;, &#39;Vancouver BC V6B 2J7&#39;, &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d118941735&#39;,
      &#39;name&#39;: &#39;Dive Bar&#39;,
      &#39;pluralName&#39;: &#39;Dive Bars&#39;,
      &#39;shortName&#39;: &#39;Dive Bar&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/nightlife/divebar_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4bf0811f6f8aa593b1fcc13c&#39;,
    &#39;name&#39;: &#39;Sandman Hotel Vancouver Airport&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;3233 St. Edwards Drive&#39;,
     &#39;lat&#39;: 49.18731231982369,
     &#39;lng&#39;: -123.10991670043694,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.18731231982369,
       &#39;lng&#39;: -123.10991670043694}],
     &#39;postalCode&#39;: &#39;V6X 3K4&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Richmond&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;3233 St. Edwards Drive&#39;,
      &#39;Richmond BC V6X 3K4&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4d79718bb359f04d1f77c714&#39;,
    &#39;name&#39;: &#39;Shangri-La Hotel Gift Shop&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1128 W Georgia St&#39;,
     &#39;crossStreet&#39;: &#39;at Thurlow St&#39;,
     &#39;lat&#39;: 49.285843,
     &#39;lng&#39;: -123.123939,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.285843,
       &#39;lng&#39;: -123.123939}],
     &#39;postalCode&#39;: &#39;V6E 0A8&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1128 W Georgia St (at Thurlow St)&#39;,
      &#39;Vancouver BC V6E 0A8&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d128951735&#39;,
      &#39;name&#39;: &#39;Gift Shop&#39;,
      &#39;pluralName&#39;: &#39;Gift Shops&#39;,
      &#39;shortName&#39;: &#39;Gift Shop&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/shops/giftshop_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;50ef23afe4b04e0d11da9edd&#39;,
    &#39;name&#39;: &#39;Afternoon Tea At The Fairmont Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;900 West Georgia Street&#39;,
     &#39;lat&#39;: 49.28386047597524,
     &#39;lng&#39;: -123.1209028770766,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.28386047597524,
       &#39;lng&#39;: -123.1209028770766}],
     &#39;postalCode&#39;: &#39;V6C 2W6&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;900 West Georgia Street&#39;,
      &#39;Vancouver BC V6C 2W6&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1dc931735&#39;,
      &#39;name&#39;: &#39;Tea Room&#39;,
      &#39;pluralName&#39;: &#39;Tea Rooms&#39;,
      &#39;shortName&#39;: &#39;Tea Room&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/food/tearoom_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4aa8720df964a520545120e3&#39;,
    &#39;name&#39;: &#39;Plaza 500 Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;500 W. 12th Ave&#39;,
     &#39;crossStreet&#39;: &#39;Cambie&#39;,
     &#39;lat&#39;: 49.260282,
     &#39;lng&#39;: -123.115433,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.260282,
       &#39;lng&#39;: -123.115433}],
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;500 W. 12th Ave (Cambie)&#39;,
      &#39;Vancouver BC&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4bd744ae304fce722b4a33ab&#39;,
    &#39;name&#39;: &#39;Radisson Hotel Vancouver Airport&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;8181 Cambie Road&#39;,
     &#39;lat&#39;: 49.185186990585585,
     &#39;lng&#39;: -123.13548445701593,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.185186990585585,
       &#39;lng&#39;: -123.13548445701593}],
     &#39;postalCode&#39;: &#39;V6X 3X9&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Richmond&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;8181 Cambie Road&#39;,
      &#39;Richmond BC V6X 3X9&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;63943521&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4af32fb0f964a5208aeb21e3&#39;,
    &#39;name&#39;: &#39;Executive Airport Plaza Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;7311 Westminster Hwy.&#39;,
     &#39;lat&#39;: 49.17058434191942,
     &#39;lng&#39;: -123.14589652536898,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.17058434191942,
       &#39;lng&#39;: -123.14589652536898}],
     &#39;postalCode&#39;: &#39;V6X 1A3&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Richmond&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;7311 Westminster Hwy.&#39;,
      &#39;Richmond BC V6X 1A3&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;5d0475892632ec002c3700fd&#39;,
    &#39;name&#39;: &#39;Hotel Belmont&#39;,
    &#39;location&#39;: {&#39;lat&#39;: 49.2791,
     &#39;lng&#39;: -123.123085,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.2791,
       &#39;lng&#39;: -123.123085}],
     &#39;postalCode&#39;: &#39;V6B 6K4&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;Vancouver BC V6B 6K4&#39;, &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4ee524c5f790897ed1175fb5&#39;,
    &#39;name&#39;: &#39;Hotel Nathoo&#39;,
    &#39;location&#39;: {&#39;lat&#39;: 49.271329015509416,
     &#39;lng&#39;: -123.1239860132618,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.271329015509416,
       &#39;lng&#39;: -123.1239860132618}],
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;Vancouver BC&#39;, &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;536df916498e122752bc08a3&#39;,
    &#39;name&#39;: &#39;Hotel Blu&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;177 Robson Street&#39;,
     &#39;lat&#39;: 49.278342669044825,
     &#39;lng&#39;: -123.11444104804278,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.278342669044825,
       &#39;lng&#39;: -123.11444104804278}],
     &#39;postalCode&#39;: &#39;V6B 0N3&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;177 Robson Street&#39;,
      &#39;Vancouver BC V6B 0N3&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4bce3b55cc8cd13af40bc4cf&#39;,
    &#39;name&#39;: &#39;Pinnacle Hotel At The Pier&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;138 Victory Ship Way&#39;,
     &#39;crossStreet&#39;: &#39;Lonsdale and Esplanade&#39;,
     &#39;lat&#39;: 49.310460983581685,
     &#39;lng&#39;: -123.07896474929457,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.310460983581685,
       &#39;lng&#39;: -123.07896474929457}],
     &#39;postalCode&#39;: &#39;V7L 0B1&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;North Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;138 Victory Ship Way (Lonsdale and Esplanade)&#39;,
      &#39;North Vancouver BC V7L 0B1&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;90490185&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4aab4eb7f964a520605920e3&#39;,
    &#39;name&#39;: &#39;The Buchan Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1906 Haro Street&#39;,
     &#39;crossStreet&#39;: &#39;btn Chilco and Denman&#39;,
     &#39;lat&#39;: 49.2917255624254,
     &#39;lng&#39;: -123.1383758735297,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.2917255624254,
       &#39;lng&#39;: -123.1383758735297}],
     &#39;postalCode&#39;: &#39;V6G 1H7&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1906 Haro Street (btn Chilco and Denman)&#39;,
      &#39;Vancouver BC V6G 1H7&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4c69803e8d22c928fb66b745&#39;,
    &#39;name&#39;: &#39;The Lobby Restaurant at the Pinnacle Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;138 Victory Ship Way&#39;,
     &#39;crossStreet&#39;: &#39;Victory Ship Way &amp; Lonsdale&#39;,
     &#39;lat&#39;: 49.310415900015975,
     &#39;lng&#39;: -123.0791320677291,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.310415900015975,
       &#39;lng&#39;: -123.0791320677291}],
     &#39;postalCode&#39;: &#39;V7L 0B1&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;North Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;138 Victory Ship Way (Victory Ship Way &amp; Lonsdale)&#39;,
      &#39;North Vancouver BC V7L 0B1&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1c4941735&#39;,
      &#39;name&#39;: &#39;Restaurant&#39;,
      &#39;pluralName&#39;: &#39;Restaurants&#39;,
      &#39;shortName&#39;: &#39;Restaurant&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/food/default_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;venuePage&#39;: {&#39;id&#39;: &#39;90488288&#39;},
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4aab5297f964a5206c5920e3&#39;,
    &#39;name&#39;: &#39;Granville Island Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1253 Johnston St&#39;,
     &#39;crossStreet&#39;: &#39;by Cartwright St&#39;,
     &#39;lat&#39;: 49.2697671,
     &#39;lng&#39;: -123.1321867,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.2697671,
       &#39;lng&#39;: -123.1321867}],
     &#39;postalCode&#39;: &#39;V6H 3R9&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1253 Johnston St (by Cartwright St)&#39;,
      &#39;Vancouver BC V6H 3R9&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4bae5cd1f964a52007a83be3&#39;,
    &#39;name&#39;: &#39;Best Western Plus Burnaby Hotel And Conference Centre&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;5411 Kingsway&#39;,
     &#39;lat&#39;: 49.224288,
     &#39;lng&#39;: -122.9859723,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.224288,
       &#39;lng&#39;: -122.9859723}],
     &#39;postalCode&#39;: &#39;V5H 2G1&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Burnaby&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;5411 Kingsway&#39;, &#39;Burnaby BC V5H 2G1&#39;, &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4e3b97b78877b00cfc2e5102&#39;,
    &#39;name&#39;: &#39;Hotel Ambassador&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;1212 Granville Street&#39;,
     &#39;crossStreet&#39;: &#39;Davies&#39;,
     &#39;lat&#39;: 49.27692588502403,
     &#39;lng&#39;: -123.12635719243089,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.27692588502403,
       &#39;lng&#39;: -123.12635719243089}],
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;1212 Granville Street (Davies)&#39;,
      &#39;Vancouver BC&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4bd462c49854d13a0f74ff4d&#39;,
    &#39;name&#39;: &#39;Travelodge Hotel by Wyndham Vancouver Airport&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;3071 St. Edwards Dr&#39;,
     &#39;crossStreet&#39;: &#39;Bridgeport Rd&#39;,
     &#39;lat&#39;: 49.1914526019506,
     &#39;lng&#39;: -123.113041030517,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.1914526019506,
       &#39;lng&#39;: -123.113041030517}],
     &#39;postalCode&#39;: &#39;V6X 3K4&#39;,
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Richmond&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;3071 St. Edwards Dr (Bridgeport Rd)&#39;,
      &#39;Richmond BC V6X 3K4&#39;,
      &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False},
   {&#39;id&#39;: &#39;4f4b5308121dad8c5532ac16&#39;,
    &#39;name&#39;: &#39;Hodgson Hotel&#39;,
    &#39;location&#39;: {&#39;address&#39;: &#39;700 east 28th Avenue&#39;,
     &#39;lat&#39;: 49.245719003247686,
     &#39;lng&#39;: -123.09058427810669,
     &#39;labeledLatLngs&#39;: [{&#39;label&#39;: &#39;display&#39;,
       &#39;lat&#39;: 49.245719003247686,
       &#39;lng&#39;: -123.09058427810669}],
     &#39;cc&#39;: &#39;CA&#39;,
     &#39;city&#39;: &#39;Vancouver&#39;,
     &#39;state&#39;: &#39;BC&#39;,
     &#39;country&#39;: &#39;Canada&#39;,
     &#39;formattedAddress&#39;: [&#39;700 east 28th Avenue&#39;, &#39;Vancouver BC&#39;, &#39;Canada&#39;]},
    &#39;categories&#39;: [{&#39;id&#39;: &#39;4bf58dd8d48988d1fa931735&#39;,
      &#39;name&#39;: &#39;Hotel&#39;,
      &#39;pluralName&#39;: &#39;Hotels&#39;,
      &#39;shortName&#39;: &#39;Hotel&#39;,
      &#39;icon&#39;: {&#39;prefix&#39;: &#39;https://ss3.4sqi.net/img/categories_v2/travel/hotel_&#39;,
       &#39;suffix&#39;: &#39;.png&#39;},
      &#39;primary&#39;: True}],
    &#39;referralId&#39;: &#39;v-1603598705&#39;,
    &#39;hasPerk&#39;: False}],
  &#39;geocode&#39;: {&#39;what&#39;: &#39;&#39;,
   &#39;where&#39;: &#39;vancouver bc canada&#39;,
   &#39;feature&#39;: {&#39;cc&#39;: &#39;CA&#39;,
    &#39;name&#39;: &#39;Vancouver&#39;,
    &#39;displayName&#39;: &#39;Vancouver, BC, Canada&#39;,
    &#39;matchedName&#39;: &#39;Vancouver, BC, Canada&#39;,
    &#39;highlightedName&#39;: &#39;&lt;b&gt;Vancouver&lt;/b&gt;, &lt;b&gt;BC&lt;/b&gt;, &lt;b&gt;Canada&lt;/b&gt;&#39;,
    &#39;woeType&#39;: 7,
    &#39;slug&#39;: &#39;vancouver-british-columbia-canada&#39;,
    &#39;id&#39;: &#39;geonameid:6173331&#39;,
    &#39;longId&#39;: &#39;72057594044101267&#39;,
    &#39;geometry&#39;: {&#39;center&#39;: {&#39;lat&#39;: 49.24966, &#39;lng&#39;: -123.11934},
     &#39;bounds&#39;: {&#39;ne&#39;: {&#39;lat&#39;: 49.31439002686205, &#39;lng&#39;: -123.02296611995233},
      &#39;sw&#39;: {&#39;lat&#39;: 49.19840801038309, &#39;lng&#39;: -123.22524087683938}}}},
   &#39;parents&#39;: []}}}</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="4.-Get-relevant-part-of-JSON-and-transform-it-into-a-pandas-dataframe">4. Get relevant part of JSON and transform it into a <em>pandas</em> dataframe<a class="anchor-link" href="#4.-Get-relevant-part-of-JSON-and-transform-it-into-a-pandas-dataframe">&#182;</a></h4><h5 id="With-examining-json-above-we-are-going-to-retrieve-relevant-part-of-json-and-create-Pandas-DataFrame-based-on-them">With examining json above we are going to retrieve relevant part of json and create Pandas DataFrame based on them<a class="anchor-link" href="#With-examining-json-above-we-are-going-to-retrieve-relevant-part-of-json-and-create-Pandas-DataFrame-based-on-them">&#182;</a></h5>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[9]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># assign relevant part of JSON to venues</span>
<span class="n">venues</span> <span class="o">=</span> <span class="n">hotel_jo</span><span class="p">[</span><span class="s1">&#39;response&#39;</span><span class="p">][</span><span class="s1">&#39;venues&#39;</span><span class="p">]</span>

<span class="c1"># tranform venues into a dataframe</span>
<span class="n">dataframe</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">json_normalize</span><span class="p">(</span><span class="n">venues</span><span class="p">)</span>
<span class="n">dataframe</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[9]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>name</th>
      <th>categories</th>
      <th>referralId</th>
      <th>hasPerk</th>
      <th>location.address</th>
      <th>location.crossStreet</th>
      <th>location.lat</th>
      <th>location.lng</th>
      <th>location.labeledLatLngs</th>
      <th>location.postalCode</th>
      <th>location.cc</th>
      <th>location.city</th>
      <th>location.state</th>
      <th>location.country</th>
      <th>location.formattedAddress</th>
      <th>venuePage.id</th>
      <th>location.neighborhood</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>4aa738def964a520594c20e3</td>
      <td>Opus Hotel</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>322 Davie St.</td>
      <td>at Hamilton St.</td>
      <td>49.274654</td>
      <td>-123.122332</td>
      <td>[{'label': 'display', 'lat': 49.27465442332043...</td>
      <td>V6B 5Z6</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[322 Davie St. (at Hamilton St.), Vancouver BC...</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>4bd09a421f89ce723fb967ea</td>
      <td>The Sylvia Hotel</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>1154 Gilford St</td>
      <td>NaN</td>
      <td>49.288784</td>
      <td>-123.142615</td>
      <td>[{'label': 'display', 'lat': 49.288784, 'lng':...</td>
      <td>V6G 2P6</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[1154 Gilford St, Vancouver BC V6G 2P6, Canada]</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>4b0ae864f964a520d72923e3</td>
      <td>Executive Hotel Vintage Park</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>1379 Howe St.</td>
      <td>at Pacific St.</td>
      <td>49.275917</td>
      <td>-123.130317</td>
      <td>[{'label': 'display', 'lat': 49.27591745566755...</td>
      <td>V6Z 2R5</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[1379 Howe St. (at Pacific St.), Vancouver BC ...</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4ee7d0330aaf40cac3cd958b</td>
      <td>Executive Plaza Hotel</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>49.263366</td>
      <td>-123.134615</td>
      <td>[{'label': 'display', 'lat': 49.26336582709051...</td>
      <td>V6H 1H2</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[Vancouver BC V6H 1H2, Canada]</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4ba56584f964a520150339e3</td>
      <td>Best Western Plus Uptown Hotel</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>205 Kingsway</td>
      <td>NaN</td>
      <td>49.261770</td>
      <td>-123.098082</td>
      <td>[{'label': 'display', 'lat': 49.26176997209943...</td>
      <td>V5T 3J5</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[205 Kingsway, Vancouver BC V5T 3J5, Canada]</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="5.-Iteration-through-ID-of-hotels-to-find-ratings-and-store-them-in-new-data-frame">5. Iteration through ID of hotels to find ratings and store them in new data frame<a class="anchor-link" href="#5.-Iteration-through-ID-of-hotels-to-find-ratings-and-store-them-in-new-data-frame">&#182;</a></h4><h5 id="Whith-this-part-of-code-we-are-creating-new-url-for-each-id-in-dataframe-above-to-find-and-retrieve-rating-of-each-hotel-and-create-a-list-of-IDs-and-ratings-and-store-them-in-list_">Whith this part of code we are creating new url for each id in dataframe above to find and retrieve rating of each hotel and create a list of IDs and ratings and store them in list_<a class="anchor-link" href="#Whith-this-part-of-code-we-are-creating-new-url-for-each-id-in-dataframe-above-to-find-and-retrieve-rating-of-each-hotel-and-create-a-list-of-IDs-and-ratings-and-store-them-in-list_">&#182;</a></h5>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">list_</span> <span class="o">=</span> <span class="p">[]</span>
<span class="k">for</span> <span class="nb">id</span> <span class="ow">in</span> <span class="n">dataframe</span><span class="p">[</span><span class="s1">&#39;id&#39;</span><span class="p">]:</span>
    <span class="n">venue_id</span> <span class="o">=</span> <span class="nb">id</span>
    <span class="n">url</span> <span class="o">=</span> <span class="s1">&#39;https://api.foursquare.com/v2/venues/</span><span class="si">{}</span><span class="s1">?client_id=</span><span class="si">{}</span><span class="s1">&amp;client_secret=</span><span class="si">{}</span><span class="s1">&amp;v=</span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">venue_id</span><span class="p">,</span> <span class="n">CLIENT_ID</span><span class="p">,</span> <span class="n">CLIENT_SECRET</span><span class="p">,</span> <span class="n">VERSION</span><span class="p">)</span>
    <span class="n">result</span> <span class="o">=</span> <span class="n">requests</span><span class="o">.</span><span class="n">get</span><span class="p">(</span><span class="n">url</span><span class="p">)</span><span class="o">.</span><span class="n">json</span><span class="p">()</span>
    <span class="k">try</span><span class="p">:</span>
        <span class="n">list_</span><span class="o">.</span><span class="n">append</span><span class="p">([</span><span class="nb">id</span><span class="p">,</span><span class="n">result</span><span class="p">[</span><span class="s1">&#39;response&#39;</span><span class="p">][</span><span class="s1">&#39;venue&#39;</span><span class="p">][</span><span class="s1">&#39;rating&#39;</span><span class="p">]])</span>
    <span class="k">except</span><span class="p">:</span>
        <span class="k">continue</span> <span class="c1"># If hotel doesn&#39;t have rating we gently skip that hotel</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="Convert-rating-list-to-Pandas-DataFrame">Convert rating list to Pandas DataFrame<a class="anchor-link" href="#Convert-rating-list-to-Pandas-DataFrame">&#182;</a></h4><h6 id="Now,-we're-going-to-conver-our-list-to-Pandas-DataFrame">Now, we're going to conver our list to Pandas DataFrame<a class="anchor-link" href="#Now,-we're-going-to-conver-our-list-to-Pandas-DataFrame">&#182;</a></h6>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[36]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">list_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">list_</span><span class="p">)</span>
<span class="n">list_df</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[36]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>0</th>
      <th>1</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>4aa738def964a520594c20e3</td>
      <td>8.4</td>
    </tr>
    <tr>
      <th>1</th>
      <td>4bd09a421f89ce723fb967ea</td>
      <td>7.5</td>
    </tr>
    <tr>
      <th>2</th>
      <td>4b0ae864f964a520d72923e3</td>
      <td>5.3</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4ba56584f964a520150339e3</td>
      <td>6.1</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4d188bfcbb64224b4108c865</td>
      <td>5.4</td>
    </tr>
    <tr>
      <th>5</th>
      <td>4bd5c5589649ce7223a6511d</td>
      <td>6.6</td>
    </tr>
    <tr>
      <th>6</th>
      <td>4af0f4e4f964a5204ae021e3</td>
      <td>8.5</td>
    </tr>
    <tr>
      <th>7</th>
      <td>4d5ec8ce29ef236ae0cb9059</td>
      <td>9.3</td>
    </tr>
    <tr>
      <th>8</th>
      <td>4aab4f20f964a520615920e3</td>
      <td>6.0</td>
    </tr>
    <tr>
      <th>9</th>
      <td>4b9b2307f964a5206df535e3</td>
      <td>7.9</td>
    </tr>
    <tr>
      <th>10</th>
      <td>4aa74575f964a5208f4c20e3</td>
      <td>8.6</td>
    </tr>
    <tr>
      <th>11</th>
      <td>4a8e147cf964a520fc1120e3</td>
      <td>5.4</td>
    </tr>
    <tr>
      <th>12</th>
      <td>4b806d95f964a5206e7130e3</td>
      <td>5.6</td>
    </tr>
    <tr>
      <th>13</th>
      <td>4aab548ef964a520725920e3</td>
      <td>8.3</td>
    </tr>
    <tr>
      <th>14</th>
      <td>4aab4ce8f964a5205a5920e3</td>
      <td>7.5</td>
    </tr>
    <tr>
      <th>15</th>
      <td>4abe5a61f964a520ec8c20e3</td>
      <td>8.0</td>
    </tr>
    <tr>
      <th>16</th>
      <td>4acd3910f964a5207dcb20e3</td>
      <td>8.6</td>
    </tr>
    <tr>
      <th>17</th>
      <td>4b7cf5e1f964a52066aa2fe3</td>
      <td>6.1</td>
    </tr>
    <tr>
      <th>18</th>
      <td>4b99e544f964a5201f9635e3</td>
      <td>8.2</td>
    </tr>
    <tr>
      <th>19</th>
      <td>4aab560af964a520785920e3</td>
      <td>7.1</td>
    </tr>
    <tr>
      <th>20</th>
      <td>4af2380af964a520aae621e3</td>
      <td>7.3</td>
    </tr>
    <tr>
      <th>21</th>
      <td>4ba7ce4ef964a520fbb439e3</td>
      <td>5.6</td>
    </tr>
    <tr>
      <th>22</th>
      <td>51c2302d498e6c1fcae32130</td>
      <td>6.0</td>
    </tr>
    <tr>
      <th>23</th>
      <td>4ad5f692f964a520350421e3</td>
      <td>8.3</td>
    </tr>
    <tr>
      <th>24</th>
      <td>4ca0679019e4236abef06089</td>
      <td>5.0</td>
    </tr>
    <tr>
      <th>25</th>
      <td>4dc5f785887717c880324075</td>
      <td>6.2</td>
    </tr>
    <tr>
      <th>26</th>
      <td>4aeca6c6f964a520eec921e3</td>
      <td>6.2</td>
    </tr>
    <tr>
      <th>27</th>
      <td>4bd09a3f1f89ce723bb967ea</td>
      <td>7.8</td>
    </tr>
    <tr>
      <th>28</th>
      <td>4bf0811f6f8aa593b1fcc13c</td>
      <td>5.7</td>
    </tr>
    <tr>
      <th>29</th>
      <td>4bd744ae304fce722b4a33ab</td>
      <td>5.7</td>
    </tr>
    <tr>
      <th>30</th>
      <td>4af32fb0f964a5208aeb21e3</td>
      <td>5.8</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="set-column-names">set column names<a class="anchor-link" href="#set-column-names">&#182;</a></h4><h5 id="As-we-see-we-need-to-change-column-names">As we see we need to change column names<a class="anchor-link" href="#As-we-see-we-need-to-change-column-names">&#182;</a></h5>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[37]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">list_df</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="mi">0</span><span class="p">:</span><span class="s1">&#39;id&#39;</span><span class="p">,</span><span class="mi">1</span><span class="p">:</span><span class="s1">&#39;rating&#39;</span><span class="p">},</span> <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">list_df</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[37]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>rating</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>4aa738def964a520594c20e3</td>
      <td>8.4</td>
    </tr>
    <tr>
      <th>1</th>
      <td>4bd09a421f89ce723fb967ea</td>
      <td>7.5</td>
    </tr>
    <tr>
      <th>2</th>
      <td>4b0ae864f964a520d72923e3</td>
      <td>5.3</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4ba56584f964a520150339e3</td>
      <td>6.1</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4d188bfcbb64224b4108c865</td>
      <td>5.4</td>
    </tr>
    <tr>
      <th>5</th>
      <td>4bd5c5589649ce7223a6511d</td>
      <td>6.6</td>
    </tr>
    <tr>
      <th>6</th>
      <td>4af0f4e4f964a5204ae021e3</td>
      <td>8.5</td>
    </tr>
    <tr>
      <th>7</th>
      <td>4d5ec8ce29ef236ae0cb9059</td>
      <td>9.3</td>
    </tr>
    <tr>
      <th>8</th>
      <td>4aab4f20f964a520615920e3</td>
      <td>6.0</td>
    </tr>
    <tr>
      <th>9</th>
      <td>4b9b2307f964a5206df535e3</td>
      <td>7.9</td>
    </tr>
    <tr>
      <th>10</th>
      <td>4aa74575f964a5208f4c20e3</td>
      <td>8.6</td>
    </tr>
    <tr>
      <th>11</th>
      <td>4a8e147cf964a520fc1120e3</td>
      <td>5.4</td>
    </tr>
    <tr>
      <th>12</th>
      <td>4b806d95f964a5206e7130e3</td>
      <td>5.6</td>
    </tr>
    <tr>
      <th>13</th>
      <td>4aab548ef964a520725920e3</td>
      <td>8.3</td>
    </tr>
    <tr>
      <th>14</th>
      <td>4aab4ce8f964a5205a5920e3</td>
      <td>7.5</td>
    </tr>
    <tr>
      <th>15</th>
      <td>4abe5a61f964a520ec8c20e3</td>
      <td>8.0</td>
    </tr>
    <tr>
      <th>16</th>
      <td>4acd3910f964a5207dcb20e3</td>
      <td>8.6</td>
    </tr>
    <tr>
      <th>17</th>
      <td>4b7cf5e1f964a52066aa2fe3</td>
      <td>6.1</td>
    </tr>
    <tr>
      <th>18</th>
      <td>4b99e544f964a5201f9635e3</td>
      <td>8.2</td>
    </tr>
    <tr>
      <th>19</th>
      <td>4aab560af964a520785920e3</td>
      <td>7.1</td>
    </tr>
    <tr>
      <th>20</th>
      <td>4af2380af964a520aae621e3</td>
      <td>7.3</td>
    </tr>
    <tr>
      <th>21</th>
      <td>4ba7ce4ef964a520fbb439e3</td>
      <td>5.6</td>
    </tr>
    <tr>
      <th>22</th>
      <td>51c2302d498e6c1fcae32130</td>
      <td>6.0</td>
    </tr>
    <tr>
      <th>23</th>
      <td>4ad5f692f964a520350421e3</td>
      <td>8.3</td>
    </tr>
    <tr>
      <th>24</th>
      <td>4ca0679019e4236abef06089</td>
      <td>5.0</td>
    </tr>
    <tr>
      <th>25</th>
      <td>4dc5f785887717c880324075</td>
      <td>6.2</td>
    </tr>
    <tr>
      <th>26</th>
      <td>4aeca6c6f964a520eec921e3</td>
      <td>6.2</td>
    </tr>
    <tr>
      <th>27</th>
      <td>4bd09a3f1f89ce723bb967ea</td>
      <td>7.8</td>
    </tr>
    <tr>
      <th>28</th>
      <td>4bf0811f6f8aa593b1fcc13c</td>
      <td>5.7</td>
    </tr>
    <tr>
      <th>29</th>
      <td>4bd744ae304fce722b4a33ab</td>
      <td>5.7</td>
    </tr>
    <tr>
      <th>30</th>
      <td>4af32fb0f964a5208aeb21e3</td>
      <td>5.8</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="6.-Now-its-time-to-have-a-one-complete-data-frame-with-all-of-data-which-we-need-so,">6. Now its time to have a one complete data frame with all of data which we need so,<a class="anchor-link" href="#6.-Now-its-time-to-have-a-one-complete-data-frame-with-all-of-data-which-we-need-so,">&#182;</a></h3>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h5 id="Left-join-two-dataframes-based-on-id-column">Left join two dataframes based on id column<a class="anchor-link" href="#Left-join-two-dataframes-based-on-id-column">&#182;</a></h5><h5 id="Why-left-join?-then-we-just-keep-hotels-with-rating">Why left join? then we just keep hotels with rating<a class="anchor-link" href="#Why-left-join?-then-we-just-keep-hotels-with-rating">&#182;</a></h5>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[38]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">ljoin_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">merge</span><span class="p">(</span><span class="n">list_df</span><span class="p">,</span> <span class="n">dataframe</span><span class="p">,</span>
                       <span class="n">how</span><span class="o">=</span><span class="s2">&quot;left&quot;</span><span class="p">,</span> <span class="n">on</span><span class="o">=</span><span class="p">[</span><span class="s2">&quot;id&quot;</span><span class="p">])</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[42]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">ljoin_df</span><span class="o">.</span><span class="n">shape</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[42]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>(31, 19)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="It's-time-to-filter-our-data-and-make-it-more-efficient">It's time to filter our data and make it more efficient<a class="anchor-link" href="#It's-time-to-filter-our-data-and-make-it-more-efficient">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h5 id="So-we-have-list-of-31-hotel-in-Vancouver-city">So we have list of 31 hotel in Vancouver city<a class="anchor-link" href="#So-we-have-list-of-31-hotel-in-Vancouver-city">&#182;</a></h5><h6 id="It's-time-to-order-them-by-rating-and-choose-hotels-with-overal-rank-of-7-or-greater">It's time to order them by rating and choose hotels with overal rank of 7 or greater<a class="anchor-link" href="#It's-time-to-order-them-by-rating-and-choose-hotels-with-overal-rank-of-7-or-greater">&#182;</a></h6>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[48]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">ljoin_df</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">by</span><span class="o">=</span><span class="s1">&#39;rating&#39;</span><span class="p">,</span> <span class="n">ascending</span><span class="o">=</span><span class="kc">False</span><span class="p">,</span> <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">ljoin_df</span> <span class="o">=</span> <span class="n">ljoin_df</span><span class="p">[</span><span class="n">ljoin_df</span><span class="p">[</span><span class="s1">&#39;rating&#39;</span><span class="p">]</span><span class="o">&gt;=</span><span class="mi">7</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[53]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">ljoin_df</span><span class="o">.</span><span class="n">reset_index</span><span class="p">(</span><span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[55]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">ljoin_df</span><span class="o">.</span><span class="n">shape</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[55]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>(15, 20)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[56]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">ljoin_df</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[56]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>index</th>
      <th>id</th>
      <th>rating</th>
      <th>name</th>
      <th>categories</th>
      <th>referralId</th>
      <th>hasPerk</th>
      <th>location.address</th>
      <th>location.crossStreet</th>
      <th>location.lat</th>
      <th>location.lng</th>
      <th>location.labeledLatLngs</th>
      <th>location.postalCode</th>
      <th>location.cc</th>
      <th>location.city</th>
      <th>location.state</th>
      <th>location.country</th>
      <th>location.formattedAddress</th>
      <th>venuePage.id</th>
      <th>location.neighborhood</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>7</td>
      <td>4d5ec8ce29ef236ae0cb9059</td>
      <td>9.3</td>
      <td>Rosewood Hotel Georgia</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>801 W Georgia St</td>
      <td>at Howe St</td>
      <td>49.283429</td>
      <td>-123.118911</td>
      <td>[{'label': 'display', 'lat': 49.28342914255638...</td>
      <td>V6C 1P7</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[801 W Georgia St (at Howe St), Vancouver BC V...</td>
      <td>37012938</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>10</td>
      <td>4aa74575f964a5208f4c20e3</td>
      <td>8.6</td>
      <td>Sutton Place Hotel Vancouver</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>845 Burrard Street</td>
      <td>btwn Smithe St &amp; Robson St</td>
      <td>49.282640</td>
      <td>-123.123875</td>
      <td>[{'label': 'display', 'lat': 49.28264004904225...</td>
      <td>V6Z 2K6</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[845 Burrard Street (btwn Smithe St &amp; Robson S...</td>
      <td>584836110</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>16</td>
      <td>4acd3910f964a5207dcb20e3</td>
      <td>8.6</td>
      <td>Shangri-La Hotel</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>1128 West Georgia St.</td>
      <td>Thurlow</td>
      <td>49.285934</td>
      <td>-123.124081</td>
      <td>[{'label': 'display', 'lat': 49.28593423238485...</td>
      <td>V6E 0A8</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[1128 West Georgia St. (Thurlow), Vancouver BC...</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>6</td>
      <td>4af0f4e4f964a5204ae021e3</td>
      <td>8.5</td>
      <td>The Fairmont Hotel Vancouver</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>900 West Georgia Street</td>
      <td>btwn Burrard &amp; Hornby</td>
      <td>49.283805</td>
      <td>-123.120944</td>
      <td>[{'label': 'display', 'lat': 49.28380548632319...</td>
      <td>V6C 2W6</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[900 West Georgia Street (btwn Burrard &amp; Hornb...</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>0</td>
      <td>4aa738def964a520594c20e3</td>
      <td>8.4</td>
      <td>Opus Hotel</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>322 Davie St.</td>
      <td>at Hamilton St.</td>
      <td>49.274654</td>
      <td>-123.122332</td>
      <td>[{'label': 'display', 'lat': 49.27465442332043...</td>
      <td>V6B 5Z6</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[322 Davie St. (at Hamilton St.), Vancouver BC...</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>5</th>
      <td>23</td>
      <td>4ad5f692f964a520350421e3</td>
      <td>8.3</td>
      <td>Coast Coal Harbour Vancouver Hotel by APA</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>1180 West Hastings</td>
      <td>Hastings &amp; Bute</td>
      <td>49.288401</td>
      <td>-123.122343</td>
      <td>[{'label': 'display', 'lat': 49.288401, 'lng':...</td>
      <td>V6E 4R5</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[1180 West Hastings (Hastings &amp; Bute), Vancouv...</td>
      <td>512550599</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>6</th>
      <td>13</td>
      <td>4aab548ef964a520725920e3</td>
      <td>8.3</td>
      <td>Hotel LeSoleil</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>567 Hornby Street</td>
      <td>btn W Pender and Dunsmuir</td>
      <td>49.285332</td>
      <td>-123.118111</td>
      <td>[{'label': 'display', 'lat': 49.28533209101862...</td>
      <td>V6C 2E8</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[567 Hornby Street (btn W Pender and Dunsmuir)...</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>7</th>
      <td>18</td>
      <td>4b99e544f964a5201f9635e3</td>
      <td>8.2</td>
      <td>Georgian Court Hotel</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>773 Beatty St</td>
      <td>btw Robson St. and Georgia St.</td>
      <td>49.278237</td>
      <td>-123.113485</td>
      <td>[{'label': 'display', 'lat': 49.27823662737742...</td>
      <td>V6B 2M4</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[773 Beatty St (btw Robson St. and Georgia St....</td>
      <td>47719517</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>8</th>
      <td>15</td>
      <td>4abe5a61f964a520ec8c20e3</td>
      <td>8.0</td>
      <td>Four Seasons Hotel Vancouver</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>791 West Georgia Street</td>
      <td>NaN</td>
      <td>49.283210</td>
      <td>-123.118407</td>
      <td>[{'label': 'display', 'lat': 49.28321030608094...</td>
      <td>V6C 2T4</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[791 West Georgia Street, Vancouver BC V6C 2T4...</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>9</th>
      <td>9</td>
      <td>4b9b2307f964a5206df535e3</td>
      <td>7.9</td>
      <td>Best Western Plus Chateau Granville Hotel &amp; Su...</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>1100 Granville St</td>
      <td>at Helmcken St.</td>
      <td>49.277823</td>
      <td>-123.124630</td>
      <td>[{'label': 'display', 'lat': 49.277823, 'lng':...</td>
      <td>V6Z 2B6</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[1100 Granville St (at Helmcken St.), Vancouve...</td>
      <td>36728873</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>10</th>
      <td>27</td>
      <td>4bd09a3f1f89ce723bb967ea</td>
      <td>7.8</td>
      <td>Victorian Hotel Vancouver</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>514 Homer St Vancouver BC Canada</td>
      <td>Pender</td>
      <td>49.282517</td>
      <td>-123.112144</td>
      <td>[{'label': 'display', 'lat': 49.28251724902659...</td>
      <td>NaN</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[514 Homer St Vancouver BC Canada (Pender), Va...</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>11</th>
      <td>14</td>
      <td>4aab4ce8f964a5205a5920e3</td>
      <td>7.5</td>
      <td>Vancouver Marriott Pinnacle Downtown Hotel</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>1128 West Hastings Street</td>
      <td>NaN</td>
      <td>49.287790</td>
      <td>-123.120365</td>
      <td>[{'label': 'display', 'lat': 49.28778960562971...</td>
      <td>V6E 4R5</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[1128 West Hastings Street, Vancouver BC V6E 4...</td>
      <td>129932557</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1</td>
      <td>4bd09a421f89ce723fb967ea</td>
      <td>7.5</td>
      <td>The Sylvia Hotel</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>1154 Gilford St</td>
      <td>NaN</td>
      <td>49.288784</td>
      <td>-123.142615</td>
      <td>[{'label': 'display', 'lat': 49.288784, 'lng':...</td>
      <td>V6G 2P6</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[1154 Gilford St, Vancouver BC V6G 2P6, Canada]</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>13</th>
      <td>20</td>
      <td>4af2380af964a520aae621e3</td>
      <td>7.3</td>
      <td>YWCA Hotel/Residence</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>733 Beatty St.</td>
      <td>Off Robson St.</td>
      <td>49.278414</td>
      <td>-123.112770</td>
      <td>[{'label': 'display', 'lat': 49.27841416220364...</td>
      <td>V6B 4P4</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[733 Beatty St. (Off Robson St.), Vancouver BC...</td>
      <td>45901530</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>14</th>
      <td>19</td>
      <td>4aab560af964a520785920e3</td>
      <td>7.1</td>
      <td>Metropolitan Hotel Vancouver</td>
      <td>[{'id': '4bf58dd8d48988d1fa931735', 'name': 'H...</td>
      <td>v-1603598705</td>
      <td>False</td>
      <td>645 Howe Street</td>
      <td>NaN</td>
      <td>49.284180</td>
      <td>-123.118430</td>
      <td>[{'label': 'display', 'lat': 49.2841801, 'lng'...</td>
      <td>V6C 2Y9</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[645 Howe Street, Vancouver BC V6C 2Y9, Canada]</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="7.-OK!-Cleansing-time">7. OK! Cleansing time<a class="anchor-link" href="#7.-OK!-Cleansing-time">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h5 id="Now-it's-time-to-clean-our-data-frame-and-keep-just-appropriate-columns">Now it's time to clean our data frame and keep just appropriate columns<a class="anchor-link" href="#Now-it's-time-to-clean-our-data-frame-and-keep-just-appropriate-columns">&#182;</a></h5><h6 id="We're-going-to-drop-all-columns-that-we-don't-need-to-boost-performance">We're going to drop all columns that we don't need to boost performance<a class="anchor-link" href="#We're-going-to-drop-all-columns-that-we-don't-need-to-boost-performance">&#182;</a></h6>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[59]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># keep only columns that include venue name, and anything that is associated with location</span>
<span class="n">filtered_columns</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;name&#39;</span><span class="p">,</span> <span class="s1">&#39;rating&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="p">[</span><span class="n">col</span> <span class="k">for</span> <span class="n">col</span> <span class="ow">in</span> <span class="n">ljoin_df</span><span class="o">.</span><span class="n">columns</span> <span class="k">if</span> <span class="n">col</span><span class="o">.</span><span class="n">startswith</span><span class="p">(</span><span class="s1">&#39;location.&#39;</span><span class="p">)]</span> <span class="o">+</span> <span class="p">[</span><span class="s1">&#39;id&#39;</span><span class="p">]</span>
<span class="n">dataframe_filtered</span> <span class="o">=</span> <span class="n">ljoin_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[:,</span> <span class="n">filtered_columns</span><span class="p">]</span>

<span class="c1"># clean column names by keeping only last term</span>
<span class="n">dataframe_filtered</span><span class="o">.</span><span class="n">columns</span> <span class="o">=</span> <span class="p">[</span><span class="n">column</span><span class="o">.</span><span class="n">split</span><span class="p">(</span><span class="s1">&#39;.&#39;</span><span class="p">)[</span><span class="o">-</span><span class="mi">1</span><span class="p">]</span> <span class="k">for</span> <span class="n">column</span> <span class="ow">in</span> <span class="n">dataframe_filtered</span><span class="o">.</span><span class="n">columns</span><span class="p">]</span>

<span class="n">dataframe_filtered</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[59]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>name</th>
      <th>rating</th>
      <th>address</th>
      <th>crossStreet</th>
      <th>lat</th>
      <th>lng</th>
      <th>labeledLatLngs</th>
      <th>postalCode</th>
      <th>cc</th>
      <th>city</th>
      <th>state</th>
      <th>country</th>
      <th>formattedAddress</th>
      <th>neighborhood</th>
      <th>id</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Rosewood Hotel Georgia</td>
      <td>9.3</td>
      <td>801 W Georgia St</td>
      <td>at Howe St</td>
      <td>49.283429</td>
      <td>-123.118911</td>
      <td>[{'label': 'display', 'lat': 49.28342914255638...</td>
      <td>V6C 1P7</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[801 W Georgia St (at Howe St), Vancouver BC V...</td>
      <td>NaN</td>
      <td>4d5ec8ce29ef236ae0cb9059</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Sutton Place Hotel Vancouver</td>
      <td>8.6</td>
      <td>845 Burrard Street</td>
      <td>btwn Smithe St &amp; Robson St</td>
      <td>49.282640</td>
      <td>-123.123875</td>
      <td>[{'label': 'display', 'lat': 49.28264004904225...</td>
      <td>V6Z 2K6</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[845 Burrard Street (btwn Smithe St &amp; Robson S...</td>
      <td>NaN</td>
      <td>4aa74575f964a5208f4c20e3</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Shangri-La Hotel</td>
      <td>8.6</td>
      <td>1128 West Georgia St.</td>
      <td>Thurlow</td>
      <td>49.285934</td>
      <td>-123.124081</td>
      <td>[{'label': 'display', 'lat': 49.28593423238485...</td>
      <td>V6E 0A8</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[1128 West Georgia St. (Thurlow), Vancouver BC...</td>
      <td>NaN</td>
      <td>4acd3910f964a5207dcb20e3</td>
    </tr>
    <tr>
      <th>3</th>
      <td>The Fairmont Hotel Vancouver</td>
      <td>8.5</td>
      <td>900 West Georgia Street</td>
      <td>btwn Burrard &amp; Hornby</td>
      <td>49.283805</td>
      <td>-123.120944</td>
      <td>[{'label': 'display', 'lat': 49.28380548632319...</td>
      <td>V6C 2W6</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[900 West Georgia Street (btwn Burrard &amp; Hornb...</td>
      <td>NaN</td>
      <td>4af0f4e4f964a5204ae021e3</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Opus Hotel</td>
      <td>8.4</td>
      <td>322 Davie St.</td>
      <td>at Hamilton St.</td>
      <td>49.274654</td>
      <td>-123.122332</td>
      <td>[{'label': 'display', 'lat': 49.27465442332043...</td>
      <td>V6B 5Z6</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[322 Davie St. (at Hamilton St.), Vancouver BC...</td>
      <td>NaN</td>
      <td>4aa738def964a520594c20e3</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coast Coal Harbour Vancouver Hotel by APA</td>
      <td>8.3</td>
      <td>1180 West Hastings</td>
      <td>Hastings &amp; Bute</td>
      <td>49.288401</td>
      <td>-123.122343</td>
      <td>[{'label': 'display', 'lat': 49.288401, 'lng':...</td>
      <td>V6E 4R5</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[1180 West Hastings (Hastings &amp; Bute), Vancouv...</td>
      <td>NaN</td>
      <td>4ad5f692f964a520350421e3</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Hotel LeSoleil</td>
      <td>8.3</td>
      <td>567 Hornby Street</td>
      <td>btn W Pender and Dunsmuir</td>
      <td>49.285332</td>
      <td>-123.118111</td>
      <td>[{'label': 'display', 'lat': 49.28533209101862...</td>
      <td>V6C 2E8</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[567 Hornby Street (btn W Pender and Dunsmuir)...</td>
      <td>NaN</td>
      <td>4aab548ef964a520725920e3</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Georgian Court Hotel</td>
      <td>8.2</td>
      <td>773 Beatty St</td>
      <td>btw Robson St. and Georgia St.</td>
      <td>49.278237</td>
      <td>-123.113485</td>
      <td>[{'label': 'display', 'lat': 49.27823662737742...</td>
      <td>V6B 2M4</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[773 Beatty St (btw Robson St. and Georgia St....</td>
      <td>NaN</td>
      <td>4b99e544f964a5201f9635e3</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Four Seasons Hotel Vancouver</td>
      <td>8.0</td>
      <td>791 West Georgia Street</td>
      <td>NaN</td>
      <td>49.283210</td>
      <td>-123.118407</td>
      <td>[{'label': 'display', 'lat': 49.28321030608094...</td>
      <td>V6C 2T4</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[791 West Georgia Street, Vancouver BC V6C 2T4...</td>
      <td>NaN</td>
      <td>4abe5a61f964a520ec8c20e3</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Best Western Plus Chateau Granville Hotel &amp; Su...</td>
      <td>7.9</td>
      <td>1100 Granville St</td>
      <td>at Helmcken St.</td>
      <td>49.277823</td>
      <td>-123.124630</td>
      <td>[{'label': 'display', 'lat': 49.277823, 'lng':...</td>
      <td>V6Z 2B6</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[1100 Granville St (at Helmcken St.), Vancouve...</td>
      <td>NaN</td>
      <td>4b9b2307f964a5206df535e3</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Victorian Hotel Vancouver</td>
      <td>7.8</td>
      <td>514 Homer St Vancouver BC Canada</td>
      <td>Pender</td>
      <td>49.282517</td>
      <td>-123.112144</td>
      <td>[{'label': 'display', 'lat': 49.28251724902659...</td>
      <td>NaN</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[514 Homer St Vancouver BC Canada (Pender), Va...</td>
      <td>NaN</td>
      <td>4bd09a3f1f89ce723bb967ea</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Vancouver Marriott Pinnacle Downtown Hotel</td>
      <td>7.5</td>
      <td>1128 West Hastings Street</td>
      <td>NaN</td>
      <td>49.287790</td>
      <td>-123.120365</td>
      <td>[{'label': 'display', 'lat': 49.28778960562971...</td>
      <td>V6E 4R5</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[1128 West Hastings Street, Vancouver BC V6E 4...</td>
      <td>NaN</td>
      <td>4aab4ce8f964a5205a5920e3</td>
    </tr>
    <tr>
      <th>12</th>
      <td>The Sylvia Hotel</td>
      <td>7.5</td>
      <td>1154 Gilford St</td>
      <td>NaN</td>
      <td>49.288784</td>
      <td>-123.142615</td>
      <td>[{'label': 'display', 'lat': 49.288784, 'lng':...</td>
      <td>V6G 2P6</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[1154 Gilford St, Vancouver BC V6G 2P6, Canada]</td>
      <td>NaN</td>
      <td>4bd09a421f89ce723fb967ea</td>
    </tr>
    <tr>
      <th>13</th>
      <td>YWCA Hotel/Residence</td>
      <td>7.3</td>
      <td>733 Beatty St.</td>
      <td>Off Robson St.</td>
      <td>49.278414</td>
      <td>-123.112770</td>
      <td>[{'label': 'display', 'lat': 49.27841416220364...</td>
      <td>V6B 4P4</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[733 Beatty St. (Off Robson St.), Vancouver BC...</td>
      <td>NaN</td>
      <td>4af2380af964a520aae621e3</td>
    </tr>
    <tr>
      <th>14</th>
      <td>Metropolitan Hotel Vancouver</td>
      <td>7.1</td>
      <td>645 Howe Street</td>
      <td>NaN</td>
      <td>49.284180</td>
      <td>-123.118430</td>
      <td>[{'label': 'display', 'lat': 49.2841801, 'lng'...</td>
      <td>V6C 2Y9</td>
      <td>CA</td>
      <td>Vancouver</td>
      <td>BC</td>
      <td>Canada</td>
      <td>[645 Howe Street, Vancouver BC V6C 2Y9, Canada]</td>
      <td>NaN</td>
      <td>4aab560af964a520785920e3</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[64]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Get list of column names to more cleansing dataframe</span>
<span class="n">dataframe_filtered</span><span class="o">.</span><span class="n">columns</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[64]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Index([&#39;name&#39;, &#39;rating&#39;, &#39;address&#39;, &#39;crossStreet&#39;, &#39;lat&#39;, &#39;lng&#39;,
       &#39;labeledLatLngs&#39;, &#39;postalCode&#39;, &#39;cc&#39;, &#39;city&#39;, &#39;state&#39;, &#39;country&#39;,
       &#39;formattedAddress&#39;, &#39;neighborhood&#39;, &#39;id&#39;],
      dtype=&#39;object&#39;)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[65]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># We just need to keep id, name, address, lat, lng so:</span>
<span class="n">hotel_df</span> <span class="o">=</span> <span class="n">dataframe_filtered</span><span class="o">.</span><span class="n">loc</span><span class="p">[:,[</span><span class="s1">&#39;name&#39;</span><span class="p">,</span> <span class="s1">&#39;rating&#39;</span><span class="p">,</span> <span class="s1">&#39;address&#39;</span><span class="p">,</span> <span class="s1">&#39;lat&#39;</span><span class="p">,</span> <span class="s1">&#39;lng&#39;</span><span class="p">,</span><span class="s1">&#39;id&#39;</span><span class="p">]]</span>
<span class="c1"># our final data frame of hotels is:</span>
<span class="n">hotel_df</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[65]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>name</th>
      <th>rating</th>
      <th>address</th>
      <th>lat</th>
      <th>lng</th>
      <th>id</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Rosewood Hotel Georgia</td>
      <td>9.3</td>
      <td>801 W Georgia St</td>
      <td>49.283429</td>
      <td>-123.118911</td>
      <td>4d5ec8ce29ef236ae0cb9059</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Sutton Place Hotel Vancouver</td>
      <td>8.6</td>
      <td>845 Burrard Street</td>
      <td>49.282640</td>
      <td>-123.123875</td>
      <td>4aa74575f964a5208f4c20e3</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Shangri-La Hotel</td>
      <td>8.6</td>
      <td>1128 West Georgia St.</td>
      <td>49.285934</td>
      <td>-123.124081</td>
      <td>4acd3910f964a5207dcb20e3</td>
    </tr>
    <tr>
      <th>3</th>
      <td>The Fairmont Hotel Vancouver</td>
      <td>8.5</td>
      <td>900 West Georgia Street</td>
      <td>49.283805</td>
      <td>-123.120944</td>
      <td>4af0f4e4f964a5204ae021e3</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Opus Hotel</td>
      <td>8.4</td>
      <td>322 Davie St.</td>
      <td>49.274654</td>
      <td>-123.122332</td>
      <td>4aa738def964a520594c20e3</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coast Coal Harbour Vancouver Hotel by APA</td>
      <td>8.3</td>
      <td>1180 West Hastings</td>
      <td>49.288401</td>
      <td>-123.122343</td>
      <td>4ad5f692f964a520350421e3</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Hotel LeSoleil</td>
      <td>8.3</td>
      <td>567 Hornby Street</td>
      <td>49.285332</td>
      <td>-123.118111</td>
      <td>4aab548ef964a520725920e3</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Georgian Court Hotel</td>
      <td>8.2</td>
      <td>773 Beatty St</td>
      <td>49.278237</td>
      <td>-123.113485</td>
      <td>4b99e544f964a5201f9635e3</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Four Seasons Hotel Vancouver</td>
      <td>8.0</td>
      <td>791 West Georgia Street</td>
      <td>49.283210</td>
      <td>-123.118407</td>
      <td>4abe5a61f964a520ec8c20e3</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Best Western Plus Chateau Granville Hotel &amp; Su...</td>
      <td>7.9</td>
      <td>1100 Granville St</td>
      <td>49.277823</td>
      <td>-123.124630</td>
      <td>4b9b2307f964a5206df535e3</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Victorian Hotel Vancouver</td>
      <td>7.8</td>
      <td>514 Homer St Vancouver BC Canada</td>
      <td>49.282517</td>
      <td>-123.112144</td>
      <td>4bd09a3f1f89ce723bb967ea</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Vancouver Marriott Pinnacle Downtown Hotel</td>
      <td>7.5</td>
      <td>1128 West Hastings Street</td>
      <td>49.287790</td>
      <td>-123.120365</td>
      <td>4aab4ce8f964a5205a5920e3</td>
    </tr>
    <tr>
      <th>12</th>
      <td>The Sylvia Hotel</td>
      <td>7.5</td>
      <td>1154 Gilford St</td>
      <td>49.288784</td>
      <td>-123.142615</td>
      <td>4bd09a421f89ce723fb967ea</td>
    </tr>
    <tr>
      <th>13</th>
      <td>YWCA Hotel/Residence</td>
      <td>7.3</td>
      <td>733 Beatty St.</td>
      <td>49.278414</td>
      <td>-123.112770</td>
      <td>4af2380af964a520aae621e3</td>
    </tr>
    <tr>
      <th>14</th>
      <td>Metropolitan Hotel Vancouver</td>
      <td>7.1</td>
      <td>645 Howe Street</td>
      <td>49.284180</td>
      <td>-123.118430</td>
      <td>4aab560af964a520785920e3</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="8.-Now-we-just-need-to-gently-save-it-as-csv-for-future-use">8. Now we just need to gently save it as csv for future use<a class="anchor-link" href="#8.-Now-we-just-need-to-gently-save-it-as-csv-for-future-use">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[66]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">hotel_df</span><span class="o">.</span><span class="n">to_csv</span><span class="p">(</span><span class="s1">&#39;hotel_df.csv&#39;</span><span class="p">,</span> <span class="n">index</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Same-as-what-we-did-untill-now,-we-should-repeat-this-process-4-more-time-to-create-our-data-setd:">Same as what we did untill now, we should repeat this process 4 more time to create our data setd:<a class="anchor-link" href="#Same-as-what-we-did-untill-now,-we-should-repeat-this-process-4-more-time-to-create-our-data-setd:">&#182;</a></h2><ul>
<li>bus_df.csv   </li>
<li>metro_df.csv</li>
<li>unrban_df.csv</li>
<li>rest_df.csv</li>
</ul>
<h6 id="Note:-rest_df-stands-for-restaurant-dataframe">Note: rest_df stands for restaurant dataframe<a class="anchor-link" href="#Note:-rest_df-stands-for-restaurant-dataframe">&#182;</a></h6>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="So,-as-soon-as-we-are-done-with-retrieving-data,-we-start-to-put-them-on-map-for-best-usage-experience">So, as soon as we are done with retrieving data, we start to put them on map for best usage experience<a class="anchor-link" href="#So,-as-soon-as-we-are-done-with-retrieving-data,-we-start-to-put-them-on-map-for-best-usage-experience">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h5 id="first-we-need-to-install-and-import-Folium-library-so-if-you-already-have-it-just-run-code-below-otherwise-uncomment-first-line-and-then-run-the-block">first we need to install and import Folium library so if you already have it just run code below otherwise uncomment first line and then run the block<a class="anchor-link" href="#first-we-need-to-install-and-import-Folium-library-so-if-you-already-have-it-just-run-code-below-otherwise-uncomment-first-line-and-then-run-the-block">&#182;</a></h5>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># !pip install folium</span>
<span class="kn">import</span> <span class="nn">folium</span> 
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="Import-all-csv-file-that-we've-already-created">Import all csv file that we've already created<a class="anchor-link" href="#Import-all-csv-file-that-we've-already-created">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[2]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">metro_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;metro_df.csv&#39;</span><span class="p">)</span>
<span class="n">hotel_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;hotel_df.csv&#39;</span><span class="p">)</span>
<span class="n">urban_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;urban_df.csv&#39;</span><span class="p">)</span>
<span class="n">rest_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;rest_df.csv&#39;</span><span class="p">)</span>
<span class="n">bus_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;bus_df.csv&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[3]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">hotel_df</span><span class="o">.</span><span class="n">columns</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[3]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Index([&#39;name&#39;, &#39;rating&#39;, &#39;address&#39;, &#39;lat&#39;, &#39;lng&#39;, &#39;id&#39;], dtype=&#39;object&#39;)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="Since-we-don't-need-id-column-anymore-we're-going-to-remove-it-to-improve-speed-of-next-steps">Since we don't need id column anymore we're going to remove it to improve speed of next steps<a class="anchor-link" href="#Since-we-don't-need-id-column-anymore-we're-going-to-remove-it-to-improve-speed-of-next-steps">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[4]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">metro_df</span> <span class="o">=</span> <span class="n">metro_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[:,[</span><span class="s1">&#39;name&#39;</span><span class="p">,</span> <span class="s1">&#39;address&#39;</span><span class="p">,</span> <span class="s1">&#39;lat&#39;</span><span class="p">,</span> <span class="s1">&#39;lng&#39;</span><span class="p">]]</span>
<span class="n">hotel_df</span> <span class="o">=</span> <span class="n">hotel_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[:,[</span><span class="s1">&#39;name&#39;</span><span class="p">,</span> <span class="s1">&#39;rating&#39;</span><span class="p">,</span> <span class="s1">&#39;address&#39;</span><span class="p">,</span> <span class="s1">&#39;lat&#39;</span><span class="p">,</span> <span class="s1">&#39;lng&#39;</span><span class="p">]]</span>
<span class="n">urban_df</span> <span class="o">=</span> <span class="n">urban_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[:,[</span><span class="s1">&#39;name&#39;</span><span class="p">,</span> <span class="s1">&#39;rating&#39;</span><span class="p">,</span> <span class="s1">&#39;address&#39;</span><span class="p">,</span> <span class="s1">&#39;lat&#39;</span><span class="p">,</span> <span class="s1">&#39;lng&#39;</span><span class="p">]]</span>
<span class="n">rest_df</span> <span class="o">=</span> <span class="n">rest_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[:,[</span><span class="s1">&#39;name&#39;</span><span class="p">,</span> <span class="s1">&#39;rating&#39;</span><span class="p">,</span> <span class="s1">&#39;address&#39;</span><span class="p">,</span> <span class="s1">&#39;lat&#39;</span><span class="p">,</span> <span class="s1">&#39;lng&#39;</span><span class="p">]]</span>
<span class="n">bus_df</span> <span class="o">=</span> <span class="n">bus_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[:,[</span><span class="s1">&#39;name&#39;</span><span class="p">,</span> <span class="s1">&#39;address&#39;</span><span class="p">,</span> <span class="s1">&#39;lat&#39;</span><span class="p">,</span> <span class="s1">&#39;lng&#39;</span><span class="p">]]</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="Test-our-dataframes">Test our dataframes<a class="anchor-link" href="#Test-our-dataframes">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">metro_df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[5]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>name</th>
      <th>address</th>
      <th>lat</th>
      <th>lng</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Metro news</td>
      <td>Oakridge skytrain</td>
      <td>49.250795</td>
      <td>-123.117416</td>
    </tr>
    <tr>
      <th>1</th>
      <td>King Edward SkyTrain Station</td>
      <td>500 W King Edward Ave.</td>
      <td>49.249120</td>
      <td>-123.115703</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Metro News</td>
      <td>100 W 49th Ave</td>
      <td>49.225866</td>
      <td>-123.116441</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Metro News</td>
      <td>(@ 16th Ave &amp; Oak St)</td>
      <td>49.259135</td>
      <td>-123.127178</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Yaletown - Roundhouse SkyTrain Station</td>
      <td>200 Davie St.</td>
      <td>49.274531</td>
      <td>-123.121993</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[6]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">hotel_df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[6]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>name</th>
      <th>rating</th>
      <th>address</th>
      <th>lat</th>
      <th>lng</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Rosewood Hotel Georgia</td>
      <td>9.3</td>
      <td>801 W Georgia St</td>
      <td>49.283429</td>
      <td>-123.118911</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Sutton Place Hotel Vancouver</td>
      <td>8.6</td>
      <td>845 Burrard Street</td>
      <td>49.282640</td>
      <td>-123.123875</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Shangri-La Hotel</td>
      <td>8.6</td>
      <td>1128 West Georgia St.</td>
      <td>49.285934</td>
      <td>-123.124081</td>
    </tr>
    <tr>
      <th>3</th>
      <td>The Fairmont Hotel Vancouver</td>
      <td>8.5</td>
      <td>900 West Georgia Street</td>
      <td>49.283805</td>
      <td>-123.120944</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Opus Hotel</td>
      <td>8.4</td>
      <td>322 Davie St.</td>
      <td>49.274654</td>
      <td>-123.122332</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[7]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">urban_df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[7]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>name</th>
      <th>rating</th>
      <th>address</th>
      <th>lat</th>
      <th>lng</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Stanley Park</td>
      <td>9.6</td>
      <td>Stanley Park Dr</td>
      <td>49.302488</td>
      <td>-123.141718</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Stanley Park English Bay Seawall</td>
      <td>9.6</td>
      <td>Beach Ave</td>
      <td>49.290230</td>
      <td>-123.146868</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Pacific Spirit Regional Park</td>
      <td>9.4</td>
      <td>Pacific Spirit Park</td>
      <td>49.249263</td>
      <td>-123.211370</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Queen Elizabeth Park</td>
      <td>9.3</td>
      <td>4600 Cambie St</td>
      <td>49.241565</td>
      <td>-123.113355</td>
    </tr>
    <tr>
      <th>4</th>
      <td>David Lam Park</td>
      <td>9.2</td>
      <td>1300 Pacific Blvd.</td>
      <td>49.272467</td>
      <td>-123.123866</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[8]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">bus_df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[8]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>name</th>
      <th>address</th>
      <th>lat</th>
      <th>lng</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Bus Stop 51512 (25)</td>
      <td>W King Edward Ave</td>
      <td>49.248431</td>
      <td>-123.118522</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Bus Stop 51511 (25)</td>
      <td>W King Edward Ave</td>
      <td>49.248998</td>
      <td>-123.121991</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Bus Stop 51574 (25)</td>
      <td>WB W King Edward Ave</td>
      <td>49.249126</td>
      <td>-123.115789</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Bus Stop 50475 (15,33)</td>
      <td>Cambie St</td>
      <td>49.249172</td>
      <td>-123.115393</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Bus Stop 50419 (15,33)</td>
      <td>Cambie St</td>
      <td>49.248611</td>
      <td>-123.115708</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[9]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">rest_df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[9]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>name</th>
      <th>rating</th>
      <th>address</th>
      <th>lat</th>
      <th>lng</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Hawksworth Restaurant</td>
      <td>9.1</td>
      <td>801 W Georgia St</td>
      <td>49.283362</td>
      <td>-123.119462</td>
    </tr>
    <tr>
      <th>1</th>
      <td>España Restaurant</td>
      <td>8.6</td>
      <td>1118 Denman St.</td>
      <td>49.288019</td>
      <td>-123.140467</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Cardero's Restaurant</td>
      <td>8.5</td>
      <td>1583 Coal Harbour Quay</td>
      <td>49.291655</td>
      <td>-123.127686</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Peaceful Restaurant 和平饭店</td>
      <td>8.1</td>
      <td>43 E 5th Ave</td>
      <td>49.266510</td>
      <td>-123.103731</td>
    </tr>
    <tr>
      <th>4</th>
      <td>The Sandbar Seafood Restaurant</td>
      <td>8.1</td>
      <td>1536 Johnston St.</td>
      <td>49.272188</td>
      <td>-123.133918</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h4 id="Everything-is-ok,-so-we're-going-to-create-folium-map-base-on-our-dataframes">Everything is ok, so we're going to create folium map base on our dataframes<a class="anchor-link" href="#Everything-is-ok,-so-we're-going-to-create-folium-map-base-on-our-dataframes">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[10]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">hotel_df</span><span class="o">.</span><span class="n">shape</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[10]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>15</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[11]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">## latitude and longitude of Vancouver</span>
<span class="n">latitude</span> <span class="o">=</span> <span class="mf">49.2576508</span>
<span class="n">longitude</span> <span class="o">=</span> <span class="o">-</span><span class="mf">123.10</span>

<span class="n">venues_map</span> <span class="o">=</span> <span class="n">folium</span><span class="o">.</span><span class="n">Map</span><span class="p">(</span><span class="n">location</span><span class="o">=</span><span class="p">[</span><span class="n">latitude</span><span class="p">,</span> <span class="n">longitude</span><span class="p">],</span> <span class="n">zoom_start</span><span class="o">=</span><span class="mi">12</span><span class="p">)</span>  <span class="c1"># It will create a map around Vancouver city</span>


<span class="c1"># add the hotels as red circle markers</span>
<span class="k">for</span> <span class="n">lat</span><span class="p">,</span> <span class="n">lng</span><span class="p">,</span> <span class="n">label</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">hotel_df</span><span class="p">[</span><span class="s1">&#39;lat&#39;</span><span class="p">],</span> <span class="n">hotel_df</span><span class="p">[</span><span class="s1">&#39;lng&#39;</span><span class="p">],</span> <span class="n">hotel_df</span><span class="p">[</span><span class="s1">&#39;name&#39;</span><span class="p">]):</span>
    <span class="n">folium</span><span class="o">.</span><span class="n">CircleMarker</span><span class="p">(</span>
        <span class="p">[</span><span class="n">lat</span><span class="p">,</span> <span class="n">lng</span><span class="p">],</span>
        <span class="n">radius</span><span class="o">=</span><span class="mi">5</span><span class="p">,</span>
        <span class="n">color</span><span class="o">=</span><span class="s1">&#39;red&#39;</span><span class="p">,</span>
        <span class="n">popup</span><span class="o">=</span><span class="n">label</span><span class="p">,</span>
        <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
        <span class="n">fill_color</span><span class="o">=</span><span class="s1">&#39;red&#39;</span><span class="p">,</span>
        <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.6</span>
    <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">venues_map</span><span class="p">)</span>

    
<span class="c1">#add the bus stations as purple circle markers</span>
<span class="k">for</span> <span class="n">lat</span><span class="p">,</span> <span class="n">lng</span><span class="p">,</span> <span class="n">label</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">bus_df</span><span class="p">[</span><span class="s1">&#39;lat&#39;</span><span class="p">],</span> <span class="n">bus_df</span><span class="p">[</span><span class="s1">&#39;lng&#39;</span><span class="p">],</span> <span class="n">bus_df</span><span class="p">[</span><span class="s1">&#39;name&#39;</span><span class="p">]):</span>
    <span class="n">folium</span><span class="o">.</span><span class="n">CircleMarker</span><span class="p">(</span>
        <span class="p">[</span><span class="n">lat</span><span class="p">,</span> <span class="n">lng</span><span class="p">],</span>
        <span class="n">radius</span><span class="o">=</span><span class="mi">5</span><span class="p">,</span>
        <span class="n">color</span><span class="o">=</span><span class="s1">&#39;purple&#39;</span><span class="p">,</span>
        <span class="n">popup</span><span class="o">=</span><span class="n">label</span><span class="p">,</span>
        <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
        <span class="n">fill_color</span><span class="o">=</span><span class="s1">&#39;purple&#39;</span><span class="p">,</span>
        <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.6</span>
    <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">venues_map</span><span class="p">)</span>
    
<span class="c1">#add the metro stations as yellow circle markers</span>
<span class="k">for</span> <span class="n">lat</span><span class="p">,</span> <span class="n">lng</span><span class="p">,</span> <span class="n">label</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">metro_df</span><span class="p">[</span><span class="s1">&#39;lat&#39;</span><span class="p">],</span> <span class="n">metro_df</span><span class="p">[</span><span class="s1">&#39;lng&#39;</span><span class="p">],</span> <span class="n">metro_df</span><span class="p">[</span><span class="s1">&#39;name&#39;</span><span class="p">]):</span>
    <span class="n">folium</span><span class="o">.</span><span class="n">CircleMarker</span><span class="p">(</span>
        <span class="p">[</span><span class="n">lat</span><span class="p">,</span> <span class="n">lng</span><span class="p">],</span>
        <span class="n">radius</span><span class="o">=</span><span class="mi">5</span><span class="p">,</span>
        <span class="n">color</span><span class="o">=</span><span class="s1">&#39;yellow&#39;</span><span class="p">,</span>
        <span class="n">popup</span><span class="o">=</span><span class="n">label</span><span class="p">,</span>
        <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
        <span class="n">fill_color</span><span class="o">=</span><span class="s1">&#39;yellow&#39;</span><span class="p">,</span>
        <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.6</span>
    <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">venues_map</span><span class="p">)</span>
    
<span class="c1">#add the restaurants as orange circle markers</span>
<span class="k">for</span> <span class="n">lat</span><span class="p">,</span> <span class="n">lng</span><span class="p">,</span> <span class="n">label</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">rest_df</span><span class="p">[</span><span class="s1">&#39;lat&#39;</span><span class="p">],</span> <span class="n">rest_df</span><span class="p">[</span><span class="s1">&#39;lng&#39;</span><span class="p">],</span> <span class="n">rest_df</span><span class="p">[</span><span class="s1">&#39;name&#39;</span><span class="p">]):</span>
    <span class="n">folium</span><span class="o">.</span><span class="n">CircleMarker</span><span class="p">(</span>
        <span class="p">[</span><span class="n">lat</span><span class="p">,</span> <span class="n">lng</span><span class="p">],</span>
        <span class="n">radius</span><span class="o">=</span><span class="mi">5</span><span class="p">,</span>
        <span class="n">color</span><span class="o">=</span><span class="s1">&#39;orange&#39;</span><span class="p">,</span>
        <span class="n">popup</span><span class="o">=</span><span class="n">label</span><span class="p">,</span>
        <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
        <span class="n">fill_color</span><span class="o">=</span><span class="s1">&#39;orange&#39;</span><span class="p">,</span>
        <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.6</span>
    <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">venues_map</span><span class="p">)</span>
    
<span class="c1">#add the parks as green circle markers</span>
<span class="k">for</span> <span class="n">lat</span><span class="p">,</span> <span class="n">lng</span><span class="p">,</span> <span class="n">label</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">urban_df</span><span class="p">[</span><span class="s1">&#39;lat&#39;</span><span class="p">],</span> <span class="n">urban_df</span><span class="p">[</span><span class="s1">&#39;lng&#39;</span><span class="p">],</span> <span class="n">urban_df</span><span class="p">[</span><span class="s1">&#39;name&#39;</span><span class="p">]):</span>
    <span class="n">folium</span><span class="o">.</span><span class="n">CircleMarker</span><span class="p">(</span>
        <span class="p">[</span><span class="n">lat</span><span class="p">,</span> <span class="n">lng</span><span class="p">],</span>
        <span class="n">radius</span><span class="o">=</span><span class="mi">5</span><span class="p">,</span>
        <span class="n">color</span><span class="o">=</span><span class="s1">&#39;green&#39;</span><span class="p">,</span>
        <span class="n">popup</span><span class="o">=</span><span class="n">label</span><span class="p">,</span>
        <span class="n">fill</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
        <span class="n">fill_color</span><span class="o">=</span><span class="s1">&#39;green&#39;</span><span class="p">,</span>
        <span class="n">fill_opacity</span><span class="o">=</span><span class="mf">0.6</span>
    <span class="p">)</span><span class="o">.</span><span class="n">add_to</span><span class="p">(</span><span class="n">venues_map</span><span class="p">)</span>


<span class="c1"># display map</span>
<span class="n">venues_map</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[11]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div style="width:100%;"><div style="position:relative;width:100%;height:0;padding-bottom:60%;"><span style="color:#565656">Make this Notebook Trusted to load map: File -> Trust Notebook</span><iframe src="about:blank" style="position:absolute;width:100%;height:100%;left:0;top:0;border:none !important;" data-html=PCFET0NUWVBFIGh0bWw+CjxoZWFkPiAgICAKICAgIDxtZXRhIGh0dHAtZXF1aXY9ImNvbnRlbnQtdHlwZSIgY29udGVudD0idGV4dC9odG1sOyBjaGFyc2V0PVVURi04IiAvPgogICAgCiAgICAgICAgPHNjcmlwdD4KICAgICAgICAgICAgTF9OT19UT1VDSCA9IGZhbHNlOwogICAgICAgICAgICBMX0RJU0FCTEVfM0QgPSBmYWxzZTsKICAgICAgICA8L3NjcmlwdD4KICAgIAogICAgPHNjcmlwdCBzcmM9Imh0dHBzOi8vY2RuLmpzZGVsaXZyLm5ldC9ucG0vbGVhZmxldEAxLjYuMC9kaXN0L2xlYWZsZXQuanMiPjwvc2NyaXB0PgogICAgPHNjcmlwdCBzcmM9Imh0dHBzOi8vY29kZS5qcXVlcnkuY29tL2pxdWVyeS0xLjEyLjQubWluLmpzIj48L3NjcmlwdD4KICAgIDxzY3JpcHQgc3JjPSJodHRwczovL21heGNkbi5ib290c3RyYXBjZG4uY29tL2Jvb3RzdHJhcC8zLjIuMC9qcy9ib290c3RyYXAubWluLmpzIj48L3NjcmlwdD4KICAgIDxzY3JpcHQgc3JjPSJodHRwczovL2NkbmpzLmNsb3VkZmxhcmUuY29tL2FqYXgvbGlicy9MZWFmbGV0LmF3ZXNvbWUtbWFya2Vycy8yLjAuMi9sZWFmbGV0LmF3ZXNvbWUtbWFya2Vycy5qcyI+PC9zY3JpcHQ+CiAgICA8bGluayByZWw9InN0eWxlc2hlZXQiIGhyZWY9Imh0dHBzOi8vY2RuLmpzZGVsaXZyLm5ldC9ucG0vbGVhZmxldEAxLjYuMC9kaXN0L2xlYWZsZXQuY3NzIi8+CiAgICA8bGluayByZWw9InN0eWxlc2hlZXQiIGhyZWY9Imh0dHBzOi8vbWF4Y2RuLmJvb3RzdHJhcGNkbi5jb20vYm9vdHN0cmFwLzMuMi4wL2Nzcy9ib290c3RyYXAubWluLmNzcyIvPgogICAgPGxpbmsgcmVsPSJzdHlsZXNoZWV0IiBocmVmPSJodHRwczovL21heGNkbi5ib290c3RyYXBjZG4uY29tL2Jvb3RzdHJhcC8zLjIuMC9jc3MvYm9vdHN0cmFwLXRoZW1lLm1pbi5jc3MiLz4KICAgIDxsaW5rIHJlbD0ic3R5bGVzaGVldCIgaHJlZj0iaHR0cHM6Ly9tYXhjZG4uYm9vdHN0cmFwY2RuLmNvbS9mb250LWF3ZXNvbWUvNC42LjMvY3NzL2ZvbnQtYXdlc29tZS5taW4uY3NzIi8+CiAgICA8bGluayByZWw9InN0eWxlc2hlZXQiIGhyZWY9Imh0dHBzOi8vY2RuanMuY2xvdWRmbGFyZS5jb20vYWpheC9saWJzL0xlYWZsZXQuYXdlc29tZS1tYXJrZXJzLzIuMC4yL2xlYWZsZXQuYXdlc29tZS1tYXJrZXJzLmNzcyIvPgogICAgPGxpbmsgcmVsPSJzdHlsZXNoZWV0IiBocmVmPSJodHRwczovL3Jhd2Nkbi5naXRoYWNrLmNvbS9weXRob24tdmlzdWFsaXphdGlvbi9mb2xpdW0vbWFzdGVyL2ZvbGl1bS90ZW1wbGF0ZXMvbGVhZmxldC5hd2Vzb21lLnJvdGF0ZS5jc3MiLz4KICAgIDxzdHlsZT5odG1sLCBib2R5IHt3aWR0aDogMTAwJTtoZWlnaHQ6IDEwMCU7bWFyZ2luOiAwO3BhZGRpbmc6IDA7fTwvc3R5bGU+CiAgICA8c3R5bGU+I21hcCB7cG9zaXRpb246YWJzb2x1dGU7dG9wOjA7Ym90dG9tOjA7cmlnaHQ6MDtsZWZ0OjA7fTwvc3R5bGU+CiAgICAKICAgICAgICAgICAgPG1ldGEgbmFtZT0idmlld3BvcnQiIGNvbnRlbnQ9IndpZHRoPWRldmljZS13aWR0aCwKICAgICAgICAgICAgICAgIGluaXRpYWwtc2NhbGU9MS4wLCBtYXhpbXVtLXNjYWxlPTEuMCwgdXNlci1zY2FsYWJsZT1ubyIgLz4KICAgICAgICAgICAgPHN0eWxlPgogICAgICAgICAgICAgICAgI21hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSB7CiAgICAgICAgICAgICAgICAgICAgcG9zaXRpb246IHJlbGF0aXZlOwogICAgICAgICAgICAgICAgICAgIHdpZHRoOiAxMDAuMCU7CiAgICAgICAgICAgICAgICAgICAgaGVpZ2h0OiAxMDAuMCU7CiAgICAgICAgICAgICAgICAgICAgbGVmdDogMC4wJTsKICAgICAgICAgICAgICAgICAgICB0b3A6IDAuMCU7CiAgICAgICAgICAgICAgICB9CiAgICAgICAgICAgIDwvc3R5bGU+CiAgICAgICAgCjwvaGVhZD4KPGJvZHk+ICAgIAogICAgCiAgICAgICAgICAgIDxkaXYgY2xhc3M9ImZvbGl1bS1tYXAiIGlkPSJtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkiID48L2Rpdj4KICAgICAgICAKPC9ib2R5Pgo8c2NyaXB0PiAgICAKICAgIAogICAgICAgICAgICB2YXIgbWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5ID0gTC5tYXAoCiAgICAgICAgICAgICAgICAibWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5IiwKICAgICAgICAgICAgICAgIHsKICAgICAgICAgICAgICAgICAgICBjZW50ZXI6IFs0OS4yNTc2NTA4LCAtMTIzLjFdLAogICAgICAgICAgICAgICAgICAgIGNyczogTC5DUlMuRVBTRzM4NTcsCiAgICAgICAgICAgICAgICAgICAgem9vbTogMTIsCiAgICAgICAgICAgICAgICAgICAgem9vbUNvbnRyb2w6IHRydWUsCiAgICAgICAgICAgICAgICAgICAgcHJlZmVyQ2FudmFzOiBmYWxzZSwKICAgICAgICAgICAgICAgIH0KICAgICAgICAgICAgKTsKCiAgICAgICAgICAgIAoKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgdGlsZV9sYXllcl8xMmRkMWE4ZWU1OWY0M2RlOWQzYTUwNDM4ZWExYzQ1MiA9IEwudGlsZUxheWVyKAogICAgICAgICAgICAgICAgImh0dHBzOi8ve3N9LnRpbGUub3BlbnN0cmVldG1hcC5vcmcve3p9L3t4fS97eX0ucG5nIiwKICAgICAgICAgICAgICAgIHsiYXR0cmlidXRpb24iOiAiRGF0YSBieSBcdTAwMjZjb3B5OyBcdTAwM2NhIGhyZWY9XCJodHRwOi8vb3BlbnN0cmVldG1hcC5vcmdcIlx1MDAzZU9wZW5TdHJlZXRNYXBcdTAwM2MvYVx1MDAzZSwgdW5kZXIgXHUwMDNjYSBocmVmPVwiaHR0cDovL3d3dy5vcGVuc3RyZWV0bWFwLm9yZy9jb3B5cmlnaHRcIlx1MDAzZU9EYkxcdTAwM2MvYVx1MDAzZS4iLCAiZGV0ZWN0UmV0aW5hIjogZmFsc2UsICJtYXhOYXRpdmVab29tIjogMTgsICJtYXhab29tIjogMTgsICJtaW5ab29tIjogMCwgIm5vV3JhcCI6IGZhbHNlLCAib3BhY2l0eSI6IDEsICJzdWJkb21haW5zIjogImFiYyIsICJ0bXMiOiBmYWxzZX0KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2FlYmM3ZWJiN2FlYTQ5NzRhYTEzMzM2YTMxZWIyMDc0ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjgzNDI5MTQyNTU2MzgsIC0xMjMuMTE4OTEwNzMyNjM1MjFdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInJlZCIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJyZWQiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzZkNzdlODAwYTk0MjRlNmQ5ZDRiM2RjYWRjZDI3NGVlID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9lMGJjYTU1NDgzNzM0NGZlYjA1ZmQ3MWY3Y2M4ZmUyYiA9ICQoYDxkaXYgaWQ9Imh0bWxfZTBiY2E1NTQ4MzczNDRmZWIwNWZkNzFmN2NjOGZlMmIiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlJvc2V3b29kIEhvdGVsIEdlb3JnaWE8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfNmQ3N2U4MDBhOTQyNGU2ZDlkNGIzZGNhZGNkMjc0ZWUuc2V0Q29udGVudChodG1sX2UwYmNhNTU0ODM3MzQ0ZmViMDVmZDcxZjdjYzhmZTJiKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9hZWJjN2ViYjdhZWE0OTc0YWExMzMzNmEzMWViMjA3NC5iaW5kUG9wdXAocG9wdXBfNmQ3N2U4MDBhOTQyNGU2ZDlkNGIzZGNhZGNkMjc0ZWUpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2E0M2VmYzk4ZWQ4MzRhNTM5ZTJhZjA2NzE2MmRmOWE2ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjgyNjQwMDQ5MDQyMjUsIC0xMjMuMTIzODc1MjkyNjY4NDddLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInJlZCIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJyZWQiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2EwNTBkMzU1NDMyNjQ3MzU4MGYwODc5MWZhOWZiOGU1ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF82NjBmYjY1ZmRhMmE0ZTYyODNkODAzYjdjNmJhM2FlOSA9ICQoYDxkaXYgaWQ9Imh0bWxfNjYwZmI2NWZkYTJhNGU2MjgzZDgwM2I3YzZiYTNhZTkiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlN1dHRvbiBQbGFjZSBIb3RlbCBWYW5jb3V2ZXI8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfYTA1MGQzNTU0MzI2NDczNTgwZjA4NzkxZmE5ZmI4ZTUuc2V0Q29udGVudChodG1sXzY2MGZiNjVmZGEyYTRlNjI4M2Q4MDNiN2M2YmEzYWU5KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9hNDNlZmM5OGVkODM0YTUzOWUyYWYwNjcxNjJkZjlhNi5iaW5kUG9wdXAocG9wdXBfYTA1MGQzNTU0MzI2NDczNTgwZjA4NzkxZmE5ZmI4ZTUpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzY1ZWZhZWNlMDgzOTRiMGQ5NjBmNGUwYWRjYmZjZGI0ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjg1OTM0MjMyMzg0ODU0LCAtMTIzLjEyNDA4MDUwNzA5NjE1XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJyZWQiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicmVkIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8zMjIwMTZmZjQwMWQ0YjdkYjM3YzA4OGE2NzZkMmIzOCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfN2QyYjk4ZDliMWUzNGM4ODkxMDc1YjFjZjgwNDFkZjggPSAkKGA8ZGl2IGlkPSJodG1sXzdkMmI5OGQ5YjFlMzRjODg5MTA3NWIxY2Y4MDQxZGY4IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5TaGFuZ3JpLUxhIEhvdGVsPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzMyMjAxNmZmNDAxZDRiN2RiMzdjMDg4YTY3NmQyYjM4LnNldENvbnRlbnQoaHRtbF83ZDJiOThkOWIxZTM0Yzg4OTEwNzViMWNmODA0MWRmOCk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfNjVlZmFlY2UwODM5NGIwZDk2MGY0ZTBhZGNiZmNkYjQuYmluZFBvcHVwKHBvcHVwXzMyMjAxNmZmNDAxZDRiN2RiMzdjMDg4YTY3NmQyYjM4KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl85Y2I2M2NlMjUwYWE0OGIyODgyYjI2NDUwOTZhNzFiMCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4MzgwNTQ4NjMyMzIsIC0xMjMuMTIwOTQ0XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJyZWQiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicmVkIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF82Yzk5M2JhZTU4NjE0NDU0YjI0MDk1OWM2MzNhNDBhNyA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfMWI0OTAyY2Q3MGQwNGJmNzhmYzYwYTJlNmM3NmQ5MjQgPSAkKGA8ZGl2IGlkPSJodG1sXzFiNDkwMmNkNzBkMDRiZjc4ZmM2MGEyZTZjNzZkOTI0IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5UaGUgRmFpcm1vbnQgSG90ZWwgVmFuY291dmVyPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzZjOTkzYmFlNTg2MTQ0NTRiMjQwOTU5YzYzM2E0MGE3LnNldENvbnRlbnQoaHRtbF8xYjQ5MDJjZDcwZDA0YmY3OGZjNjBhMmU2Yzc2ZDkyNCk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfOWNiNjNjZTI1MGFhNDhiMjg4MmIyNjQ1MDk2YTcxYjAuYmluZFBvcHVwKHBvcHVwXzZjOTkzYmFlNTg2MTQ0NTRiMjQwOTU5YzYzM2E0MGE3KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9iNWU0MmVjM2RjNWE0M2U3YWI4YzIwYTQ3M2ZmYjJkYyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI3NDY1NDQyMzMyMDQzNSwgLTEyMy4xMjIzMzE4OTcxNjMyOF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicmVkIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInJlZCIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfOGQ0YTVmYWU0ODUyNGQ4OGFiMDg2NDkyNmFhYjU2NmUgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2RkNDE0N2VjN2I0MDQ1Y2ZhOTAxMTcwNmI0NTg2YmUxID0gJChgPGRpdiBpZD0iaHRtbF9kZDQxNDdlYzdiNDA0NWNmYTkwMTE3MDZiNDU4NmJlMSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+T3B1cyBIb3RlbDwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF84ZDRhNWZhZTQ4NTI0ZDg4YWIwODY0OTI2YWFiNTY2ZS5zZXRDb250ZW50KGh0bWxfZGQ0MTQ3ZWM3YjQwNDVjZmE5MDExNzA2YjQ1ODZiZTEpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2I1ZTQyZWMzZGM1YTQzZTdhYjhjMjBhNDczZmZiMmRjLmJpbmRQb3B1cChwb3B1cF84ZDRhNWZhZTQ4NTI0ZDg4YWIwODY0OTI2YWFiNTY2ZSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZWZlMjhlZmQzNzBhNDlkM2I1ZmM4M2E5ODNkY2QxZjAgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yODg0MDEsIC0xMjMuMTIyMzQyOTk5OTk5OTldLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInJlZCIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJyZWQiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzI2ODJiMGZiZDA4MzQ5ZWFhYmQ4OTEwMGViZTA3Mjg2ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF8zZGJkMmYwNGJkNDU0ZDY5OWJjNzE5MWU1ZGQxYTNmOSA9ICQoYDxkaXYgaWQ9Imh0bWxfM2RiZDJmMDRiZDQ1NGQ2OTliYzcxOTFlNWRkMWEzZjkiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkNvYXN0IENvYWwgSGFyYm91ciBWYW5jb3V2ZXIgSG90ZWwgYnkgQVBBPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzI2ODJiMGZiZDA4MzQ5ZWFhYmQ4OTEwMGViZTA3Mjg2LnNldENvbnRlbnQoaHRtbF8zZGJkMmYwNGJkNDU0ZDY5OWJjNzE5MWU1ZGQxYTNmOSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfZWZlMjhlZmQzNzBhNDlkM2I1ZmM4M2E5ODNkY2QxZjAuYmluZFBvcHVwKHBvcHVwXzI2ODJiMGZiZDA4MzQ5ZWFhYmQ4OTEwMGViZTA3Mjg2KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl84MmYyOTM2OGNlODM0ZTVjOGUwN2MzZjg0OTUwNDAyNCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4NTMzMjA5MTAxODYyLCAtMTIzLjExODExMDY5Njk0MDA0XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJyZWQiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicmVkIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF83YWYyNmRlYmQxM2I0YjI0OTQ1MzRhMjQyZDUwNGMwMCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNjkyZGQxN2RmMzBlNDdiNTljOTEwNzAxN2FhZDY2ZDkgPSAkKGA8ZGl2IGlkPSJodG1sXzY5MmRkMTdkZjMwZTQ3YjU5YzkxMDcwMTdhYWQ2NmQ5IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Ib3RlbCBMZVNvbGVpbDwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF83YWYyNmRlYmQxM2I0YjI0OTQ1MzRhMjQyZDUwNGMwMC5zZXRDb250ZW50KGh0bWxfNjkyZGQxN2RmMzBlNDdiNTljOTEwNzAxN2FhZDY2ZDkpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzgyZjI5MzY4Y2U4MzRlNWM4ZTA3YzNmODQ5NTA0MDI0LmJpbmRQb3B1cChwb3B1cF83YWYyNmRlYmQxM2I0YjI0OTQ1MzRhMjQyZDUwNGMwMCkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfM2EwN2Q2M2UyYTQ0NGFlMzkzYjg3YWI2MDI4MDE3MzQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNzgyMzY2MjczNzc0MjQsIC0xMjMuMTEzNDg0ODA0ODkzNDZdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInJlZCIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJyZWQiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzViMzQ5OGM4OTQ5MTRlYTM5NTZiMzRiMjdhZWViNGJlID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9lNzEzMTc1NDUyMWI0Y2YyOWM1ZDJkMTJkMWMyZmMxNyA9ICQoYDxkaXYgaWQ9Imh0bWxfZTcxMzE3NTQ1MjFiNGNmMjljNWQyZDEyZDFjMmZjMTciIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkdlb3JnaWFuIENvdXJ0IEhvdGVsPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzViMzQ5OGM4OTQ5MTRlYTM5NTZiMzRiMjdhZWViNGJlLnNldENvbnRlbnQoaHRtbF9lNzEzMTc1NDUyMWI0Y2YyOWM1ZDJkMTJkMWMyZmMxNyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfM2EwN2Q2M2UyYTQ0NGFlMzkzYjg3YWI2MDI4MDE3MzQuYmluZFBvcHVwKHBvcHVwXzViMzQ5OGM4OTQ5MTRlYTM5NTZiMzRiMjdhZWViNGJlKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9iOTNlMTI1OWY3NzE0ODZjYjAwMTdjZWVhMTQ5N2I2YiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4MzIxMDMwNjA4MDk1LCAtMTIzLjExODQwNzE5MTk0NTRdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInJlZCIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJyZWQiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzM1MGFkN2QxNTU0YjRjMjQ4NDQ3Mzc5YzYxZGYzZmE2ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF85ODdhNjViYTA3MjY0MDBjYTVmYTI2ZTVjN2NiMWIwZiA9ICQoYDxkaXYgaWQ9Imh0bWxfOTg3YTY1YmEwNzI2NDAwY2E1ZmEyNmU1YzdjYjFiMGYiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkZvdXIgU2Vhc29ucyBIb3RlbCBWYW5jb3V2ZXI8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfMzUwYWQ3ZDE1NTRiNGMyNDg0NDczNzljNjFkZjNmYTYuc2V0Q29udGVudChodG1sXzk4N2E2NWJhMDcyNjQwMGNhNWZhMjZlNWM3Y2IxYjBmKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9iOTNlMTI1OWY3NzE0ODZjYjAwMTdjZWVhMTQ5N2I2Yi5iaW5kUG9wdXAocG9wdXBfMzUwYWQ3ZDE1NTRiNGMyNDg0NDczNzljNjFkZjNmYTYpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzk5ZDM4MTczNDg5NTQ0ZDZhYWQ5NGE1NjY3NDQ1YmZlID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjc3ODIzLCAtMTIzLjEyNDYzMDAwMDAwMDAxXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJyZWQiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicmVkIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8wYmUwMGJiOTY3Mzg0ZTE4YTQwOWZmODAzZWIzYzgzNCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfYmE3NTI5MDU5YzE0NDdkOTk2YjZhNWE0ZjNmODdlNzQgPSAkKGA8ZGl2IGlkPSJodG1sX2JhNzUyOTA1OWMxNDQ3ZDk5NmI2YTVhNGYzZjg3ZTc0IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CZXN0IFdlc3Rlcm4gUGx1cyBDaGF0ZWF1IEdyYW52aWxsZSBIb3RlbCAmIFN1aXRlcyAmIENvbmZlcmVuY2UgQ3RyLjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8wYmUwMGJiOTY3Mzg0ZTE4YTQwOWZmODAzZWIzYzgzNC5zZXRDb250ZW50KGh0bWxfYmE3NTI5MDU5YzE0NDdkOTk2YjZhNWE0ZjNmODdlNzQpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzk5ZDM4MTczNDg5NTQ0ZDZhYWQ5NGE1NjY3NDQ1YmZlLmJpbmRQb3B1cChwb3B1cF8wYmUwMGJiOTY3Mzg0ZTE4YTQwOWZmODAzZWIzYzgzNCkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfY2UxNWFmN2E0ZTAyNDYzMmI0MmE5NGM3MWNmM2JhYzQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yODI1MTcyNDkwMjY2LCAtMTIzLjExMjE0NDIxMTA5NjI0XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJyZWQiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicmVkIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF82MzY1NTU2MjcxZGU0ZjZhOTZiZjcyNTZlNjA5NGVmMyA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNTZmZGZhOWNiZWVjNDcwN2IyZWNmNmI0NGRiNzg2NDcgPSAkKGA8ZGl2IGlkPSJodG1sXzU2ZmRmYTljYmVlYzQ3MDdiMmVjZjZiNDRkYjc4NjQ3IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5WaWN0b3JpYW4gSG90ZWwgVmFuY291dmVyPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzYzNjU1NTYyNzFkZTRmNmE5NmJmNzI1NmU2MDk0ZWYzLnNldENvbnRlbnQoaHRtbF81NmZkZmE5Y2JlZWM0NzA3YjJlY2Y2YjQ0ZGI3ODY0Nyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfY2UxNWFmN2E0ZTAyNDYzMmI0MmE5NGM3MWNmM2JhYzQuYmluZFBvcHVwKHBvcHVwXzYzNjU1NTYyNzFkZTRmNmE5NmJmNzI1NmU2MDk0ZWYzKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9lNjMxYmRhYTQ3ZmY0YTU3ODFiZjdiMWVjOTc0ZTAwNCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4Nzc4OTYwNTYyOTcxLCAtMTIzLjEyMDM2NDY2NTIxMDY0XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJyZWQiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicmVkIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9lYzViYjIzOWUwMDk0MWQzOWI1YmU0MGYyMjM2MzY3MyA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNjgzYmQ3Y2M2M2ZlNGMyZGI0ZWI4MWNjY2Y5YjhiZDggPSAkKGA8ZGl2IGlkPSJodG1sXzY4M2JkN2NjNjNmZTRjMmRiNGViODFjY2NmOWI4YmQ4IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5WYW5jb3V2ZXIgTWFycmlvdHQgUGlubmFjbGUgRG93bnRvd24gSG90ZWw8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfZWM1YmIyMzllMDA5NDFkMzliNWJlNDBmMjIzNjM2NzMuc2V0Q29udGVudChodG1sXzY4M2JkN2NjNjNmZTRjMmRiNGViODFjY2NmOWI4YmQ4KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9lNjMxYmRhYTQ3ZmY0YTU3ODFiZjdiMWVjOTc0ZTAwNC5iaW5kUG9wdXAocG9wdXBfZWM1YmIyMzllMDA5NDFkMzliNWJlNDBmMjIzNjM2NzMpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzJmNmRhYjhmMTQwZDRhYjBiNjEzNmI1MTY5NGRkNjI5ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjg4Nzg0LCAtMTIzLjE0MjYxNDk5OTk5OTk5XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJyZWQiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicmVkIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9lZWMwZmNjMTYwMzQ0ZmU2ODdjYjY0NmViZDA1NDdlNiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNzNmNTU0MTY0NTk4NDk3ZjhiMDQxMGQyZGJjNDg1ZjggPSAkKGA8ZGl2IGlkPSJodG1sXzczZjU1NDE2NDU5ODQ5N2Y4YjA0MTBkMmRiYzQ4NWY4IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5UaGUgU3lsdmlhIEhvdGVsPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2VlYzBmY2MxNjAzNDRmZTY4N2NiNjQ2ZWJkMDU0N2U2LnNldENvbnRlbnQoaHRtbF83M2Y1NTQxNjQ1OTg0OTdmOGIwNDEwZDJkYmM0ODVmOCk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfMmY2ZGFiOGYxNDBkNGFiMGI2MTM2YjUxNjk0ZGQ2MjkuYmluZFBvcHVwKHBvcHVwX2VlYzBmY2MxNjAzNDRmZTY4N2NiNjQ2ZWJkMDU0N2U2KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8wODEyMDRiNmE3NjY0YzI4YWIyMTg5YmExYzNiYzhkZSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI3ODQxNDE2MjIwMzY0LCAtMTIzLjExMjc2OTY0MTc0OTE0XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJyZWQiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicmVkIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF84YjBiMTU1N2VjYTQ0ZGE1YTU5MjVjMDJlZTg3MmYwNCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNmUxZWRhOTkxODJjNDRkM2I5NDBiMWQ3YWE5NjZlYzYgPSAkKGA8ZGl2IGlkPSJodG1sXzZlMWVkYTk5MTgyYzQ0ZDNiOTQwYjFkN2FhOTY2ZWM2IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5ZV0NBIEhvdGVsL1Jlc2lkZW5jZTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF84YjBiMTU1N2VjYTQ0ZGE1YTU5MjVjMDJlZTg3MmYwNC5zZXRDb250ZW50KGh0bWxfNmUxZWRhOTkxODJjNDRkM2I5NDBiMWQ3YWE5NjZlYzYpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzA4MTIwNGI2YTc2NjRjMjhhYjIxODliYTFjM2JjOGRlLmJpbmRQb3B1cChwb3B1cF84YjBiMTU1N2VjYTQ0ZGE1YTU5MjVjMDJlZTg3MmYwNCkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYzI4Yjk2MjUyY2MwNGQ3MmFiNTYzZjFmYjJiMTc3YTIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yODQxODAxLCAtMTIzLjExODQzMDMwMDAwMDAxXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJyZWQiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicmVkIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8wZjA4M2ZhN2YxYzU0NjRlYTc3ZTljNzU5ZDQyYzllZSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfMzQzM2NmOGEyMTY1NGJiNzkzMjEzNzZmZjI5Y2VhODggPSAkKGA8ZGl2IGlkPSJodG1sXzM0MzNjZjhhMjE2NTRiYjc5MzIxMzc2ZmYyOWNlYTg4IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5NZXRyb3BvbGl0YW4gSG90ZWwgVmFuY291dmVyPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzBmMDgzZmE3ZjFjNTQ2NGVhNzdlOWM3NTlkNDJjOWVlLnNldENvbnRlbnQoaHRtbF8zNDMzY2Y4YTIxNjU0YmI3OTMyMTM3NmZmMjljZWE4OCk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYzI4Yjk2MjUyY2MwNGQ3MmFiNTYzZjFmYjJiMTc3YTIuYmluZFBvcHVwKHBvcHVwXzBmMDgzZmE3ZjFjNTQ2NGVhNzdlOWM3NTlkNDJjOWVlKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8xOWE0MTI2NDg4MTA0OTY2YTM3ZWIxYTkyMjJjNjIwMSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI0ODQzMSwgLTEyMy4xMTg1MjJdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2QwNTJiMDIyNjVlMTQ1MGVhM2RlMzdlMzIxMzA5YjFlID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF8zNDY3NWMyMGMzMzc0Njc0YmU5MDE3M2JjMzc5ZGIyYSA9ICQoYDxkaXYgaWQ9Imh0bWxfMzQ2NzVjMjBjMzM3NDY3NGJlOTAxNzNiYzM3OWRiMmEiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUxNTEyICgyNSk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfZDA1MmIwMjI2NWUxNDUwZWEzZGUzN2UzMjEzMDliMWUuc2V0Q29udGVudChodG1sXzM0Njc1YzIwYzMzNzQ2NzRiZTkwMTczYmMzNzlkYjJhKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl8xOWE0MTI2NDg4MTA0OTY2YTM3ZWIxYTkyMjJjNjIwMS5iaW5kUG9wdXAocG9wdXBfZDA1MmIwMjI2NWUxNDUwZWEzZGUzN2UzMjEzMDliMWUpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzNiMWJjZDQ4Mzg0MDRlYTBiNzg0NjkzOTAxYWE4ZjQ2ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjQ4OTk4LCAtMTIzLjEyMTk5MV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfYzZhOGFkODU3OTIzNGE3MGEyNjk1ZWRhMTE0NzFiYjIgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2I5ZjcxNWJjMGYyZjQzY2JiZDdmNDBiNTY1OWU3N2MzID0gJChgPGRpdiBpZD0iaHRtbF9iOWY3MTViYzBmMmY0M2NiYmQ3ZjQwYjU2NTllNzdjMyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTE1MTEgKDI1KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9jNmE4YWQ4NTc5MjM0YTcwYTI2OTVlZGExMTQ3MWJiMi5zZXRDb250ZW50KGh0bWxfYjlmNzE1YmMwZjJmNDNjYmJkN2Y0MGI1NjU5ZTc3YzMpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzNiMWJjZDQ4Mzg0MDRlYTBiNzg0NjkzOTAxYWE4ZjQ2LmJpbmRQb3B1cChwb3B1cF9jNmE4YWQ4NTc5MjM0YTcwYTI2OTVlZGExMTQ3MWJiMikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMTQ1ZmYxNGMwMjdmNDBhZWIxMTI4NDFjMWYxMzFkZTcgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDkxMjYzMTIwNDE0NzYsIC0xMjMuMTE1Nzg4OTk2MjE5NjRdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzQxN2MyZGFkYTZlZDQzM2NiN2JmNzhhNWFlYTU0ODdjID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9kYmFhODRkYzgzNzY0MzZhOGI5NDJmZGNhNzM5MzczMiA9ICQoYDxkaXYgaWQ9Imh0bWxfZGJhYTg0ZGM4Mzc2NDM2YThiOTQyZmRjYTczOTM3MzIiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUxNTc0ICgyNSk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfNDE3YzJkYWRhNmVkNDMzY2I3YmY3OGE1YWVhNTQ4N2Muc2V0Q29udGVudChodG1sX2RiYWE4NGRjODM3NjQzNmE4Yjk0MmZkY2E3MzkzNzMyKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl8xNDVmZjE0YzAyN2Y0MGFlYjExMjg0MWMxZjEzMWRlNy5iaW5kUG9wdXAocG9wdXBfNDE3YzJkYWRhNmVkNDMzY2I3YmY3OGE1YWVhNTQ4N2MpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzE5YjEyMTlhNDUzZjQ0M2I4OTE2YTAyZDkwZWZkNDQ0ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjQ5MTcyMjI4NzY0MjMsIC0xMjMuMTE1MzkyNjA4NzY1NjddLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzU2N2JiYjIzMTYyNzRiOTQ4NGY3YjY4ZmU5ZmEzZWQ3ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9kZmFlZjdiNWQ2MWM0MjQyOTYwMDU4MzYxNWNhZTAwNiA9ICQoYDxkaXYgaWQ9Imh0bWxfZGZhZWY3YjVkNjFjNDI0Mjk2MDA1ODM2MTVjYWUwMDYiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUwNDc1ICgxNSwzMyk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfNTY3YmJiMjMxNjI3NGI5NDg0ZjdiNjhmZTlmYTNlZDcuc2V0Q29udGVudChodG1sX2RmYWVmN2I1ZDYxYzQyNDI5NjAwNTgzNjE1Y2FlMDA2KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl8xOWIxMjE5YTQ1M2Y0NDNiODkxNmEwMmQ5MGVmZDQ0NC5iaW5kUG9wdXAocG9wdXBfNTY3YmJiMjMxNjI3NGI5NDg0ZjdiNjhmZTlmYTNlZDcpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2ZiZjgxZmQ5Yzg2NjRjMGQ5ZGQzNWM1ZWIxYWY3Y2IyID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjQ4NjEwODc4OTAyNDU0LCAtMTIzLjExNTcwNzYwMTM3MTExXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF80NzQ1MTkzNmQxMTc0ODJlOWRkNDk5MTYwMmUzZTljMSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNjM1YmFiZmI1OGJlNDUxYTkyMjBmNWMwMzZjNDVmNTIgPSAkKGA8ZGl2IGlkPSJodG1sXzYzNWJhYmZiNThiZTQ1MWE5MjIwZjVjMDM2YzQ1ZjUyIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MDQxOSAoMTUsMzMpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzQ3NDUxOTM2ZDExNzQ4MmU5ZGQ0OTkxNjAyZTNlOWMxLnNldENvbnRlbnQoaHRtbF82MzViYWJmYjU4YmU0NTFhOTIyMGY1YzAzNmM0NWY1Mik7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfZmJmODFmZDljODY2NGMwZDlkZDM1YzVlYjFhZjdjYjIuYmluZFBvcHVwKHBvcHVwXzQ3NDUxOTM2ZDExNzQ4MmU5ZGQ0OTkxNjAyZTNlOWMxKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9mNjAzMTg0MTllN2M0Zjk4YWZiNGE4NmY0MGIxNDdiYyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI1MDk4NTQwMzQ1NDgxLCAtMTIzLjExNTQ2ODQxMDYzNTMyXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF80ZWNhZjg3NzBlNjM0MGNjYmY5OTQzMWM2NjU3OGY1NiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfODA0Nzk1NGM1ZTIzNDk0NTljMDQ3MmM2NTQyOGVkNTggPSAkKGA8ZGl2IGlkPSJodG1sXzgwNDc5NTRjNWUyMzQ5NDU5YzA0NzJjNjU0MjhlZDU4IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MDQ3NiAoMTUsMzMpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzRlY2FmODc3MGU2MzQwY2NiZjk5NDMxYzY2NTc4ZjU2LnNldENvbnRlbnQoaHRtbF84MDQ3OTU0YzVlMjM0OTQ1OWMwNDcyYzY1NDI4ZWQ1OCk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfZjYwMzE4NDE5ZTdjNGY5OGFmYjRhODZmNDBiMTQ3YmMuYmluZFBvcHVwKHBvcHVwXzRlY2FmODc3MGU2MzQwY2NiZjk5NDMxYzY2NTc4ZjU2KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9kZTg4ZGJlMmYyYzY0NmNmYjg0MTBkYjExNDVkZDc0OSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI0ODkzMDU4MzE1MzQ5NSwgLTEyMy4xMTQ4NTY0NjIxMzc5NV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfMDY2Y2EwZWRlZTBjNGEyYTg2YzExYjYyODU1NDIzOGIgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2RmNjBjOGFlODIyNDQ2YTA5MzgyZjQwNGU1ZjE4NjQzID0gJChgPGRpdiBpZD0iaHRtbF9kZjYwYzhhZTgyMjQ0NmEwOTM4MmY0MDRlNWYxODY0MyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTE1MTMgKDI1KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8wNjZjYTBlZGVlMGM0YTJhODZjMTFiNjI4NTU0MjM4Yi5zZXRDb250ZW50KGh0bWxfZGY2MGM4YWU4MjI0NDZhMDkzODJmNDA0ZTVmMTg2NDMpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2RlODhkYmUyZjJjNjQ2Y2ZiODQxMGRiMTE0NWRkNzQ5LmJpbmRQb3B1cChwb3B1cF8wNjZjYTBlZGVlMGM0YTJhODZjMTFiNjI4NTU0MjM4YikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNWM0ZjcyZjY4ZDE3NDQ1MWE5ODMzZWNkMTk1ZDBhYWUgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNTMxNzMsIC0xMjMuMTE1MzQzXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9hMjJkMDEzMDNkZDI0NTY2OTAzNTE5MTgwYzA0ZWQ0OSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfOGI3N2IxMGVkMWE5NGNkYjg1NzE4YmU4NzRlMWJjNTcgPSAkKGA8ZGl2IGlkPSJodG1sXzhiNzdiMTBlZDFhOTRjZGI4NTcxOGJlODc0ZTFiYzU3IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MDQ3NyAoMTUsMzMpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2EyMmQwMTMwM2RkMjQ1NjY5MDM1MTkxODBjMDRlZDQ5LnNldENvbnRlbnQoaHRtbF84Yjc3YjEwZWQxYTk0Y2RiODU3MThiZTg3NGUxYmM1Nyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfNWM0ZjcyZjY4ZDE3NDQ1MWE5ODMzZWNkMTk1ZDBhYWUuYmluZFBvcHVwKHBvcHVwX2EyMmQwMTMwM2RkMjQ1NjY5MDM1MTkxODBjMDRlZDQ5KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8zNGFmZWEwMmY2YjM0YjhhYjk3NDhkYzZhN2EzNzgyMyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI0OTMyNzAyMjI4OTIxLCAtMTIzLjEyNjU4NjQ4OTc4ODQ0XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9kYmYyNjQyOTRjYTY0NzVmYjNkYzRlMjIzNTk5MjMwNCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNWNjYWQxMTA1MjAxNDAxMWEzYjA1YjQwYzNlMWIwNWYgPSAkKGA8ZGl2IGlkPSJodG1sXzVjY2FkMTEwNTIwMTQwMTFhM2IwNWI0MGMzZTFiMDVmIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MTU3NiAoMjUpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2RiZjI2NDI5NGNhNjQ3NWZiM2RjNGUyMjM1OTkyMzA0LnNldENvbnRlbnQoaHRtbF81Y2NhZDExMDUyMDE0MDExYTNiMDViNDBjM2UxYjA1Zik7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfMzRhZmVhMDJmNmIzNGI4YWI5NzQ4ZGM2YTdhMzc4MjMuYmluZFBvcHVwKHBvcHVwX2RiZjI2NDI5NGNhNjQ3NWZiM2RjNGUyMjM1OTkyMzA0KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl84MjVmNzZjOTE0YTI0NzEyOWM1ZWQ0Mjk1NzI1ZWJlNyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI0OTAzMTc2NTAyMDc3NCwgLTEyMy4xMjY5MDEzODgxNjgzMl0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfNzk0MTZiMTkwOGFjNDNiYmJmNzVhYzNhOWIzOTNkYjMgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2Q3NDVkYTk1NGIwNjQyNTc4NzMxMmFlNWUzMDRjOWZlID0gJChgPGRpdiBpZD0iaHRtbF9kNzQ1ZGE5NTRiMDY0MjU3ODczMTJhZTVlMzA0YzlmZSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTE1MTAgKDI1KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF83OTQxNmIxOTA4YWM0M2JiYmY3NWFjM2E5YjM5M2RiMy5zZXRDb250ZW50KGh0bWxfZDc0NWRhOTU0YjA2NDI1Nzg3MzEyYWU1ZTMwNGM5ZmUpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzgyNWY3NmM5MTRhMjQ3MTI5YzVlZDQyOTU3MjVlYmU3LmJpbmRQb3B1cChwb3B1cF83OTQxNmIxOTA4YWM0M2JiYmY3NWFjM2E5YjM5M2RiMykKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNTQ0MTcyMmY1NzQ4NDU0OTk5MzYwYmM4ZGQyODBiYjMgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDg4NjcsIC0xMjMuMTExNzRdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzlkOTM2NGQ1ODc1MDQ0NThiNWJjYTU2OTRiMGE3MGQxID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF8yNDYzYWIwOTNiZDQ0NDRjOWNmOTg0YjVjMDIzYzg3OSA9ICQoYDxkaXYgaWQ9Imh0bWxfMjQ2M2FiMDkzYmQ0NDQ0YzljZjk4NGI1YzAyM2M4NzkiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUxNTE0ICgyNSk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfOWQ5MzY0ZDU4NzUwNDQ1OGI1YmNhNTY5NGIwYTcwZDEuc2V0Q29udGVudChodG1sXzI0NjNhYjA5M2JkNDQ0NGM5Y2Y5ODRiNWMwMjNjODc5KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl81NDQxNzIyZjU3NDg0NTQ5OTkzNjBiYzhkZDI4MGJiMy5iaW5kUG9wdXAocG9wdXBfOWQ5MzY0ZDU4NzUwNDQ1OGI1YmNhNTY5NGIwYTcwZDEpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzIzYTBhYjc0YWNkZTRlMGJhYWVkZDk1MjI5YzU5MDhiID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjQ5NjA2MDQ3ODM3NzQ0LCAtMTIzLjEyNzM3ODgyMTM3M10sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfMTA0ZDZiNjgwMmNiNGYwNmJiZWRhMjFkMjViMzI0ZjYgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzg0YjllMzhkMzFlYjRlNTJhMmI1ZDg4OWNlZmE1MTUwID0gJChgPGRpdiBpZD0iaHRtbF84NGI5ZTM4ZDMxZWI0ZTUyYTJiNWQ4ODljZWZhNTE1MCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTA0NTYgKDE3KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8xMDRkNmI2ODAyY2I0ZjA2YmJlZGEyMWQyNWIzMjRmNi5zZXRDb250ZW50KGh0bWxfODRiOWUzOGQzMWViNGU1MmEyYjVkODg5Y2VmYTUxNTApOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzIzYTBhYjc0YWNkZTRlMGJhYWVkZDk1MjI5YzU5MDhiLmJpbmRQb3B1cChwb3B1cF8xMDRkNmI2ODAyY2I0ZjA2YmJlZGEyMWQyNWIzMjRmNikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNjZkNzkzYWMzZDI4NGUzZGJhMzgyOWFjZDI3NDA2MGYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDg5NjY0NjAyOTMxMDQsIC0xMjMuMTI3NTM1ODMyMjY2OTZdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzdjNzc2YWUyNzA2MjRkNzI5NjQzOGE2ZjMyN2RlYjc0ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9hZjc3YjZiMDI3MTQ0ZWJiYjcwY2FkYTkzYTNkNjBlYyA9ICQoYDxkaXYgaWQ9Imh0bWxfYWY3N2I2YjAyNzE0NGViYmI3MGNhZGE5M2EzZDYwZWMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUwMzM3ICgxNyk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfN2M3NzZhZTI3MDYyNGQ3Mjk2NDM4YTZmMzI3ZGViNzQuc2V0Q29udGVudChodG1sX2FmNzdiNmIwMjcxNDRlYmJiNzBjYWRhOTNhM2Q2MGVjKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl82NmQ3OTNhYzNkMjg0ZTNkYmEzODI5YWNkMjc0MDYwZi5iaW5kUG9wdXAocG9wdXBfN2M3NzZhZTI3MDYyNGQ3Mjk2NDM4YTZmMzI3ZGViNzQpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2JiOWQ4MGRlOGQ1NDQ3YzU4ODQ5NmVkNjhlNzJiZDA5ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjQ5MzkyNDQzNDIzOSwgLTEyMy4xMjc4ODMwNzY2Njc4XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9hM2Q5MmNjNGM0OGY0Zjk3OTMxNmY2MjBiYzA4ZWYyNCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNGE0NDMyMDkyYjhlNDIyOGIyMDlmYjg0YTVkNmJlNzcgPSAkKGA8ZGl2IGlkPSJodG1sXzRhNDQzMjA5MmI4ZTQyMjhiMjA5ZmI4NGE1ZDZiZTc3IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MTU3NyAoMjUpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2EzZDkyY2M0YzQ4ZjRmOTc5MzE2ZjYyMGJjMDhlZjI0LnNldENvbnRlbnQoaHRtbF80YTQ0MzIwOTJiOGU0MjI4YjIwOWZiODRhNWQ2YmU3Nyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYmI5ZDgwZGU4ZDU0NDdjNTg4NDk2ZWQ2OGU3MmJkMDkuYmluZFBvcHVwKHBvcHVwX2EzZDkyY2M0YzQ4ZjRmOTc5MzE2ZjYyMGJjMDhlZjI0KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8xNzAzZmFhNWU3YTQ0OGE4OGZkNmNlYjU1OTkyNzk2YiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI0NzQ5MjY2Mjc2NjA2NCwgLTEyMy4xMjc1NTAxNzc3NzEyM10sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfZjBmNTUwOGYzNzQ2NDAwNGE5MmRhMDIzZDU2MjY1YmUgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2FjNTc3YjNlMThmMjQzY2JhZjBhNGQ4MDdmZGU4MDQ3ID0gJChgPGRpdiBpZD0iaHRtbF9hYzU3N2IzZTE4ZjI0M2NiYWYwYTRkODA3ZmRlODA0NyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTA0NTUgKDE3KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9mMGY1NTA4ZjM3NDY0MDA0YTkyZGEwMjNkNTYyNjViZS5zZXRDb250ZW50KGh0bWxfYWM1NzdiM2UxOGYyNDNjYmFmMGE0ZDgwN2ZkZTgwNDcpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzE3MDNmYWE1ZTdhNDQ4YTg4ZmQ2Y2ViNTU5OTI3OTZiLmJpbmRQb3B1cChwb3B1cF9mMGY1NTA4ZjM3NDY0MDA0YTkyZGEwMjNkNTYyNjViZSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYjFiYjk1OTgyZWIzNDhhNjk5ZGE0MGI0NzU2YjljNTQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNTE0MzA5NDA0NDQzOSwgLTEyMy4xMjc3ODQxNjA2MTkzXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9iOTRiOTJjZDhiYTk0N2UxODdjYjNmODQzYjQwOTZlZCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfYTA1ZmI0ZjY3OWE1NGI0OWExNzU2ZmZkYzAwNWQ3ZTcgPSAkKGA8ZGl2IGlkPSJodG1sX2EwNWZiNGY2NzlhNTRiNDlhMTc1NmZmZGMwMDVkN2U3IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MDMzNiAoMTcpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2I5NGI5MmNkOGJhOTQ3ZTE4N2NiM2Y4NDNiNDA5NmVkLnNldENvbnRlbnQoaHRtbF9hMDVmYjRmNjc5YTU0YjQ5YTE3NTZmZmRjMDA1ZDdlNyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYjFiYjk1OTgyZWIzNDhhNjk5ZGE0MGI0NzU2YjljNTQuYmluZFBvcHVwKHBvcHVwX2I5NGI5MmNkOGJhOTQ3ZTE4N2NiM2Y4NDNiNDA5NmVkKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9hODY2OGY0Y2I5NTU0MjY1YjNhY2NkZTYzNGM3NDQzNiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI1NDk1MzcxMTE4MDE1LCAtMTIzLjExNTE5NTIwOTk4ODVdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2FlZjI5MmNlY2MyMDQ1NzhiZmRhOGQxNDBmY2E4MzhhID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9jMWU0ZGE3MWY2OGM0NzdlYmU0ODJiMjI2NjMyNWM3ZSA9ICQoYDxkaXYgaWQ9Imh0bWxfYzFlNGRhNzFmNjhjNDc3ZWJlNDgyYjIyNjYzMjVjN2UiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUwNDE2ICgxNSwzMyk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfYWVmMjkyY2VjYzIwNDU3OGJmZGE4ZDE0MGZjYTgzOGEuc2V0Q29udGVudChodG1sX2MxZTRkYTcxZjY4YzQ3N2ViZTQ4MmIyMjY2MzI1YzdlKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9hODY2OGY0Y2I5NTU0MjY1YjNhY2NkZTYzNGM3NDQzNi5iaW5kUG9wdXAocG9wdXBfYWVmMjkyY2VjYzIwNDU3OGJmZGE4ZDE0MGZjYTgzOGEpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzAwOWQxMTZjNDNlZTQxODk5MzZhYzcyZjAwNjFmMDIzID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjQ0ODQzMjg5OTY2ODk0LCAtMTIzLjEyNTAxODU1OTE2NDE4XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF80YzQ1OTYyOWZkZjc0Y2M2ODJlZjljNDNjODdhNDIxZSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfOTM2NDcxYmYyNGZhNDIzZDhmODcwNGFhYjA2ODQ3MjMgPSAkKGA8ZGl2IGlkPSJodG1sXzkzNjQ3MWJmMjRmYTQyM2Q4Zjg3MDRhYWIwNjg0NzIzIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MDQyMCAoMTUsMzMpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzRjNDU5NjI5ZmRmNzRjYzY4MmVmOWM0M2M4N2E0MjFlLnNldENvbnRlbnQoaHRtbF85MzY0NzFiZjI0ZmE0MjNkOGY4NzA0YWFiMDY4NDcyMyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfMDA5ZDExNmM0M2VlNDE4OTkzNmFjNzJmMDA2MWYwMjMuYmluZFBvcHVwKHBvcHVwXzRjNDU5NjI5ZmRmNzRjYzY4MmVmOWM0M2M4N2E0MjFlKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl81YTYyY2U5YzMxMmM0Yzk4OGFhM2JhMjBiNGU4Mjk3YiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI1NTEwNjA2NzE5MTc4LCAtMTIzLjExNTA3MTgxNDc4NDJdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzdlNTlmNzYyZDU0OTQ0YjBhMTA2NmZhMGE3YzgwMjAyID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9hYmFmOTg0ZDIwZTA0ODkyODhiMzQ1NzY1ZTE5MjljZiA9ICQoYDxkaXYgaWQ9Imh0bWxfYWJhZjk4NGQyMGUwNDg5Mjg4YjM0NTc2NWUxOTI5Y2YiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUwNDc4ICgxNSwzMyk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfN2U1OWY3NjJkNTQ5NDRiMGExMDY2ZmEwYTdjODAyMDIuc2V0Q29udGVudChodG1sX2FiYWY5ODRkMjBlMDQ4OTI4OGIzNDU3NjVlMTkyOWNmKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl81YTYyY2U5YzMxMmM0Yzk4OGFhM2JhMjBiNGU4Mjk3Yi5iaW5kUG9wdXAocG9wdXBfN2U1OWY3NjJkNTQ5NDRiMGExMDY2ZmEwYTdjODAyMDIpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzk3MDlkNDYzZThjMTQ5ZjNiMGU2MTM4NDBjOTVhZDc5ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjUzOTYzLCAtMTIzLjEyNzM0OF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfNGNlZWEwODljZGIyNDc3MDg3Zjk2N2U3MmI5OGEzY2UgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzcyMjg3NTMxNDQyYzRlNmE5MDliYWEyNTY1MzIzMmM0ID0gJChgPGRpdiBpZD0iaHRtbF83MjI4NzUzMTQ0MmM0ZTZhOTA5YmFhMjU2NTMyMzJjNCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTA0NTggKDE3KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF80Y2VlYTA4OWNkYjI0NzcwODdmOTY3ZTcyYjk4YTNjZS5zZXRDb250ZW50KGh0bWxfNzIyODc1MzE0NDJjNGU2YTkwOWJhYTI1NjUzMjMyYzQpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzk3MDlkNDYzZThjMTQ5ZjNiMGU2MTM4NDBjOTVhZDc5LmJpbmRQb3B1cChwb3B1cF80Y2VlYTA4OWNkYjI0NzcwODdmOTY3ZTcyYjk4YTNjZSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfODUyYjg4OTkyMWEzNDNhOThmM2EzNTc0YTVhMTVlZjcgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDMwMzUsIC0xMjMuMTE4NDkwOTk5OTk5OTldLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzAyMzhlNjIxZjA4YjQzZmY4ZjYzN2EwMDQ2ZDg4ZDY2ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF81YzM5NmRjNDZkMDU0ODY0YTNiYzZhMzJmOGQwM2ZiNiA9ICQoYDxkaXYgaWQ9Imh0bWxfNWMzOTZkYzQ2ZDA1NDg2NGEzYmM2YTMyZjhkMDNmYjYiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUwNDIxICgxNSk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfMDIzOGU2MjFmMDhiNDNmZjhmNjM3YTAwNDZkODhkNjYuc2V0Q29udGVudChodG1sXzVjMzk2ZGM0NmQwNTQ4NjRhM2JjNmEzMmY4ZDAzZmI2KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl84NTJiODg5OTIxYTM0M2E5OGYzYTM1NzRhNWExNWVmNy5iaW5kUG9wdXAocG9wdXBfMDIzOGU2MjFmMDhiNDNmZjhmNjM3YTAwNDZkODhkNjYpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzRjZDFhMGUyMDc5ZDRjM2E4MWIyZjFiZTE0ZWUwNTI1ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjQzODM1MDU5OTQyNjIsIC0xMjMuMTI0NjkzNjUxMjgxNzZdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzc2NGNiMmJiOGFlOTQ2NDhiMzBiNWFhMWE0MTkwMDE4ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9iMmUzYWExYTA0MTM0NTJlYjUzYmE3MTUxZjAxZmNhYSA9ICQoYDxkaXYgaWQ9Imh0bWxfYjJlM2FhMWEwNDEzNDUyZWI1M2JhNzE1MWYwMWZjYWEiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDYxMDk5ICgzMyk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfNzY0Y2IyYmI4YWU5NDY0OGIzMGI1YWExYTQxOTAwMTguc2V0Q29udGVudChodG1sX2IyZTNhYTFhMDQxMzQ1MmViNTNiYTcxNTFmMDFmY2FhKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl80Y2QxYTBlMjA3OWQ0YzNhODFiMmYxYmUxNGVlMDUyNS5iaW5kUG9wdXAocG9wdXBfNzY0Y2IyYmI4YWU5NDY0OGIzMGI1YWExYTQxOTAwMTgpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2YzMDUzOTQ1MmRmZTRkZTdiNTkwNDA0MjNiZTc2MzllID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjU0MDY0NDk3MzIwNywgLTEyMy4xMjczNjE5MDIxOTQ2NV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfZjYzOTJjY2I3MjFmNDdiMTg4ODhkNGU5Mzg3NjIyZGIgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzBiYzY4YTllYmE4MDQxNGZiNDliMTY3YTg0MGY2YWE2ID0gJChgPGRpdiBpZD0iaHRtbF8wYmM2OGE5ZWJhODA0MTRmYjQ5YjE2N2E4NDBmNmFhNiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTAzMzUgKDE3KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9mNjM5MmNjYjcyMWY0N2IxODg4OGQ0ZTkzODc2MjJkYi5zZXRDb250ZW50KGh0bWxfMGJjNjhhOWViYTgwNDE0ZmI0OWIxNjdhODQwZjZhYTYpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2YzMDUzOTQ1MmRmZTRkZTdiNTkwNDA0MjNiZTc2MzllLmJpbmRQb3B1cChwb3B1cF9mNjM5MmNjYjcyMWY0N2IxODg4OGQ0ZTkzODc2MjJkYikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfOTgwNDlmYzk2ZTdkNDNmNmI2MTc1M2QwNWM0MGVlOGYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDQ2MTk2MDExNzI0MiwgLTEyMy4xMjY1Njk4OTc2MzQ4NV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfZmZlMjc1NWE3YTYyNGM2OTk1Y2Q4MmNlMGZlMjY1ZmQgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzc5MzcyZGJlZGFjYTQxYTJhMzc2MzhiZDI5ZTFkZDU2ID0gJChgPGRpdiBpZD0iaHRtbF83OTM3MmRiZWRhY2E0MWEyYTM3NjM4YmQyOWUxZGQ1NiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTA0NTQgKDE3KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9mZmUyNzU1YTdhNjI0YzY5OTVjZDgyY2UwZmUyNjVmZC5zZXRDb250ZW50KGh0bWxfNzkzNzJkYmVkYWNhNDFhMmEzNzYzOGJkMjllMWRkNTYpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzk4MDQ5ZmM5NmU3ZDQzZjZiNjE3NTNkMDVjNDBlZThmLmJpbmRQb3B1cChwb3B1cF9mZmUyNzU1YTdhNjI0YzY5OTVjZDgyY2UwZmUyNjVmZCkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYjk0YTkyM2ZhNzk3NDE3Y2E2Y2U5ZTg0MDJhNDA4OTQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNTY5MTA5ODMxMDA0MDQsIC0xMjMuMTE1NDQwNTc5MjkxODddLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2UxZDA4NWVlZjE2ODQ1OTFhOGMxNGJiZjZlMmNjMmU1ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9lN2M3YWI2MGJkNjc0ZWVkOWMyZDc4NjlhN2MzZjQwNSA9ICQoYDxkaXYgaWQ9Imh0bWxfZTdjN2FiNjBiZDY3NGVlZDljMmQ3ODY5YTdjM2Y0MDUiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDYxMTIxICgzMyk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfZTFkMDg1ZWVmMTY4NDU5MWE4YzE0YmJmNmUyY2MyZTUuc2V0Q29udGVudChodG1sX2U3YzdhYjYwYmQ2NzRlZWQ5YzJkNzg2OWE3YzNmNDA1KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9iOTRhOTIzZmE3OTc0MTdjYTZjZTllODQwMmE0MDg5NC5iaW5kUG9wdXAocG9wdXBfZTFkMDg1ZWVmMTY4NDU5MWE4YzE0YmJmNmUyY2MyZTUpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzQ5YzQ3ZTU5OGRlMzQwZjg4ZjMwMGNlNTMxOWVmZTI5ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjU2ODQ3LCAtMTIzLjExNTE1MzMxMjY3OTUyXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF84NDRhZjI1MzRmNDA0MDM1YmQ1MzI2N2EyMDgzYzExYiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfY2Q3M2FkNjcwYjIzNDVjZDkxMzY2ODYxN2VmYjllOWEgPSAkKGA8ZGl2IGlkPSJodG1sX2NkNzNhZDY3MGIyMzQ1Y2Q5MTM2Njg2MTdlZmI5ZTlhIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MDQxNSAoMTUsMzMpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzg0NGFmMjUzNGY0MDQwMzViZDUzMjY3YTIwODNjMTFiLnNldENvbnRlbnQoaHRtbF9jZDczYWQ2NzBiMjM0NWNkOTEzNjY4NjE3ZWZiOWU5YSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfNDljNDdlNTk4ZGUzNDBmODhmMzAwY2U1MzE5ZWZlMjkuYmluZFBvcHVwKHBvcHVwXzg0NGFmMjUzNGY0MDQwMzViZDUzMjY3YTIwODNjMTFiKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9jOGYzYjExNzliNGQ0MzU0YjhlNTdmMWYxZDNjNWNjMSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI0NDEzNCwgLTEyMy4xMjc2OThdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzI5MTMzYzE1N2Y5ZTQ3ZWE4MjI2NDQ2YmRkN2FjZjJjID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9iNWQzNzI0OGYyNDA0OWUxODM2NjZlM2I3NmZkMDA4MyA9ICQoYDxkaXYgaWQ9Imh0bWxfYjVkMzcyNDhmMjQwNDllMTgzNjY2ZTNiNzZmZDAwODMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUwMzM5ICgxNyk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfMjkxMzNjMTU3ZjllNDdlYTgyMjY0NDZiZGQ3YWNmMmMuc2V0Q29udGVudChodG1sX2I1ZDM3MjQ4ZjI0MDQ5ZTE4MzY2NmUzYjc2ZmQwMDgzKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9jOGYzYjExNzliNGQ0MzU0YjhlNTdmMWYxZDNjNWNjMS5iaW5kUG9wdXAocG9wdXBfMjkxMzNjMTU3ZjllNDdlYTgyMjY0NDZiZGQ3YWNmMmMpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzIyYjUzODAxNWYyODRhZGQ4MWM4MzQ5OGQ0N2QwZjZlID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjU3MTQ0MDA0ODUwMjU0LCAtMTIzLjExNTA4MjY1MDkxNTc4XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9iMmRjYzIzYTQ1YTM0Yzc5OTljNmNkZGIzNzBjYzEwNSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNjZhMDU5ZDgyNjRjNGIwYjkwYzkyNDc0OTViNTQxMTMgPSAkKGA8ZGl2IGlkPSJodG1sXzY2YTA1OWQ4MjY0YzRiMGI5MGM5MjQ3NDk1YjU0MTEzIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MDQ3OSAoMTUpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2IyZGNjMjNhNDVhMzRjNzk5OWM2Y2RkYjM3MGNjMTA1LnNldENvbnRlbnQoaHRtbF82NmEwNTlkODI2NGM0YjBiOTBjOTI0NzQ5NWI1NDExMyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfMjJiNTM4MDE1ZjI4NGFkZDgxYzgzNDk4ZDQ3ZDBmNmUuYmluZFBvcHVwKHBvcHVwX2IyZGNjMjNhNDVhMzRjNzk5OWM2Y2RkYjM3MGNjMTA1KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9hMTYyZDU2YmUyNjY0MWVkYWQ2NWZhNzFhZTdiNGEyMyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI0ODc0ODIwNjA5NDQyNiwgLTEyMy4xMDcyMzE4NzQ4OTQwMV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfNWI2ZjA3NGFiNTE2NDI2NDkzNzBiODMzODc1NzY3N2YgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzdhYjM0ZjgwZmVmMzRlMzI5MGE0MmM5ZjI5NDkzNDk0ID0gJChgPGRpdiBpZD0iaHRtbF83YWIzNGY4MGZlZjM0ZTMyOTBhNDJjOWYyOTQ5MzQ5NCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTE1MTYgKDI1KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF81YjZmMDc0YWI1MTY0MjY0OTM3MGI4MzM4NzU3Njc3Zi5zZXRDb250ZW50KGh0bWxfN2FiMzRmODBmZWYzNGUzMjkwYTQyYzlmMjk0OTM0OTQpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2ExNjJkNTZiZTI2NjQxZWRhZDY1ZmE3MWFlN2I0YTIzLmJpbmRQb3B1cChwb3B1cF81YjZmMDc0YWI1MTY0MjY0OTM3MGI4MzM4NzU3Njc3ZikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfOGQwMzcyNjFjMGUxNDU0ZWI0NTRhMGI2YjQyNGU4NjggPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNTY1MTc5Mjc4ODUyNTUsIC0xMjMuMTI3MDQwODYzMDM3MTJdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzFmY2EzMGUyM2Y0ZTQ0Yzc4YmM1MjA0NjAwNmI2ZGU3ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF80NGQwNDViNzQ1MTI0OTM1YWE3YTA1N2FjZTk1MjQ4YSA9ICQoYDxkaXYgaWQ9Imh0bWxfNDRkMDQ1Yjc0NTEyNDkzNWFhN2EwNTdhY2U5NTI0OGEiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUwNDU5ICgxNyk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfMWZjYTMwZTIzZjRlNDRjNzhiYzUyMDQ2MDA2YjZkZTcuc2V0Q29udGVudChodG1sXzQ0ZDA0NWI3NDUxMjQ5MzVhYTdhMDU3YWNlOTUyNDhhKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl84ZDAzNzI2MWMwZTE0NTRlYjQ1NGEwYjZiNDI0ZTg2OC5iaW5kUG9wdXAocG9wdXBfMWZjYTMwZTIzZjRlNDRjNzhiYzUyMDQ2MDA2YjZkZTcpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2FjNmMxMmFlMTkzMzRmMWFiZjU2YWI0OTM1MDU2ZTU2ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjU2OTYyOTU4NDAzMTg2LCAtMTIzLjEyNzc3NTUyODM2MzI5XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9hYWRkZGRjZmY3MTE0NGY0OTgxNDkwNDBhYTkwNjc0NCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNDg5ZGFhMDIzNDM3NGNkOGJiMTRjNGFhMTRkODliYjIgPSAkKGA8ZGl2IGlkPSJodG1sXzQ4OWRhYTAyMzQzNzRjZDhiYjE0YzRhYTE0ZDg5YmIyIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA2MTA5NiAoMzMpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2FhZGRkZGNmZjcxMTQ0ZjQ5ODE0OTA0MGFhOTA2NzQ0LnNldENvbnRlbnQoaHRtbF80ODlkYWEwMjM0Mzc0Y2Q4YmIxNGM0YWExNGQ4OWJiMik7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYWM2YzEyYWUxOTMzNGYxYWJmNTZhYjQ5MzUwNTZlNTYuYmluZFBvcHVwKHBvcHVwX2FhZGRkZGNmZjcxMTQ0ZjQ5ODE0OTA0MGFhOTA2NzQ0KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8wMjg1YWUyMDA5Yjc0YTg5YWRhZTQ3OGY4MzI3NDNmYiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI1NzI0NjU3OTIzMTI5LCAtMTIzLjEyNzE4OTA5NDgzOTA0XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF83YjUxN2Q0OWM1Yjg0MWQxOWVmMmIyN2VkNmNjZGQ2YSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNDczYTMxY2MzOWYwNGIwYWFiYzk0Njk5ZjA4ODZmYWYgPSAkKGA8ZGl2IGlkPSJodG1sXzQ3M2EzMWNjMzlmMDRiMGFhYmM5NDY5OWYwODg2ZmFmIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA2MTEyNCAoMzMpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzdiNTE3ZDQ5YzViODQxZDE5ZWYyYjI3ZWQ2Y2NkZDZhLnNldENvbnRlbnQoaHRtbF80NzNhMzFjYzM5ZjA0YjBhYWJjOTQ2OTlmMDg4NmZhZik7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfMDI4NWFlMjAwOWI3NGE4OWFkYWU0NzhmODMyNzQzZmIuYmluZFBvcHVwKHBvcHVwXzdiNTE3ZDQ5YzViODQxZDE5ZWYyYjI3ZWQ2Y2NkZDZhKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8wNDQ5OGJmMDMwOWY0MWU1YWQwMzBkMzY5YzViZWE5NSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI1NzU4Mzg1MDk0ODU2LCAtMTIzLjEyNjU5MjY2ODYyODg2XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF85NTYxYzkyMTkwZjE0M2U3YmJiYTAzZjM2ZjI0ZjQ1ZSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfMTQyZTQxZDVkZDUzNGM3ZmJhOWVkMTY4YTIyZWQ0ODAgPSAkKGA8ZGl2IGlkPSJodG1sXzE0MmU0MWQ1ZGQ1MzRjN2ZiYTllZDE2OGEyMmVkNDgwIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MDMzMyAoMTcpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzk1NjFjOTIxOTBmMTQzZTdiYmJhMDNmMzZmMjRmNDVlLnNldENvbnRlbnQoaHRtbF8xNDJlNDFkNWRkNTM0YzdmYmE5ZWQxNjhhMjJlZDQ4MCk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfMDQ0OThiZjAzMDlmNDFlNWFkMDMwZDM2OWM1YmVhOTUuYmluZFBvcHVwKHBvcHVwXzk1NjFjOTIxOTBmMTQzZTdiYmJhMDNmMzZmMjRmNDVlKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9iM2MwOTQ0N2RlMTc0MTRmYmYzNTQxMmM4NGE5ZTUyOCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI0MjcxNzk5NTI2MzE1NiwgLTEyMy4xMDg2ODAwNzI1Mzk3N10sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfNmYxMDZiZWI3ZWNjNDcyZmFjZjFhY2UyODgzNzdlNDMgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2MzZmI0ZWE1NzczNzQ5MmJhOTZhZmI4MjU5MDc3NjU1ID0gJChgPGRpdiBpZD0iaHRtbF9jM2ZiNGVhNTc3Mzc0OTJiYTk2YWZiODI1OTA3NzY1NSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNjExMDAgKDMzKTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF82ZjEwNmJlYjdlY2M0NzJmYWNmMWFjZTI4ODM3N2U0My5zZXRDb250ZW50KGh0bWxfYzNmYjRlYTU3NzM3NDkyYmE5NmFmYjgyNTkwNzc2NTUpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2IzYzA5NDQ3ZGUxNzQxNGZiZjM1NDEyYzg0YTllNTI4LmJpbmRQb3B1cChwb3B1cF82ZjEwNmJlYjdlY2M0NzJmYWNmMWFjZTI4ODM3N2U0MykKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfN2Y5MDI4Yjg1ZGYyNDIyNjllNjcxNGNhNTIyZjAwNTIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDE0NDY0MDMwMjY4MiwgLTEyMy4xMjc4NTYyNTQ1Nzc2Ml0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfOTJhNWYwMWY4Mzg1NDkxMGFmYTcwZDlhMjIwNmEyNjYgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2EyNDBkZTI1ZjA0ZDQ2NGRhYzYwYzg3YjAyMDFjYzAzID0gJChgPGRpdiBpZD0iaHRtbF9hMjQwZGUyNWYwNGQ0NjRkYWM2MGM4N2IwMjAxY2MwMyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTA0NTMgKDE3KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF85MmE1ZjAxZjgzODU0OTEwYWZhNzBkOWEyMjA2YTI2Ni5zZXRDb250ZW50KGh0bWxfYTI0MGRlMjVmMDRkNDY0ZGFjNjBjODdiMDIwMWNjMDMpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzdmOTAyOGI4NWRmMjQyMjY5ZTY3MTRjYTUyMmYwMDUyLmJpbmRQb3B1cChwb3B1cF85MmE1ZjAxZjgzODU0OTEwYWZhNzBkOWEyMjA2YTI2NikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZWI1NjI2ODFlODA0NDcxNmFkYTgzNjA1ZDgyZjkzYmYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNTg1MjA1ODE1ODE3NTYsIC0xMjMuMTI2NzgzMzcwOTcxNjhdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzFlZjUyZmU4MTE0MDQ2OTY5ZWIyNTU4YjMyODU0M2YzID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9kOTg3MzZhOGNkOWE0ZTlhODIwMGM5NzlmMmY0ZWY1ZSA9ICQoYDxkaXYgaWQ9Imh0bWxfZDk4NzM2YThjZDlhNGU5YTgyMDBjOTc5ZjJmNGVmNWUiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUwMzMyICgxNyk8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfMWVmNTJmZTgxMTQwNDY5NjllYjI1NThiMzI4NTQzZjMuc2V0Q29udGVudChodG1sX2Q5ODczNmE4Y2Q5YTRlOWE4MjAwYzk3OWYyZjRlZjVlKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9lYjU2MjY4MWU4MDQ0NzE2YWRhODM2MDVkODJmOTNiZi5iaW5kUG9wdXAocG9wdXBfMWVmNTJmZTgxMTQwNDY5NjllYjI1NThiMzI4NTQzZjMpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzc1OTRiMDQ3M2VmMzQzMjE5YzFmOWY1Mzg3OTIzYzc2ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjU5NDE1NDE3OTYxMTY1LCAtMTIzLjExNTA2MjcwMjYwOTQ1XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF82ODYwMjYwNDg0OGI0OWY4ODYxMGU4MGVkNDJhYTM2MSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfMGRkOGQzMzhjMTc5NGRhOWI3ZmY5NjIxZjVmNjRlYWQgPSAkKGA8ZGl2IGlkPSJodG1sXzBkZDhkMzM4YzE3OTRkYTliN2ZmOTYyMWY1ZjY0ZWFkIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MDQ4MCAoMTUpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzY4NjAyNjA0ODQ4YjQ5Zjg4NjEwZTgwZWQ0MmFhMzYxLnNldENvbnRlbnQoaHRtbF8wZGQ4ZDMzOGMxNzk0ZGE5YjdmZjk2MjFmNWY2NGVhZCk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfNzU5NGIwNDczZWYzNDMyMTljMWY5ZjUzODc5MjNjNzYuYmluZFBvcHVwKHBvcHVwXzY4NjAyNjA0ODQ4YjQ5Zjg4NjEwZTgwZWQ0MmFhMzYxKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9lMTBlZjg0N2Y4NTk0OTIzOWU3NmY3YzVjMjk5MjAyZiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI1OTExODQ4MzM3NjQyLCAtMTIzLjEyNjc0NDEwNjM0MjY4XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF82ZTA4MzRhYzVjNjI0OGY5OTMzZDZlODgyNjBiNjljZiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfOWJlYTgwOGQ3NjA3NDk1M2EyMTBiZTZmYzI4MzY2NmQgPSAkKGA8ZGl2IGlkPSJodG1sXzliZWE4MDhkNzYwNzQ5NTNhMjEwYmU2ZmMyODM2NjZkIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MDQ2MCAoMTcpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzZlMDgzNGFjNWM2MjQ4Zjk5MzNkNmU4ODI2MGI2OWNmLnNldENvbnRlbnQoaHRtbF85YmVhODA4ZDc2MDc0OTUzYTIxMGJlNmZjMjgzNjY2ZCk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfZTEwZWY4NDdmODU5NDkyMzllNzZmN2M1YzI5OTIwMmYuYmluZFBvcHVwKHBvcHVwXzZlMDgzNGFjNWM2MjQ4Zjk5MzNkNmU4ODI2MGI2OWNmKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl84ZmZmNjA5MDU1Y2Q0Y2ZlOWViY2VhZmI5NTI4MzI0YSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI2MDExMTM2NTkxMTI2LCAtMTIzLjExNDgzMTk0NDg2NDU5XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF83YzExOGJiNTdlMTI0YzdhOTYxMmMzNmEzMTUzMDZlNSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfOTU4YzE3NDg1NGI2NDczZGI3NjI2YTc1OThkNjY3Y2MgPSAkKGA8ZGl2IGlkPSJodG1sXzk1OGMxNzQ4NTRiNjQ3M2RiNzYyNmE3NTk4ZDY2N2NjIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MDQxNCAoMTUpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzdjMTE4YmI1N2UxMjRjN2E5NjEyYzM2YTMxNTMwNmU1LnNldENvbnRlbnQoaHRtbF85NThjMTc0ODU0YjY0NzNkYjc2MjZhNzU5OGQ2NjdjYyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfOGZmZjYwOTA1NWNkNGNmZTllYmNlYWZiOTUyODMyNGEuYmluZFBvcHVwKHBvcHVwXzdjMTE4YmI1N2UxMjRjN2E5NjEyYzM2YTMxNTMwNmU1KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9kMjQ1MGNmZmY2MTU0ZDBiYTI5NjhmZTczNTJmNWY3MCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjIzODc1OTc0MTk2OTYxNiwgLTEyMy4xMTY2ODUxMDg5ODU1MV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfNjdjYjBmMDQ5N2Q4NDM3OGExMmUyYzJlZDNiYTMyYWMgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzhkYjY5OThlMjAzMjQyNTk5YmE4NjExNzUxZGM2YjBlID0gJChgPGRpdiBpZD0iaHRtbF84ZGI2OTk4ZTIwMzI0MjU5OWJhODYxMTc1MWRjNmIwZSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTA0MjMgKDE1KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF82N2NiMGYwNDk3ZDg0Mzc4YTEyZTJjMmVkM2JhMzJhYy5zZXRDb250ZW50KGh0bWxfOGRiNjk5OGUyMDMyNDI1OTliYTg2MTE3NTFkYzZiMGUpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2QyNDUwY2ZmZjYxNTRkMGJhMjk2OGZlNzM1MmY1ZjcwLmJpbmRQb3B1cChwb3B1cF82N2NiMGYwNDk3ZDg0Mzc4YTEyZTJjMmVkM2JhMzJhYykKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNGQ0OTg5YzQ5YjdhNDYwOGE2NDJkNmM3M2ZiOTBlYWIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNjA0MzkxMzE2MzQ2MzQsIC0xMjMuMTE1MDI0NTY2NjUwNF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfNjllNTdjNDMyNTZhNDY5MmIzYTg1ZjY3NjczYjVhZmIgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzg2ZjgzYTI0OGU2ODRhODBhZTBjYmZmMmZmZDQxNGY0ID0gJChgPGRpdiBpZD0iaHRtbF84NmY4M2EyNDhlNjg0YTgwYWUwY2JmZjJmZmQ0MTRmNCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTA0ODEgKDE1KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF82OWU1N2M0MzI1NmE0NjkyYjNhODVmNjc2NzNiNWFmYi5zZXRDb250ZW50KGh0bWxfODZmODNhMjQ4ZTY4NGE4MGFlMGNiZmYyZmZkNDE0ZjQpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzRkNDk4OWM0OWI3YTQ2MDhhNjQyZDZjNzNmYjkwZWFiLmJpbmRQb3B1cChwb3B1cF82OWU1N2M0MzI1NmE0NjkyYjNhODVmNjc2NzNiNWFmYikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNzczMDc5YTVkNjc4NDFhYWE4YTMzNzFhNDRiZDBiYjEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNTE5MzQ5NTk5NzMwNSwgLTEyMy4xMjc2NjI1MjYwMDM1OF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfOWFiMWQ0MGE1OThlNDNlMmJmMWYzZmZkZTRhMTM0ZDAgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzM5N2NiODhjMGNiNDQ2MjdiNjM2OWU3NTJkODkxMDQ0ID0gJChgPGRpdiBpZD0iaHRtbF8zOTdjYjg4YzBjYjQ0NjI3YjYzNjllNzUyZDg5MTA0NCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTA0NTcgKDE3KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF85YWIxZDQwYTU5OGU0M2UyYmYxZjNmZmRlNGExMzRkMC5zZXRDb250ZW50KGh0bWxfMzk3Y2I4OGMwY2I0NDYyN2I2MzY5ZTc1MmQ4OTEwNDQpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzc3MzA3OWE1ZDY3ODQxYWFhOGEzMzcxYTQ0YmQwYmIxLmJpbmRQb3B1cChwb3B1cF85YWIxZDQwYTU5OGU0M2UyYmYxZjNmZmRlNGExMzRkMCkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYWIwM2EwNmI5OGNhNDhjMGIxMzY1M2RiYjI2MGNlNWIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDkxNzM3NDIyNjIwNCwgLTEyMy4xMzcwMjA0MDcxMTc5Ml0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfNGIyMGNlNzFmYjU0NDhjOTk4ZmFhYjg2ZmI4OTUyZjEgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzAxMjc1MDVjNGU0MzQ3MGFhYzBjNDIwNDE5YTY2ZjQ4ID0gJChgPGRpdiBpZD0iaHRtbF8wMTI3NTA1YzRlNDM0NzBhYWMwYzQyMDQxOWE2NmY0OCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTE1NzkgKDI1KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF80YjIwY2U3MWZiNTQ0OGM5OThmYWFiODZmYjg5NTJmMS5zZXRDb250ZW50KGh0bWxfMDEyNzUwNWM0ZTQzNDcwYWFjMGM0MjA0MTlhNjZmNDgpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2FiMDNhMDZiOThjYTQ4YzBiMTM2NTNkYmIyNjBjZTViLmJpbmRQb3B1cChwb3B1cF80YjIwY2U3MWZiNTQ0OGM5OThmYWFiODZmYjg5NTJmMSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNTRhNmZjZDNkYmM4NDljMjlkYjU0ODk3NjE4M2NmMzAgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDg4NDk2NzM5NTIyNCwgLTEyMy4xMDE0ODQ3NzU1NDMyXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9lYzQ5Mjg1NjViYzI0ZWZiOTM1YzVmMmYwNGZlOGZlYyA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfZjg5YjA5YzAxMTAwNDhlZmJiZmM1NGQxNDcxYzlhNDYgPSAkKGA8ZGl2IGlkPSJodG1sX2Y4OWIwOWMwMTEwMDQ4ZWZiYmZjNTRkMTQ3MWM5YTQ2IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MTU3MSAoMjUpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2VjNDkyODU2NWJjMjRlZmI5MzVjNWYyZjA0ZmU4ZmVjLnNldENvbnRlbnQoaHRtbF9mODliMDljMDExMDA0OGVmYmJmYzU0ZDE0NzFjOWE0Nik7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfNTRhNmZjZDNkYmM4NDljMjlkYjU0ODk3NjE4M2NmMzAuYmluZFBvcHVwKHBvcHVwX2VjNDkyODU2NWJjMjRlZmI5MzVjNWYyZjA0ZmU4ZmVjKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8zZjNjZjg5MDA5YjU0MjJlOWNlNTNmNmE4OTBlZGNjZSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI2MDM0MTQxMzIzNDIxLCAtMTIzLjEyNjY1MDc5MjQwNjEyXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF83ZWUzNjU2NTVhMzM0ZDllYjgxZWZiN2E3MDY0NjExZCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfZjk0OGU2ZTA3M2U2NDBmNWIwNWZhNDY1YWQ1YmJkMjkgPSAkKGA8ZGl2IGlkPSJodG1sX2Y5NDhlNmUwNzNlNjQwZjViMDVmYTQ2NWFkNWJiZDI5IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MDMzMSAoMTcpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzdlZTM2NTY1NWEzMzRkOWViODFlZmI3YTcwNjQ2MTFkLnNldENvbnRlbnQoaHRtbF9mOTQ4ZTZlMDczZTY0MGY1YjA1ZmE0NjVhZDViYmQyOSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfM2YzY2Y4OTAwOWI1NDIyZTljZTUzZjZhODkwZWRjY2UuYmluZFBvcHVwKHBvcHVwXzdlZTM2NTY1NWEzMzRkOWViODFlZmI3YTcwNjQ2MTFkKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9kMDc5ZWM4ZjliNDE0MmMwOWIyZTFkZDExNTBhYWZjOSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI0OTM2NTAwMDAwMDAwNCwgLTEyMy4xMDEyMzVdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2JiMzc2YjY1MTA3ZTQzZDJhNWI5ODkwN2E5ZDU4ZDQzID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF83Zjk2NTVlMWMyNTE0MjdlOGUwNzg1ZmZiMDBiZTIyZCA9ICQoYDxkaXYgaWQ9Imh0bWxfN2Y5NjU1ZTFjMjUxNDI3ZThlMDc4NWZmYjAwYmUyMmQiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUwMjQ1ICgzKTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9iYjM3NmI2NTEwN2U0M2QyYTViOTg5MDdhOWQ1OGQ0My5zZXRDb250ZW50KGh0bWxfN2Y5NjU1ZTFjMjUxNDI3ZThlMDc4NWZmYjAwYmUyMmQpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2QwNzllYzhmOWI0MTQyYzA5YjJlMWRkMTE1MGFhZmM5LmJpbmRQb3B1cChwb3B1cF9iYjM3NmI2NTEwN2U0M2QyYTViOTg5MDdhOWQ1OGQ0MykKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYzlmZjE3NzQxOWVjNDU1YWJmNmY0MmVhMjE5MjhkNmEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDgzNjQsIC0xMjMuMTAxMDg4OTk5OTk5OTldLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2FlZjJhY2I2NWU1MjRjMzc4N2ZmYmRhZDY2MDgyYWUwID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF8xMTQxN2MxYzRiZGY0MGM5OGY1MzQzZGFmZjJjOWMwMCA9ICQoYDxkaXYgaWQ9Imh0bWxfMTE0MTdjMWM0YmRmNDBjOThmNTM0M2RhZmYyYzljMDAiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDYxNjA4ICgzKTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9hZWYyYWNiNjVlNTI0YzM3ODdmZmJkYWQ2NjA4MmFlMC5zZXRDb250ZW50KGh0bWxfMTE0MTdjMWM0YmRmNDBjOThmNTM0M2RhZmYyYzljMDApOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2M5ZmYxNzc0MTllYzQ1NWFiZjZmNDJlYTIxOTI4ZDZhLmJpbmRQb3B1cChwb3B1cF9hZWYyYWNiNjVlNTI0YzM3ODdmZmJkYWQ2NjA4MmFlMCkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZjNlMTc0OGRlZjE5NDAwYWFiMjIzZjQ5MDMzODVmYjQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDg1MjYsIC0xMjMuMTAxMDYyMDAwMDAwMDFdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInB1cnBsZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJwdXJwbGUiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzBlYTYzYjQzMWM5YTQzNWI5NjNmZGUxZmQzODBiZWQ1ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF83YjVhY2E5YjI5ZDg0MTllYmQzYWExMzRkN2Y4ZjI4MyA9ICQoYDxkaXYgaWQ9Imh0bWxfN2I1YWNhOWIyOWQ4NDE5ZWJkM2FhMTM0ZDdmOGYyODMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJ1cyBTdG9wIDUwMjQ2ICgzKTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8wZWE2M2I0MzFjOWE0MzViOTYzZmRlMWZkMzgwYmVkNS5zZXRDb250ZW50KGh0bWxfN2I1YWNhOWIyOWQ4NDE5ZWJkM2FhMTM0ZDdmOGYyODMpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2YzZTE3NDhkZWYxOTQwMGFhYjIyM2Y0OTAzMzg1ZmI0LmJpbmRQb3B1cChwb3B1cF8wZWE2M2I0MzFjOWE0MzViOTYzZmRlMWZkMzgwYmVkNSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZjlkZGQwNzM0MTRmNDBlOGIzODE3YjJhNTYzZjhiZTIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNTE0MDYyMjI2MDEwNiwgLTEyMy4xMDA5ODQ3MjkwNzgwMV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAicHVycGxlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInB1cnBsZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfM2NjMWJkYTRjZmNmNDhlZWJjNjI3NDI4MzNjNWQxOWQgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzkxNjkxZTIxMGE1YzRjZDZiNTAzMDA0MDBmZWQxMWMwID0gJChgPGRpdiBpZD0iaHRtbF85MTY5MWUyMTBhNWM0Y2Q2YjUwMzAwNDAwZmVkMTFjMCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzIFN0b3AgNTk4MzcgKDMpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzNjYzFiZGE0Y2ZjZjQ4ZWViYzYyNzQyODMzYzVkMTlkLnNldENvbnRlbnQoaHRtbF85MTY5MWUyMTBhNWM0Y2Q2YjUwMzAwNDAwZmVkMTFjMCk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfZjlkZGQwNzM0MTRmNDBlOGIzODE3YjJhNTYzZjhiZTIuYmluZFBvcHVwKHBvcHVwXzNjYzFiZGE0Y2ZjZjQ4ZWViYzYyNzQyODMzYzVkMTlkKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9kNWRmYjQ3MjcwYzI0MjkwYmY1MjQ4MDVlODM1YTUwZiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI0ODczMDYxNDA0NDM2LCAtMTIzLjEwMDc3NjY3MjM2MzI4XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJwdXJwbGUiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAicHVycGxlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8xMjE4OTM0NGYwM2Q0OThmYTRmM2JhYzM3NjhiYTEwZCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfOTc4Yzc0MzE1ZDM4NGM4Y2E4MTUxNmQ4NzIzNjE0NTcgPSAkKGA8ZGl2IGlkPSJodG1sXzk3OGM3NDMxNWQzODRjOGNhODE1MTZkODcyMzYxNDU3IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgU3RvcCA1MTUxOCAoMjUpPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzEyMTg5MzQ0ZjAzZDQ5OGZhNGYzYmFjMzc2OGJhMTBkLnNldENvbnRlbnQoaHRtbF85NzhjNzQzMTVkMzg0YzhjYTgxNTE2ZDg3MjM2MTQ1Nyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfZDVkZmI0NzI3MGMyNDI5MGJmNTI0ODA1ZTgzNWE1MGYuYmluZFBvcHVwKHBvcHVwXzEyMTg5MzQ0ZjAzZDQ5OGZhNGYzYmFjMzc2OGJhMTBkKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8zNDQ2NWQxZTM4NmI0ODljYTM1NzgxNWE0N2E2YjIwMyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI1MDc5NTAwMDAwMDAwNCwgLTEyMy4xMTc0MTU5OTk5OTk5OV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfODA2YWU3MzFiZTAxNGJjOGFmZjZkOGU3NTYzMjY4MzEgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzFlYmM1Y2YwMzQwMDQxNjM4ZGNkMjNlMGY0Y2U1NGVlID0gJChgPGRpdiBpZD0iaHRtbF8xZWJjNWNmMDM0MDA0MTYzOGRjZDIzZTBmNGNlNTRlZSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TWV0cm8gbmV3czwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF84MDZhZTczMWJlMDE0YmM4YWZmNmQ4ZTc1NjMyNjgzMS5zZXRDb250ZW50KGh0bWxfMWViYzVjZjAzNDAwNDE2MzhkY2QyM2UwZjRjZTU0ZWUpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzM0NDY1ZDFlMzg2YjQ4OWNhMzU3ODE1YTQ3YTZiMjAzLmJpbmRQb3B1cChwb3B1cF84MDZhZTczMWJlMDE0YmM4YWZmNmQ4ZTc1NjMyNjgzMSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYTllZTE1YWQ5NjIzNGNlNTk4NTI0MGI3MWQzODQ0MGYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDkxMjA0Mjk0NjAzOCwgLTEyMy4xMTU3MDMwOTg0NTYwNF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfMGY0ZTQ0NmZkZjU2NDhkMGFkNjNmM2UyZjQ1Y2M4ODUgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2Q2NTg4NGIwODYyZDQwYjc4YWYwN2ExNzNlOTk0N2VlID0gJChgPGRpdiBpZD0iaHRtbF9kNjU4ODRiMDg2MmQ0MGI3OGFmMDdhMTczZTk5NDdlZSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+S2luZyBFZHdhcmQgU2t5VHJhaW4gU3RhdGlvbjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8wZjRlNDQ2ZmRmNTY0OGQwYWQ2M2YzZTJmNDVjYzg4NS5zZXRDb250ZW50KGh0bWxfZDY1ODg0YjA4NjJkNDBiNzhhZjA3YTE3M2U5OTQ3ZWUpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2E5ZWUxNWFkOTYyMzRjZTU5ODUyNDBiNzFkMzg0NDBmLmJpbmRQb3B1cChwb3B1cF8wZjRlNDQ2ZmRmNTY0OGQwYWQ2M2YzZTJmNDVjYzg4NSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZDgzYmFiODNiNDk5NDFiODgwMGM5MTlkOTllMWU0MjAgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yMjU4NjU3OTE4MzkyNzYsIC0xMjMuMTE2NDQwNzczMDEwMjRdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInllbGxvdyIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJ5ZWxsb3ciLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzU2MTIxMTNiZGViMTQ3MjZhYWMwMGRiZmYyNWYyZjlkID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9mNmZmYWU1MzY5YTU0OTFhYThmOTFiMWQzZmJkODlkMyA9ICQoYDxkaXYgaWQ9Imh0bWxfZjZmZmFlNTM2OWE1NDkxYWE4ZjkxYjFkM2ZiZDg5ZDMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPk1ldHJvIE5ld3M8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfNTYxMjExM2JkZWIxNDcyNmFhYzAwZGJmZjI1ZjJmOWQuc2V0Q29udGVudChodG1sX2Y2ZmZhZTUzNjlhNTQ5MWFhOGY5MWIxZDNmYmQ4OWQzKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9kODNiYWI4M2I0OTk0MWI4ODAwYzkxOWQ5OWUxZTQyMC5iaW5kUG9wdXAocG9wdXBfNTYxMjExM2JkZWIxNDcyNmFhYzAwZGJmZjI1ZjJmOWQpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzhhZWJiYjljZTg5MTQ4NDU5NDcyMDk3M2RiM2I0NDhiID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjU5MTM1LCAtMTIzLjEyNzE3OF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfODdiMGYxNmIwYTJlNGQ4MTkyMzkyYjEyNzU3ZjEzZDkgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2U2MjEzZDI5YmM0YTQ3Yzc5MDgxYzkxZjE5ZTZmNGRkID0gJChgPGRpdiBpZD0iaHRtbF9lNjIxM2QyOWJjNGE0N2M3OTA4MWM5MWYxOWU2ZjRkZCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TWV0cm8gTmV3czwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF84N2IwZjE2YjBhMmU0ZDgxOTIzOTJiMTI3NTdmMTNkOS5zZXRDb250ZW50KGh0bWxfZTYyMTNkMjliYzRhNDdjNzkwODFjOTFmMTllNmY0ZGQpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzhhZWJiYjljZTg5MTQ4NDU5NDcyMDk3M2RiM2I0NDhiLmJpbmRQb3B1cChwb3B1cF84N2IwZjE2YjBhMmU0ZDgxOTIzOTJiMTI3NTdmMTNkOSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNmUzMmY3Njc2NzJlNGY1NWE1OTM0OTQ3NWFkZTNkZTYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNzQ1MzA2MzkxNzU5NSwgLTEyMy4xMjE5OTI2NDQ3MzMwOF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfMzdiNDFjOTkxYmVkNDc0Nzg3NTUwNmI2N2M3ODFlNWQgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzQwODNlOTdjMjU0MTRmYTlhMjFkN2ZkOGMyOTY3ZjM5ID0gJChgPGRpdiBpZD0iaHRtbF80MDgzZTk3YzI1NDE0ZmE5YTIxZDdmZDhjMjk2N2YzOSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+WWFsZXRvd24gLSBSb3VuZGhvdXNlIFNreVRyYWluIFN0YXRpb248L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfMzdiNDFjOTkxYmVkNDc0Nzg3NTUwNmI2N2M3ODFlNWQuc2V0Q29udGVudChodG1sXzQwODNlOTdjMjU0MTRmYTlhMjFkN2ZkOGMyOTY3ZjM5KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl82ZTMyZjc2NzY3MmU0ZjU1YTU5MzQ5NDc1YWRlM2RlNi5iaW5kUG9wdXAocG9wdXBfMzdiNDFjOTkxYmVkNDc0Nzg3NTUwNmI2N2M3ODFlNWQpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzFjOGYzZTEyYTY1ZjRiNWY4MWY4MDdjMjY3NGM5ZWM1ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjYzNTgyODcxNzUzNzYsIC0xMjMuMTMyNjg5NTk1MjIyNDZdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInllbGxvdyIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJ5ZWxsb3ciLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2Q0NDc0ZDg0ZjZkMTRlYTdiMTI0NmQzYzk1ODQwZTM4ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF84NDJmZDIxYzdjNTc0ZGEzOTBhNmY5YTlhMjg2ZGMzNyA9ICQoYDxkaXYgaWQ9Imh0bWxfODQyZmQyMWM3YzU3NGRhMzkwYTZmOWE5YTI4NmRjMzciIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPk1ldHJvIFZhbiBNb3J0Z2FnZXMgfCBNaWNhaCBWZXJjZWxlcyB8IFZhbmNvdXZlciBNb3J0Z2FnZSBCcm9rZXIgJiBDb25zdWx0YW50PC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2Q0NDc0ZDg0ZjZkMTRlYTdiMTI0NmQzYzk1ODQwZTM4LnNldENvbnRlbnQoaHRtbF84NDJmZDIxYzdjNTc0ZGEzOTBhNmY5YTlhMjg2ZGMzNyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfMWM4ZjNlMTJhNjVmNGI1ZjgxZjgwN2MyNjc0YzllYzUuYmluZFBvcHVwKHBvcHVwX2Q0NDc0ZDg0ZjZkMTRlYTdiMTI0NmQzYzk1ODQwZTM4KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9hZDkwOTlmYzdmMmE0MTAwYWE1NjI1NGVkOTA2NWRmYSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4NzkwMjI3NTA5MzUzNiwgLTEyMy4xMjAxNzk2OTQ5Njk2NF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfZDcxNjU0NTFlYWE3NDJiZGEzZDM2NTZjMWUxMGI2NDcgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzcwNjMzMDNiNDRiMDRkOWU5MTBlMTMwYTNlOTc5OTlkID0gJChgPGRpdiBpZD0iaHRtbF83MDYzMzAzYjQ0YjA0ZDllOTEwZTEzMGEzZTk3OTk5ZCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TWV0cm8gUGFya2luZyBIZWFkIE9mZmljZTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9kNzE2NTQ1MWVhYTc0MmJkYTNkMzY1NmMxZTEwYjY0Ny5zZXRDb250ZW50KGh0bWxfNzA2MzMwM2I0NGIwNGQ5ZTkxMGUxMzBhM2U5Nzk5OWQpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2FkOTA5OWZjN2YyYTQxMDBhYTU2MjU0ZWQ5MDY1ZGZhLmJpbmRQb3B1cChwb3B1cF9kNzE2NTQ1MWVhYTc0MmJkYTNkMzY1NmMxZTEwYjY0NykKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZTA3ZGM2ZjQ5N2QyNDUzZGIxZjc4MjBkNjdhNTJhMDUgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNjM1NDksIC0xMjMuMDk5NjMyXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8zZDNlY2RhMTAzMDA0MjIxYWU5ZjU3ZDFlYTdiZTJmZiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfMzlmODg5ZTI1MzJlNDk5NWE0NDJiY2JhOWEwM2MyN2IgPSAkKGA8ZGl2IGlkPSJodG1sXzM5Zjg4OWUyNTMyZTQ5OTVhNDQyYmNiYTlhMDNjMjdiIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5NZXRybyBWaXN0YTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8zZDNlY2RhMTAzMDA0MjIxYWU5ZjU3ZDFlYTdiZTJmZi5zZXRDb250ZW50KGh0bWxfMzlmODg5ZTI1MzJlNDk5NWE0NDJiY2JhOWEwM2MyN2IpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2UwN2RjNmY0OTdkMjQ1M2RiMWY3ODIwZDY3YTUyYTA1LmJpbmRQb3B1cChwb3B1cF8zZDNlY2RhMTAzMDA0MjIxYWU5ZjU3ZDFlYTdiZTJmZikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfODViM2RhZWRkZTcwNDhjMjkxMGZlOTc1ZjMwMmRlODYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNjI5MDkyODI0NzA4NjUsIC0xMjMuMTE0NTk4NzExMjIwMjFdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInllbGxvdyIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJ5ZWxsb3ciLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2VhZGQ2YTcxYTIzMzQ3NmU5ZWVjNjJlYzViYTU0OWMwID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF82YzBjMTE5OGNlOGE0YmJjOTRkNzRhNTZhMDM5ZTU5YiA9ICQoYDxkaXYgaWQ9Imh0bWxfNmMwYzExOThjZThhNGJiYzk0ZDc0YTU2YTAzOWU1OWIiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJyb2Fkd2F5IC0gQ2l0eSBIYWxsIFNreVRyYWluIFN0YXRpb248L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfZWFkZDZhNzFhMjMzNDc2ZTllZWM2MmVjNWJhNTQ5YzAuc2V0Q29udGVudChodG1sXzZjMGMxMTk4Y2U4YTRiYmM5NGQ3NGE1NmEwMzllNTliKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl84NWIzZGFlZGRlNzA0OGMyOTEwZmU5NzVmMzAyZGU4Ni5iaW5kUG9wdXAocG9wdXBfZWFkZDZhNzFhMjMzNDc2ZTllZWM2MmVjNWJhNTQ5YzApCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzQ5NTlmNmRjMTBkOTRmMzliOTJjMmYyZmQxNDQ2ZTk2ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjg1NTcxNjQ1MzIwMDA1LCAtMTIzLjExMjExNDAyMTY5MDkzXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF83NzAzNTllMDljZjI0ZmJjYjE1Yjg4MTdjYjQ4ZjBhNiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNjM4OTk1NGI5NGIyNDkyMTk4Mjc0ZGRmMWQzN2M5ZWUgPSAkKGA8ZGl2IGlkPSJodG1sXzYzODk5NTRiOTRiMjQ5MjE5ODI3NGRkZjFkMzdjOWVlIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5XYXRlcmZyb250IFN0YXRpb248L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfNzcwMzU5ZTA5Y2YyNGZiY2IxNWI4ODE3Y2I0OGYwYTYuc2V0Q29udGVudChodG1sXzYzODk5NTRiOTRiMjQ5MjE5ODI3NGRkZjFkMzdjOWVlKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl80OTU5ZjZkYzEwZDk0ZjM5YjkyYzJmMmZkMTQ0NmU5Ni5iaW5kUG9wdXAocG9wdXBfNzcwMzU5ZTA5Y2YyNGZiY2IxNWI4ODE3Y2I0OGYwYTYpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2JlMzFkZjQxODIxZjQ5MTdiYTgwYTA4MmQ1MWYxOTEwID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjQ2Nzc1NjE0MTEzNDI1LCAtMTIzLjA5MDA1MDYxMTg3NjZdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInllbGxvdyIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJ5ZWxsb3ciLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2VjOWZlZDAyYzJiNjQ5Nzc5MTA3ZGNiYjk2NWRjZmQ2ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF8zMGIyMTcwNDQ3OTE0MmQ0YmU2ZmM1ZDZmZWM0NjA1YiA9ICQoYDxkaXYgaWQ9Imh0bWxfMzBiMjE3MDQ0NzkxNDJkNGJlNmZjNWQ2ZmVjNDYwNWIiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPk1ldHJvIFJlbWl0dGFuY2UgQ2VudGVyLCBJbmMuPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2VjOWZlZDAyYzJiNjQ5Nzc5MTA3ZGNiYjk2NWRjZmQ2LnNldENvbnRlbnQoaHRtbF8zMGIyMTcwNDQ3OTE0MmQ0YmU2ZmM1ZDZmZWM0NjA1Yik7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYmUzMWRmNDE4MjFmNDkxN2JhODBhMDgyZDUxZjE5MTAuYmluZFBvcHVwKHBvcHVwX2VjOWZlZDAyYzJiNjQ5Nzc5MTA3ZGNiYjk2NWRjZmQ2KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl81NDlkOWQ0MzRkZjU0MTFlYmZlMTkxMTQzZDI3YzQ4OSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjIzMzIyMjM1MjMwODUsIC0xMjMuMTE2NjcwMzMzNDQwOTVdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInllbGxvdyIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJ5ZWxsb3ciLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2EzOGNiNzRkZGMzMTQ3ZTFiNDk1OTUyOTA1M2ZiMDc2ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF84YWUwYTNkNmJhYmY0YzU2YjkwNWJmNTMwNjA0OWYxMyA9ICQoYDxkaXYgaWQ9Imh0bWxfOGFlMGEzZDZiYWJmNGM1NmI5MDViZjUzMDYwNDlmMTMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPk9ha3JpZGdlIC0gNDFzdCBBdmVudWUgU2t5VHJhaW4gU3RhdGlvbjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9hMzhjYjc0ZGRjMzE0N2UxYjQ5NTk1MjkwNTNmYjA3Ni5zZXRDb250ZW50KGh0bWxfOGFlMGEzZDZiYWJmNGM1NmI5MDViZjUzMDYwNDlmMTMpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzU0OWQ5ZDQzNGRmNTQxMWViZmUxOTExNDNkMjdjNDg5LmJpbmRQb3B1cChwb3B1cF9hMzhjYjc0ZGRjMzE0N2UxYjQ5NTk1MjkwNTNmYjA3NikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYjFhNzYzNjYzOGFhNDgwZDgyMDdjMzkyNDYyNWYxOGIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNzMwNzg3Mjg2MzY4MSwgLTEyMy4xMDAzNjAwNzg3NDc1NF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfYTY0NDExNTViNTY5NDhjY2FkZmM4MTc3ZjQ3MGIzZGYgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzdkYmFmY2E0OTNjMzQ5MDU5YTNlZjJhMjk3MmRjMWYwID0gJChgPGRpdiBpZD0iaHRtbF83ZGJhZmNhNDkzYzM0OTA1OWEzZWYyYTI5NzJkYzFmMCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TWFpbiBTdHJlZXQg4oCTIFNjaWVuY2UgV29ybGQgU2t5VHJhaW4gU3RhdGlvbjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9hNjQ0MTE1NWI1Njk0OGNjYWRmYzgxNzdmNDcwYjNkZi5zZXRDb250ZW50KGh0bWxfN2RiYWZjYTQ5M2MzNDkwNTlhM2VmMmEyOTcyZGMxZjApOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2IxYTc2MzY2MzhhYTQ4MGQ4MjA3YzM5MjQ2MjVmMThiLmJpbmRQb3B1cChwb3B1cF9hNjQ0MTE1NWI1Njk0OGNjYWRmYzgxNzdmNDcwYjNkZikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfOGVhNWZhODAyOGU2NGUxMDlhOTllODhhODA2MmY4YmIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNjIzNDU3MzM5NjgyNzQsIC0xMjMuMDY5MjE5MzQ1MDk5NzRdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInllbGxvdyIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJ5ZWxsb3ciLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2FjYTY1M2E0ZTViYjQzYTBiNjZmMzVjZjc5MmQ3MWIxID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9jOTAxMTczMzA4Mjc0MDg4ODM0OTBmZDAwYTAxYTVmYSA9ICQoYDxkaXYgaWQ9Imh0bWxfYzkwMTE3MzMwODI3NDA4ODgzNDkwZmQwMGEwMWE1ZmEiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkNvbW1lcmNpYWwgLSBCcm9hZHdheSBTa3lUcmFpbiBTdGF0aW9uPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2FjYTY1M2E0ZTViYjQzYTBiNjZmMzVjZjc5MmQ3MWIxLnNldENvbnRlbnQoaHRtbF9jOTAxMTczMzA4Mjc0MDg4ODM0OTBmZDAwYTAxYTVmYSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfOGVhNWZhODAyOGU2NGUxMDlhOTllODhhODA2MmY4YmIuYmluZFBvcHVwKHBvcHVwX2FjYTY1M2E0ZTViYjQzYTBiNjZmMzVjZjc5MmQ3MWIxKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9jNTNhNGQ1MWM5ZDA0NWQzOWI0NTlhMzcxYTZkNmI0OCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjIyNzM2NDY4NDg4Mjk3LCAtMTIyLjk5OTk2NTM5OTQ5MDA3XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF81NGQxMDg0MjNiNWE0OGFkOGE3NGY3MzMyMzM1MzYyYyA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfYjE2MmI3NjcwZjg3NDRhYWJmYzAxMWNlNmUwMzcxODkgPSAkKGA8ZGl2IGlkPSJodG1sX2IxNjJiNzY3MGY4NzQ0YWFiZmMwMTFjZTZlMDM3MTg5IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5NZXRyb3BvbGlzIGF0IE1ldHJvdG93bjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF81NGQxMDg0MjNiNWE0OGFkOGE3NGY3MzMyMzM1MzYyYy5zZXRDb250ZW50KGh0bWxfYjE2MmI3NjcwZjg3NDRhYWJmYzAxMWNlNmUwMzcxODkpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2M1M2E0ZDUxYzlkMDQ1ZDM5YjQ1OWEzNzFhNmQ2YjQ4LmJpbmRQb3B1cChwb3B1cF81NGQxMDg0MjNiNWE0OGFkOGE3NGY3MzMyMzM1MzYyYykKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYzE1ZTZlNzJjOGM1NDUzMDkxNDc0OGQzZDAzMjU2MmEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yMjYzMTI1NDgxNzcxLCAtMTIzLjExNjE0MTI4NDk5NzA4XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9hOThiYmExNDM1NTE0NDU3YWUxODAzNjRmYzc3OGFmYSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfMjU4MWZhZjgzNjc3NDJkODlmNjdjOTg3MWQ4NzU1MTQgPSAkKGA8ZGl2IGlkPSJodG1sXzI1ODFmYWY4MzY3NzQyZDg5ZjY3Yzk4NzFkODc1NTE0IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5MYW5nYXJhIC0gNDl0aCBBdmVudWUgU2t5VHJhaW4gU3RhdGlvbjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9hOThiYmExNDM1NTE0NDU3YWUxODAzNjRmYzc3OGFmYS5zZXRDb250ZW50KGh0bWxfMjU4MWZhZjgzNjc3NDJkODlmNjdjOTg3MWQ4NzU1MTQpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2MxNWU2ZTcyYzhjNTQ1MzA5MTQ3NDhkM2QwMzI1NjJhLmJpbmRQb3B1cChwb3B1cF9hOThiYmExNDM1NTE0NDU3YWUxODAzNjRmYzc3OGFmYSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZDM0NWI2NWQyM2JmNDljNjg0ZjI1MGU3ZWExNTlhNDMgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNjY1NDYyODkxOTY1MSwgLTEyMy4xMTU1NTQ2OTQ0ODQzN10sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfMWEyZDI4NmFkOGI4NGRlMTg1MjgzOThlY2M1ODg5NWUgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzRlOGQxZTE2ODBhOTRmYWFhMDVjMGI1NzkxMGQ5NDdjID0gJChgPGRpdiBpZD0iaHRtbF80ZThkMWUxNjgwYTk0ZmFhYTA1YzBiNTc5MTBkOTQ3YyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+T2x5bXBpYyBWaWxsYWdlIFNreVRyYWluIFN0YXRpb248L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfMWEyZDI4NmFkOGI4NGRlMTg1MjgzOThlY2M1ODg5NWUuc2V0Q29udGVudChodG1sXzRlOGQxZTE2ODBhOTRmYWFhMDVjMGI1NzkxMGQ5NDdjKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9kMzQ1YjY1ZDIzYmY0OWM2ODRmMjUwZTdlYTE1OWE0My5iaW5kUG9wdXAocG9wdXBfMWEyZDI4NmFkOGI4NGRlMTg1MjgzOThlY2M1ODg5NWUpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2I4NGM1NWEzMzU4YzRhNzc4N2JmOGU0NGNlMTliNTg0ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjc5MjY3MjA3NDc5OTYsIC0xMjMuMTA5NDQ3MjA2NzM3NzNdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInllbGxvdyIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJ5ZWxsb3ciLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2E0MGE4ZGVjYTI3YTQ4NjQ4Y2MyZjliNzQ0Y2UxZWNhID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF80MDJjNWY5MmRjNTA0NWQ0ODY2NGY5ZTc0YmI4Y2NlZiA9ICQoYDxkaXYgaWQ9Imh0bWxfNDAyYzVmOTJkYzUwNDVkNDg2NjRmOWU3NGJiOGNjZWYiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlN0YWRpdW0gLSBDaGluYXRvd24gU2t5VHJhaW4gU3RhdGlvbjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9hNDBhOGRlY2EyN2E0ODY0OGNjMmY5Yjc0NGNlMWVjYS5zZXRDb250ZW50KGh0bWxfNDAyYzVmOTJkYzUwNDVkNDg2NjRmOWU3NGJiOGNjZWYpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2I4NGM1NWEzMzU4YzRhNzc4N2JmOGU0NGNlMTliNTg0LmJpbmRQb3B1cChwb3B1cF9hNDBhOGRlY2EyN2E0ODY0OGNjMmY5Yjc0NGNlMWVjYSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYWIzMGE0Y2UyZmJkNDdjM2I0ZWJjMzliNWQ2ZmFiZDIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yMjU3MjY4NDgzNzg3MSwgLTEyMy4wMDMyNjQ0ODQyNzU1OF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfOGY2MmIzMmM0YWY0NDY4NTkyMDhhMWM2NTJiNjIzNmEgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzRlMGJiNWFhY2MyNzQ2YzZiZmJkZmJjYjFkZTA3Y2U4ID0gJChgPGRpdiBpZD0iaHRtbF80ZTBiYjVhYWNjMjc0NmM2YmZiZGZiY2IxZGUwN2NlOCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TWV0cm90b3duIFNreVRyYWluIFN0YXRpb248L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfOGY2MmIzMmM0YWY0NDY4NTkyMDhhMWM2NTJiNjIzNmEuc2V0Q29udGVudChodG1sXzRlMGJiNWFhY2MyNzQ2YzZiZmJkZmJjYjFkZTA3Y2U4KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9hYjMwYTRjZTJmYmQ0N2MzYjRlYmMzOWI1ZDZmYWJkMi5iaW5kUG9wdXAocG9wdXBfOGY2MmIzMmM0YWY0NDY4NTkyMDhhMWM2NTJiNjIzNmEpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2I3N2UxNmNkMDQ0ZTRjNTg4OWEyMmQ0MGJkYTYyMDRhID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjY4NjQ3NjQzMTkyMzQ1LCAtMTIzLjA4NTg0ODc4Mzg4Njk1XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF81MGEwZTgwNTJhNWQ0NDIwYjdlYzVmMjZkMGY1OTc2YyA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNjNhMDU5MWZhMTNmNGM3ZTlkZjBiNDcxODQ3ZWI1YzkgPSAkKGA8ZGl2IGlkPSJodG1sXzYzYTA1OTFmYTEzZjRjN2U5ZGYwYjQ3MTg0N2ViNWM5IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Sb2NreSBNb3VudGFpbmVlciBWYW5jb3V2ZXIgU3RhdGlvbjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF81MGEwZTgwNTJhNWQ0NDIwYjdlYzVmMjZkMGY1OTc2Yy5zZXRDb250ZW50KGh0bWxfNjNhMDU5MWZhMTNmNGM3ZTlkZjBiNDcxODQ3ZWI1YzkpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2I3N2UxNmNkMDQ0ZTRjNTg4OWEyMmQ0MGJkYTYyMDRhLmJpbmRQb3B1cChwb3B1cF81MGEwZTgwNTJhNWQ0NDIwYjdlYzVmMjZkMGY1OTc2YykKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMTY0N2I4MTNlNTQxNDgwYzk2MDM3MzUzODYzZTUyNTUgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yODU2MzkwMDgxODM2NywgLTEyMy4xMjAwNDI1ODEwODI0Ml0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfODY5NDEyYzhkZGI3NDFjYjlkMDU2MzBmZmQ3ODAwODEgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2U5N2UwY2U0Y2EyZDQ2MmFiMzkxM2Q1MjkwMWFmMzBjID0gJChgPGRpdiBpZD0iaHRtbF9lOTdlMGNlNGNhMmQ0NjJhYjM5MTNkNTI5MDFhZjMwYyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVycmFyZCBTa3lUcmFpbiBTdGF0aW9uPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzg2OTQxMmM4ZGRiNzQxY2I5ZDA1NjMwZmZkNzgwMDgxLnNldENvbnRlbnQoaHRtbF9lOTdlMGNlNGNhMmQ0NjJhYjM5MTNkNTI5MDFhZjMwYyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfMTY0N2I4MTNlNTQxNDgwYzk2MDM3MzUzODYzZTUyNTUuYmluZFBvcHVwKHBvcHVwXzg2OTQxMmM4ZGRiNzQxY2I5ZDA1NjMwZmZkNzgwMDgxKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl81MzI3Y2JjNGM2Mzk0NjEzYWRkMjlkZjY4YTZjZTI4OCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjIzODU2MTkyNjY0MzExNSwgLTEyMy4wMzE5MTM0Njk0MjAyN10sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfZGFmZDAxZDY0YWFjNDI4MzlkOWNkZjZlNmVmODVjMTEgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2Q3OWU1ODM5ZWYxZjRhNTI4NjIxNGVlNGY1MGNlOWViID0gJChgPGRpdiBpZD0iaHRtbF9kNzllNTgzOWVmMWY0YTUyODYyMTRlZTRmNTBjZTllYiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Sm95Y2UgLSBDb2xsaW5nd29vZCBTa3lUcmFpbiBTdGF0aW9uPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2RhZmQwMWQ2NGFhYzQyODM5ZDljZGY2ZTZlZjg1YzExLnNldENvbnRlbnQoaHRtbF9kNzllNTgzOWVmMWY0YTUyODYyMTRlZTRmNTBjZTllYik7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfNTMyN2NiYzRjNjM5NDYxM2FkZDI5ZGY2OGE2Y2UyODguYmluZFBvcHVwKHBvcHVwX2RhZmQwMWQ2NGFhYzQyODM5ZDljZGY2ZTZlZjg1YzExKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl83Yjk5NjBiNjczNjM0NzBjYjk3N2ZmNWNmYmJmNDU2YyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4MzQzMTk4OTA4ODY5LCAtMTIzLjExNjQ3MTk3OTM4MDQ1XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8xZDJmMmQwYTM4ODU0N2U3OWU4NTU3ZjJiMzc0ZmI1ZSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfZWQyZDg5ZTBkZWExNGVlZTk4ZGU5NWViMDNiN2U3NTAgPSAkKGA8ZGl2IGlkPSJodG1sX2VkMmQ4OWUwZGVhMTRlZWU5OGRlOTVlYjAzYjdlNzUwIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5HcmFudmlsbGUgU2t5VHJhaW4gU3RhdGlvbjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8xZDJmMmQwYTM4ODU0N2U3OWU4NTU3ZjJiMzc0ZmI1ZS5zZXRDb250ZW50KGh0bWxfZWQyZDg5ZTBkZWExNGVlZTk4ZGU5NWViMDNiN2U3NTApOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzdiOTk2MGI2NzM2MzQ3MGNiOTc3ZmY1Y2ZiYmY0NTZjLmJpbmRQb3B1cChwb3B1cF8xZDJmMmQwYTM4ODU0N2U3OWU4NTU3ZjJiMzc0ZmI1ZSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNTk2ZmE1NTVkMjUwNDhkY2E0YzE5OTUzMzc1Y2RiNzIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4zMjAxNDA2NjE4NDk2OSwgLTEyMy4wNzIzNTIxMTE3NzMyXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8yZWQ3OTYwMDgzZDk0NDcyODE4YWZlY2I3NmNhMTA3MyA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfOWIzYWMxYjUwODhlNDQzY2I2NWNjNzc1ZTg1MTExYzggPSAkKGA8ZGl2IGlkPSJodG1sXzliM2FjMWI1MDg4ZTQ0M2NiNjVjYzc3NWU4NTExMWM4IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5NZXRybyBOZXdzIFBpY2t1cDwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8yZWQ3OTYwMDgzZDk0NDcyODE4YWZlY2I3NmNhMTA3My5zZXRDb250ZW50KGh0bWxfOWIzYWMxYjUwODhlNDQzY2I2NWNjNzc1ZTg1MTExYzgpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzU5NmZhNTU1ZDI1MDQ4ZGNhNGMxOTk1MzM3NWNkYjcyLmJpbmRQb3B1cChwb3B1cF8yZWQ3OTYwMDgzZDk0NDcyODE4YWZlY2I3NmNhMTA3MykKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYzMyOWVlZTgwNTkwNDNiOWIzMTYxNTU0NTkzNjA0ZjEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDgzMzAxNjU3MDQyOSwgLTEyMy4wNTU5NjgzNDM5ODM3Ml0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfZGM5NjFmYjczMjU3NDY0MmFhMjkyM2FlYmQ5YmEzZjQgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzE4MDdjNGQ3M2Q4YTRkMjhiOTcwYTI4N2JkZDM2OTI1ID0gJChgPGRpdiBpZD0iaHRtbF8xODA3YzRkNzNkOGE0ZDI4Yjk3MGEyODdiZGQzNjkyNSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TmFuYWltbyBTa3lUcmFpbiBTdGF0aW9uPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2RjOTYxZmI3MzI1NzQ2NDJhYTI5MjNhZWJkOWJhM2Y0LnNldENvbnRlbnQoaHRtbF8xODA3YzRkNzNkOGE0ZDI4Yjk3MGEyODdiZGQzNjkyNSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYzMyOWVlZTgwNTkwNDNiOWIzMTYxNTU0NTkzNjA0ZjEuYmluZFBvcHVwKHBvcHVwX2RjOTYxZmI3MzI1NzQ2NDJhYTI5MjNhZWJkOWJhM2Y0KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9lMDcyNTdmMmNhMjM0N2ZlOTYwYzljZTAxYmYxMDY1MSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjIzMjc4ODAwMDk0MjIzLCAtMTIzLjA4OTk2MjAwNTYxNTIzXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8zOWJiNWI2NjUxNDc0ODFlOTAxMzEzZDQ1OGY2ODVkZiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfYTdjYjhkZGY4NDBlNDBkNWE1MGE2ZDYxNDhiMzVlN2UgPSAkKGA8ZGl2IGlkPSJodG1sX2E3Y2I4ZGRmODQwZTQwZDVhNTBhNmQ2MTQ4YjM1ZTdlIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgNDEgVUJDL0pveWNlIFN0YXRpb248L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfMzliYjViNjY1MTQ3NDgxZTkwMTMxM2Q0NThmNjg1ZGYuc2V0Q29udGVudChodG1sX2E3Y2I4ZGRmODQwZTQwZDVhNTBhNmQ2MTQ4YjM1ZTdlKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9lMDcyNTdmMmNhMjM0N2ZlOTYwYzljZTAxYmYxMDY1MS5iaW5kUG9wdXAocG9wdXBfMzliYjViNjY1MTQ3NDgxZTkwMTMxM2Q0NThmNjg1ZGYpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2I5MmY3MjgyZWM5OTRlMmU5N2IxMDVkYjIzODIwODgzID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjQ0MTgyOTk2MzUxNjgsIC0xMjMuMDQ1MjA2MDA3OTU1MzZdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInllbGxvdyIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJ5ZWxsb3ciLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2ZiNmZhMTM0NTlmZDRiZGI4ZGE2N2QzZGRlMGEzNWY0ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF81Zjc2NDE3YTY0NTg0OTA5OGZiNmUxODEzZDA2NTc2NCA9ICQoYDxkaXYgaWQ9Imh0bWxfNWY3NjQxN2E2NDU4NDkwOThmYjZlMTgxM2QwNjU3NjQiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPjI5dGggQXZlbnVlIFNreVRyYWluIFN0YXRpb248L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfZmI2ZmExMzQ1OWZkNGJkYjhkYTY3ZDNkZGUwYTM1ZjQuc2V0Q29udGVudChodG1sXzVmNzY0MTdhNjQ1ODQ5MDk4ZmI2ZTE4MTNkMDY1NzY0KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9iOTJmNzI4MmVjOTk0ZTJlOTdiMTA1ZGIyMzgyMDg4My5iaW5kUG9wdXAocG9wdXBfZmI2ZmExMzQ1OWZkNGJkYjhkYTY3ZDNkZGUwYTM1ZjQpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzZjZTVjNzk2ZTdjNTRiOWViMzRhZmNhYTQxMGEwYTc2ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjc0MzAyMjk5OTk5OTk1LCAtMTIzLjEwMDQxMjVdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInllbGxvdyIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJ5ZWxsb3ciLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzYzZmU4MTdkYmJiYjQ5YjI5NTFiODNlNGIxZDQ0NzYyID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF81M2IxNWU3NzQ5OTU0MmNmYjRhODFlMjBlZTlhZWVlZCA9ICQoYDxkaXYgaWQ9Imh0bWxfNTNiMTVlNzc0OTk1NDJjZmI0YTgxZTIwZWU5YWVlZWQiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkkuRC5BLiAtIE1haW4gU3RhdGlvbiBQaGFybWFjeTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF82M2ZlODE3ZGJiYmI0OWIyOTUxYjgzZTRiMWQ0NDc2Mi5zZXRDb250ZW50KGh0bWxfNTNiMTVlNzc0OTk1NDJjZmI0YTgxZTIwZWU5YWVlZWQpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzZjZTVjNzk2ZTdjNTRiOWViMzRhZmNhYTQxMGEwYTc2LmJpbmRQb3B1cChwb3B1cF82M2ZlODE3ZGJiYmI0OWIyOTUxYjgzZTRiMWQ0NDc2MikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZWFkNzJmY2Q1NjU5NGQ2MWEwY2IyYzA3N2M1M2ZmNmMgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yMjY0NjgyMDAwMDAwMSwgLTEyMi45OTM0MjQ5MDAwMDAwMV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfMWExZjc3ZTQ0YjAzNGQ1MDkzMjZhYzhjOTMwYjM1NmYgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzEyZTdlMjM0Yzc0MjQwNjE4Nzg4MDVjZGUwNjk1Yjc4ID0gJChgPGRpdiBpZD0iaHRtbF8xMmU3ZTIzNGM3NDI0MDYxODc4ODA1Y2RlMDY5NWI3OCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TWV0cm8gUGF3biBCcm9rZXJzPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzFhMWY3N2U0NGIwMzRkNTA5MzI2YWM4YzkzMGIzNTZmLnNldENvbnRlbnQoaHRtbF8xMmU3ZTIzNGM3NDI0MDYxODc4ODA1Y2RlMDY5NWI3OCk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfZWFkNzJmY2Q1NjU5NGQ2MWEwY2IyYzA3N2M1M2ZmNmMuYmluZFBvcHVwKHBvcHVwXzFhMWY3N2U0NGIwMzRkNTA5MzI2YWM4YzkzMGIzNTZmKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8yMDAyMzBlODNmMmE0NTAxYjVhZDdlZjRlMzYyNDg1NCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjIwOTQyMjMwNzExMDc1NiwgLTEyMy4xMTcwMzM1MjE4NjE0NF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfOTdiODkyYTQ3MTdjNGFiOTg0MjFkMDk2NzMwNWUxNDEgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2QxMGFkNGQ5NGRkMjQ5Nzc4OGYxN2I2ODMyNzk1YWIzID0gJChgPGRpdiBpZD0iaHRtbF9kMTBhZDRkOTRkZDI0OTc3ODhmMTdiNjgzMjc5NWFiMyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TWFyaW5lIERyaXZlIFNreVRyYWluIFN0YXRpb248L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfOTdiODkyYTQ3MTdjNGFiOTg0MjFkMDk2NzMwNWUxNDEuc2V0Q29udGVudChodG1sX2QxMGFkNGQ5NGRkMjQ5Nzc4OGYxN2I2ODMyNzk1YWIzKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl8yMDAyMzBlODNmMmE0NTAxYjVhZDdlZjRlMzYyNDg1NC5iaW5kUG9wdXAocG9wdXBfOTdiODkyYTQ3MTdjNGFiOTg0MjFkMDk2NzMwNWUxNDEpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2IxMDc4YzU2OGQ3NjRkYWNhOWQxNWM4ZTAzMDE5M2JjID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjA3NTE4LCAtMTIzLjEwNjIzOTk5OTk5OTk5XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF84MjJkYTkzNWMzODE0ZDJlOWE2YjdlMzQ0ZjU5ZjIxYSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNzMwMGNkMWE0OWEwNGY3Mzk4MTkzZjA5OWE3MTg1ZmEgPSAkKGA8ZGl2IGlkPSJodG1sXzczMDBjZDFhNDlhMDRmNzM5ODE5M2YwOTlhNzE4NWZhIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij4xLTgwMC1HT1QtSlVOSz8gVmFuY291dmVyIE1ldHJvPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzgyMmRhOTM1YzM4MTRkMmU5YTZiN2UzNDRmNTlmMjFhLnNldENvbnRlbnQoaHRtbF83MzAwY2QxYTQ5YTA0ZjczOTgxOTNmMDk5YTcxODVmYSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYjEwNzhjNTY4ZDc2NGRhY2E5ZDE1YzhlMDMwMTkzYmMuYmluZFBvcHVwKHBvcHVwXzgyMmRhOTM1YzM4MTRkMmU5YTZiN2UzNDRmNTlmMjFhKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl82ZmE5NmNmM2YwMWU0MjdkOGQ5MzVkYTZmZjI4NzFmZSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI2NjQxNjUyODM5NjE4LCAtMTIzLjAwMTk0MjA4NDcyOTEyXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9iZThlOTQ5M2Y4ODQ0YTYxOTU4YjM0NDFjYThlZDc2MSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfZDI5YjUxYzdlY2Y4NGY2ODk0NzFmMmY5Zjg5NjA2YmQgPSAkKGA8ZGl2IGlkPSJodG1sX2QyOWI1MWM3ZWNmODRmNjg5NDcxZjJmOWY4OTYwNmJkIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CcmVudHdvb2QgVG93biBDZW50cmUgU2t5VHJhaW4gU3RhdGlvbjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9iZThlOTQ5M2Y4ODQ0YTYxOTU4YjM0NDFjYThlZDc2MS5zZXRDb250ZW50KGh0bWxfZDI5YjUxYzdlY2Y4NGY2ODk0NzFmMmY5Zjg5NjA2YmQpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzZmYTk2Y2YzZjAxZTQyN2Q4ZDkzNWRhNmZmMjg3MWZlLmJpbmRQb3B1cChwb3B1cF9iZThlOTQ5M2Y4ODQ0YTYxOTU4YjM0NDFjYThlZDc2MSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNTgyNTFmYTQ5MjVkNGQwNjkzZDAxNWYzOWJhMmRkNjAgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNzY0Mjg4MTQ4MDg2MywgLTEyMy4xMzk4NzI1NTA5NjQzNl0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfNDc4YjU0YWYyODIzNDY5NTg4NjA1NzRjYmRmMTA5NjggPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzgzNzNmMWU4YTVlODRhOWZhNTY1ZmM1Zjk1OGVhZDU1ID0gJChgPGRpdiBpZD0iaHRtbF84MzczZjFlOGE1ZTg0YTlmYTU2NWZjNWY5NThlYWQ1NSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Q0NHIFN0YXRpb24gS2l0c2lsYW5vPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzQ3OGI1NGFmMjgyMzQ2OTU4ODYwNTc0Y2JkZjEwOTY4LnNldENvbnRlbnQoaHRtbF84MzczZjFlOGE1ZTg0YTlmYTU2NWZjNWY5NThlYWQ1NSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfNTgyNTFmYTQ5MjVkNGQwNjkzZDAxNWYzOWJhMmRkNjAuYmluZFBvcHVwKHBvcHVwXzQ3OGI1NGFmMjgyMzQ2OTU4ODYwNTc0Y2JkZjEwOTY4KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8xMzFkYzY1ZGRhMjk0ZWI5OGIxNzc0NGE3YTk2ODhhOSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4MjQyMDg3NTY4NDMxNiwgLTEyMy4xMTg0Mzg0ODMxNDc5NF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfYWRjZDk1NTBhZjQwNDVjMmI2MDI3M2FkN2YwMTIzMjQgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2FiMWFlMmU1OWYzZjRjNDNiZWJhY2I0MGQwYzY4OTk3ID0gJChgPGRpdiBpZD0iaHRtbF9hYjFhZTJlNTlmM2Y0YzQzYmViYWNiNDBkMGM2ODk5NyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+VmFuY291dmVyIENpdHkgQ2VudHJlIFNreVRyYWluIFN0YXRpb248L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfYWRjZDk1NTBhZjQwNDVjMmI2MDI3M2FkN2YwMTIzMjQuc2V0Q29udGVudChodG1sX2FiMWFlMmU1OWYzZjRjNDNiZWJhY2I0MGQwYzY4OTk3KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl8xMzFkYzY1ZGRhMjk0ZWI5OGIxNzc0NGE3YTk2ODhhOS5iaW5kUG9wdXAocG9wdXBfYWRjZDk1NTBhZjQwNDVjMmI2MDI3M2FkN2YwMTIzMjQpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzNiMzI3OTk1ODRkOTRmNmU5ZTkwODgwMWU4MDJmMzY5ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjczNTY4MDA3MjY2NTcsIC0xMjMuMDk3OTAxNDg2Mzk5MTFdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInllbGxvdyIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJ5ZWxsb3ciLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzQyN2RjZjc1ZjM1OTRmMjU5NGE0MDZjYjcwZmI2MjM2ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF80NmFkMDRiYWZlY2I0MWMwYTY5NDMxZmZjNjJhYzY1ZSA9ICQoYDxkaXYgaWQ9Imh0bWxfNDZhZDA0YmFmZWNiNDFjMGE2OTQzMWZmYzYyYWM2NWUiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlBhY2lmaWMgQ2VudHJhbCBTdGF0aW9uPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzQyN2RjZjc1ZjM1OTRmMjU5NGE0MDZjYjcwZmI2MjM2LnNldENvbnRlbnQoaHRtbF80NmFkMDRiYWZlY2I0MWMwYTY5NDMxZmZjNjJhYzY1ZSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfM2IzMjc5OTU4NGQ5NGY2ZTllOTA4ODAxZTgwMmYzNjkuYmluZFBvcHVwKHBvcHVwXzQyN2RjZjc1ZjM1OTRmMjU5NGE0MDZjYjcwZmI2MjM2KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8wMWFhZjAwMmE4ZGQ0NThlYjlhMjI1MTY5MGM0NjQ0YyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI2NTY4OTQxMTczNjAwNSwgLTEyMy4wNzg4MzA2NzA3MTUxOV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfYThlMTVjMzVmNDc1NGU5NTk5YjIzYTE4MmUyMTc1NzEgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzczYmIxNGU0ZDY3NzRlYmJhZTE1MzU3YmFiZmM1Zjg1ID0gJChgPGRpdiBpZD0iaHRtbF83M2JiMTRlNGQ2Nzc0ZWJiYWUxNTM1N2JhYmZjNWY4NSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+VkNDIC0gQ2xhcmsgU2t5VHJhaW4gU3RhdGlvbjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9hOGUxNWMzNWY0NzU0ZTk1OTliMjNhMTgyZTIxNzU3MS5zZXRDb250ZW50KGh0bWxfNzNiYjE0ZTRkNjc3NGViYmFlMTUzNTdiYWJmYzVmODUpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzAxYWFmMDAyYThkZDQ1OGViOWEyMjUxNjkwYzQ2NDRjLmJpbmRQb3B1cChwb3B1cF9hOGUxNWMzNWY0NzU0ZTk1OTliMjNhMTgyZTIxNzU3MSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNGU0NzEzNWE0MGRlNGMwNjhjODYwYzJiNmYyYTY4MjQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4xOTY3MDIzNDA4ODU3ODYsIC0xMjMuMTQ2NTcxOTEzMTE3N10sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfYjhhZDZjODNmN2FiNGQ0ZGFiNmJjZTk0ZDkxMTA2ZTIgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2U4ZDc0YmU5MzI0OTRiMzY4NDA0NzhhYmZlODUxY2Q1ID0gJChgPGRpdiBpZD0iaHRtbF9lOGQ3NGJlOTMyNDk0YjM2ODQwNDc4YWJmZTg1MWNkNSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+VGVtcGxldG9uIFNreVRyYWluIFN0YXRpb248L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfYjhhZDZjODNmN2FiNGQ0ZGFiNmJjZTk0ZDkxMTA2ZTIuc2V0Q29udGVudChodG1sX2U4ZDc0YmU5MzI0OTRiMzY4NDA0NzhhYmZlODUxY2Q1KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl80ZTQ3MTM1YTQwZGU0YzA2OGM4NjBjMmI2ZjJhNjgyNC5iaW5kUG9wdXAocG9wdXBfYjhhZDZjODNmN2FiNGQ0ZGFiNmJjZTk0ZDkxMTA2ZTIpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzdmNDNiZTJiMGJkNTRjYWE5Mjc2NGQwMDkzNWJmMjk5ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjg1NjIwNTIxOTc5NDUsIC0xMjMuMTEyMDc0OTM5NjI1NzZdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInllbGxvdyIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJ5ZWxsb3ciLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzlmYzQ4YzUzMGZiOTQ5ZWM4Yjg2YzA0OTllYmRjNGQ1ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9lZGFjZTZlODcyN2U0NGMyODUwZjE4Nzg2MzgzNGQ1MiA9ICQoYDxkaXYgaWQ9Imh0bWxfZWRhY2U2ZTg3MjdlNDRjMjg1MGYxODc4NjM4MzRkNTIiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlN0YXRpb24gTmV3c3RhbmQ8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfOWZjNDhjNTMwZmI5NDllYzhiODZjMDQ5OWViZGM0ZDUuc2V0Q29udGVudChodG1sX2VkYWNlNmU4NzI3ZTQ0YzI4NTBmMTg3ODYzODM0ZDUyKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl83ZjQzYmUyYjBiZDU0Y2FhOTI3NjRkMDA5MzViZjI5OS5iaW5kUG9wdXAocG9wdXBfOWZjNDhjNTMwZmI5NDllYzhiODZjMDQ5OWViZGM0ZDUpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzMyYzJlNzlhYjhhMzRkYmI5NjMwOTQzODBiN2U3MGU5ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjMzODczNjA2MTUyNDUsIC0xMjMuMTUzNjU1NTI5NDc5OV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfOGQwN2QzMGFjMTBjNGZkMmJhMTI4MTA4NmNkYzI5ODEgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzVmOWMwOWE5N2E2MzQ2NDBiODk4YmMxODY2ODJmNTkzID0gJChgPGRpdiBpZD0iaHRtbF81ZjljMDlhOTdhNjM0NjQwYjg5OGJjMTg2NjgyZjU5MyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+S2VycmlzZGFsZSBTdGF0aW9uIE1lZGljYWwgQ2xpbmljPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzhkMDdkMzBhYzEwYzRmZDJiYTEyODEwODZjZGMyOTgxLnNldENvbnRlbnQoaHRtbF81ZjljMDlhOTdhNjM0NjQwYjg5OGJjMTg2NjgyZjU5Myk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfMzJjMmU3OWFiOGEzNGRiYjk2MzA5NDM4MGI3ZTcwZTkuYmluZFBvcHVwKHBvcHVwXzhkMDdkMzBhYzEwYzRmZDJiYTEyODEwODZjZGMyOTgxKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8yYmNjOTU3ZDQ4ZTc0YWY4YWNlNTUwZWRmOTU2MWM1YyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4MTE1MDkyNzYxODY0LCAtMTIzLjA3NDQ1MDk3OTAyMzE1XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8xNTEzNzUwMzAzZWE0MjlkYTJiY2QyMmIyZTExYWE5YyA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfZWQyZjhkZTMyMDJhNGU2MDkwZTk0ZDZjZDhiYTM4ZjcgPSAkKGA8ZGl2IGlkPSJodG1sX2VkMmY4ZGUzMjAyYTRlNjA5MGU5NGQ2Y2Q4YmEzOGY3IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXMgMTYgQXJidXR1cy8yOXRoIEF2ZSBTdGF0aW9uPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzE1MTM3NTAzMDNlYTQyOWRhMmJjZDIyYjJlMTFhYTljLnNldENvbnRlbnQoaHRtbF9lZDJmOGRlMzIwMmE0ZTYwOTBlOTRkNmNkOGJhMzhmNyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfMmJjYzk1N2Q0OGU3NGFmOGFjZTU1MGVkZjk1NjFjNWMuYmluZFBvcHVwKHBvcHVwXzE1MTM3NTAzMDNlYTQyOWRhMmJjZDIyYjJlMTFhYTljKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9lZGU4ZWQ0Y2E0ODY0MzNiODUyZDQyYzQ2YWI3ZTljMCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjE5NDE3MDk5NDM4MDExLCAtMTIzLjE3ODU1MDAwNDk1OTA5XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8xZDEyMDI5OGE3YjI0MDgwYmUwZjRiZDhiMDQ1YzQzMiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfZDY1YTk0ODhkZTczNGNjODg5MDcwMzc5NGI1ZjY0ODAgPSAkKGA8ZGl2IGlkPSJodG1sX2Q2NWE5NDg4ZGU3MzRjYzg4OTA3MDM3OTRiNWY2NDgwIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5ZVlLigJNBaXJwb3J0IFN0YXRpb248L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfMWQxMjAyOThhN2IyNDA4MGJlMGY0YmQ4YjA0NWM0MzIuc2V0Q29udGVudChodG1sX2Q2NWE5NDg4ZGU3MzRjYzg4OTA3MDM3OTRiNWY2NDgwKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9lZGU4ZWQ0Y2E0ODY0MzNiODUyZDQyYzQ2YWI3ZTljMC5iaW5kUG9wdXAocG9wdXBfMWQxMjAyOThhN2IyNDA4MGJlMGY0YmQ4YjA0NWM0MzIpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzUwMzgwMzI3ZTVjZTQzNTNiMjZiZDdjN2YwZWE0MzY0ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMTk1NDg0NDgzMzY5NTMsIC0xMjMuMTI2MTkwODQ5MjE1NjVdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogInllbGxvdyIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJ5ZWxsb3ciLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzVjZDk0ODk0ZTRlYTQ5MWU4OWNiZWQyODVhODAwMjQ2ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF8xODg5NDE1YmQ0ZjE0ZTcwOTE1MGUzODA1YjVlYWFkNiA9ICQoYDxkaXYgaWQ9Imh0bWxfMTg4OTQxNWJkNGYxNGU3MDkxNTBlMzgwNWI1ZWFhZDYiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJyaWRnZXBvcnQgU3RhdGlvbjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF81Y2Q5NDg5NGU0ZWE0OTFlODljYmVkMjg1YTgwMDI0Ni5zZXRDb250ZW50KGh0bWxfMTg4OTQxNWJkNGYxNGU3MDkxNTBlMzgwNWI1ZWFhZDYpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzUwMzgwMzI3ZTVjZTQzNTNiMjZiZDdjN2YwZWE0MzY0LmJpbmRQb3B1cChwb3B1cF81Y2Q5NDg5NGU0ZWE0OTFlODljYmVkMjg1YTgwMDI0NikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYjE3Yjc3MzcyOGVlNDE3YWFjNmM5OTdiODZjOGVjYWIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yODMzODA1MzAwMjk0MywgLTEyMy4xMTY3NTM5NjEzMjQ1Ml0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAieWVsbG93IiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogInllbGxvdyIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfNTZlY2Q5ZTkzMzIxNDI0NWI2NGQ1YTlhZDU1MjVlYzQgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzRlZWMyNjYzNmMwNTQ2ZGRhMDVlZTAzMGFlZDQ4NTEwID0gJChgPGRpdiBpZD0iaHRtbF80ZWVjMjY2MzZjMDU0NmRkYTA1ZWUwMzBhZWQ0ODUxMCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+R3JhbnZpbGxlIFN0YXRpb24gRGVudGFsPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzU2ZWNkOWU5MzMyMTQyNDViNjRkNWE5YWQ1NTI1ZWM0LnNldENvbnRlbnQoaHRtbF80ZWVjMjY2MzZjMDU0NmRkYTA1ZWUwMzBhZWQ0ODUxMCk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYjE3Yjc3MzcyOGVlNDE3YWFjNmM5OTdiODZjOGVjYWIuYmluZFBvcHVwKHBvcHVwXzU2ZWNkOWU5MzMyMTQyNDViNjRkNWE5YWQ1NTI1ZWM0KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9lMGZhZmZkM2JmY2M0NzM1OTIwY2JlNmQ0MDI2YTZlYyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4NjA4NjEzMTIyNTU5NSwgLTEyMy4wNzEzODU5ODk5MjMzXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJ5ZWxsb3ciLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAieWVsbG93IiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8xMDMxZmQ4M2U4YjU0NzdjYTEyYWM5ODBhZjMwOWJiMiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfYzRkZGY2MGJmMDRlNGVkNGEzOWMyZmFmOGFiNzdiNjMgPSAkKGA8ZGl2IGlkPSJodG1sX2M0ZGRmNjBiZjA0ZTRlZDRhMzljMmZhZjhhYjc3YjYzIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Qb3J0IE1ldHJvIFZhbmNvdXZlcjwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8xMDMxZmQ4M2U4YjU0NzdjYTEyYWM5ODBhZjMwOWJiMi5zZXRDb250ZW50KGh0bWxfYzRkZGY2MGJmMDRlNGVkNGEzOWMyZmFmOGFiNzdiNjMpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2UwZmFmZmQzYmZjYzQ3MzU5MjBjYmU2ZDQwMjZhNmVjLmJpbmRQb3B1cChwb3B1cF8xMDMxZmQ4M2U4YjU0NzdjYTEyYWM5ODBhZjMwOWJiMikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYTEyM2EwNjk5ZDA0NGE4Mjg4MGE4OTYzZjVjMGZmYjEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yODMzNjIyODI2Nzg2NSwgLTEyMy4xMTk0NjE4MTI1NTUyMl0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAib3JhbmdlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogIm9yYW5nZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfZWNhMGRjNGZhNjQxNDBlZGJjMjY0NmI0NWRiYTBlMWUgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2RiOTNmZTYyMmRlMDQ5YjFiMTg2NWI4NWVkOWYxMDQzID0gJChgPGRpdiBpZD0iaHRtbF9kYjkzZmU2MjJkZTA0OWIxYjE4NjViODVlZDlmMTA0MyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+SGF3a3N3b3J0aCBSZXN0YXVyYW50PC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2VjYTBkYzRmYTY0MTQwZWRiYzI2NDZiNDVkYmEwZTFlLnNldENvbnRlbnQoaHRtbF9kYjkzZmU2MjJkZTA0OWIxYjE4NjViODVlZDlmMTA0Myk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYTEyM2EwNjk5ZDA0NGE4Mjg4MGE4OTYzZjVjMGZmYjEuYmluZFBvcHVwKHBvcHVwX2VjYTBkYzRmYTY0MTQwZWRiYzI2NDZiNDVkYmEwZTFlKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl85MjZlZmZhOWM0YWU0MjZlYmYwOTEyODY2YWY5NGU0MiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4ODAxOSwgLTEyMy4xNDA0NjY5OTk5OTk5OV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAib3JhbmdlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogIm9yYW5nZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfOWY1ZDEwMDNlNGQzNDE2MzhlOTI1ZTdmYjBhMDNlY2YgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzI1M2NlMDAyYTdiZTQzOWU4MGVmNmJmYTZiNzc5NDM1ID0gJChgPGRpdiBpZD0iaHRtbF8yNTNjZTAwMmE3YmU0MzllODBlZjZiZmE2Yjc3OTQzNSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+RXNwYcOxYSBSZXN0YXVyYW50PC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzlmNWQxMDAzZTRkMzQxNjM4ZTkyNWU3ZmIwYTAzZWNmLnNldENvbnRlbnQoaHRtbF8yNTNjZTAwMmE3YmU0MzllODBlZjZiZmE2Yjc3OTQzNSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfOTI2ZWZmYTljNGFlNDI2ZWJmMDkxMjg2NmFmOTRlNDIuYmluZFBvcHVwKHBvcHVwXzlmNWQxMDAzZTRkMzQxNjM4ZTkyNWU3ZmIwYTAzZWNmKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8yOTc1MjEyMTRjNmQ0NjJiOTc0OWIwMGQ3MzdmMjVlNyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI5MTY1NTAyMjQyMTU3LCAtMTIzLjEyNzY4NTUzMDA3MTE2XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJvcmFuZ2UiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAib3JhbmdlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8xNDE2ZWI5YzNmNWI0MGEzOGU5MGU0N2Y0MjFjNzZjOCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfMmQ3MTVjYWZjNjcxNDk1N2FmMjllY2JjYWRmNGMyZWEgPSAkKGA8ZGl2IGlkPSJodG1sXzJkNzE1Y2FmYzY3MTQ5NTdhZjI5ZWNiY2FkZjRjMmVhIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5DYXJkZXJvJ3MgUmVzdGF1cmFudDwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8xNDE2ZWI5YzNmNWI0MGEzOGU5MGU0N2Y0MjFjNzZjOC5zZXRDb250ZW50KGh0bWxfMmQ3MTVjYWZjNjcxNDk1N2FmMjllY2JjYWRmNGMyZWEpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzI5NzUyMTIxNGM2ZDQ2MmI5NzQ5YjAwZDczN2YyNWU3LmJpbmRQb3B1cChwb3B1cF8xNDE2ZWI5YzNmNWI0MGEzOGU5MGU0N2Y0MjFjNzZjOCkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMGZhNGVkZDc5NWNkNGQyNzgyNTk3YzM0YzY4NGJjNzYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNjY1MDk2ODg4NTAwMTQsIC0xMjMuMTAzNzMwNzE0MTIyNTJdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogIm9yYW5nZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJvcmFuZ2UiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzIyNWQ5MDQ5ZWFlMjRmMjE5MjJlZGQwM2MwY2JkMjJiID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF82MGU0N2M4OGIxYmY0YzFjODQ3ZjA1YTU4N2M5NmE1MyA9ICQoYDxkaXYgaWQ9Imh0bWxfNjBlNDdjODhiMWJmNGMxYzg0N2YwNWE1ODdjOTZhNTMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlBlYWNlZnVsIFJlc3RhdXJhbnQg5ZKM5bmz6aWt5bqXPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzIyNWQ5MDQ5ZWFlMjRmMjE5MjJlZGQwM2MwY2JkMjJiLnNldENvbnRlbnQoaHRtbF82MGU0N2M4OGIxYmY0YzFjODQ3ZjA1YTU4N2M5NmE1Myk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfMGZhNGVkZDc5NWNkNGQyNzgyNTk3YzM0YzY4NGJjNzYuYmluZFBvcHVwKHBvcHVwXzIyNWQ5MDQ5ZWFlMjRmMjE5MjJlZGQwM2MwY2JkMjJiKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9iNmFmZGRhNDRkNTQ0NmFjOTZkYzg2ZjFkZDE0NGEyMSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI3MjE4ODE0MzI5OTI5NiwgLTEyMy4xMzM5MTc3MjQyMzM4OF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAib3JhbmdlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogIm9yYW5nZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfYmQzZTNhNzMzNzgzNGM0ZDkwOWI5YzlmZjQ0NjNiYzUgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzE1NGE1YzkxNWNmZTQ1ZGE4ZWUyOTk2MGUzMzg1YTAxID0gJChgPGRpdiBpZD0iaHRtbF8xNTRhNWM5MTVjZmU0NWRhOGVlMjk5NjBlMzM4NWEwMSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+VGhlIFNhbmRiYXIgU2VhZm9vZCBSZXN0YXVyYW50PC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2JkM2UzYTczMzc4MzRjNGQ5MDliOWM5ZmY0NDYzYmM1LnNldENvbnRlbnQoaHRtbF8xNTRhNWM5MTVjZmU0NWRhOGVlMjk5NjBlMzM4NWEwMSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYjZhZmRkYTQ0ZDU0NDZhYzk2ZGM4NmYxZGQxNDRhMjEuYmluZFBvcHVwKHBvcHVwX2JkM2UzYTczMzc4MzRjNGQ5MDliOWM5ZmY0NDYzYmM1KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9hNmE0ZDgzZWUxOTg0ZTkzYmYzMjQyNjkyODAzNTYyZCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4MDQyMDQ2NzE0ODg5LCAtMTIzLjEwMTIwNDUyMTQyNjE0XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJvcmFuZ2UiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAib3JhbmdlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF82OWNlNzM3Njc5MGM0YTRkOTRiMjZlMjViNjMxYzYzMiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfOGVmZDk1MzJhZDBmNDYyMDgzMWI2NTdiZTNmNTA5MmYgPSAkKGA8ZGl2IGlkPSJodG1sXzhlZmQ5NTMyYWQwZjQ2MjA4MzFiNjU3YmUzZjUwOTJmIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5OZXcgVG93biBCYWtlcnkgJiBSZXN0YXVyYW50PC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzY5Y2U3Mzc2NzkwYzRhNGQ5NGIyNmUyNWI2MzFjNjMyLnNldENvbnRlbnQoaHRtbF84ZWZkOTUzMmFkMGY0NjIwODMxYjY1N2JlM2Y1MDkyZik7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYTZhNGQ4M2VlMTk4NGU5M2JmMzI0MjY5MjgwMzU2MmQuYmluZFBvcHVwKHBvcHVwXzY5Y2U3Mzc2NzkwYzRhNGQ5NGIyNmUyNWI2MzFjNjMyKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8yNTg2MmU2MzA2NjY0OTFiYTEzZmIxNzZmMjExYTE1ZiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjIzMTcyMTQ5ODE4MTE0NSwgLTEyMy4wNjU2MDM3Nzg3NjUzOF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAib3JhbmdlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogIm9yYW5nZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfNGNlZWY1YTIxMDc0NDhlNzhlZTJkN2EwZjVkMjM3MjggPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2VmMWEwZDhmNDA3NDRjOGM5MzAwNDNiMmVkYTBmZWRlID0gJChgPGRpdiBpZD0iaHRtbF9lZjFhMGQ4ZjQwNzQ0YzhjOTMwMDQzYjJlZGEwZmVkZSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TXVpIEdhcmRlbiBSZXN0YXVyYW50PC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzRjZWVmNWEyMTA3NDQ4ZTc4ZWUyZDdhMGY1ZDIzNzI4LnNldENvbnRlbnQoaHRtbF9lZjFhMGQ4ZjQwNzQ0YzhjOTMwMDQzYjJlZGEwZmVkZSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfMjU4NjJlNjMwNjY2NDkxYmExM2ZiMTc2ZjIxMWExNWYuYmluZFBvcHVwKHBvcHVwXzRjZWVmNWEyMTA3NDQ4ZTc4ZWUyZDdhMGY1ZDIzNzI4KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl85Mjg0ZGFkMjQwOGQ0ZjkzOGQ4YmVjNGUwMjI4MmZiNiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI2MzA4NTc2ODA0OTg2LCAtMTIzLjExNTgwNzc3MTY4MjczXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJvcmFuZ2UiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAib3JhbmdlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9kNDI5ZWJjNTUyY2U0MzcwYjYxZjQzYzFhZmMzMmY4ZCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfYjQzNjAwM2YxMTBkNDJhNTg5NjU5MDk1MzAzY2YzZmYgPSAkKGA8ZGl2IGlkPSJodG1sX2I0MzYwMDNmMTEwZDQyYTU4OTY1OTA5NTMwM2NmM2ZmIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5QZWFjZWZ1bCBSZXN0YXVyYW50IOWSjOW5s+mlreW6lzwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9kNDI5ZWJjNTUyY2U0MzcwYjYxZjQzYzFhZmMzMmY4ZC5zZXRDb250ZW50KGh0bWxfYjQzNjAwM2YxMTBkNDJhNTg5NjU5MDk1MzAzY2YzZmYpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzkyODRkYWQyNDA4ZDRmOTM4ZDhiZWM0ZTAyMjgyZmI2LmJpbmRQb3B1cChwb3B1cF9kNDI5ZWJjNTUyY2U0MzcwYjYxZjQzYzFhZmMzMmY4ZCkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMTBhN2ZkMjZiZTVlNDkxNmI2ZjA5ZjA5NTcwYzU1YWIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNTczMDk0OTk0OTYwNywgLTEyMy4wNDk5MjM1NzgxNjk2XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJvcmFuZ2UiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAib3JhbmdlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF80NGI4NTZkYzllN2U0NDU5YjRmMGVjYjYyYTM2MmJkZCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfZDgyZTU3NjU5NDMyNDVmYTlmY2EyYTJlYzU0ZTA1ZWQgPSAkKGA8ZGl2IGlkPSJodG1sX2Q4MmU1NzY1OTQzMjQ1ZmE5ZmNhMmEyZWM1NGUwNWVkIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5EYXJpbyBJdGFsaWFuIFJlc3RhdXJhbnQ8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfNDRiODU2ZGM5ZTdlNDQ1OWI0ZjBlY2I2MmEzNjJiZGQuc2V0Q29udGVudChodG1sX2Q4MmU1NzY1OTQzMjQ1ZmE5ZmNhMmEyZWM1NGUwNWVkKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl8xMGE3ZmQyNmJlNWU0OTE2YjZmMDlmMDk1NzBjNTVhYi5iaW5kUG9wdXAocG9wdXBfNDRiODU2ZGM5ZTdlNDQ1OWI0ZjBlY2I2MmEzNjJiZGQpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzRlYmY1YzMwZmZjNDRhN2Y4YjYyYmRmMTQ1YTAyMzBkID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjczNTcxNzU0MTkwNTYsIC0xMjMuMTIzMzU3MDk3NzU3M10sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAib3JhbmdlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogIm9yYW5nZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfNThjNTNlNDY5ZmVhNDBlY2E5ZDNmMDg4MWQxYzliMzMgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzA2OWJlMWM2ODYwNTRhNGI5YzdiMWQxNzgzOWIwYTNhID0gJChgPGRpdiBpZD0iaHRtbF8wNjliZTFjNjg2MDU0YTRiOWM3YjFkMTc4MzliMGEzYSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+S2ktaXN1IEphcGFuZXNlIFJlc3RhdXJhbnQ8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfNThjNTNlNDY5ZmVhNDBlY2E5ZDNmMDg4MWQxYzliMzMuc2V0Q29udGVudChodG1sXzA2OWJlMWM2ODYwNTRhNGI5YzdiMWQxNzgzOWIwYTNhKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl80ZWJmNWMzMGZmYzQ0YTdmOGI2MmJkZjE0NWEwMjMwZC5iaW5kUG9wdXAocG9wdXBfNThjNTNlNDY5ZmVhNDBlY2E5ZDNmMDg4MWQxYzliMzMpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzQyOTkwY2M1MjgyNDQ5ZjFiZjE2ZDY3ODA5ZjUyMWU4ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjYzNDIxMjA5MzI1MjYsIC0xMjMuMTM2NTM2MjEyNzk1Nl0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAib3JhbmdlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogIm9yYW5nZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfMDk1Y2MwNDQ5MzY5NDYxOWJmYzY2MWI3N2M2NmZhNzcgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzI2ZGMxZDYyMDY5NDQ5MmI5YWMxNjRiMTNiYTZjODc5ID0gJChgPGRpdiBpZD0iaHRtbF8yNmRjMWQ2MjA2OTQ0OTJiOWFjMTY0YjEzYmE2Yzg3OSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TWFzYSBKYXBhbmVzZSBSZXN0YXVyYW50PC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzA5NWNjMDQ0OTM2OTQ2MTliZmM2NjFiNzdjNjZmYTc3LnNldENvbnRlbnQoaHRtbF8yNmRjMWQ2MjA2OTQ0OTJiOWFjMTY0YjEzYmE2Yzg3OSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfNDI5OTBjYzUyODI0NDlmMWJmMTZkNjc4MDlmNTIxZTguYmluZFBvcHVwKHBvcHVwXzA5NWNjMDQ0OTM2OTQ2MTliZmM2NjFiNzdjNjZmYTc3KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8wMmI0ODcxMWU5MzU0Yzk0YmM3YzQxZTdkZWU1MDE4MCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4MjkyOTY2MTMyOTUyNiwgLTEyMy4xMTU0Mjc3NTAzMTI1OF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAib3JhbmdlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogIm9yYW5nZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfZDQ4N2M4Mzk2NWUzNGQyMjkxZDc0M2I2OTFjNGQ3M2YgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzkzNzBhMDkyZjBiMzQyMGI4M2U2OGE4MDJlYThiN2RjID0gJChgPGRpdiBpZD0iaHRtbF85MzcwYTA5MmYwYjM0MjBiODNlNjhhODAyZWE4YjdkYyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+UGVhY2VmdWwgUmVzdGF1cmFudDwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9kNDg3YzgzOTY1ZTM0ZDIyOTFkNzQzYjY5MWM0ZDczZi5zZXRDb250ZW50KGh0bWxfOTM3MGEwOTJmMGIzNDIwYjgzZTY4YTgwMmVhOGI3ZGMpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzAyYjQ4NzExZTkzNTRjOTRiYzdjNDFlN2RlZTUwMTgwLmJpbmRQb3B1cChwb3B1cF9kNDg3YzgzOTY1ZTM0ZDIyOTFkNzQzYjY5MWM0ZDczZikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMTMyYzNhMzdiNTJhNGZlNjhkMjAxY2UzYjEzN2JhMDAgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNjk0NDI0MzMzNzUzLCAtMTIzLjEzODY5MTE5NDQ2MzQ1XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJvcmFuZ2UiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAib3JhbmdlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF80YTJjMTFlZmU2ZTY0ZGRiOGU5ZGY0NWE2MDk1NGFkOSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNjVlZGY5NmJmNGMwNGVlNDgzMTU2YmE3YWEyODVlNjYgPSAkKGA8ZGl2IGlkPSJodG1sXzY1ZWRmOTZiZjRjMDRlZTQ4MzE1NmJhN2FhMjg1ZTY2IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5BZmdoYW4gSG9yc2VtZW4gUmVzdGF1cmFudDwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF80YTJjMTFlZmU2ZTY0ZGRiOGU5ZGY0NWE2MDk1NGFkOS5zZXRDb250ZW50KGh0bWxfNjVlZGY5NmJmNGMwNGVlNDgzMTU2YmE3YWEyODVlNjYpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzEzMmMzYTM3YjUyYTRmZTY4ZDIwMWNlM2IxMzdiYTAwLmJpbmRQb3B1cChwb3B1cF80YTJjMTFlZmU2ZTY0ZGRiOGU5ZGY0NWE2MDk1NGFkOSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMGRlNDRjMjVlMjkyNDQxYzk3MmVlNmIxMTcwYmFjMjAgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yODMxNjA5MjEyMTAwMSwgLTEyMy4xMTI1MDI4OTI1NTcwMl0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAib3JhbmdlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogIm9yYW5nZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfZmIwOWFhMTQyNGZkNDM1Yzg1YTg1NjQ5YmI2N2Q0OWIgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzI2MWQ0ZDAyNmI0NTRkNmE5ODQ2MWQxZjg4MGYyM2RmID0gJChgPGRpdiBpZD0iaHRtbF8yNjFkNGQwMjZiNDU0ZDZhOTg0NjFkMWY4ODBmMjNkZiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+WWFnZ2VyJ3MgRG93bnRvd24gUmVzdGF1cmFudCAmIFNwb3J0cyBCYXI8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfZmIwOWFhMTQyNGZkNDM1Yzg1YTg1NjQ5YmI2N2Q0OWIuc2V0Q29udGVudChodG1sXzI2MWQ0ZDAyNmI0NTRkNmE5ODQ2MWQxZjg4MGYyM2RmKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl8wZGU0NGMyNWUyOTI0NDFjOTcyZWU2YjExNzBiYWMyMC5iaW5kUG9wdXAocG9wdXBfZmIwOWFhMTQyNGZkNDM1Yzg1YTg1NjQ5YmI2N2Q0OWIpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzVlOWEyNTQyNWZiNjQyMzBiZDliZmU1ZDUyZDRiYjVjID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjU5NDI5MjA5NDE1OTgsIC0xMjMuMDY5NjE3ODE0NjAwOTVdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogIm9yYW5nZSIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJvcmFuZ2UiLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzYzNDlkYTQ5ODM1NTQ4ODY4MzE4ZTBmYTk0Zjk4NjZkID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF80ZDBhNmIyNWU1YWQ0YmIwYjBlNDIzMWJlZTFkOGM1YiA9ICQoYDxkaXYgaWQ9Imh0bWxfNGQwYTZiMjVlNWFkNGJiMGIwZTQyMzFiZWUxZDhjNWIiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlN6ZWNodWFuIENob25ncWluZyBSZXN0YXVyYW50PC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzYzNDlkYTQ5ODM1NTQ4ODY4MzE4ZTBmYTk0Zjk4NjZkLnNldENvbnRlbnQoaHRtbF80ZDBhNmIyNWU1YWQ0YmIwYjBlNDIzMWJlZTFkOGM1Yik7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfNWU5YTI1NDI1ZmI2NDIzMGJkOWJmZTVkNTJkNGJiNWMuYmluZFBvcHVwKHBvcHVwXzYzNDlkYTQ5ODM1NTQ4ODY4MzE4ZTBmYTk0Zjk4NjZkKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9lYmI0ZjQ3MGJlODc0NGU2YmE0YTk3YzBiNDMzNWUzYiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI2OTM0Nzc4MTY4MzY0LCAtMTIzLjEzMDczMDY2NzY3NjE4XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJvcmFuZ2UiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAib3JhbmdlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8yMmEwMTMyYzY1ZWI0ZWFmOTg5YjIzODE5Mzc2ZTk4ZiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNzU4NDIzODZlZTM0NDBhN2FlOWRkYzBmNjc4NGJhNDEgPSAkKGA8ZGl2IGlkPSJodG1sXzc1ODQyMzg2ZWUzNDQwYTdhZTlkZGMwZjY3ODRiYTQxIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Eb2Nrc2lkZSBSZXN0YXVyYW50PC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzIyYTAxMzJjNjVlYjRlYWY5ODliMjM4MTkzNzZlOThmLnNldENvbnRlbnQoaHRtbF83NTg0MjM4NmVlMzQ0MGE3YWU5ZGRjMGY2Nzg0YmE0MSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfZWJiNGY0NzBiZTg3NDRlNmJhNGE5N2MwYjQzMzVlM2IuYmluZFBvcHVwKHBvcHVwXzIyYTAxMzJjNjVlYjRlYWY5ODliMjM4MTkzNzZlOThmKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl81YWRlY2I3ZWE1ODQ0YThkYWUyNzQ3ZDBjZDFkOWE5ZCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI1NDYwOTcwODQwNTc1LCAtMTIzLjExNTA0NzA0NDE2Mjk2XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJvcmFuZ2UiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAib3JhbmdlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF81ZmUxZTJlZDQxMjE0OTNiOWJhZDBmYzU5ZmUyOWU2MiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfMWIzZWJhNzZkMjIwNDRkZjkzMDUxOGFjZTQyYzE1YzggPSAkKGA8ZGl2IGlkPSJodG1sXzFiM2ViYTc2ZDIyMDQ0ZGY5MzA1MThhY2U0MmMxNWM4IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij4zRyBWZWdldGFyaWFuIFJlc3RhdXJhbnQ8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfNWZlMWUyZWQ0MTIxNDkzYjliYWQwZmM1OWZlMjllNjIuc2V0Q29udGVudChodG1sXzFiM2ViYTc2ZDIyMDQ0ZGY5MzA1MThhY2U0MmMxNWM4KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl81YWRlY2I3ZWE1ODQ0YThkYWUyNzQ3ZDBjZDFkOWE5ZC5iaW5kUG9wdXAocG9wdXBfNWZlMWUyZWQ0MTIxNDkzYjliYWQwZmM1OWZlMjllNjIpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzIyZmJjNDczY2U4ZTRlZTQ5NmVkODRjZGRmYjJjNjBjID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjYzNzk2NjkxOTYzNjU1LCAtMTIzLjEwMTY0NTI0Nzc5MTc3XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJvcmFuZ2UiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAib3JhbmdlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8wZjJjZjY0NDA4YmQ0NzlkOGUyNmNiZDNjYWNmZWI5NiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfYzc1MzczNjBlNTZjNDhiMjg4NDk0MjcyMDVlOGRiN2IgPSAkKGA8ZGl2IGlkPSJodG1sX2M3NTM3MzYwZTU2YzQ4YjI4ODQ5NDI3MjA1ZThkYjdiIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5FaWdodCDCvSBSZXN0YXVyYW50IExvdW5nZTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8wZjJjZjY0NDA4YmQ0NzlkOGUyNmNiZDNjYWNmZWI5Ni5zZXRDb250ZW50KGh0bWxfYzc1MzczNjBlNTZjNDhiMjg4NDk0MjcyMDVlOGRiN2IpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzIyZmJjNDczY2U4ZTRlZTQ5NmVkODRjZGRmYjJjNjBjLmJpbmRQb3B1cChwb3B1cF8wZjJjZjY0NDA4YmQ0NzlkOGUyNmNiZDNjYWNmZWI5NikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfM2ZiOWM1NzEyMTgwNDNhOTk5YTBiNzkyY2E5NjY4ZWQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNjA4NjYyMzIxMjg4MSwgLTEyMy4xMTU0MjA3OTY4NzUzNl0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAib3JhbmdlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogIm9yYW5nZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfYzQzNjkwNWNiMGRjNDJkNmI5NzNjMGYzMjgwODUzZDIgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzczYjY5YmM1MGE0ZDQ3MjBhMzFlYTVkOGJjYWZjMDRhID0gJChgPGRpdiBpZD0iaHRtbF83M2I2OWJjNTBhNGQ0NzIwYTMxZWE1ZDhiY2FmYzA0YSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+S2lyaW4gU2VhZm9vZCBSZXN0YXVyYW50IOeOiem6kum6n+a1t+murumFkuWutiAoS2lyaW4gU2VhZm9vZCBSZXN0YXVyYW50KTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9jNDM2OTA1Y2IwZGM0MmQ2Yjk3M2MwZjMyODA4NTNkMi5zZXRDb250ZW50KGh0bWxfNzNiNjliYzUwYTRkNDcyMGEzMWVhNWQ4YmNhZmMwNGEpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzNmYjljNTcxMjE4MDQzYTk5OWEwYjc5MmNhOTY2OGVkLmJpbmRQb3B1cChwb3B1cF9jNDM2OTA1Y2IwZGM0MmQ2Yjk3M2MwZjMyODA4NTNkMikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfOWJjMGFlNzI1NTM5NGM2OTliYWM3YjcwY2VjNDNmODQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNjM3Nzg3NDk0MjIxMiwgLTEyMy4xMjE0NTIxNjc1NDQ2NV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAib3JhbmdlIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogIm9yYW5nZSIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfZmRiNzE2MTZlYzcyNDc2NTk1OWQ5ZDdmOTk1NWNmZTggPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzM3MjM3YWViZDNiMTQ5MTFiYTdiNWFiYjdhNzA5M2E2ID0gJChgPGRpdiBpZD0iaHRtbF8zNzIzN2FlYmQzYjE0OTExYmE3YjVhYmI3YTcwOTNhNiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+RHluYXN0eSBTZWFmb29kIFJlc3RhdXJhbnQg55qH5pyd5rW36a6u6YWS5a62PC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2ZkYjcxNjE2ZWM3MjQ3NjU5NTlkOWQ3Zjk5NTVjZmU4LnNldENvbnRlbnQoaHRtbF8zNzIzN2FlYmQzYjE0OTExYmE3YjVhYmI3YTcwOTNhNik7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfOWJjMGFlNzI1NTM5NGM2OTliYWM3YjcwY2VjNDNmODQuYmluZFBvcHVwKHBvcHVwX2ZkYjcxNjE2ZWM3MjQ3NjU5NTlkOWQ3Zjk5NTVjZmU4KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl81YzlkMjAxMTE3NDM0N2IwODE0NjIyYTJmOWMyMGQ0NCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjIzNjk5MjgxNjA3NjYxNSwgLTEyMy4wNjU1NTUzNTQ4OTcyXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJvcmFuZ2UiLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAib3JhbmdlIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF83MzVkNzQyOTA2MWI0Y2Q0YmQ5OWU4YzMyMGU0Y2U2YyA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfMmU1M2MxOGZmNzRlNDdiNDkyOGVmZmRiOWUwMGI4NWEgPSAkKGA8ZGl2IGlkPSJodG1sXzJlNTNjMThmZjc0ZTQ3YjQ5MjhlZmZkYjllMDBiODVhIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5TYW5keSBMYSBDaGluZXNlIFJlc3RhdXJhbnQ8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfNzM1ZDc0MjkwNjFiNGNkNGJkOTllOGMzMjBlNGNlNmMuc2V0Q29udGVudChodG1sXzJlNTNjMThmZjc0ZTQ3YjQ5MjhlZmZkYjllMDBiODVhKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl81YzlkMjAxMTE3NDM0N2IwODE0NjIyYTJmOWMyMGQ0NC5iaW5kUG9wdXAocG9wdXBfNzM1ZDc0MjkwNjFiNGNkNGJkOTllOGMzMjBlNGNlNmMpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzM3YTk0MWUyNDNmMDQ5Mjc4M2MzMTQ1YTllNDE2OThhID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMzAyNDg4NDQ3MDM4MjQsIC0xMjMuMTQxNzE3OTEwNzY2NjJdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogImdyZWVuIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogImdyZWVuIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8yODZmOTM4NTBmMTA0MTE5YTkwMDUxMGVlOTEzNTlmNCA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNzMzYTY3NTliYjdmNGVmZDgyODdiOTgxOTI1YmRiMzkgPSAkKGA8ZGl2IGlkPSJodG1sXzczM2E2NzU5YmI3ZjRlZmQ4Mjg3Yjk4MTkyNWJkYjM5IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5TdGFubGV5IFBhcms8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfMjg2ZjkzODUwZjEwNDExOWE5MDA1MTBlZTkxMzU5ZjQuc2V0Q29udGVudChodG1sXzczM2E2NzU5YmI3ZjRlZmQ4Mjg3Yjk4MTkyNWJkYjM5KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl8zN2E5NDFlMjQzZjA0OTI3ODNjMzE0NWE5ZTQxNjk4YS5iaW5kUG9wdXAocG9wdXBfMjg2ZjkzODUwZjEwNDExOWE5MDA1MTBlZTkxMzU5ZjQpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzdhYTljZjQyZGMwODRmNTViZjFiNTdkZWFhOWYwMWRlID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjkwMjMwMDk5NTkzNzg1LCAtMTIzLjE0Njg2Nzc1MjA3NTJdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogImdyZWVuIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogImdyZWVuIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9jZDcwYjE3ODM3YmE0YWZlOWM2YWM4ZWVhNjE3YTVlMSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfMjZmYmY3NDI5MTY2NDY0NmFhOWYzN2U0NWY0NWMzYWMgPSAkKGA8ZGl2IGlkPSJodG1sXzI2ZmJmNzQyOTE2NjQ2NDZhYTlmMzdlNDVmNDVjM2FjIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5TdGFubGV5IFBhcmsgRW5nbGlzaCBCYXkgU2Vhd2FsbDwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9jZDcwYjE3ODM3YmE0YWZlOWM2YWM4ZWVhNjE3YTVlMS5zZXRDb250ZW50KGh0bWxfMjZmYmY3NDI5MTY2NDY0NmFhOWYzN2U0NWY0NWMzYWMpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzdhYTljZjQyZGMwODRmNTViZjFiNTdkZWFhOWYwMWRlLmJpbmRQb3B1cChwb3B1cF9jZDcwYjE3ODM3YmE0YWZlOWM2YWM4ZWVhNjE3YTVlMSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZDdlMjRiYzkwMDg0NGNjMmFjODgyOThhZjgzYjNhNWIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDkyNjI4Nzk2NDA1OCwgLTEyMy4yMTEzNjk1MTQ0NjUzMl0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAiZ3JlZW4iLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAiZ3JlZW4iLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzIzNWI3NzI0NzE3MDRjYzQ5ZmU1YWY2ZDY1MWE0MWE1ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9iMzRmMzJiYmYwNDI0Mjg5ODMxYjQxODVjMzQzZGU5YyA9ICQoYDxkaXYgaWQ9Imh0bWxfYjM0ZjMyYmJmMDQyNDI4OTgzMWI0MTg1YzM0M2RlOWMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlBhY2lmaWMgU3Bpcml0IFJlZ2lvbmFsIFBhcms8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfMjM1Yjc3MjQ3MTcwNGNjNDlmZTVhZjZkNjUxYTQxYTUuc2V0Q29udGVudChodG1sX2IzNGYzMmJiZjA0MjQyODk4MzFiNDE4NWMzNDNkZTljKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9kN2UyNGJjOTAwODQ0Y2MyYWM4ODI5OGFmODNiM2E1Yi5iaW5kUG9wdXAocG9wdXBfMjM1Yjc3MjQ3MTcwNGNjNDlmZTVhZjZkNjUxYTQxYTUpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2VjNTk5ZmNlMmQ2NzQ0MWI4YjQ1OThiZjZkMzM3MzgzID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjQxNTY0NTU1MjQ3NzIsIC0xMjMuMTEzMzU1MjA1NDA4MTRdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogImdyZWVuIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogImdyZWVuIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF81MDA3ZTJmZDQxZDI0OTIyYTE1NmQ0OWE5ZDY1YTM5OSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfZjE2YzkyYjU5ZmJmNGFkY2I1ZjJiMDg5ZWYyOGQwNjUgPSAkKGA8ZGl2IGlkPSJodG1sX2YxNmM5MmI1OWZiZjRhZGNiNWYyYjA4OWVmMjhkMDY1IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5RdWVlbiBFbGl6YWJldGggUGFyazwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF81MDA3ZTJmZDQxZDI0OTIyYTE1NmQ0OWE5ZDY1YTM5OS5zZXRDb250ZW50KGh0bWxfZjE2YzkyYjU5ZmJmNGFkY2I1ZjJiMDg5ZWYyOGQwNjUpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2VjNTk5ZmNlMmQ2NzQ0MWI4YjQ1OThiZjZkMzM3MzgzLmJpbmRQb3B1cChwb3B1cF81MDA3ZTJmZDQxZDI0OTIyYTE1NmQ0OWE5ZDY1YTM5OSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfN2I5ODM3MjM5ZTM1NDEyZjlkMTlhNTQ0NmMwYWYxYjkgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNzI0NjY1NTI5MTM1MSwgLTEyMy4xMjM4NjU1NjMwMjI5Nl0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAiZ3JlZW4iLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAiZ3JlZW4iLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzFhOGJlZGRlN2UzODQxYzliNGZhZGM5MDYwMDg4YjE0ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9lZjQxOGU1NGJlZmE0OGQ5OGEyZTkwYzk1ZDg1YThiYiA9ICQoYDxkaXYgaWQ9Imh0bWxfZWY0MThlNTRiZWZhNDhkOThhMmU5MGM5NWQ4NWE4YmIiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkRhdmlkIExhbSBQYXJrPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzFhOGJlZGRlN2UzODQxYzliNGZhZGM5MDYwMDg4YjE0LnNldENvbnRlbnQoaHRtbF9lZjQxOGU1NGJlZmE0OGQ5OGEyZTkwYzk1ZDg1YThiYik7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfN2I5ODM3MjM5ZTM1NDEyZjlkMTlhNTQ0NmMwYWYxYjkuYmluZFBvcHVwKHBvcHVwXzFhOGJlZGRlN2UzODQxYzliNGZhZGM5MDYwMDg4YjE0KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9kNWMzNWI0ODcxNDU0ZmE3YmY5ZmI3MDIzMWViNDZkNyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI2Njg4MDQzMjkwNjY0LCAtMTIzLjEyNDY4MDUxOTEwNF0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAiZ3JlZW4iLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAiZ3JlZW4iLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2ZiYjg5OTZkNGZiMTQxM2NiNTFmOTZiZmRkYTU2ZDc0ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9iNTAzZmRjYmY2MGU0N2E5ODQzMDgzZmI2ZDM5MjZjMyA9ICQoYDxkaXYgaWQ9Imh0bWxfYjUwM2ZkY2JmNjBlNDdhOTg0MzA4M2ZiNmQzOTI2YzMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkNoYXJsZXNvbiBQYXJrPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwX2ZiYjg5OTZkNGZiMTQxM2NiNTFmOTZiZmRkYTU2ZDc0LnNldENvbnRlbnQoaHRtbF9iNTAzZmRjYmY2MGU0N2E5ODQzMDgzZmI2ZDM5MjZjMyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfZDVjMzViNDg3MTQ1NGZhN2JmOWZiNzAyMzFlYjQ2ZDcuYmluZFBvcHVwKHBvcHVwX2ZiYjg5OTZkNGZiMTQxM2NiNTFmOTZiZmRkYTU2ZDc0KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9hN2ViY2Q0ZGY0ODQ0ZTVmOTY2NWY4ZTBjNDZiMGFmNCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI3MjM4Mjg3ODYyMTY1NiwgLTEyMy4xMjk0MzMzOTM0Nzg0MV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAiZ3JlZW4iLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAiZ3JlZW4iLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzE5MWE5NWE0NTgzNjQ2ODk5MmE1ODc2ZjM0MmZmNjhmID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9mNGEyYmE1MTU4NzM0NTgwODQ0MWNkNGUxOTBlZWQ3NCA9ICQoYDxkaXYgaWQ9Imh0bWxfZjRhMmJhNTE1ODczNDU4MDg0NDFjZDRlMTkwZWVkNzQiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkdlb3JnZSBXYWluYm9ybiBQYXJrPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzE5MWE5NWE0NTgzNjQ2ODk5MmE1ODc2ZjM0MmZmNjhmLnNldENvbnRlbnQoaHRtbF9mNGEyYmE1MTU4NzM0NTgwODQ0MWNkNGUxOTBlZWQ3NCk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYTdlYmNkNGRmNDg0NGU1Zjk2NjVmOGUwYzQ2YjBhZjQuYmluZFBvcHVwKHBvcHVwXzE5MWE5NWE0NTgzNjQ2ODk5MmE1ODc2ZjM0MmZmNjhmKQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl82Njg1NTA3NGUzODQ0ZGZiYTJjN2MwYTZhZTI3MmQ5OCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI3MzU0NzAyNDg5MzE3LCAtMTIzLjExMzc1MTA2NDM1MjczXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJncmVlbiIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJncmVlbiIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfZGEzMGI1MzczMTAxNDE5YmE2MWNmMjljOWU0MDMxYTAgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2I2NzljZjQ5MWNiNDQ3NjViNjJiNmM5NTA4MjBmMjIyID0gJChgPGRpdiBpZD0iaHRtbF9iNjc5Y2Y0OTFjYjQ0NzY1YjYyYjZjOTUwODIwZjIyMiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Q29vcGVyJ3MgUGFyazwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9kYTMwYjUzNzMxMDE0MTliYTYxY2YyOWM5ZTQwMzFhMC5zZXRDb250ZW50KGh0bWxfYjY3OWNmNDkxY2I0NDc2NWI2MmI2Yzk1MDgyMGYyMjIpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzY2ODU1MDc0ZTM4NDRkZmJhMmM3YzBhNmFlMjcyZDk4LmJpbmRQb3B1cChwb3B1cF9kYTMwYjUzNzMxMDE0MTliYTYxY2YyOWM5ZTQwMzFhMCkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfY2I2YTRmYWE2OTFlNDhlZDk5MzJiNjNjM2YxNjliYjggPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNDIwMjE0NDkyOTQ1NzYsIC0xMjMuMTEyMDU1MjM0ODE3MThdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogImdyZWVuIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogImdyZWVuIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8wN2E0ZGVlMTlhNzI0ZTYzOTFkZDQyZGMyYWYzNmFlNiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfZDA1NGZlZTVjOTcwNGQ5MmI2NzZkMTkwODE5MzAyMmYgPSAkKGA8ZGl2IGlkPSJodG1sX2QwNTRmZWU1Yzk3MDRkOTJiNjc2ZDE5MDgxOTMwMjJmIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5TZWFzb25zIGluIHRoZSBQYXJrPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzA3YTRkZWUxOWE3MjRlNjM5MWRkNDJkYzJhZjM2YWU2LnNldENvbnRlbnQoaHRtbF9kMDU0ZmVlNWM5NzA0ZDkyYjY3NmQxOTA4MTkzMDIyZik7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfY2I2YTRmYWE2OTFlNDhlZDk5MzJiNjNjM2YxNjliYjguYmluZFBvcHVwKHBvcHVwXzA3YTRkZWUxOWE3MjRlNjM5MWRkNDJkYzJhZjM2YWU2KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9hMzE1ZDAzZTI3NTY0MzJiYTg0NjUwMTJhYzJmN2QyOCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI4NDk5MDIwMjE4MjE0LCAtMTIzLjEwMTMyNjc3ODAyMTY0XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJncmVlbiIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJncmVlbiIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfMGZjZjFjNjIwNWQwNDk3MzhhZDFlNzZiOGYzYmQ4NjggPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzExNGE3ZGU2MTQyNTQzMDJhZjk1ZWJmMjljOTMzMTIxID0gJChgPGRpdiBpZD0iaHRtbF8xMTRhN2RlNjE0MjU0MzAyYWY5NWViZjI5YzkzMzEyMSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Q3JhYiBQYXJrPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzBmY2YxYzYyMDVkMDQ5NzM4YWQxZTc2YjhmM2JkODY4LnNldENvbnRlbnQoaHRtbF8xMTRhN2RlNjE0MjU0MzAyYWY5NWViZjI5YzkzMzEyMSk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfYTMxNWQwM2UyNzU2NDMyYmE4NDY1MDEyYWMyZjdkMjguYmluZFBvcHVwKHBvcHVwXzBmY2YxYzYyMDVkMDQ5NzM4YWQxZTc2YjhmM2JkODY4KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl84NjE3YmRmOGZmNWQ0ZmY0YjdkNmRmNmQyYzM5YjA3ZCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjIxNzU0MTA0MTU2MTY1LCAtMTIzLjIxMzIxNDg3NDI2NzU2XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJncmVlbiIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJncmVlbiIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfMjFkNjhhYzU5ZGFiNGNlYWJmNDdiMGFkMGIwNTYyYjYgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2FhNjVkZTgzYjdjZDRhN2E5NGMwYTQ5OGYwZTViOTFjID0gJChgPGRpdiBpZD0iaHRtbF9hYTY1ZGU4M2I3Y2Q0YTdhOTRjMGE0OThmMGU1YjkxYyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+SW9uYSBCZWFjaCBSZWdpb25hbCBQYXJrPC9kaXY+YClbMF07CiAgICAgICAgICAgIHBvcHVwXzIxZDY4YWM1OWRhYjRjZWFiZjQ3YjBhZDBiMDU2MmI2LnNldENvbnRlbnQoaHRtbF9hYTY1ZGU4M2I3Y2Q0YTdhOTRjMGE0OThmMGU1YjkxYyk7CiAgICAgICAgCgogICAgICAgIGNpcmNsZV9tYXJrZXJfODYxN2JkZjhmZjVkNGZmNGI3ZDZkZjZkMmMzOWIwN2QuYmluZFBvcHVwKHBvcHVwXzIxZDY4YWM1OWRhYjRjZWFiZjQ3YjBhZDBiMDU2MmI2KQogICAgICAgIDsKCiAgICAgICAgCiAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl83ZDdmOTI1NmM3M2U0YzgzYmZiOWM1ZDEwNjhkNmFkZSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQ5LjI5MzAxMTM5NTA3MzQyLCAtMTIzLjE0NjM4OTU3NDcyNjQxXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJncmVlbiIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJncmVlbiIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfMDBkODc1ODAwYWRkNGMyOGI3OTViMmRiNmFjMzg3MzcgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzc5ZmUwZjYzMGM0ZTQzMjZhZTliOTZjMmQ2ODA0NzU5ID0gJChgPGRpdiBpZD0iaHRtbF83OWZlMGY2MzBjNGU0MzI2YWU5Yjk2YzJkNjgwNDc1OSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+U3RhbmxleSBQYXJrIFBpdGNoICYgUHV0dDwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8wMGQ4NzU4MDBhZGQ0YzI4Yjc5NWIyZGI2YWMzODczNy5zZXRDb250ZW50KGh0bWxfNzlmZTBmNjMwYzRlNDMyNmFlOWI5NmMyZDY4MDQ3NTkpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzdkN2Y5MjU2YzczZTRjODNiZmI5YzVkMTA2OGQ2YWRlLmJpbmRQb3B1cChwb3B1cF8wMGQ4NzU4MDBhZGQ0YzI4Yjc5NWIyZGI2YWMzODczNykKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNjZhYmRmMjgwODhhNDUwZTk3ZjU3NzE2M2RjNmJhNmIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNTcwNDE4MTU0MTcyOSwgLTEyMy4xMDU5NDU1ODg2NjA1XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJncmVlbiIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJncmVlbiIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfYzU3NTM1NDM1NDkxNGM2ZGExMjUzZjJiZmI3MjgzMDQgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzdlM2E1OTQ5NjY3ZjQyMzBiZjllMWJiODhkNzNiZWIwID0gJChgPGRpdiBpZD0iaHRtbF83ZTNhNTk0OTY2N2Y0MjMwYmY5ZTFiYjg4ZDczYmViMCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TXQuIFBsZWFzYW50IFBhcms8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfYzU3NTM1NDM1NDkxNGM2ZGExMjUzZjJiZmI3MjgzMDQuc2V0Q29udGVudChodG1sXzdlM2E1OTQ5NjY3ZjQyMzBiZjllMWJiODhkNzNiZWIwKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl82NmFiZGYyODA4OGE0NTBlOTdmNTc3MTYzZGM2YmE2Yi5iaW5kUG9wdXAocG9wdXBfYzU3NTM1NDM1NDkxNGM2ZGExMjUzZjJiZmI3MjgzMDQpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2I1NTFiYzUzY2RiNTRkZWZiOWViNWJiYWM4OGJkYmRjID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjgyNTYwMDg1NDkwMzI0LCAtMTIzLjEyOTIyOTU0NTU5MzI2XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJncmVlbiIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJncmVlbiIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfOTAxMWEwODNhMTIxNGIwZjk1YTkxZmY4MjE3MTljZjAgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzg1ODg4YzBmNTg3MDQ1YWNiZDQ2OTZhYWRkYTNjYjZhID0gJChgPGRpdiBpZD0iaHRtbF84NTg4OGMwZjU4NzA0NWFjYmQ0Njk2YWFkZGEzY2I2YSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TmVsc29uIFBhcms8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfOTAxMWEwODNhMTIxNGIwZjk1YTkxZmY4MjE3MTljZjAuc2V0Q29udGVudChodG1sXzg1ODg4YzBmNTg3MDQ1YWNiZDQ2OTZhYWRkYTNjYjZhKTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9iNTUxYmM1M2NkYjU0ZGVmYjllYjViYmFjODhiZGJkYy5iaW5kUG9wdXAocG9wdXBfOTAxMWEwODNhMTIxNGIwZjk1YTkxZmY4MjE3MTljZjApCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzcwOTRjMTY5MTFkMTQ2ZDc5NjJjMjJmODEzNGUwODcxID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjc1MzczMzU3MDkyMTEsIC0xMjMuMTIzMzk5Nzc5NDEwM10sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAiZ3JlZW4iLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAiZ3JlZW4iLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzAyODFkMzA3MmUzMzRkMWI5YmJlM2FmZDA0NDlhYjJiID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF84ZjBmNTdlOTIzNTA0NmIxOWRhMGY3ZmNjZGZjMjc5OSA9ICQoYDxkaXYgaWQ9Imh0bWxfOGYwZjU3ZTkyMzUwNDZiMTlkYTBmN2ZjY2RmYzI3OTkiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkVtZXJ5IEJhcm5lcyBQYXJrICYgUGxheWdyb3VuZDwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8wMjgxZDMwNzJlMzM0ZDFiOWJiZTNhZmQwNDQ5YWIyYi5zZXRDb250ZW50KGh0bWxfOGYwZjU3ZTkyMzUwNDZiMTlkYTBmN2ZjY2RmYzI3OTkpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzcwOTRjMTY5MTFkMTQ2ZDc5NjJjMjJmODEzNGUwODcxLmJpbmRQb3B1cChwb3B1cF8wMjgxZDMwNzJlMzM0ZDFiOWJiZTNhZmQwNDQ5YWIyYikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYWYzMjM1YWI4NTc5NGRmNTk2MTNiZTliNDVhMzM0NjMgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNTE1ODc5NzI1OTA4OCwgLTEyMy4wOTc1NTgwMjE1NDU0MV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAiZ3JlZW4iLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAiZ3JlZW4iLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwX2JjNWFjODUxZWYxMDRjMGJhYWY0NWVmOGRiZWY4Y2Q0ID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF8yODZiZGMyY2FhZGQ0MGJjOGZiNjRiMzUwODg2NDRlYSA9ICQoYDxkaXYgaWQ9Imh0bWxfMjg2YmRjMmNhYWRkNDBiYzhmYjY0YjM1MDg4NjQ0ZWEiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlByaW5jZSBFZHdhcmQgUGFyazwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9iYzVhYzg1MWVmMTA0YzBiYWFmNDVlZjhkYmVmOGNkNC5zZXRDb250ZW50KGh0bWxfMjg2YmRjMmNhYWRkNDBiYzhmYjY0YjM1MDg4NjQ0ZWEpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2FmMzIzNWFiODU3OTRkZjU5NjEzYmU5YjQ1YTMzNDYzLmJpbmRQb3B1cChwb3B1cF9iYzVhYzg1MWVmMTA0YzBiYWFmNDVlZjhkYmVmOGNkNCkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYTI0NDdkYmQ0ZDYxNDM3OTg1ZjFlYzI0MTE2N2E5OGYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4zMjY0MDg2MjkxNTE2NCwgLTEyMy4xMzU4ODE0MjM5NTAyXSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJncmVlbiIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJncmVlbiIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfNjY2ZjcxYTI0NmJiNDBlNzg4NmVkZGIwYzE3M2YwYWIgPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sX2IzYzY2OWYwMzA1YjRiOWVhYjhmMTdkOGU2MmJjNGNhID0gJChgPGRpdiBpZD0iaHRtbF9iM2M2NjlmMDMwNWI0YjllYWI4ZjE3ZDhlNjJiYzRjYSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+UGFyayBSb3lhbCBTb3V0aDwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF82NjZmNzFhMjQ2YmI0MGU3ODg2ZWRkYjBjMTczZjBhYi5zZXRDb250ZW50KGh0bWxfYjNjNjY5ZjAzMDViNGI5ZWFiOGYxN2Q4ZTYyYmM0Y2EpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2EyNDQ3ZGJkNGQ2MTQzNzk4NWYxZWMyNDExNjdhOThmLmJpbmRQb3B1cChwb3B1cF82NjZmNzFhMjQ2YmI0MGU3ODg2ZWRkYjBjMTczZjBhYikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZWU4NDc3Y2QzOTVmNDIxMWFiNGY5ZGZlMzNjNTEwZTAgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNTUxMjI5MjE3NzM3OSwgLTEyMy4xMjE5NjM2NTg3NjkwOV0sCiAgICAgICAgICAgICAgICB7ImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLCAiY29sb3IiOiAiZ3JlZW4iLCAiZGFzaEFycmF5IjogbnVsbCwgImRhc2hPZmZzZXQiOiBudWxsLCAiZmlsbCI6IHRydWUsICJmaWxsQ29sb3IiOiAiZ3JlZW4iLCAiZmlsbE9wYWNpdHkiOiAwLjYsICJmaWxsUnVsZSI6ICJldmVub2RkIiwgImxpbmVDYXAiOiAicm91bmQiLCAibGluZUpvaW4iOiAicm91bmQiLCAib3BhY2l0eSI6IDEuMCwgInJhZGl1cyI6IDUsICJzdHJva2UiOiB0cnVlLCAid2VpZ2h0IjogM30KICAgICAgICAgICAgKS5hZGRUbyhtYXBfZDRjOWZiN2M1YjVkNGEwMzliYmNlMGIwYjkwZjhlNzkpOwogICAgICAgIAogICAgCiAgICAgICAgdmFyIHBvcHVwXzkyY2UzYzY1MDgwYTRiOWRiMjVlYTYzN2U2ZGRhN2VhID0gTC5wb3B1cCh7Im1heFdpZHRoIjogIjEwMCUifSk7CgogICAgICAgIAogICAgICAgICAgICB2YXIgaHRtbF9hNjA3YzI3MzA1OGM0MzFkOTdjY2EwOWQ1NmVlNTdhNyA9ICQoYDxkaXYgaWQ9Imh0bWxfYTYwN2MyNzMwNThjNDMxZDk3Y2NhMDlkNTZlZTU3YTciIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkhlYXRoZXIgUGFyazwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF85MmNlM2M2NTA4MGE0YjlkYjI1ZWE2MzdlNmRkYTdlYS5zZXRDb250ZW50KGh0bWxfYTYwN2MyNzMwNThjNDMxZDk3Y2NhMDlkNTZlZTU3YTcpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyX2VlODQ3N2NkMzk1ZjQyMTFhYjRmOWRmZTMzYzUxMGUwLmJpbmRQb3B1cChwb3B1cF85MmNlM2M2NTA4MGE0YjlkYjI1ZWE2MzdlNmRkYTdlYSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfODc4MDA3NjlhNWNlNDZiYjk1OTQyYzk3MzFlMTI3NTEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNzcxMzM4Mjg1NjkyNiwgLTEyMy4xMjM4MzYwODk0OTldLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogImdyZWVuIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogImdyZWVuIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8zYzIyYTAyZWE4Nzk0NTFmYmFiMDdlY2I5MTcwODkyOSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfYTUyMTY3NmRjOTZkNDRjY2JhYWIwMGExZjhkNGRiNjEgPSAkKGA8ZGl2IGlkPSJodG1sX2E1MjE2NzZkYzk2ZDQ0Y2NiYWFiMDBhMWY4ZDRkYjYxIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5FbWVyeSBCYXJuZXMgKERvZyBQYXJrKTwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF8zYzIyYTAyZWE4Nzk0NTFmYmFiMDdlY2I5MTcwODkyOS5zZXRDb250ZW50KGh0bWxfYTUyMTY3NmRjOTZkNDRjY2JhYWIwMGExZjhkNGRiNjEpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzg3ODAwNzY5YTVjZTQ2YmI5NTk0MmM5NzMxZTEyNzUxLmJpbmRQb3B1cChwb3B1cF8zYzIyYTAyZWE4Nzk0NTFmYmFiMDdlY2I5MTcwODkyOSkKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMjM4MWMzODU4NGE3NDIwMDg1ZWIxMGNiNjI5OTFmZWMgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNjQwNzk5NzA0NDk4ODUsIC0xMjMuMTA4MDI5MzY1NTM5NTZdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogImdyZWVuIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogImdyZWVuIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF9jNjUyMDkyYTA3ZGQ0ZDdlOGQ5YWFlNDRkZWNlOTZmMiA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfOTdlNDU1N2MwOTY5NDllYWEyZGEwMWRkOWRiMjg3YTkgPSAkKGA8ZGl2IGlkPSJodG1sXzk3ZTQ1NTdjMDk2OTQ5ZWFhMmRhMDFkZDlkYjI4N2E5IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Kb25hdGhvbiBSb2dlcnMgUGFyazwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9jNjUyMDkyYTA3ZGQ0ZDdlOGQ5YWFlNDRkZWNlOTZmMi5zZXRDb250ZW50KGh0bWxfOTdlNDU1N2MwOTY5NDllYWEyZGEwMWRkOWRiMjg3YTkpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzIzODFjMzg1ODRhNzQyMDA4NWViMTBjYjYyOTkxZmVjLmJpbmRQb3B1cChwb3B1cF9jNjUyMDkyYTA3ZGQ0ZDdlOGQ5YWFlNDRkZWNlOTZmMikKICAgICAgICA7CgogICAgICAgIAogICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZGU3MWFkYmM4ZWM2NGQ0NWExNDZjNzM3YmViZTU1ZjcgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0OS4yNTQ2MTQzMzAwNDgyNTYsIC0xMjMuMTE0ODA2MzUxNDc1ODVdLAogICAgICAgICAgICAgICAgeyJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwgImNvbG9yIjogImdyZWVuIiwgImRhc2hBcnJheSI6IG51bGwsICJkYXNoT2Zmc2V0IjogbnVsbCwgImZpbGwiOiB0cnVlLCAiZmlsbENvbG9yIjogImdyZWVuIiwgImZpbGxPcGFjaXR5IjogMC42LCAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsICJsaW5lQ2FwIjogInJvdW5kIiwgImxpbmVKb2luIjogInJvdW5kIiwgIm9wYWNpdHkiOiAxLjAsICJyYWRpdXMiOiA1LCAic3Ryb2tlIjogdHJ1ZSwgIndlaWdodCI6IDN9CiAgICAgICAgICAgICkuYWRkVG8obWFwX2Q0YzlmYjdjNWI1ZDRhMDM5YmJjZTBiMGI5MGY4ZTc5KTsKICAgICAgICAKICAgIAogICAgICAgIHZhciBwb3B1cF8xNGNjNjUzNzM4MTg0OTAzOGQ5NjE5MjQ4ZGNlYWIzZSA9IEwucG9wdXAoeyJtYXhXaWR0aCI6ICIxMDAlIn0pOwoKICAgICAgICAKICAgICAgICAgICAgdmFyIGh0bWxfNmQ2Nzk0NTZmYWYyNDMyNzk3MTkwZDA1NDhkOTJmMjkgPSAkKGA8ZGl2IGlkPSJodG1sXzZkNjc5NDU2ZmFmMjQzMjc5NzE5MGQwNTQ4ZDkyZjI5IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5QYXJrIFRoZWF0cmU8L2Rpdj5gKVswXTsKICAgICAgICAgICAgcG9wdXBfMTRjYzY1MzczODE4NDkwMzhkOTYxOTI0OGRjZWFiM2Uuc2V0Q29udGVudChodG1sXzZkNjc5NDU2ZmFmMjQzMjc5NzE5MGQwNTQ4ZDkyZjI5KTsKICAgICAgICAKCiAgICAgICAgY2lyY2xlX21hcmtlcl9kZTcxYWRiYzhlYzY0ZDQ1YTE0NmM3MzdiZWJlNTVmNy5iaW5kUG9wdXAocG9wdXBfMTRjYzY1MzczODE4NDkwMzhkOTYxOTI0OGRjZWFiM2UpCiAgICAgICAgOwoKICAgICAgICAKICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzVjNjZmNzRkMzdiODQzMThiNzhmYjNhMTViM2FlMGM5ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDkuMjMwNzEzNjUyNTQzNzA2LCAtMTIzLjA4NjMxODQ1NDE4MTk5XSwKICAgICAgICAgICAgICAgIHsiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsICJjb2xvciI6ICJncmVlbiIsICJkYXNoQXJyYXkiOiBudWxsLCAiZGFzaE9mZnNldCI6IG51bGwsICJmaWxsIjogdHJ1ZSwgImZpbGxDb2xvciI6ICJncmVlbiIsICJmaWxsT3BhY2l0eSI6IDAuNiwgImZpbGxSdWxlIjogImV2ZW5vZGQiLCAibGluZUNhcCI6ICJyb3VuZCIsICJsaW5lSm9pbiI6ICJyb3VuZCIsICJvcGFjaXR5IjogMS4wLCAicmFkaXVzIjogNSwgInN0cm9rZSI6IHRydWUsICJ3ZWlnaHQiOiAzfQogICAgICAgICAgICApLmFkZFRvKG1hcF9kNGM5ZmI3YzViNWQ0YTAzOWJiY2UwYjBiOTBmOGU3OSk7CiAgICAgICAgCiAgICAKICAgICAgICB2YXIgcG9wdXBfZjA2YWE4MThmMDIyNGUzY2EzNGQ4MDZjM2NlOWI2NzggPSBMLnBvcHVwKHsibWF4V2lkdGgiOiAiMTAwJSJ9KTsKCiAgICAgICAgCiAgICAgICAgICAgIHZhciBodG1sXzA1NjRhYjdiNjYxNTRkMDk5MTVhYjgwNmM3NDFkYzU0ID0gJChgPGRpdiBpZD0iaHRtbF8wNTY0YWI3YjY2MTU0ZDA5OTE1YWI4MDZjNzQxZGM1NCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+TWVtb3JpYWwgU291dGggUGFyazwvZGl2PmApWzBdOwogICAgICAgICAgICBwb3B1cF9mMDZhYTgxOGYwMjI0ZTNjYTM0ZDgwNmMzY2U5YjY3OC5zZXRDb250ZW50KGh0bWxfMDU2NGFiN2I2NjE1NGQwOTkxNWFiODA2Yzc0MWRjNTQpOwogICAgICAgIAoKICAgICAgICBjaXJjbGVfbWFya2VyXzVjNjZmNzRkMzdiODQzMThiNzhmYjNhMTViM2FlMGM5LmJpbmRQb3B1cChwb3B1cF9mMDZhYTgxOGYwMjI0ZTNjYTM0ZDgwNmMzY2U5YjY3OCkKICAgICAgICA7CgogICAgICAgIAogICAgCjwvc2NyaXB0Pg== onload="this.contentDocument.open();this.contentDocument.write(atob(this.getAttribute('data-html')));this.contentDocument.close();" allowfullscreen webkitallowfullscreen mozallowfullscreen></iframe></div></div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Maps-Description:">Maps Description:<a class="anchor-link" href="#Maps-Description:">&#182;</a></h1><h5 id="Purpule-circles:-Bus-stops"><strong>Purpule circles</strong>: <em>Bus stops</em><a class="anchor-link" href="#Purpule-circles:-Bus-stops">&#182;</a></h5><h5 id="Yellow-circles:-Metro-Stations"><strong>Yellow circles</strong>: <em>Metro Stations</em><a class="anchor-link" href="#Yellow-circles:-Metro-Stations">&#182;</a></h5><h5 id="Red-circles:-Hotels-with-overall-rank-of-7-or-greater"><strong>Red circles</strong>: <em>Hotels with overall rank of 7 or greater</em><a class="anchor-link" href="#Red-circles:-Hotels-with-overall-rank-of-7-or-greater">&#182;</a></h5><h5 id="orange-circles:-Restaurants-with-overall-rank-of-7-or-greater"><strong>orange circles</strong>: <em>Restaurants with overall rank of 7 or greater</em><a class="anchor-link" href="#orange-circles:-Restaurants-with-overall-rank-of-7-or-greater">&#182;</a></h5><h5 id="Green-circles:-Urban-areas(In-this-case,-parks)-with-overall-rank-of-7-or-greater"><strong>Green circles</strong>: <em>Urban areas(In this case, parks) with overall rank of 7 or greater</em><a class="anchor-link" href="#Green-circles:-Urban-areas(In-this-case,-parks)-with-overall-rank-of-7-or-greater">&#182;</a></h5>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h5 id="Reporter-github:--https://github.com/spacelover92"><strong>Reporter github</strong>:  <em><a href="https://github.com/spacelover92">https://github.com/spacelover92</a></em><a class="anchor-link" href="#Reporter-github:--https://github.com/spacelover92">&#182;</a></h5><h5 id="Creation-Date:-October-25,-2020"><strong>Creation Date</strong>: October 25, 2020<a class="anchor-link" href="#Creation-Date:-October-25,-2020">&#182;</a></h5>
</div>
</div>
</div>
    </div>
  </div>
</body>

 


</html>
