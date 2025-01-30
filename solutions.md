p1-b: tar -xvzf challenges.tar.gz
p2-b: cd challenges

p3-b: ls challenges
p4-b: mkdir foo
p5-b: mkdir -p foo/bar/1/2/3
p6-b: rm -rf foo
p7-b: echo "Hello World"
p8-b: echo "Hello World" > hello.txt
p9-b: touch empty.txt
p10-b: rm empty.txt
p11-b: > empty.txt
p12-b: echo -n > empty.txt
p13-b: cp hello.txt goodbye.txt
p14-b: mv goodbye.txt hello_copy.txt
p15-b: cmp hello.txt hello_copy.txt
p16-b: cat hello.txt hello_copy.txt > 2_hellos.txt
p17-b: pwd
p18-b: ls -l challenges
p19-b: echo "Text to append" >> restricted.txt
p20-b: ./hello_executable
p21-b: ./challenge_20
p22-b: gcc compile_me.c -o compile_me && ./compile_me
p23-b: ./redirect > output.txt
p24-b: date
p25-b: ps
p26-b: nproc
p27-b: uname -r
p28-b: grep -rl "You found the needle in the haystack!" bunch_of_files/
p29-b: head -n 25 people.csv
p30-b: tail -n 25 people.csv
p31-b: diff greeting1.txt greeting2.txt
p32-b: echo "Hello"; sleep 5; echo "world!"
p33-b: dd if=/dev/zero of=zero_file bs=1M count=1
p34-b: dd if=/dev/urandom of=random_file bs=1M count=2
p35-b: wc -l README.txt
p36-b: tac README.txt
p37-b: cut -d',' -f2 people.csv
p38-b: cut -d',' -f2 people.csv | sort -u | wc -l
p39-b: cut -d',' -f2 people.csv | sort -u | tail -n +2 | wc -l