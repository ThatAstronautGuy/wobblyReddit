@-webkit-keyframes spaceboots { 0% { -webkit-transform: translate(2px, 1px) rotate(0deg); } 10% { -webkit-transform: translate(-1px, -2px) rotate(-0.5deg); } 20% { -webkit-transform: translate(-3px, 0px) rotate(0.5deg); } 30% { -webkit-transform: translate(0px, 2px) rotate(0deg); } 40% { -webkit-transform: translate(1px, -1px) rotate(0.5deg); } 50% { -webkit-transform: translate(-1px, 2px) rotate(-0.5deg); } 60% { -webkit-transform: translate(-3px, 1px) rotate(0deg); } 70% { -webkit-transform: translate(2px, 1px) rotate(-0.5deg); } 80% { -webkit-transform: translate(-1px, -1px) rotate(0.5deg); } 90% { -webkit-transform: translate(2px, 2px) rotate(0deg); } 100% { -webkit-transform: translate(1px, -2px) rotate(-0.5deg); }}
body *:hover { -webkit-animation-name: spaceboots; -webkit-animation-duration: 3s; -webkit-transform-origin:50% 50%; -webkit-animation-iteration-count: infinite; -webkit-animation-timing-function: linear;}
@keyframes spaceboots { 0% { transform: translate(2px, 1px) rotate(0deg); } 10% { transform: translate(-1px, -2px) rotate(-0.5deg); } 20% { transform: translate(-3px, 0px) rotate(0.5deg); } 30% { transform: translate(0px, 2px) rotate(0deg); } 40% { transform: translate(1px, -1px) rotate(0.5deg); } 50% { transform: translate(-1px, 2px) rotate(-0.5deg); } 60% { transform: translate(-3px, 1px) rotate(0deg); } 70% { transform: translate(2px, 1px) rotate(-0.5deg); } 80% { transform: translate(-1px, -1px) rotate(0.5deg); } 90% { transform: translate(2px, 2px) rotate(0deg); } 100% { transform: translate(1px, -2px) rotate(-0.5deg); }}
body *:hover { animation-name: spaceboots; animation-duration: 3s; transform-origin:50% 50%; animation-iteration-count: infinite; animation-timing-function: linear;}
