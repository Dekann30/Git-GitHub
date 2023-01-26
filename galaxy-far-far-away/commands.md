# In a Galaxy Far far Away


### Directions

1. Create a directory called death_star, and make the following files inside of it: darth_vader.txt, princess_leia.txt, storm_trooper.txt
2. In galaxy-far-far-away, make a directory named tatooineand create the following files in it: luke.txt, ben_kenobi.txt
3. Inside of tatooinemake a directory called millenium_falcon, and in it create: han_solo.txt, chewbaca.txt
4. Rename ben_kenobi.txt to obi_wan.txt
5. Copy storm_trooper.txt from death_star to tatooine
6. Move luke.txtand obi_wan.txtto the millenium_falcon
7. Move millenium_falconout of tatooineand into galaxy-far-far-away
8. Move millenium_falconinto death_star
9. Move princess_leia.txtinto the millenium_falcon
10. Delete obi_wan.txt

### Terminal Commands

1. mkdir death_star -> cd death_star -> touch darth_vader.txt princess_leia.txt storm_trooper.txt
2. cd .. -> mkdir tatooine -> cd tatooine -> touch luke.txt ben_kenobi.txt
3. mkdir millenium_falcon -> cd millenium_falcon -> touch han_solo.txt chewbaca.txt
4. mv ben_kenobi.txt obi_wan.txt
5. cp death_star/storm_trooper.txt tatooine/
6. cd tatooine/ -> mv luke.txt obi_wan.txt millenium_falcon/
7. cd .. -> cd .. -> cd .. -> mv galaxy-far-far-away/tatooine/millenium_falcon/ ... galaxy-far-far-away
8. mv millenium_falcon/ ... death_star/
9. cd death_star/ -> mv princess_leia.txt millenium_falcon/
10. rm millenium_falcon/obi_wan.txt