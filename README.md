lightweight-java-profiler
=========================

参考：https://colobu.com/2016/08/10/Java-Flame-Graphs/

```	
make all
-agentpath:/usr/local/lightweight-java-profiler-read-only/build-64/liblagent.so

git clone http://github.com/brendangregg/FlameGraph
cd FlameGraph
./stackcollapse-ljp.awk < ../traces.txt | ./flamegraph.pl > ../traces.svg

```
