/\*_ @type {import('tailwindcss').Config} _/
module.exports = {
content: [(main address of js, html file)"./*.{html,js}"],
theme: {
screens: {
sm: "480px",
md: "768px",
lg: "976px",
xl: "1440px",
},
extend: {
colors: {
brightRed: "hsl(12,88%,59%)",
brightRedLight: "hsl(12,88%,69%)",
brightRedSupLight: "hsl(12,88%,95%)",
darkBlue: "hsl(228 ,39%, 23%)",
darkGrayishBlue: "hsl(227, 12% ,61 )",
veryDarkBlue: "hsl(223 ,12%, 13%)",
veryPaleRed: "hsl(13 ,100%, 96%)",
veryLightGray: "hsl(0,0%,98%)",
},
},
},
plugins: [],
};

# margin

m-3
mt mr mb ml
mx my
mx-auto

# flex

.flex.justify-between.items-center-->

<!-- <div class="flex justify-between items-center"></div> -->

flex-col-reverse

## spacing

0.5 =2px --> 1=4px
2px/4px/6px/8px
