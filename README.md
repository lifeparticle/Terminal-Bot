# Terminal-Bot

```bash
echo \# 5. Number Generation        > Number\ Generation.md
echo \# 6. Fibonacci Series         > Fibonacci\ Series.md
echo \# 7. Combinatorics            > Combinatorics.md
echo \# 8. Dynamic Programming      > Dynamic\ Programming.md
echo \# 9. Greedy                   > Greedy.md
echo \# 10. Algorithm               > Algorithm.md
echo \# 11. Number Theory           > Number\ Theory.md
echo \# 12. Numerical Methods       > Numerical\ Methods.md
echo \# 13. Basics of Numbers       > Basics\ of\ Numbers.md
echo \# 14. Java                    > Java.md
echo \# 15. Computational Geometry  > Computational\ Geometry.md
echo \# 16. Math                    > Math.md
echo \# 17. Physics                 > Physics.md
echo \# 18. ASCII Table             > ASCII\ Table.md
```


```bash
for i in {15..50}; do
  mkdir "$i. "
done
```

```bash
declare -a array=("Number Generation" "Fibonacci Series" "Combinatorics" "Algorithm" "Number Theory" "Numerical Methods" "Basics of Numbers" "Java" "Computational Geometry" "Math" "Physics" "ASCII Table")

for ((i=1; i<${#array[@]}+1; ++i));
do
  echo "# $i. ${array[$i]}" > ${array[$i]}.md
done
```
