# Merge-Sort-Projesi-patika

https://app.patika.dev/varolius
https://app.patika.dev/paths
https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje


Proje 2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamaları:

1->[16,21,11]...[8,12,22]
2->[16,21]...[11]...[8,12]...[22]
3->[16]..[21]...[11]...[8]..[12]...[22]
4->[16,21]...[11]...[8,12]...[22]
5->[11,16,21]...[8,12,22]
6->[8,11,12,16,21,22]


Recursive fonsiyon oldugu için n defa ve sürekli 2ye böldügü için logndir => O(n*logn) 
Bu dizi icin n = 6 dir => O(6*log6)dir
