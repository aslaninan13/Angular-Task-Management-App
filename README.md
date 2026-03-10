# Task Managing App #

ps - f
ps aux
ps aux - - sort:-pcpu
ps -o pid
kill 
kill
ps aux | head -5
ps aux - -sort:-pcpu
ps aux - -sort:-pcpu | head -5
touch infloop
ls
nano infloop
rm infloop
touch intloop.c
nano infloop.c
gcc infloop.c -o output
./output & 
ps -o pmem
ps aux - -sort:-pcpu | watch -n 1 ‘ps -e -o pid,pcpu,pmem’

nano infloop.c
ps aux - -sort:-pcpu | head-15 | watch -n 1 ‘ps -e -o pid,pcpu,pmem’

watch -n 1 ‘ps -e -o pid,pcpu,pmem,uname’ | head -15 | ps aux - -sort:-pcpu

kill -STOP 9855
kill -CONT 9855
kill 9855
