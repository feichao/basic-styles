### Base Style

```
/* 覆盖默认盒模型 */
* {
  box-sizing: border-box;
  outline: none;
}

/* 统一样式 */
html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
  margin: 0;
  padding: 0;
  border: 0;
  vertical-align: middle;
}

/* 兼容旧浏览器 */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}

body {
  line-height: 1;
}

ol,
ul {
  list-style: none;
}

blockquote,
q {
  quotes: none;
}

blockquote:before,
blockquote:after,
q:before,
q:after {
  content: '';
  content: none;
}

/* table默认边框设置 */
table {
  border-collapse: collapse;
  border-spacing: 0;
}

/* 图片默认宽度为100% */
img {
  border-style: none;
  width: 100%;
}

hr {
  border: none;
  border-top: 1px solid #e0e0e0;
  margin: 0;
}

hr.dashed {
  border-top: 1px dashed #e0e0e0;
}

.hidden {
  display: none !important;
}

/* 设置父元素的overflow可避免因浮动塌陷 */
.o-f-hidden {
  overflow: hidden;
}

.fo-left {
  float: left !important;
}

.fo-right {
  float: right !important;
}

.c-pointer {
  cursor: pointer;
}

/* 文字单行省略 */
.ellipsis {
  display: block;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

.tx-center {
  text-align: center !important;
}

.clear {
  clear: both;
}

.clear-right {
  clear: right;
}

.clear-left {
  clear: left;
}

.clear-fix:after {
  clear: both;
  content: '';
  display: block;
}

.unuser-select {
  -moz-user-select: none;
  -webkit-user-select: none;
  -ms-user-select: none;
}

/* margin padding 超级有用 */
.no-margin {
  margin: 0 !important;
}

.margin-auto {
  margin: auto;
}

.no-padding {
  padding: 0 !important;
}

.mgl0 {
  margin-left: 0 !important;
}

.mgl1 {
  margin-left: 10px !important;
}

.mgl2 {
  margin-left: 20px !important;
}

.mgl3 {
  margin-left: 30px !important;
}

.mgl4 {
  margin-left: 40px !important;
}

.mgr0 {
  margin-right: 0 !important;
}

.mgr1 {
  margin-right: 10px !important;
}

.mgr2 {
  margin-right: 20px !important;
}

.mgr3 {
  margin-right: 30px !important;
}

.mgr4 {
  margin-right: 40px !important;
}

.mgt0 {
  margin-top: 0 !important;
}

.mgt1 {
  margin-top: 10px !important;
}

.mgt2 {
  margin-top: 20px !important;
}

.mgt3 {
  margin-top: 30px !important;
}

.mgt4 {
  margin-top: 40px !important;
}

.mgb0 {
  margin-bottom: 0 !important;
}

.mgb1 {
  margin-bottom: 10px !important;
}

.mgb2 {
  margin-bottom: 20px !important;
}

.mgb3 {
  margin-bottom: 30px !important;
}

.mgb4 {
  margin-bottom: 40px !important;
}

.pdl0 {
  padding-left: 0 !important;
}

.pdl1 {
  padding-left: 10px !important;
}

.pdl2 {
  padding-left: 20px !important;
}

.pdl3 {
  padding-left: 30px !important;
}

.pdl4 {
  padding-left: 40px !important;
}

.pdr0 {
  padding-right: 0 !important;
}

.pdr1 {
  padding-right: 10px !important;
}

.pdr2 {
  padding-right: 20px !important;
}

.pdr3 {
  padding-right: 30px !important;
}

.pdr4 {
  padding-right: 40px !important;
}

.pdt0 {
  padding-top: 0 !important;
}

.pdt1 {
  padding-top: 10px !important;
}

.pdt2 {
  padding-top: 20px !important;
}

.pdt3 {
  padding-top: 30px !important;
}

.pdt4 {
  padding-top: 40px !important;
}

.pdb0 {
  padding-bottom: 0 !important;
}

.pdb1 {
  padding-bottom: 10px !important;
}

.pdb2 {
  padding-bottom: 20px !important;
}

.pdb3 {
  padding-bottom: 30px !important;
}

.pdb4 {
  padding-bottom: 40px !important;
}
```
