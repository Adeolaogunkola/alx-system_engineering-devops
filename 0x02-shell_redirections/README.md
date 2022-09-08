1. echo 'Hello, World'
2. echo "\"(Ôo)'" 
3. cat /etc/passwd   
4. cat /etc/passwd /etc/hosts 
5. tail -n 10 /etc/passwd   
6. head -n 10 /etc/passwd 
7. head -n 3 iacta | tail -n 1   
8. echo "Best School" >\*\\'"Best School"\'\\*$\?\*\*\*\*\*:) 
9. ls -la > ls_cwd_content
10. tail -n 1 iacta >> iacta 
11. find . -type f -name "*.js" -delete
12. find . -type d -not -name '.' | wc -l 
13. ls -t1 | head -n 10
14. sort | uniq -u 
15. grep -i "root" /etc/passwd 
16. grep -c -i "bin" /etc/passwd 
17. grep -i "root" -A 3 /etc/passwd 
18. grep -i -v "bin" /etc/passwd 
19. grep -i "^[a-z]" /etc/ssh/sshd_config 
20. tr "A" "Z" | tr "c" "e" 21. tr -d "cC" 
22. rev
23. cut -d ':' -f 1,6 /etc/passwd | sort 
24. find . -empty | rev | cut -d '/' -f 1 | rev 
25. find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f 
26. cut -c 1 | paste -s -d '' 27. tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev | cut -d ' ' -f -1 | rev 
