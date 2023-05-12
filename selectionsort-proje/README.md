<h1> Insertion Sort Project</h1> 
<h1>Soru 1 </h1> 
<p> [22,27,16,2,18,6] -> Insertion Sort </p>
<p> Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.</p>
<h1> Cevap: </h1> 
<ul>  
<li> Verilen örüntüye ait en küçük eleman olan 2'yi en baştaki sayı olan 22 ile değiştiriyoruz. [22,27,16,2,18,6] -->  [2,27,16,22,18,6] </li>
<li> İkinci olarak en küçük elemanımız 6 olduğu için 27 ile yer değiştiriyoruz. [2,27,16,22,18,6] -->  [2,6,16,22,18,27] </li>
<li> 16 sayısından sonra en küçük 18 olduğu için 22 ile yer değiştiriyoruz. [2,27,16,22,18,6] -->  [2,6,16,18,22,27] </li>
<li> Finalde sıralamamız bu şekilde oluyor: [2,6,16,18,22,27] </li>
</ul> 
<h1> Soru 2 </h1>
<p> Big-O gösterimini yazınız. </p>
<h1> Cevap: </h1> 
<p> n(n+1)/2 ---> o(n^2) </p>
<h1> Soru 3 </h1>
<p> Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız. </p>
<h1> Cevap:</h1> 
<p> [2,6,16,18,22,27] ---> 18 sayısı burada ortada bulunduğu için Avarage case kapsamına girer. </p>
<p> Avarage case:  Aradığımız sayının ortada olması </p>
<h1> Soru 4 </h1>
<p> [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız. </p>
<h1> Cevap: </h1> 
<p> [7,3,5,8,2,9,4,15,6] <strong>n</strong></p>
<p> [2,3,5,8,7,9,4,15,6] <strong>n-1</strong></p>
<p> [2,3,4,8,7,9,5,15,6] <strong>n-2</strong></p>
<p> [2,3,4,5,7,9,8,15,6] <strong>n-3</strong></p>



