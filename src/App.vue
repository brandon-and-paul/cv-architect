<template>
  <Resume />
</template>

<script>
import Resume from "./components/Resume";
import Form from "./components/Form";

export default {
  components: { Resume, Form },
  mounted() {
    console.log(30);
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@300;500;700&display=swap');

:root {
    /* CSS HEX */
--black-coral: #5e6472ff;
--atomic-tangerine: #f79256ff;
--light-slate-gray: #668b99ff;
--maximum-blue: #6db1bfff;
--thistle: #d0bcd5ff;
--gold-crayola: #f9c784ff;
--maize-crayola: #e2c044ff;
--pale-purple-pantone: #f1e3f3ff;
--xanadu: #7d8881ff;
--dark-green: #082d0fff;

/* CSS HSL */
--black-coral: hsla(222, 10%, 41%, 1);
--atomic-tangerine: hsla(22, 91%, 65%, 1);
--light-slate-gray: hsla(196, 20%, 50%, 1);
--maximum-blue: hsla(190, 39%, 59%, 1);
--thistle: hsla(288, 23%, 79%, 1);
--gold-crayola: hsla(34, 91%, 75%, 1);
--maize-crayola: hsla(47, 73%, 58%, 1);
--pale-purple-pantone: hsla(293, 40%, 92%, 1);
--xanadu: hsla(142, 4%, 51%, 1);
--dark-green: hsla(131, 70%, 10%, 1);

/* SCSS HEX */
$black-coral: #5e6472ff;
$atomic-tangerine: #f79256ff;
$light-slate-gray: #668b99ff;
$maximum-blue: #6db1bfff;
$thistle: #d0bcd5ff;
$gold-crayola: #f9c784ff;
$maize-crayola: #e2c044ff;
$pale-purple-pantone: #f1e3f3ff;
$xanadu: #7d8881ff;
$dark-green: #082d0fff;

/* SCSS HSL */
$black-coral: hsla(222, 10%, 41%, 1);
$atomic-tangerine: hsla(22, 91%, 65%, 1);
$light-slate-gray: hsla(196, 20%, 50%, 1);
$maximum-blue: hsla(190, 39%, 59%, 1);
$thistle: hsla(288, 23%, 79%, 1);
$gold-crayola: hsla(34, 91%, 75%, 1);
$maize-crayola: hsla(47, 73%, 58%, 1);
$pale-purple-pantone: hsla(293, 40%, 92%, 1);
$xanadu: hsla(142, 4%, 51%, 1);
$dark-green: hsla(131, 70%, 10%, 1);

/* SCSS RGB */
$black-coral: rgba(94, 100, 114, 1);
$atomic-tangerine: rgba(247, 146, 86, 1);
$light-slate-gray: rgba(102, 139, 153, 1);
$maximum-blue: rgba(109, 177, 191, 1);
$thistle: rgba(208, 188, 213, 1);
$gold-crayola: rgba(249, 199, 132, 1);
$maize-crayola: rgba(226, 192, 68, 1);
$pale-purple-pantone: rgba(241, 227, 243, 1);
$xanadu: rgba(125, 136, 129, 1);
$dark-green: rgba(8, 45, 15, 1);

/* SCSS Gradient */
$gradient-top: linear-gradient(0deg, #5e6472ff, #f79256ff, #668b99ff, #6db1bfff, #d0bcd5ff, #f9c784ff, #e2c044ff, #f1e3f3ff, #7d8881ff, #082d0fff);
$gradient-right: linear-gradient(90deg, #5e6472ff, #f79256ff, #668b99ff, #6db1bfff, #d0bcd5ff, #f9c784ff, #e2c044ff, #f1e3f3ff, #7d8881ff, #082d0fff);
$gradient-bottom: linear-gradient(180deg, #5e6472ff, #f79256ff, #668b99ff, #6db1bfff, #d0bcd5ff, #f9c784ff, #e2c044ff, #f1e3f3ff, #7d8881ff, #082d0fff);
$gradient-left: linear-gradient(270deg, #5e6472ff, #f79256ff, #668b99ff, #6db1bfff, #d0bcd5ff, #f9c784ff, #e2c044ff, #f1e3f3ff, #7d8881ff, #082d0fff);
$gradient-top-right: linear-gradient(45deg, #5e6472ff, #f79256ff, #668b99ff, #6db1bfff, #d0bcd5ff, #f9c784ff, #e2c044ff, #f1e3f3ff, #7d8881ff, #082d0fff);
$gradient-bottom-right: linear-gradient(135deg, #5e6472ff, #f79256ff, #668b99ff, #6db1bfff, #d0bcd5ff, #f9c784ff, #e2c044ff, #f1e3f3ff, #7d8881ff, #082d0fff);
$gradient-top-left: linear-gradient(225deg, #5e6472ff, #f79256ff, #668b99ff, #6db1bfff, #d0bcd5ff, #f9c784ff, #e2c044ff, #f1e3f3ff, #7d8881ff, #082d0fff);
$gradient-bottom-left: linear-gradient(315deg, #5e6472ff, #f79256ff, #668b99ff, #6db1bfff, #d0bcd5ff, #f9c784ff, #e2c044ff, #f1e3f3ff, #7d8881ff, #082d0fff);
$gradient-radial: radial-gradient(#5e6472ff, #f79256ff, #668b99ff, #6db1bfff, #d0bcd5ff, #f9c784ff, #e2c044ff, #f1e3f3ff, #7d8881ff, #082d0fff);
}

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Fira Code', monospace;
}

body {
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
