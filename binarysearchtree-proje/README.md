<h1> Binary Search Tree Project - Proje 3 </h1>
<p> Soru: </p>
<p> [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. </p>
<p> Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb. </p>

        5            ---> Root düğümümüz 5
      /   \
     4     8          
    / \   / \
   2   6 7   9
  / \   /
 0   3 1
<p> Kendisinden büyük olan değerler sağ düğüme küçük olanlar ise sol düğümden bulunur. </p>
<p> '4' değeri '5' dan küçük olduğu için sol düğüme girilmiştir '8' değeri '5' dan büyük olduğu için sağ düğüme girilmiştir geri kalan değerlerde aynı durum geçerlidir. '7' değeri '8' den küçük olduğu için 8 'in sol düğümüne yazılmıştır. '9' değeri '8' den büyük olduğu için sağ düğümüne yazılmıştır gibi. </p>
