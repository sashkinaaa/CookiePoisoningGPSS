# CookiePoisoningGPSS
GPSS simulator of Cookie Poisoning cyberattack

The time delay of each process (1-8) in Exp_PoisonCookies_attack.gps file is chosen as follows: T1 = T2 = T3 = T4 = T5 = T6 = T7 = T8 = 5 with exponential distribution. The processes are performed on digital equipment and they are more likely to complete in a short time period than in a long time period, hence all durations for the successful completion of the processes in steps (1-8) are chosen to have exponential distribution:	y=1-e^λt
Note that for the given model in PoisonCookies_attack.gps, the time delay for each process is chosen individually. Also, the chosen time delay distribution is exponential, but the model is invariant about these distributions (determined, uniform, exponential, etc.).
