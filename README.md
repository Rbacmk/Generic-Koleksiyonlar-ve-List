# Generic-Koleksiyonlar-ve-List
// Generic Koleksiyonlar ve List
            // List<T>class
            // System.Collection.Generic= Namespace.
            // t-->Generic . Object türündedir.
            List <int> sayiListesi = new List <int>();
            sayiListesi.Add(29);
            sayiListesi.Add(30);
            sayiListesi.Add(50);
            sayiListesi.Add(40);
            sayiListesi.Add(35);
            sayiListesi.Add(21);

            List<string> Renkler = new List<string>();
            Renkler.Add("mavi");
            Renkler.Add("Kırmızı");
            Renkler.Add("Beyaz");
            Renkler.Add("Siyah");

            // Count = İçinde kaç tane eleman var .
            Console.WriteLine(Renkler.Count); 
            ///////
            ///Foreach ile ekrana yazdırabiliriz.
           /// foreach ve List.ForEach ile elemanlara erişim
          
            foreach (int renk in Renkler)
            {
                Console.WriteLine(renk);
            }
            Renkler.ForEach(renk >= Console.WriteLine(renk));
            //////
            ///
            //Listeden eleman çıkarma
            sayiListesi.Remove(30);
            sayiListesi.ForEach(sayiListesi => Console.WriteLine(sayi));
            sayiListesi.Remove(0); 0 ıncı indeksi sil.

                // Liste içerisinde arama.
            if (sayiListesi.Contains(10))
                Console.WriteLine("10 Liste içerisinde bulundu!.");
            // Eleman ile index'e erişme
            Renkler.BinanrySearch("Beyaz");// Beyaz rengin indexini getirir.
            // Diziyi listeye çevirmeye
            string[] hayvanlar = { "kedi", "köpek", "Kuş", "maymun" };
           List<string> hayvanlarListesi = new List<string> List<string>(hayvanlar);
            // Listeyi nasıl temizlerim ?
            hayvanlarListesi.Clear();


            // Liste içerisinde nesne tutmak.
            List<Kullanıcılar> kullanıcıListesi = new List<Kullanıcılar>();
            Kullanıcılar kullanıcı1 = new Kullanıcılar();
            kullanıcı1.Isım = "Rabia";
            kullanıcı1.Soyisim = "Çakmak";
            kullanıcı1.Yas = 34;
            kullanıcı1.Add(kullanıcı1); // Atadım.
            // Public erişime açık. Private kapalıdır.
            public class Kullanıcılar
        {
            private string isim;
           private  string soyisim;
            private int yas;

            public string İsim { get => isim; set => isim = value; }

            public string Soyisim { get => soyisim; set => soyisim = value; }
            public int Yas { get => yas; set => yas = value; }
        }
