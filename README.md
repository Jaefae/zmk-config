# Xerneas
![alt text](https://github.com/Jaefae/zmk-config/blob/main/shinyxerneas.png?raw=true)
## Disclaimer
This is my personal configuration I use for the Sweep Bling LP (Shoutout KeebMaker)
## Layout
I use homerow mods with the main two layers of use being
### Layer 1

        //╭──────────┬──────────┬──────────┬──────────┬──────────╮   ╭──────────┬──────────┬──────────┬──────────┬──────────╮
        //│  W       │  L       │  Y       │  P       │  B       │   │  Z       │  F       │  O       │  U       │  ' "     │
            &kp W      &kp L      &kp Y      &kp P      &kp B          &kp Z      &kp F      &kp O      &kp U      &kp SQT
        //├──────────┼──────────┼──────────┼──────────┼──────────┤   ├──────────┼──────────┼──────────┼──────────┼──────────┤
        //│  C       │  R       │  S       │  T       │  G       │   │  M       │  N       │  E       │  I       │  A       │
            HRML(C,        R,         S,         T)     &kp G          &kp M      HRMR(N,        E,         I,        A)
        //├──────────┼──────────┼──────────┼──────────┼──────────┤   ├──────────┼──────────┼──────────┼──────────┼──────────┤
        //│  Q       │  J       │  V       │  D       │  K       │   │ X        │  H       │ / ?      │  ,       │  .       │
            &kp Q      &kp J      &kp V      &kp D      &kp K          &kp X      &kp H      &kp FSLH  &kp COMMA   &kp DOT
        //╰──────────┴──────────┴──────────┼──────────┼──────────┤   ├──────────┼──────────┼──────────┴──────────┴──────────╯
                                            &lt 2 TAB   &kp ENTER     &kp SPACE  &lt 1 BSPC
        //                                 ╰──────────┴──────────╯   ╰──────────┴──────────╯
### Layer 2

        //╭──────────┬──────────┬──────────┬──────────┬──────────╮   ╭──────────┬──────────┬──────────┬──────────┬──────────╮
        //│ INSERT   │  1       │  2       │  3       │          │   │ HOME     │ PAGE DN  │ PAGE UP  │ END      │  :       │
            &kp INS    &kp N1     &kp N2     &kp N3     &trans         &kp HOME   &kp PG_DN  &kp PG_UP  &kp END    &kp COLON
        //├──────────┼──────────┼──────────┼──────────┼──────────┤   ├──────────┼──────────┼──────────┼──────────┼──────────┤
        //│ DELETE   │  4       │  5       │  6       │          │   │ LEFT     │ DOWN     │ UP       │ RIGHT    │  ;       │
            &kp DEL    &kp N4     &kp N5     &kp N6     &trans         &kp LEFT   &kp DOWN   &kp UP   &kp RIGHT   &kp SEMI
        //├──────────┼──────────┼──────────┼──────────┼──────────┤   ├──────────┼──────────┼──────────┼──────────┼──────────┤
        //│ CAPS     │  7       │  8       │  9       │  0       │   │          │          │          │          │          │
           &caps_word  &kp N7     &kp N8     &kp N9     &kp N0         &trans     &trans     &trans     &trans     &trans
        //╰──────────┴──────────┴──────────┼──────────┼──────────┤   ├──────────┼──────────┼──────────┴──────────┴──────────╯
                                             &trans     &kp ESC        &trans     &trans
        //                                 ╰──────────┴──────────╯   ╰──────────┴──────────╯
            
