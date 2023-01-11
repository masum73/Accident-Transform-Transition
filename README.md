Using Transform Transition Translate CSS Properties

Self Notes: 
/* transition 1 X axis borabor samne jai */
transition: transform 2s ease-in 0.3s;  
           
 /* transition 2 X axis borabor pichone jai and rotate kore 20 degree */
transition: transform 3s ease-out 2s;
            
/* transition 3 multiple transform hoi tokhon samne o jai and rotate o hoi ..shob hoi + - 200px 130 px kore 70px */
transition: transform 3s ease-out 2s; 

/* translate only 1 bar e kaj hobe multiple translate hobe na ... multiple chaile tokhon animation diye kora lagbe purata  */


/* transition 3 - translateX(70px) e kaj kortese + - kore  */
transform: translateX(200px) rotate(20deg) translateX(-130px); 