# AI.md
**Proje Adı:** Sort the Court - Karakterli Versiyon  
**Danışman:** ChatGPT  
**Hazırlayan:** Fatemehzahra Mohammadi


---

Soru 1:  
**Soru:** Basit bir Sort the Court tarzı oyun yapmak istiyorum. HTML Canvas kullanmak mantıklı mı?  
**Yanıt:** Evet, HTML5 Canvas bu tarz 2D etkileşimli oyunlar için uygundur. Kullanıcı arayüzü, karakterler ve oyun döngüsü bu yapı üzerinden kurgulanabilir.

---

 Soru 2:  
**Soru:** Sorulara göre kullanıcıya "Evet" ve "Hayır" seçenekleri sunmak istiyorum. Bu seçimlere göre altın, mutluluk ve halk sayısı gibi değerleri değiştireceğim. Bunu nasıl organize etmeliyim?  
**Yanıt:** Her soru için karakter, metin, "evet/hayır" etkileri ve skor gibi bilgileri içeren bir nesne tanımlayarak bir liste oluşturman önerildi.

---

Soru 3:  
**Soru:** Karakterleri ekranda göstermek istiyorum. Canvas üzerinden nasıl çizmeliyim?  
**Yanıt:** `Image()` nesnesi ile görseller yüklenip `drawImage()` ile canvas'a çizilebileceği belirtildi.

---

Soru 4:  
**Soru:** Sorular metin kutusunda yazı efektiyle harf harf görünsün istiyorum. Bu nasıl yapılabilir?  
**Yanıt:** `setInterval` ile metni her birkaç milisaniyede bir harf artırarak gösterme yöntemi önerildi.

---

Soru 5:  
**Soru:** Klavye tuşlarıyla kontrol eklemek istiyorum. Örneğin sağ ok = evet, sol ok = hayır gibi. Bu mümkün mü?  
**Yanıt:** Evet, `keydown` olay dinleyicisi ile tuşlara özel seçimler yapılabileceği ifade edildi.

---

Soru 6:  
**Soru:** Oyun bittiğinde yeniden başlatma butonu görünmeli. Diğer butonlar gizlenmeli. Bunu nasıl kontrol ederim?  
**Yanıt:** DOM üzerinden `style.display` ile butonların görünürlüğü kontrol edilerek dinamik geçiş sağlanabileceği belirtildi.
