# Markdown faylı necə yaradılmalıdır? Markodown faylında hansı yazılış üsulları var?

# Başlıqlar
Başlıq yaratmaq üçün #başlıq mətnindən əvvəl heş (dies və ya türmə :D) simvol əlavə edin. İstifadə etdiyiniz nömrə #başlığın ölçüsünü müəyyən edəcək.

Məsələn:
# başlıq ən böyükdür və tək diesdən istifadə edə bilərsiniz
## ikinci böyük başlıqdır və iki diesdən istifadə edə bilərsiniz
### üçüncü başlıqdır və üç diesdən istifadə edə bilərsiniz
#### dördüncü başlıqdır və dörd diesdən istifadə edə bilərsiniz
##### beşinci başlıqdır və beş diesdən istifadə edə bilərsiniz
###### altıncı başlıqdır və altı diesdən istifadə edə bilərsiniz


-**Qalın mətnlər yazmaq üçün, mətnimizin əvvəlinə və sonuna 2 ədəd ulduz simvolu (və ya 2 ədəd altdan xətt simvolu) əlavə edirik**
-*İtalik mətnlər yazmaq üçün, mətnimizin əvvəlinə və sonuna 1 ədəd ulduz simvolu (və ya 1 ədəd altdan xətt simvolu)  əlavə edirik*
-~~Mətnlərimizin ortasında xətt çəkilməsi üçün mətnin əvvəlinə və sonuna 2 ədəd dalğalı defis əlavə edirik~~
-**Bu mətn həm qalın _həmdə  italikdir (əvvəlində və sonunda altdan xətt)_**
-***Bu mətnin hər bir simvolu isə həm qalın həm də italikdir ( bunun üçün cümləmin hər iki tərəfinə 3 ulduz əlavə etməliyəm)***
-<sub>bu alt yazıdır (alt yazı yazmaq üçün htmldəki sub teqindən istifadə etmək lazımdır)</sub>
-<sup>bu üst yazıdır (üst yazı yazmaq üçün htmldəki sup teqindən istifadə etmək lazımdır)</sup>


> Burada sitat gətirdik (Sitat üçün > işarəsindən istifadə etmək lazımdır)

Yeni bir repo yaradarkən bu əmrlərə ehtiyacımız var (bu bölməni yarada bilmək üçün ümumi cümləmin əvvəlin və sonuna 3  əyri dırnaq ``` əlavə edirik): 
``` 
touch README.md
git status 
git add --all (və ya -A və yaxud da git add .)
git commit -m "Kommitiniz"
git remote add origin "url"
git push -u origin master
```
#### sözlərə arxa fon rəngi verə bilmək üçün isə rəng kodlarımızı (hex, rgb və hsl) əyri dırnaq içərisində yaza bilərik`#0969DA`

#### Əgər README-ə hər hansısa link [daxil etmək](https://www.instagram.com/rgacademy_org) istəyirsinizsə link sözümüzü kvadrat mötərizə daxilində, gedəcəyimiz ünvanı isə normal mötərizə daxilində edə bilərik

#### Hər hansı faylı referans olaraq bildirmək istəyirsinizsə kvadrat mötərizə daxilində sözü, normal mötərizələrdə isə faylın ünvanını bildirə bilərsiniz. 