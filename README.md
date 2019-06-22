# Tutorial-Blogger
Buat Blogger Gan


Course snippet untuk blogger

Tambahkan script json-ld berikut ke bagian head (html template)

<script type='application/ld+json'>{"@context": "https://schema.org", "@type": "Course","name": "<data:blog.pageTitle/>","description": "<data:blog.metaDescription/>","provider":{"@type": "Organization","name": "<data:blog.title/>","URL": "<data:blog.homepageUrl/>"}}</script>

Save, untuk melihat bagaimana ini bekerja, uji struktur data halaman, lihat tab pertinjau.

Jika erroe, atau tertera can't fine subtitution tag, tambahkan meta tag berikut ke bagian head.

<meta expr:content='data:blog.pageTitle' itemprop='name'/>

<meta expr:content='data:blog.metaDescription' itemprop='description'/>

Pastikan setiap post memiliki teks deskripsi



<p align="center">
<img src="https://raw.githubusercontent.com/sadcode-org/Tutorial-Blogger/master/FB_IMG_1561203675530.jpg">
</a>
</p>
<br>
<br>
<p align="center">
<img src="https://raw.githubusercontent.com/sadcode-org/Tutorial-Blogger/master/FB_IMG_1561203679655.jpg"></a>
</p>
