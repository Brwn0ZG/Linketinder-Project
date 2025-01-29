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