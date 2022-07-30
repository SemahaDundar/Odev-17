# Odev-17
-Template Literals (şablon dizileri)

=>https://codesandbox.io/s/old-snowflake-o9m4zr?file=/src/index.js
const isim = `Elif`;
const mesaj = `Lise ogrencisi, ${isim}`;

console.log(mesaj);

const birim_fiyat = 180;
const adet = 6;
const satis_adet = 42;

const toplam_tutar = `Toplam: ${birim_fiyat * adet} ${satis_adet}`;//Toplam: 1080 42 

console.log(toplam_tutar);//Lise ogrencisi, Elif 



=>https://codesandbox.io/s/pedantic-tree-q90mtn?file=/src/index.js:296-436
const ders_isim = "İngilizce";
const ogrenci_sayisi = 7;

const toplam_ders = { ders_isim, ogrenci_sayisi };

console.log(toplam_ders);//{ders_isim: "İngilizce", ogrenci_sayisi: 7}
//ders_isim: "İngilizce"
//ogrenci_sayisi: 7


//https://codesandbox.io/s/flamboyant-joana-0i8ift?file=/src/index.js:299-556
bolum(28, 5);
function bolum(sayi1, sayi2) {
  return sayi1 * sayi2;
}

console.log(28 / 5);//5.6

islem(36, 6);
let islem = (sayi1, sayi2) => {
  return sayi1 - sayi2;
};
console.log(islem);

const topla = (sayi1, sayi2) => sayi1 + sayi2;
console.log(35 + 55);//hata verdi




=>https://codesandbox.io/s/competent-rain-8u0kx5?file=/src/index.js:390-712

const musteri = { ad: "Feride", soyad: "Aydin", meslek: "Dis hekimi" };

const { ad, soyad, meslek } = musteri;

console.log(ad);//Feride 
console.log(soyad);//Aydin 
console.log(meslek);//Dis hekimi 

const liste = { isim: "Neriman", meslek: "ogretmen", sehir: "İzmir"};
const { isim, ...kalanlar} = liste;

console.log(isim);//Neriman 
console.log(kalanlar);//Neriman {meslek: "ogretmen", sehir: "İzmir"}





Object/Array Destructuring (obje/dizilerin parçalarına bölünüp değişkenlere atanması)


=>https://codesandbox.io/s/affectionate-dust-cgxuot?file=/src/index.js

const siparislistesi = {romanKitap: 8, kalem: 22, silgi: 6, dergi: 4  };
const toplamFiyat {romanKitap, kalem, silgi, dergi} = siparisListesi;

console.log(dergi);

console.log(kalem);
console.log(romanKitap);
console.log(silgi);



=>https://codesandbox.io/s/broken-wind-xbr8vb?file=/src/index.js:299-830
export default fumction App(){
  const deger = { ilk: 1, artis: 4};
  const artis = (zikirMatik, matik = deger) =>{
    console.log(matik);
    return sayac.baslangic + zikirMatik * matik.artis;
  };

  return(
    <div className="App">
    <h1>Merhaba</h1>
    <button onClick={()=>{
      console.log(matik(10,{baslangic:1, artis: 30 }));
  }} ></button>
  Goster1
     </div>
  )
}

      </button>
      <button onClick={() =>{
        console.log(artis(20));

      }}
      >
        Goster2
      </button>


    </div>
  }






//Ternary Conditional Operators (üç değişkenli koşul operatörleri)
=>https://codesandbox.io/s/falling-glitter-g5fz59?file=/src/index.js:299-632
 let pastaNeyli =  "cikolata"; 
pastaNeyli == "cikolata" ? console.log("pasta cikolatali") : console.log("pasta cikolatalı degil");

let pastaDaNeVar = "frambuaz";
pastaDaNeVar == "frambuaz"? console.log("pasta frambuazli"): console.log("pasta frambuazli degil");
















